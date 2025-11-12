## Dax Measures Used 🧮

- M_Date Selection = FORMAT(MIN(DIM_DATE[Reporting Period]),"MMM/YY")&" - "& FORMAT(MAX(DIM_DATE[Reporting Period]),"MMM/YY")

- M_Date/Time Last Refreshed = "Last Refreshed: "&FORMAT(VALUES(LAST_REFRESHED[Date Last Refreshed]),"mm.dd.yy")

- M_Units Sold = SUM(FACT_SALES[Units Sold])

- M_Units Sold CY = CALCULATE(SUM(FACT_SALES[Units Sold]),DIM_DATE[Year Rank]="1")

- M_Units Sold PY = CALCULATE([M_Units Sold],DIM_DATE[Year Rank]="2")

- M_Gross Sales = SUM(FACT_SALES[Gross Sales])

- M_Discounts = SUM(FACT_SALES[Discounts])

- M_Net Sales = SUM(FACT_SALES[Sales])

- M_Cost Of Goods = SUM(FACT_SALES[COGs])

- M_Profit = [M_Net Sales]-[M_Cost Of Goods]

- M_Profit CY = CALCULATE([M_Profit],DIM_DATE[Year Rank]="1")

- M_Profit PY = CALCULATE([M_Profit],DIM_DATE[Year Rank]="2")

- M_Profit YOY% = IFERROR(CALCULATE(([M_Profit CY]-([M_Profit PY])) / ABS([M_Profit PY]),ALL(DIM_DATE[Year])),1)

- M_Profit YOY% Formatted = "YOY: "&FORMAT([M_Profit YOY%],"00%")

- M_Profit Margin = IFERROR([M_Profit] / [M_Net Sales],0)

- M_Profit Margin Formatted = IF([M_Profit Margin]>0,"+"&FORMAT([M_Profit Margin],"0%"),FORMAT([M_Profit Margin],"0%"))

- M_100% Minus Profit Margin = 1-[M_Profit Margin]

- M_Transparent = "RGBA(255,255,255,0)"

- M_# of Distinct Countries = DISTINCTCOUNT(FACT_SALES[Country])

- M_# of Distinct Segments = DISTINCTCOUNT(FACT_SALES[Segment])

- M_User Greeting = "Welcome " &SELECTEDVALUE(DIM_MANAGERS[First Name])&"!"

- M_Welcome_All = VAR Selected_User = SELECTEDVALUE(DIM_MANAGERS[Manager ID])RETURN IF(ISBLANK(Selected_User),"#fff","RGBA(255,255,255,0)")

- M_Discount Band Colors = 
  VAR High = IF(SELECTEDVALUE('FACT_SALES'[Discount Band])="High",True,False)
  VAR Medium = IF(SELECTEDVALUE('FACT_SALES'[Discount Band])="Medium",True,False)
  VAR Low = IF(SELECTEDVALUE('FACT_SALES'[Discount Band])="Low",True,False)
  VAR None = IF(SELECTEDVALUE('FACT_SALES'[Discount Band])="None",True,False)
  
  RETURN 
  SWITCH(TRUE(),High,"#e92f42",Medium,"#ffbe0b",Low,"#049570",None,"#808080","#07345F")

