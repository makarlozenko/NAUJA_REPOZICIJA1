# first_project
Sistemos informacija:
| CPU                                       | RAM | SSD   | 
|-------------------------------------------|-----|-------|
| Intel(R) Core(TM) i5-10300H CPU @ 2.50GHz | 8GB | 512GB |



# Class ir Struct palyginimas:

Struct versija:
| Testavimas               |     1000000  |  10000000 |    1000000  |  10000000 |     1000000  |  10000000 |
|--------------------------|:---------:|:---------:|:---------:|:---------:|:---------:|:---------:|
| Flagas                   |     O1   |        O1 |     O2   |        O2 |     O3   |        O3 |
| Failo   nuskaitymas      | 4.79932 s |  48.6585 s  |4.80397 s |  48.6153 s  |4.78155 s |   48.7204 s |
| Funkcija sort            |7.9945 s | 97.0551 s |8.00243 s | 96.8543 ss |8.02969 s | 97.4663 s |
| Išvedimas į   kietakius  | 2.03313 s  | 20.5126 s|2.03939 s  | 20.4697 s|2.05651 s  | 20.7823 s|
| Išvedimas į   vargšiukus | 1.43782 s  | 14.6049 s |1.4427 s  | 14.4275 s |1.44295 s  |14.5723 s |
| Bendras laikas           | 16.2648 s | 180.831 s| 16.2885 s | 180.367 s| 16.3107 s | 181.541 s|
| exe failo dydis          | 16.2648 s | 180.831 s| 16.2885 s | 180.367 s| 16.3107 s | 181.541 s|


Class versija:
| Testavimas               |     1000000  |  10000000 |    1000000  |  10000000 |     1000000  |  10000000 |
|--------------------------|:---------:|:---------:|:---------:|:---------:|:---------:|:---------:|
| Flagas                   |     O1   |        O1 |     O2   |        O2 |     O3   |        O3 |
| Failo   nuskaitymas      | 3.22829 s |  37.0912 s  |3.176 s |  33.1306 s |3.17075 s |  32.96 s  |
| Funkcija sort            | 1.18674 s | 15.7502 s |1.19442 s| 14.4812 s |1.18469 s | 14.3167 s |
| Išvedimas į   kietakius  | 1.89738 s  | 18.8566 s|1.88974 s | 18.9461 s|1.87434 s  | 18.803 s|
| Išvedimas į   vargšiukus | 1.32766 s | 13.1207 s | 1.32952 s  | 13.3899 s |1.3213 s  | 13.2821 s |
| Bendras laikas           | 7.64007 s | 84.8187 s| 7.58968 s | 79.9478 s|  7.55108 s | 79.3617 s|
| exe failo dydis          | 220 KB | 220 KB| 214 KB | 214 KB| 212 KB | 212 KB|







 









