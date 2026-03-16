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

## Source
- List of "Fukui de Otoku Coupon" participating stores by <a href=https://www.fukui-digital.co.jp/>Fukui Digital Co., Ltd.</a> → Provided by <a href=https://www.ftu-fukui.or.jp/>Fukui Tourism Federation</a> and <a href=https://code4fukui.github.io/>Code for FUKUI</a>

## Related
- [Fukui Prefecture Tourism Survey (Fukui Tourism Federation)](https://code4fukui.github.io/fukui-kanko-stat/)

## License
MIT License — see [LICENSE](LICENSE).