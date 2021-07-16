# covid19-vaccination-data-japan

首相官邸の「新型コロナワクチンについて」ページに掲載される日別の一般接種（高齢者含む）と医療従事者等の接種回数の合計から算出した各種データを配信しています。
商用・非商用を問わずご自由に使用していただいて構いません。使用に関していかなる保証もありません。ライセンス条項をご確認ください。

The total number of vaccination, the total number of vaccinated people, and the moving average per day of the last 7days shots in Japan. These numbers except "total_vaccinations" and some "raw" numbers are calculated from the daily official vaccination log published by the Prime Minister's Office of Japan. So please make sure that these numbers are not guaranteed officially by the Japanese government.

| data column | description |
|--|--|
|date| 日付 |
| total_vaccinations |総接種回数 | 
| total_vaccinations_per_hundred | 総接種回数(人口100人あたり) | 
| people_vaccinated |1回以上接種済累積人数 |
| people_vaccinated_per_hundred |1回以上接種済累積人数(人口100人あたり) | 
| people_fully_vaccinated |2回接種済累積人数 |
| people_fully_vaccinated_per_hundred |2回接種済累積人数(人口100人あたり)　| 
| daily_vaccinations |日別接種回数（7日移動平均) |
| daily_vaccinations_per_million | 日別接種回数（7日移動平均,人口100万人あたり) | 
| daily_vaccinations_raw |日別接種回数 |
| daily_vaccinations_first_raw |日別接種回数(内1回目) | 
| daily_vaccinations_second_raw |日別接種回数(内2回目) |
| korei_daily_vaccinations_raw |日別接種回数(一般接種+高齢者) |
| korei_daily_vaccinations_first_raw |日別接種回数(一般接種+高齢者)(内1回目) |
| korei_daily_vaccinations_second_raw |日別接種回数(一般接種+高齢者)(内2回目) |
| iryo_daily_vaccinations_raw |日別接種回数(医療従事者) |
| iryo_daily_vaccinations_first_raw |日別接種回数(医療従事者)(内1回目) |
| iryo_daily_vaccinations_second_raw |日別接種回数(医療従事者)(内2回目) |

総人口（126476458人）は[国連発表データ（2020年版）](https://population.un.org/wpp/Download/Standard/Population/)を使用。

