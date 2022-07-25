# Slovak (sk) locale

## `format` and `parse`

| Title                           | Token string | Date                     | `format` result                              | `parse` result           |
| ------------------------------- | ------------ | ------------------------ | -------------------------------------------- | ------------------------ |
| Calendar year                   | yo           | 1987-02-11T12:13:14.015Z | 1987.                                        | 1987-01-01T00:00:00.000Z |
|                                 |              | 0005-01-01T12:13:14.015Z | 5.                                           | 0005-01-01T00:00:00.000Z |
| Local week-numbering year       | Yo           | 1987-02-11T12:13:14.015Z | 1987.                                        | 1986-12-29T00:00:00.000Z |
|                                 |              | 0005-01-01T12:13:14.015Z | 4.                                           | 0003-12-29T00:00:00.000Z |
| Quarter (formatting)            | Qo           | 2019-01-01T12:13:14.015Z | 1.                                           | 2019-01-01T00:00:00.000Z |
|                                 |              | 2019-04-01T12:13:14.015Z | 2.                                           | 2019-04-01T00:00:00.000Z |
|                                 | QQQ          | 2019-01-01T12:13:14.015Z | Q1                                           | 2019-01-01T00:00:00.000Z |
|                                 |              | 2019-04-01T12:13:14.015Z | Q2                                           | 2019-04-01T00:00:00.000Z |
|                                 | QQQQ         | 2019-01-01T12:13:14.015Z | 1. štvrťrok                                  | 2019-01-01T00:00:00.000Z |
|                                 |              | 2019-04-01T12:13:14.015Z | 2. štvrťrok                                  | 2019-04-01T00:00:00.000Z |
|                                 | QQQQQ        | 2019-01-01T12:13:14.015Z | 1                                            | 2019-01-01T00:00:00.000Z |
|                                 |              | 2019-04-01T12:13:14.015Z | 2                                            | 2019-04-01T00:00:00.000Z |
| Quarter (stand-alone)           | qo           | 2019-01-01T12:13:14.015Z | 1.                                           | 2019-01-01T00:00:00.000Z |
|                                 |              | 2019-04-01T12:13:14.015Z | 2.                                           | 2019-04-01T00:00:00.000Z |
|                                 | qqq          | 2019-01-01T12:13:14.015Z | Q1                                           | 2019-01-01T00:00:00.000Z |
|                                 |              | 2019-04-01T12:13:14.015Z | Q2                                           | 2019-04-01T00:00:00.000Z |
|                                 | qqqq         | 2019-01-01T12:13:14.015Z | 1. štvrťrok                                  | 2019-01-01T00:00:00.000Z |
|                                 |              | 2019-04-01T12:13:14.015Z | 2. štvrťrok                                  | 2019-04-01T00:00:00.000Z |
| Month (formatting)              | Mo           | 2019-02-11T12:13:14.015Z | 2.                                           | 2019-02-01T00:00:00.000Z |
|                                 |              | 2019-07-10T12:13:14.015Z | 7.                                           | 2019-07-01T00:00:00.000Z |
|                                 | MMM          | 2019-02-11T12:13:14.015Z | feb                                          | 2019-02-01T00:00:00.000Z |
|                                 |              | 2019-07-10T12:13:14.015Z | júl                                          | 2019-07-01T00:00:00.000Z |
|                                 | MMMM         | 2019-02-11T12:13:14.015Z | februára                                     | 2019-02-01T00:00:00.000Z |
|                                 |              | 2019-07-10T12:13:14.015Z | júla                                         | 2019-07-01T00:00:00.000Z |
|                                 | MMMMM        | 2019-02-11T12:13:14.015Z | f                                            | 2019-02-01T00:00:00.000Z |
|                                 |              | 2019-07-10T12:13:14.015Z | j                                            | 2019-01-01T00:00:00.000Z |
| Month (stand-alone)             | Lo           | 2019-02-11T12:13:14.015Z | 2.                                           | 2019-02-01T00:00:00.000Z |
|                                 |              | 2019-07-10T12:13:14.015Z | 7.                                           | 2019-07-01T00:00:00.000Z |
|                                 | LLL          | 2019-02-11T12:13:14.015Z | feb                                          | 2019-02-01T00:00:00.000Z |
|                                 |              | 2019-07-10T12:13:14.015Z | júl                                          | 2019-07-01T00:00:00.000Z |
|                                 | LLLL         | 2019-02-11T12:13:14.015Z | február                                      | 2019-02-01T00:00:00.000Z |
|                                 |              | 2019-07-10T12:13:14.015Z | júl                                          | 2019-07-01T00:00:00.000Z |
|                                 | LLLLL        | 2019-02-11T12:13:14.015Z | f                                            | 2019-02-01T00:00:00.000Z |
|                                 |              | 2019-07-10T12:13:14.015Z | j                                            | 2019-01-01T00:00:00.000Z |
| Local week of year              | wo           | 2019-01-01T12:13:14.015Z | 1.                                           | 2018-12-31T00:00:00.000Z |
|                                 |              | 2019-12-01T12:13:14.015Z | 48.                                          | 2019-11-25T00:00:00.000Z |
| ISO week of year                | Io           | 2019-01-01T12:13:14.015Z | 1.                                           | 2018-12-31T00:00:00.000Z |
|                                 |              | 2019-12-01T12:13:14.015Z | 48.                                          | 2019-11-25T00:00:00.000Z |
| Day of month                    | do           | 2019-02-11T12:13:14.015Z | 11.                                          | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-28T12:13:14.015Z | 28.                                          | 2019-02-28T00:00:00.000Z |
| Day of year                     | Do           | 2019-02-11T12:13:14.015Z | 42.                                          | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-12-31T12:13:14.015Z | 365.                                         | 2019-12-31T00:00:00.000Z |
| Day of week (formatting)        | E            | 2019-02-11T12:13:14.015Z | po                                           | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-15T12:13:14.015Z | pi                                           | 2019-02-15T00:00:00.000Z |
|                                 | EE           | 2019-02-11T12:13:14.015Z | po                                           | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-15T12:13:14.015Z | pi                                           | 2019-02-15T00:00:00.000Z |
|                                 | EEE          | 2019-02-11T12:13:14.015Z | po                                           | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-15T12:13:14.015Z | pi                                           | 2019-02-15T00:00:00.000Z |
|                                 | EEEE         | 2019-02-11T12:13:14.015Z | pondelok                                     | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-15T12:13:14.015Z | piatok                                       | 2019-02-15T00:00:00.000Z |
|                                 | EEEEE        | 2019-02-11T12:13:14.015Z | p                                            | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-15T12:13:14.015Z | p                                            | 2019-02-11T00:00:00.000Z |
|                                 | EEEEEE       | 2019-02-11T12:13:14.015Z | po                                           | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-15T12:13:14.015Z | pi                                           | 2019-02-15T00:00:00.000Z |
| ISO day of week (formatting)    | io           | 2019-02-11T12:13:14.015Z | 1.                                           | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-15T12:13:14.015Z | 5.                                           | 2019-02-15T00:00:00.000Z |
|                                 | iii          | 2019-02-11T12:13:14.015Z | po                                           | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-15T12:13:14.015Z | pi                                           | 2019-02-15T00:00:00.000Z |
|                                 | iiii         | 2019-02-11T12:13:14.015Z | pondelok                                     | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-15T12:13:14.015Z | piatok                                       | 2019-02-15T00:00:00.000Z |
|                                 | iiiii        | 2019-02-11T12:13:14.015Z | p                                            | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-15T12:13:14.015Z | p                                            | 2019-02-11T00:00:00.000Z |
|                                 | iiiiii       | 2019-02-11T12:13:14.015Z | po                                           | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-15T12:13:14.015Z | pi                                           | 2019-02-15T00:00:00.000Z |
| Local day of week (formatting)  | eo           | 2019-02-11T12:13:14.015Z | 1.                                           | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-15T12:13:14.015Z | 5.                                           | 2019-02-15T00:00:00.000Z |
|                                 | eee          | 2019-02-11T12:13:14.015Z | po                                           | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-15T12:13:14.015Z | pi                                           | 2019-02-15T00:00:00.000Z |
|                                 | eeee         | 2019-02-11T12:13:14.015Z | pondelok                                     | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-15T12:13:14.015Z | piatok                                       | 2019-02-15T00:00:00.000Z |
|                                 | eeeee        | 2019-02-11T12:13:14.015Z | p                                            | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-15T12:13:14.015Z | p                                            | 2019-02-11T00:00:00.000Z |
|                                 | eeeeee       | 2019-02-11T12:13:14.015Z | po                                           | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-15T12:13:14.015Z | pi                                           | 2019-02-15T00:00:00.000Z |
| Local day of week (stand-alone) | co           | 2019-02-11T12:13:14.015Z | 1.                                           | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-15T12:13:14.015Z | 5.                                           | 2019-02-15T00:00:00.000Z |
|                                 | ccc          | 2019-02-11T12:13:14.015Z | po                                           | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-15T12:13:14.015Z | pi                                           | 2019-02-15T00:00:00.000Z |
|                                 | cccc         | 2019-02-11T12:13:14.015Z | pondelok                                     | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-15T12:13:14.015Z | piatok                                       | 2019-02-15T00:00:00.000Z |
|                                 | ccccc        | 2019-02-11T12:13:14.015Z | p                                            | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-15T12:13:14.015Z | p                                            | 2019-02-11T00:00:00.000Z |
|                                 | cccccc       | 2019-02-11T12:13:14.015Z | po                                           | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-15T12:13:14.015Z | pi                                           | 2019-02-15T00:00:00.000Z |
| AM, PM                          | a            | 2019-02-11T11:13:14.015Z | AM                                           | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-11T14:13:14.015Z | PM                                           | 2019-02-11T12:00:00.000Z |
|                                 |              | 2019-02-11T19:13:14.015Z | PM                                           | 2019-02-11T12:00:00.000Z |
|                                 |              | 2019-02-11T02:13:14.015Z | AM                                           | 2019-02-11T00:00:00.000Z |
|                                 | aa           | 2019-02-11T11:13:14.015Z | AM                                           | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-11T14:13:14.015Z | PM                                           | 2019-02-11T12:00:00.000Z |
|                                 |              | 2019-02-11T19:13:14.015Z | PM                                           | 2019-02-11T12:00:00.000Z |
|                                 |              | 2019-02-11T02:13:14.015Z | AM                                           | 2019-02-11T00:00:00.000Z |
|                                 | aaa          | 2019-02-11T11:13:14.015Z | am                                           | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-11T14:13:14.015Z | pm                                           | 2019-02-11T12:00:00.000Z |
|                                 |              | 2019-02-11T19:13:14.015Z | pm                                           | 2019-02-11T12:00:00.000Z |
|                                 |              | 2019-02-11T02:13:14.015Z | am                                           | 2019-02-11T00:00:00.000Z |
|                                 | aaaa         | 2019-02-11T11:13:14.015Z | AM                                           | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-11T14:13:14.015Z | PM                                           | 2019-02-11T12:00:00.000Z |
|                                 |              | 2019-02-11T19:13:14.015Z | PM                                           | 2019-02-11T12:00:00.000Z |
|                                 |              | 2019-02-11T02:13:14.015Z | AM                                           | 2019-02-11T00:00:00.000Z |
|                                 | aaaaa        | 2019-02-11T11:13:14.015Z | AM                                           | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-11T14:13:14.015Z | PM                                           | 2019-02-11T12:00:00.000Z |
|                                 |              | 2019-02-11T19:13:14.015Z | PM                                           | 2019-02-11T12:00:00.000Z |
|                                 |              | 2019-02-11T02:13:14.015Z | AM                                           | 2019-02-11T00:00:00.000Z |
| AM, PM, noon, midnight          | b            | 2019-02-11T11:13:14.015Z | AM                                           | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-11T14:13:14.015Z | PM                                           | 2019-02-11T12:00:00.000Z |
|                                 |              | 2019-02-11T19:13:14.015Z | PM                                           | 2019-02-11T12:00:00.000Z |
|                                 |              | 2019-02-11T02:13:14.015Z | AM                                           | 2019-02-11T00:00:00.000Z |
|                                 | bb           | 2019-02-11T11:13:14.015Z | AM                                           | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-11T14:13:14.015Z | PM                                           | 2019-02-11T12:00:00.000Z |
|                                 |              | 2019-02-11T19:13:14.015Z | PM                                           | 2019-02-11T12:00:00.000Z |
|                                 |              | 2019-02-11T02:13:14.015Z | AM                                           | 2019-02-11T00:00:00.000Z |
|                                 | bbb          | 2019-02-11T11:13:14.015Z | am                                           | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-11T14:13:14.015Z | pm                                           | 2019-02-11T12:00:00.000Z |
|                                 |              | 2019-02-11T19:13:14.015Z | pm                                           | 2019-02-11T12:00:00.000Z |
|                                 |              | 2019-02-11T02:13:14.015Z | am                                           | 2019-02-11T00:00:00.000Z |
|                                 | bbbb         | 2019-02-11T11:13:14.015Z | AM                                           | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-11T14:13:14.015Z | PM                                           | 2019-02-11T12:00:00.000Z |
|                                 |              | 2019-02-11T19:13:14.015Z | PM                                           | 2019-02-11T12:00:00.000Z |
|                                 |              | 2019-02-11T02:13:14.015Z | AM                                           | 2019-02-11T00:00:00.000Z |
|                                 | bbbbb        | 2019-02-11T11:13:14.015Z | AM                                           | 2019-02-11T00:00:00.000Z |
|                                 |              | 2019-02-11T14:13:14.015Z | PM                                           | 2019-02-11T12:00:00.000Z |
|                                 |              | 2019-02-11T19:13:14.015Z | PM                                           | 2019-02-11T12:00:00.000Z |
|                                 |              | 2019-02-11T02:13:14.015Z | AM                                           | 2019-02-11T00:00:00.000Z |
| Flexible day period             | B            | 2019-02-11T11:13:14.015Z | ráno                                         | 2019-02-11T04:00:00.000Z |
|                                 |              | 2019-02-11T14:13:14.015Z | popol.                                       | Invalid Date             |
|                                 |              | 2019-02-11T19:13:14.015Z | večer                                        | 2019-02-11T17:00:00.000Z |
|                                 |              | 2019-02-11T02:13:14.015Z | v noci                                       | 2019-02-11T00:00:00.000Z |
|                                 | BB           | 2019-02-11T11:13:14.015Z | ráno                                         | 2019-02-11T04:00:00.000Z |
|                                 |              | 2019-02-11T14:13:14.015Z | popol.                                       | Invalid Date             |
|                                 |              | 2019-02-11T19:13:14.015Z | večer                                        | 2019-02-11T17:00:00.000Z |
|                                 |              | 2019-02-11T02:13:14.015Z | v noci                                       | 2019-02-11T00:00:00.000Z |
|                                 | BBB          | 2019-02-11T11:13:14.015Z | ráno                                         | 2019-02-11T04:00:00.000Z |
|                                 |              | 2019-02-11T14:13:14.015Z | popol.                                       | Invalid Date             |
|                                 |              | 2019-02-11T19:13:14.015Z | večer                                        | 2019-02-11T17:00:00.000Z |
|                                 |              | 2019-02-11T02:13:14.015Z | v noci                                       | 2019-02-11T00:00:00.000Z |
|                                 | BBBB         | 2019-02-11T11:13:14.015Z | ráno                                         | 2019-02-11T04:00:00.000Z |
|                                 |              | 2019-02-11T14:13:14.015Z | popoludní                                    | 2019-02-11T12:00:00.000Z |
|                                 |              | 2019-02-11T19:13:14.015Z | večer                                        | 2019-02-11T17:00:00.000Z |
|                                 |              | 2019-02-11T02:13:14.015Z | v noci                                       | 2019-02-11T00:00:00.000Z |
|                                 | BBBBB        | 2019-02-11T11:13:14.015Z | ráno                                         | 2019-02-11T04:00:00.000Z |
|                                 |              | 2019-02-11T14:13:14.015Z | pop.                                         | 2019-02-11T12:00:00.000Z |
|                                 |              | 2019-02-11T19:13:14.015Z | več.                                         | 2019-02-11T17:00:00.000Z |
|                                 |              | 2019-02-11T02:13:14.015Z | v n.                                         | 2019-02-11T00:00:00.000Z |
| Hour [1-12]                     | ho           | 2019-02-11T11:13:14.015Z | 11.                                          | 2019-02-11T11:00:00.000Z |
|                                 |              | 2019-02-11T23:13:14.015Z | 11.                                          | 2019-02-11T23:00:00.000Z |
| Hour [0-23]                     | Ho           | 2019-02-11T11:13:14.015Z | 11.                                          | 2019-02-11T11:00:00.000Z |
|                                 |              | 2019-02-11T23:13:14.015Z | 23.                                          | 2019-02-11T23:00:00.000Z |
| Hour [0-11]                     | Ko           | 2019-02-11T11:13:14.015Z | 11.                                          | 2019-02-11T11:00:00.000Z |
|                                 |              | 2019-02-11T23:13:14.015Z | 11.                                          | 2019-02-11T23:00:00.000Z |
| Hour [1-24]                     | ko           | 2019-02-11T11:13:14.015Z | 11.                                          | 2019-02-11T11:00:00.000Z |
|                                 |              | 2019-02-11T23:13:14.015Z | 23.                                          | 2019-02-11T23:00:00.000Z |
| Minute                          | mo           | 2019-01-01T12:01:14.015Z | 1.                                           | 2019-01-01T12:01:00.000Z |
|                                 |              | 2019-04-01T12:55:14.015Z | 55.                                          | 2019-04-01T12:55:00.000Z |
| Second                          | so           | 2019-01-01T12:13:01.015Z | 1.                                           | 2019-01-01T12:13:01.000Z |
|                                 |              | 2019-04-01T12:13:55.015Z | 55.                                          | 2019-04-01T12:13:55.000Z |
| Long localized date             | P            | 1987-02-11T12:13:14.015Z | 11. 2. 1987                                  | 1987-02-11T00:00:00.000Z |
|                                 |              | 1453-05-29T23:59:59.999Z | 29. 5. 1453                                  | 1453-05-29T00:00:00.000Z |
|                                 | PP           | 1987-02-11T12:13:14.015Z | 11. 2. 1987                                  | 1987-02-11T00:00:00.000Z |
|                                 |              | 1453-05-29T23:59:59.999Z | 29. 5. 1453                                  | 1453-05-29T00:00:00.000Z |
|                                 | PPP          | 1987-02-11T12:13:14.015Z | 11. februára 1987                            | 1987-02-11T00:00:00.000Z |
|                                 |              | 1453-05-29T23:59:59.999Z | 29. mája 1453                                | 1453-05-29T00:00:00.000Z |
|                                 | PPPP         | 1987-02-11T12:13:14.015Z | streda 11. februára 1987                     | 1987-02-11T00:00:00.000Z |
|                                 |              | 1453-05-29T23:59:59.999Z | nedeľa 29. mája 1453                         | 1453-05-29T00:00:00.000Z |
| Long localized time             | p            | 1987-02-11T12:13:14.015Z | 12:13                                        | 1987-02-11T12:13:00.000Z |
|                                 |              | 1453-05-29T23:59:59.999Z | 23:59                                        | 1453-05-29T23:59:00.000Z |
|                                 | pp           | 1987-02-11T12:13:14.015Z | 12:13:14                                     | 1987-02-11T12:13:14.000Z |
|                                 |              | 1453-05-29T23:59:59.999Z | 23:59:59                                     | 1453-05-29T23:59:59.000Z |
|                                 | ppp          | 1987-02-11T12:13:14.015Z | 12:13:14 GMT+0                               | Errored                  |
|                                 |              | 1453-05-29T23:59:59.999Z | 23:59:59 GMT+0                               | Errored                  |
|                                 | pppp         | 1987-02-11T12:13:14.015Z | 12:13:14 GMT+00:00                           | Errored                  |
|                                 |              | 1453-05-29T23:59:59.999Z | 23:59:59 GMT+00:00                           | Errored                  |
| Combination of date and time    | Pp           | 1987-02-11T12:13:14.015Z | 11. 2. 1987 12:13                            | 1987-02-11T12:13:00.000Z |
|                                 |              | 1453-05-29T23:59:59.999Z | 29. 5. 1453 23:59                            | 1453-05-29T23:59:00.000Z |
|                                 | PPpp         | 1987-02-11T12:13:14.015Z | 11. 2. 1987, 12:13:14                        | 1987-02-11T12:13:14.000Z |
|                                 |              | 1453-05-29T23:59:59.999Z | 29. 5. 1453, 23:59:59                        | 1453-05-29T23:59:59.000Z |
|                                 | PPPppp       | 1987-02-11T12:13:14.015Z | 11. februára 1987, 12:13:14 GMT+0            | Errored                  |
|                                 |              | 1453-05-29T23:59:59.999Z | 29. mája 1453, 23:59:59 GMT+0                | Errored                  |
|                                 | PPPPpppp     | 1987-02-11T12:13:14.015Z | streda 11. februára 1987, 12:13:14 GMT+00:00 | Errored                  |
|                                 |              | 1453-05-29T23:59:59.999Z | nedeľa 29. mája 1453, 23:59:59 GMT+00:00     | Errored                  |

