# Data Files

## Source: Federal Reserve Economic Data (FRED)

Unemployment rate and CPI for Phillips Curve analysis

### Files:
- UNRATE.csv
- CPIAUCSL.csv
- fred_data.csv (merged data)

### Download Date: 2026-01-27

Data can also be downloaded directly in R using:
```r
library(quantmod)
getSymbols("UNRATE", src = "FRED")
getSymbols("CPIAUCSL", src = "FRED")
```

