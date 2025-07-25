# IOR Benchmark Results

## Write Operations

| Transfer Size | Block Size | MiB/s (Mean) | MiB/s (Max) | MiB/s (Min) | MiB/s (StdDev) | MiB/s StdDev % | OPs (Mean) | OPs (Min) | OPs (Max) | OPs (StdDev) | OPs StdDev % | Mean Time (s) |
|---------------|------------|--------------|-------------|-------------|----------------|----------------|------------|-----------|-----------|--------------|--------------|---------------|
| 4 KiB         | 64 MiB     | 1944.18      | 2012.93     | 1875.69     | 183.50         | 9.44%          | 503004.68  | 487890.86 | 517585.64 | 41252.42     | 8.20%         | 204.82        |
| 8 KiB         | 64 MiB     | 1774.17      | 1918.37     | 1629.96     | 159.50         | 8.99%          | 233245.41  | 216200.78 | 245669.19 | 23588.57     | 10.11%        | 225.01        |
| 16 KiB        | 64 MiB     | 1792.86      | 1902.78     | 1682.96     | 186.17         | 10.38%         | 114742.94  | 107709.87 | 121918.11 | 11917.71     | 10.39%        | 223.79        |
| 32 KiB        | 64 MiB     | 1778.42      | 1886.74     | 1670.31     | 159.15         | 8.95%          | 56908.63   | 53449.98  | 60395.54  | 5925.49      | 10.41%        | 253.15        |
| 64 KiB        | 64 MiB     | 1674.89      | 1754.38     | 1595.42     | 84.79          | 5.06%          | 26798.15   | 25526.86  | 28077.53  | 1356.40      | 5.06%         | 236.56        |
| 4 MiB         | 1 GiB      | 1888.42      | 1979.47     | 1797.29     | 166.73         | 8.83%          | 472.11     | 449.32    | 494.87    | 47.40        | 10.04%        | 213.52        |
| 4 MiB         | 128 MiB    | 1369.11      | 1436.82     | 1301.67     | 143.18         | 10.46%         | 342.28     | 325.42    | 359.21    | 30.52        | 8.92%         | 594.13        |
| 8 MiB         | 1 GiB      | 1786.21      | 1931.67     | 1586.32     | 156.89         | 8.78%          | 223.28     | 198.29    | 241.46    | 19.66        | 8.81%         | 222.38        |
| 8 MiB         | 128 MiB    | 1440.09      | 1526.34     | 1353.89     | 148.52         | 10.31%         | 180.01     | 169.24    | 190.79    | 18.40        | 10.22%        | 583.67        |
| 16 MiB        | 1 GiB      | 1635.76      | 1736.43     | 1535.27     | 170.84         | 10.44%         | 102.24     | 95.95     | 108.53    | 10.58        | 10.35%        | 252.00        |
| 16 MiB        | 128 MiB    | 1413.61      | 1492.35     | 1334.87     | 125.44         | 8.87%          | 88.35      | 83.43     | 93.27     | 9.28         | 10.50%        | 573.37        |
| 32 MiB        | 1 GiB      | 1900.87      | 2013.86     | 1787.73     | 189.97         | 10.00%         | 59.40      | 55.87     | 62.93     | 5.96         | 10.03%        | 210.54        |
| 32 MiB        | 128 MiB    | 1401.97      | 1485.28     | 1318.63     | 122.84         | 8.76%          | 43.81      | 41.21     | 46.42     | 3.83         | 8.74%         | 568.72        |
| 64 MiB        | 1 GiB      | 1893.18      | 2003.69     | 1782.74     | 198.91         | 10.51%         | 29.58      | 27.86     | 31.31     | 3.11         | 10.51%        | 211.40        |
| 64 MiB        | 128 MiB    | 1386.05      | 1469.36     | 1302.64     | 122.92         | 8.87%          | 21.66      | 20.35     | 22.96     | 2.20         | 10.16%        | 5684.70       |

## Read Operations

