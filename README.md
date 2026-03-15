# fukui-kanko-coupon

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

This project aims to visualize the usage status of the "Fukui de Otoku Coupon" campaign, which is intended to revive the dwindling travel demand caused by the COVID-19 pandemic and support the severely affected tourism businesses in Fukui Prefecture, Japan.

## Demo
[1km mesh map of usage amount](https://code4fukui.github.io/fukui-kanko-coupon/)

## Open Data
This project provides the following open data:

- CC BY [List of users (User ID, Prefecture, Gender, Usage Count, Usage Amount, Age)](users.csv) ([by usage amount](users_amount.csv), [by usage count](users_count.csv))
- CC BY [List of usage (Transaction Datetime, User ID, Transaction Type, Amount, Cancel Flag, Category, Category2, Geo3x3)](mesh-tr.csv)
- CC BY [Usage amount per mesh (Geo3x3, Category, Usage Amount)](mesh-tr-total.csv)
- CC0 [Mesh GeoJSON](mesh-geo3x3.geojson)

## Fukui de Otoku Coupon
- [Fukui de Otoku Coupon Campaign](https://fukui-de-coupon.jp/)
- ["Fukui de Otoku Campaign" will be resumed from January 10th!](https://www2.pref.fukui.lg.jp/press/view.php?cod=d76b8D167287688524&whence=72)

This project aims to revive the dwindling travel demand caused by the COVID-19 pandemic and support the severely affected tourism businesses in Fukui Prefecture.

### Implementation Period
January 10, 2023 (Tue) to July 20, 2023 (Thu) for accommodation and activities
(Excluding April 29 (Sat) to May 7 (Sun), 2023)

### Target Users
Travelers residing in Japan

### Conditions for Use
Presentation of "personal identification document" (original)

### Implementation Content
Provide coupons worth 2,000 yen or 1,000 yen that can be used at souvenir shops, restaurants, taxis, etc. within Fukui Prefecture, depending on the conditions for the accommodation travel.

### Distribution Conditions
Until March 31, 2023 for accommodation and activities:
- Target: Residents of all 47 prefectures in Japan
- Regional Coupon: 2,000 yen on weekdays, 1,000 yen on weekends

From April 1 to July 20, 2023 for accommodation and activities 
(Excluding April 29 (Sat) to May 7 (Sun), 2023):
- Regional Coupon: 2,000 yen on weekdays, 1,000 yen on weekends
- Fukui Prefecture's own additional project:
    - 1,000 yen/person-night for inter-regional (Hokuriku-Echizen) accommodation (10,000 yen or more/person-night) (Fukui residents only)
    - 1,000 yen/person-night for weekday accommodation in Fukui (70 years old or older and 10,000 yen or more/person-night)
    - 2,000 yen/group-night for family/group accommodation in Fukui (2 or more people and 10,000 yen or more/person-night)
    - 2,000 yen/group-night for Fukui residents who book accommodation with transportation outside the prefecture through a Fukui travel agency (2 or more people)

### Usage Period
The validity period of the original coupon is about 3 weeks at most, until August 5, 2023 (Sat).

### Usage Requirements
Limit on number of nights
- Up to 7 nights per reservation or application

No limit on number of uses

### Facilities where Coupons can be used
Stores registered as "Fukui de Otoku Coupon" participating stores within Fukui Prefecture

## Source
- List of "Fukui de Otoku Coupon" participating stores by <a href=https://www.fukui-digital.co.jp/>Fukui Digital Co., Ltd.</a> → Provided by <a href=https://www.ftu-fukui.or.jp/>Fukui Tourism Federation</a> and <a href=https://code4fukui.github.io/>Code for FUKUI</a>

## Related
- [Fukui Prefecture Tourism Survey (Fukui Tourism Federation)](https://code4fukui.github.io/fukui-kanko-stat/)