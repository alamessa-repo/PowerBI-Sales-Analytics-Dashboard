Total Sales =
SUM(Sales[SalesAmount])

Total Cost =
SUM(Sales[Cost])

Profit =
[Total Sales] - [Total Cost]

YoY Growth % =
DIVIDE(
    [Current Year Sales] - [Previous Year Sales],
    [Previous Year Sales]
)