| Transfer Size | Block Size | MiB/s (Mean) | MiB/s (Max) | MiB/s (Min) | MiB/s (StdDev) | MiB/s StdDev % | OPs (Mean) | OPs (Min) | OPs (Max) | OPs (StdDev) | OPs StdDev % | Mean Time (s) |
|---------------|------------|--------------|-------------|-------------|----------------|----------------|------------|-----------|-----------|--------------|--------------|---------------|
| 4 KiB         | 64 MiB     | 40856.45     | 43105.81    | 38563.26    | 3159.15        | 7.73%          | 9576333.78 | 9075458.88| 10078908.85| 931722.09    | 9.73%         | 14.95         |
| 8 KiB         | 64 MiB     | 28919.30     | 30785.23    | 27124.58    | 2939.50        | 10.16%         | 3490823.22 | 3275454.79| 3701388.84| 322540.13    | 9.24%         | 16.82         |
| 16 KiB        | 64 MiB     | 24746.39     | 26184.12    | 23267.19    | 2514.82        | 10.16%         | 1518781.92 | 1439291.50| 1596543.62| 144351.01    | 9.50%         | 19.73         |
| 32 KiB        | 64 MiB     | 37760.46     | 40062.86    | 35561.17    | 3671.48        | 9.72%          | 1113201.69 | 1053764.64| 1173604.61| 105650.40    | 9.49%         | 22.17         |
| 64 KiB        | 64 MiB     | 27068.18     | 28677.98    | 25683.52    | 2782.91        | 10.28%         | 433091.52  | 410936.37 | 458847.51 | 38779.70     | 8.95%         | 18.33         |
| 4 MiB         | 1 GiB      | 59525.35     | 62428.22    | 56501.96    | 6021.13        | 10.12%         | 14881.34   | 14125.49  | 15612.06  | 1458.27      | 9.80%         | 6.71          |
| 4 MiB         | 128 MiB    | 14846.82     | 15728.59    | 13907.79    | 1602.32        | 10.79%         | 3711.71    | 3476.95   | 3932.15   | 345.98       | 9.32%         | 57.35         |
| 8 MiB         | 1 GiB      | 41802.08     | 44317.64    | 39287.73    | 3514.82        | 8.41%          | 5225.26    | 4910.97   | 5539.71   | 519.88       | 9.95%         | 12.46         |
| 8 MiB         | 128 MiB    | 18318.32     | 19387.46    | 17309.51    | 1898.53        | 10.36%         | 2289.79    | 2163.69   | 2423.43   | 209.94       | 9.17%         | 44.15         |
| 16 MiB        | 1 GiB      | 24747.53     | 26246.71    | 23196.38    | 2141.36        | 8.65%          | 1546.72    | 1449.77   | 1640.42   | 156.66       | 10.13%        | 18.91         |
| 16 MiB        | 128 MiB    | 14466.98     | 15382.18    | 13514.68    | 1370.65        | 9.47%          | 904.19     | 844.67    | 961.39    | 85.24        | 9.43%         | 59.17         |
| 32 MiB        | 1 GiB      | 22334.98     | 23805.16    | 20969.97    | 2357.38        | 10.55%         | 698.59     | 655.31    | 743.91    | 74.65        | 10.69%        | 20.47         |
| 32 MiB        | 128 MiB    | 16016.96     | 16962.21    | 15043.89    | 1747.28        | 10.91%         | 500.53     | 470.12    | 530.07    | 47.28        | 9.45%         | 51.59         |
| 64 MiB        | 1 GiB      | 30000.07     | 31688.56    | 28304.31    | 3034.57        | 10.12%         | 468.75     | 442.26    | 495.13    | 47.40        | 10.11%        | 16.08         |
| 64 MiB        | 128 MiB    | 13028.81     | 13761.92    | 12298.46    | 1250.01        | 9.59%          | 203.57     | 192.16    | 215.03    | 19.96        | 9.80%         | 79.31         |
