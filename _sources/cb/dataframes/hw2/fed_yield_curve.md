# Dataframe: `hw2:fed_yield_curve` - Federal Reserve Yield Curve

Daily zero-coupon yields (SVENY01 to SVENY30, in percent) implied by the Nelson-Siegel-Svensson curve that Gurkaynak, Sack, and Wright estimate and the Federal Reserve Board publishes.


## DataFrame Glimpse

```
Rows: 17053
Columns: 31
$ SVENY01          <f64> 4.4521
$ SVENY02          <f64> 4.6416
$ SVENY03          <f64> 4.717
$ SVENY04          <f64> 4.749
$ SVENY05          <f64> 4.7715
$ SVENY06          <f64> 4.7988
$ SVENY07          <f64> 4.8355
$ SVENY08          <f64> 4.8814
$ SVENY09          <f64> 4.9343
$ SVENY10          <f64> 4.9915
$ SVENY11          <f64> 5.0505
$ SVENY12          <f64> 5.109
$ SVENY13          <f64> 5.1652
$ SVENY14          <f64> 5.2179
$ SVENY15          <f64> 5.266
$ SVENY16          <f64> 5.3089
$ SVENY17          <f64> 5.3463
$ SVENY18          <f64> 5.378
$ SVENY19          <f64> 5.4038
$ SVENY20          <f64> 5.424
$ SVENY21          <f64> 5.4386
$ SVENY22          <f64> 5.4478
$ SVENY23          <f64> 5.452
$ SVENY24          <f64> 5.4512
$ SVENY25          <f64> 5.446
$ SVENY26          <f64> 5.4364
$ SVENY27          <f64> 5.4228
$ SVENY28          <f64> 5.4056
$ SVENY29          <f64> 5.3849
$ SVENY30          <f64> 5.3611
$ Date    <datetime[ns]> 2026-10-23 00:00:00


```

## Dataframe Manifest

| Dataframe Name                 | Federal Reserve Yield Curve                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [fed_yield_curve](../dataframes/hw2/fed_yield_curve.md)                                       |
| Sources                        | Federal Reserve                                          |
| Providers                      | Federal Reserve Board                                        |
| Provider Links                 | https://www.federalreserve.gov/data/nominal-yield-curve.htm                                   |
| Tags                           | Treasury, Yield Curve, Federal Reserve                                             |
| Access Types                   |                                       |
| How is data pulled?            | Web download via Python                                                   |
| Data available up to (min)     | 2026-10-23 00:00:00                                                             |
| Data available up to (max)     | 2026-10-23 00:00:00                                                             |
| Dataframe Path                 | C:\Users\fadad\hw2-Maxpatel231\_data\fed_yield_curve.parquet                                             |


**Linked Charts:**

- None


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

