# fukui-kanko-coupon

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

This project visualizes usage data from the "Fukui de Otoku Coupon," a campaign by Fukui Prefecture, Japan, to support local tourism businesses affected by the COVID-19 pandemic.

## Demo

[**Interactive 1km Mesh Map of Coupon Usage**](https://code4fukui.github.io/fukui-kanko-coupon/)

The demo visualizes coupon spending data on an interactive map. Users can filter the data by date range, user prefecture, age, gender, and business category.

## Features

- **Interactive Map:** Visualizes coupon spending amounts across Fukui Prefecture on a zoomable map.
- **Geospatial Aggregation:** Data is aggregated into 1km² geographical meshes (Geo3x3) to show spending hotspots.
- **Dynamic Filtering:** Allows filtering of transaction data by:
    - Date Range (from 2023-01-10 to 2023-08-05)
    - User's Home Prefecture
    - User's Age Group
    - User's Gender
    - Business Category

## Open Data

This project provides the following open datasets for analysis and reuse.

- **User Data (CC BY)**
    - [`users.csv`](users.csv): List of users (User ID, Prefecture, Gender, Usage Count, Usage Amount, Age).
    - [`users_amount.csv`](users_amount.csv): Users sorted by total usage amount.
    - [`users_count.csv`](users_count.csv): Users sorted by total usage count.

- **Transaction Data (CC BY)**
    - [`mesh-tr.csv`](mesh-tr.csv): List of all transactions (Transaction Datetime, User ID, Transaction Type, Amount, Cancel Flag, Category, Category2, Geo3x3).
    - [`mesh-tr-total.csv`](mesh-tr-total.csv): Aggregated usage amount per mesh (Geo3x3, Category, Usage Amount).

- **Geospatial Data (CC0)**
    - [`mesh-geo3x3.geojson`](mesh-geo3x3.geojson): GeoJSON file defining the 1km mesh grid used for visualization.

## About the "Fukui de Otoku Coupon"

- [Fukui de Otoku Coupon Campaign (Official Site)](https://fukui-de-coupon.jp/)
- [Campaign Relaunch Announcement (Fukui Prefectural Government)](https://www2.pref.fukui.lg.jp/press/view.php?cod=d76b8D167287688524&whence=72)

## Data Source

The underlying data on participating stores was provided by the <a href=https://www.ftu-fukui.or.jp/>Fukui Tourism Federation</a> and <a href=https://code4fukui.github.io/>Code for FUKUI</a>, based on a list from <a href=https://www.fukui-digital.co.jp/>Fukui Digital Co., Ltd.</a>

## Related Projects

- [Fukui Prefecture Tourism Survey (Fukui Tourism Federation)](https://code4fukui.github.io/fukui-kanko-stat/)

## License

MIT License — see [LICENSE](LICENSE).