## `formatDistance`

If now is January 1st, 2000, 00:00.

| Date                     | Result            | `includeSeconds: true` | `addSuffix: true`         |
| ------------------------ | ----------------- | ---------------------- | ------------------------- |
| 2006-01-01T00:00:00.000Z | približne 6 rokov | približne 6 rokov      | približne o 6 rokov       |
| 2005-01-01T00:00:00.000Z | približne 5 rokov | približne 5 rokov      | približne o 5 rokov       |
| 2004-01-01T00:00:00.000Z | približne 4 roky  | približne 4 roky       | približne o 4 roky        |
| 2003-01-01T00:00:00.000Z | približne 3 roky  | približne 3 roky       | približne o 3 roky        |
| 2002-01-01T00:00:00.000Z | približne 2 roky  | približne 2 roky       | približne o 2 roky        |
| 2001-06-01T00:00:00.000Z | viac než rok      | viac než rok           | o viac než rok            |
| 2001-02-01T00:00:00.000Z | približne rok     | približne rok          | približne o rok           |
| 2001-01-01T00:00:00.000Z | približne rok     | približne rok          | približne o rok           |
| 2000-06-01T00:00:00.000Z | 5 mesiacov        | 5 mesiacov             | o 5 mesiacov              |
| 2000-03-01T00:00:00.000Z | 2 mesiace         | 2 mesiace              | o 2 mesiace               |
| 2000-02-01T00:00:00.000Z | približne mesiac  | približne mesiac       | približne o mesiac        |
| 2000-01-15T00:00:00.000Z | 14 dní            | 14 dní                 | o 14 dní                  |
| 2000-01-02T00:00:00.000Z | deň               | deň                    | o deň                     |
| 2000-01-01T06:00:00.000Z | približne 6 hodín | približne 6 hodín      | približne o 6 hodín       |
| 2000-01-01T01:00:00.000Z | približne hodina  | približne hodina       | približne o hodinu        |
| 2000-01-01T00:45:00.000Z | približne hodina  | približne hodina       | približne o hodinu        |
| 2000-01-01T00:30:00.000Z | 30 minút          | 30 minút               | o 30 minút                |
| 2000-01-01T00:15:00.000Z | 15 minút          | 15 minút               | o 15 minút                |
| 2000-01-01T00:01:00.000Z | minúta            | minúta                 | o minútu                  |
| 2000-01-01T00:00:25.000Z | menej než minúta  | pol minúty             | o menej než minútu        |
| 2000-01-01T00:00:15.000Z | menej než minúta  | menej než 20 sekúnd    | o menej než minútu        |
| 2000-01-01T00:00:05.000Z | menej než minúta  | menej než 10 sekúnd    | o menej než minútu        |
| 2000-01-01T00:00:00.000Z | menej než minúta  | menej než 5 sekúnd     | pred menej než minútou    |
| 1999-12-31T23:59:55.000Z | menej než minúta  | menej než 10 sekúnd    | pred menej než minútou    |
| 1999-12-31T23:59:45.000Z | menej než minúta  | menej než 20 sekúnd    | pred menej než minútou    |
| 1999-12-31T23:59:35.000Z | menej než minúta  | pol minúty             | pred menej než minútou    |
| 1999-12-31T23:59:00.000Z | minúta            | minúta                 | pred minútou              |
| 1999-12-31T23:45:00.000Z | 15 minút          | 15 minút               | pred 15 minútami          |
| 1999-12-31T23:30:00.000Z | 30 minút          | 30 minút               | pred 30 minútami          |
| 1999-12-31T23:15:00.000Z | približne hodina  | približne hodina       | približne pred hodinou    |
| 1999-12-31T23:00:00.000Z | približne hodina  | približne hodina       | približne pred hodinou    |
| 1999-12-31T18:00:00.000Z | približne 6 hodín | približne 6 hodín      | približne pred 6 hodinami |
| 1999-12-30T00:00:00.000Z | 2 dni             | 2 dni                  | pred 2 dňami              |
| 1999-12-15T00:00:00.000Z | 17 dní            | 17 dní                 | pred 17 dňami             |
| 1999-12-01T00:00:00.000Z | približne mesiac  | približne mesiac       | približne pred mesiacom   |
| 1999-11-01T00:00:00.000Z | 2 mesiace         | 2 mesiace              | pred 2 mesiacmi           |
| 1999-06-01T00:00:00.000Z | 7 mesiacov        | 7 mesiacov             | pred 7 mesiacmi           |
| 1999-01-01T00:00:00.000Z | približne rok     | približne rok          | približne pred rokom      |
| 1998-12-01T00:00:00.000Z | približne rok     | približne rok          | približne pred rokom      |
| 1998-06-01T00:00:00.000Z | viac než rok      | viac než rok           | pred viac než rokom       |
| 1998-01-01T00:00:00.000Z | približne 2 roky  | približne 2 roky       | približne pred 2 rokmi    |
| 1997-01-01T00:00:00.000Z | približne 3 roky  | približne 3 roky       | približne pred 3 rokmi    |
| 1996-01-01T00:00:00.000Z | približne 4 roky  | približne 4 roky       | približne pred 4 rokmi    |
| 1995-01-01T00:00:00.000Z | približne 5 rokov | približne 5 rokov      | približne pred 5 rokmi    |
| 1994-01-01T00:00:00.000Z | približne 6 rokov | približne 6 rokov      | približne pred 6 rokmi    |

