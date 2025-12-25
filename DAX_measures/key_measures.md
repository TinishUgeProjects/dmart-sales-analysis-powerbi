## Key DAX Measures Used

### Total Revenue
```DAX
Total Revenue = SUM(FactSales[SalesAmount])
```

### Monthly Sales
```DAX
Monthly Sales =
CALCULATE(
    [Total Revenue],
    DATESMTD(DimDate[Date])
)
```

### Cancellation Rate
```DAX
Cancellation Rate =
DIVIDE(
    COUNTROWS(FILTER(FactSales, FactSales[OrderStatus] = "Cancelled")),
    COUNTROWS(FactSales)
)
```
