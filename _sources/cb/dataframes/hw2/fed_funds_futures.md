# Dataframe: `hw2:fed_funds_futures` - 30-Day Fed Funds Futures

Daily futures prices retrieved from CME Globex using the Databento GLBX.MDP3 dataset, ohlcv-1d schema, and ZQ.FUT parent symbology. The close price implies a monthly average effective federal funds rate of 100 minus price. Parent symbology also returns calendar spreads, which must be excluded when analyzing outright contracts.


## DataFrame Glimpse

```
Rows: 11721
Columns: 7
$ date   <datetime[ns]> 2026-10-26 00:00:00
$ symbol          <str> 'ZQZ6'
$ open            <f64> 95.96
$ high            <f64> 95.965
$ low             <f64> 95.94
$ close           <f64> 95.95
$ volume          <u64> 15157


```

## Dataframe Manifest

| Dataframe Name                 | 30-Day Fed Funds Futures                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [fed_funds_futures](../dataframes/hw2/fed_funds_futures.md)                                       |
| Sources                        | CME Globex                                          |
| Providers                      | Databento                                        |
| Provider Links                 | https://databento.com/                                   |
| Tags                           | Futures, Federal Reserve, Monetary Policy, Fedwatch                                             |
| Access Types                   |                                       |
| How is data pulled?            | Databento Historical API                                                   |
| Data available up to (min)     | 2026-10-26 00:00:00                                                             |
| Data available up to (max)     | 2026-10-26 00:00:00                                                             |
| Dataframe Path                 | C:\Users\fadad\hw2-Maxpatel231\_data\fed_funds_futures.parquet                                             |


**Linked Charts:**


- [hw2:fedwatch_latest_forecast](../../charts/hw2.fedwatch_latest_forecast.md)



## Pipeline Manifest

| Pipeline Name                   | HW 2: The Yield Curve and the Policy Path                       |
|---------------------------------|--------------------------------------------------------|
| Pipeline ID                     | [hw2](../../../index.md)              |
| Maintainer                      | Jeremiah Bejarano               |
| Contributors                    | Jeremiah Bejarano |
| Repository                     | https://github.com/hw-finm-32800/hw2                  |
| Pipeline Web Page               | <a href="file://C:/Users/fadad/hw2-Maxpatel231/docs/index.html">Pipeline Web Page      |
| Date of Last Code Update        | 2026-10-27 20:14:41           |
| OS Compatibility                | Windows, Linux, macOS |
| Linked Dataframes               |  [hw2:crsp_treasury_consolidated](../../dataframes/hw2/crsp_treasury_consolidated.md)<br>  [hw2:fed_yield_curve](../../dataframes/hw2/fed_yield_curve.md)<br>  [hw2:fed_funds_futures](../../dataframes/hw2/fed_funds_futures.md)<br>  |


**Build Commands:**
```
doit

```