## `formatDistanceStrict`

If now is January 1st, 2000, 00:00.

| Date                     | Result     | `addSuffix: true` | With forced unit (i.e. `hour`) |
| ------------------------ | ---------- | ----------------- | ------------------------------ |
| 2006-01-01T00:00:00.000Z | 6 rokov    | o 6 rokov         | 52608 hodín                    |
| 2005-01-01T00:00:00.000Z | 5 rokov    | o 5 rokov         | 43848 hodín                    |
| 2004-01-01T00:00:00.000Z | 4 roky     | o 4 roky          | 35064 hodín                    |
| 2003-01-01T00:00:00.000Z | 3 roky     | o 3 roky          | 26304 hodín                    |
| 2002-01-01T00:00:00.000Z | 2 roky     | o 2 roky          | 17544 hodín                    |
| 2001-06-01T00:00:00.000Z | rok        | o rok             | 12408 hodín                    |
| 2001-02-01T00:00:00.000Z | rok        | o rok             | 9528 hodín                     |
| 2001-01-01T00:00:00.000Z | rok        | o rok             | 8784 hodín                     |
| 2000-06-01T00:00:00.000Z | 5 mesiacov | o 5 mesiacov      | 3648 hodín                     |
| 2000-03-01T00:00:00.000Z | 2 mesiace  | o 2 mesiace       | 1440 hodín                     |
| 2000-02-01T00:00:00.000Z | mesiac     | o mesiac          | 744 hodín                      |
| 2000-01-15T00:00:00.000Z | 14 dní     | o 14 dní          | 336 hodín                      |
| 2000-01-02T00:00:00.000Z | deň        | o deň             | 24 hodín                       |
| 2000-01-01T06:00:00.000Z | 6 hodín    | o 6 hodín         | 6 hodín                        |
| 2000-01-01T01:00:00.000Z | hodina     | o hodinu          | hodina                         |
| 2000-01-01T00:45:00.000Z | 45 minút   | o 45 minút        | hodina                         |
| 2000-01-01T00:30:00.000Z | 30 minút   | o 30 minút        | hodina                         |
| 2000-01-01T00:15:00.000Z | 15 minút   | o 15 minút        | 0 hodín                        |
| 2000-01-01T00:01:00.000Z | minúta     | o minútu          | 0 hodín                        |
| 2000-01-01T00:00:25.000Z | 25 sekúnd  | o 25 sekúnd       | 0 hodín                        |
| 2000-01-01T00:00:15.000Z | 15 sekúnd  | o 15 sekúnd       | 0 hodín                        |
| 2000-01-01T00:00:05.000Z | 5 sekúnd   | o 5 sekúnd        | 0 hodín                        |
| 2000-01-01T00:00:00.000Z | 0 sekúnd   | pred 0 sekundami  | 0 hodín                        |
| 1999-12-31T23:59:55.000Z | 5 sekúnd   | pred 5 sekundami  | 0 hodín                        |
| 1999-12-31T23:59:45.000Z | 15 sekúnd  | pred 15 sekundami | 0 hodín                        |
| 1999-12-31T23:59:35.000Z | 25 sekúnd  | pred 25 sekundami | 0 hodín                        |
| 1999-12-31T23:59:00.000Z | minúta     | pred minútou      | 0 hodín                        |
| 1999-12-31T23:45:00.000Z | 15 minút   | pred 15 minútami  | 0 hodín                        |
| 1999-12-31T23:30:00.000Z | 30 minút   | pred 30 minútami  | hodina                         |
| 1999-12-31T23:15:00.000Z | 45 minút   | pred 45 minútami  | hodina                         |
| 1999-12-31T23:00:00.000Z | hodina     | pred hodinou      | hodina                         |
| 1999-12-31T18:00:00.000Z | 6 hodín    | pred 6 hodinami   | 6 hodín                        |
| 1999-12-30T00:00:00.000Z | 2 dni      | pred 2 dňami      | 48 hodín                       |
| 1999-12-15T00:00:00.000Z | 17 dní     | pred 17 dňami     | 408 hodín                      |
| 1999-12-01T00:00:00.000Z | mesiac     | pred mesiacom     | 744 hodín                      |
| 1999-11-01T00:00:00.000Z | 2 mesiace  | pred 2 mesiacmi   | 1464 hodín                     |
| 1999-06-01T00:00:00.000Z | 7 mesiacov | pred 7 mesiacmi   | 5136 hodín                     |
| 1999-01-01T00:00:00.000Z | rok        | pred rokom        | 8760 hodín                     |
| 1998-12-01T00:00:00.000Z | rok        | pred rokom        | 9504 hodín                     |
| 1998-06-01T00:00:00.000Z | 2 roky     | pred 2 rokmi      | 13896 hodín                    |
| 1998-01-01T00:00:00.000Z | 2 roky     | pred 2 rokmi      | 17520 hodín                    |
| 1997-01-01T00:00:00.000Z | 3 roky     | pred 3 rokmi      | 26280 hodín                    |
| 1996-01-01T00:00:00.000Z | 4 roky     | pred 4 rokmi      | 35064 hodín                    |
| 1995-01-01T00:00:00.000Z | 5 rokov    | pred 5 rokmi      | 43824 hodín                    |
| 1994-01-01T00:00:00.000Z | 6 rokov    | pred 6 rokmi      | 52584 hodín                    |

## `formatRelative`

If now is January 1st, 2000, 00:00.

| Date                     | Result            |
| ------------------------ | ----------------- |
| 2000-01-10T00:00:00.000Z | 10. 1. 2000       |
| 2000-01-05T00:00:00.000Z | v stredu o 0:00   |
| 2000-01-02T00:00:00.000Z | zajtra o 0:00     |
| 2000-01-01T00:00:00.000Z | dnes o 0:00       |
| 1999-12-31T00:00:00.000Z | včera o 0:00      |
| 1999-12-27T00:00:00.000Z | v pondelok o 0:00 |
| 1999-12-21T00:00:00.000Z | 21. 12. 1999      |

## `formatDuration`

| Duration      | Result     |
| ------------- | ---------- |
| {"years":0}   | 0 rokov    |
| {"years":1}   | rok        |
| {"years":2}   | 2 roky     |
| {"months":0}  | 0 mesiacov |
| {"months":1}  | mesiac     |
| {"months":2}  | 2 mesiace  |
| {"weeks":0}   | 0 týždňov  |
| {"weeks":1}   | týždeň     |
| {"weeks":2}   | 2 týždne   |
| {"days":0}    | 0 dní      |
| {"days":1}    | deň        |
| {"days":2}    | 2 dni      |
| {"hours":0}   | 0 hodín    |
| {"hours":1}   | hodina     |
| {"hours":2}   | 2 hodiny   |
| {"minutes":0} | 0 minút    |
| {"minutes":1} | minúta     |
| {"minutes":2} | 2 minúty   |
| {"seconds":0} | 0 sekúnd   |
| {"seconds":1} | sekunda    |
| {"seconds":2} | 2 sekundy  |