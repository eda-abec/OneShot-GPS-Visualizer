# OneShot report with Coordinates Visualizer

Displays report from [OneShot](https://github.com/drygdryg/OneShot), annotated by [os_gps_merge](https://github.com/eda-abec/OneShot-GPS-Merge) on OpenStreetMap.

## Usage
All you need is to open the HTML file in web browser and load a .csv file obtained from [os_gps_merge](https://github.com/eda-abec/OneShot-GPS-Merge).

## CSV Format
Columns are same as in OneShot report, with `CurrentLatitude` and `CurrentLongitude` added to end.
```
encoding="utf-8"
delimiter=';'
```

## TODOs
- improve popups
- search bar, maybe?
- make file input interface more decent, or even support drag&drop over whole page
- some name and icon in header and tab bar
- handle loading/reloading. Should already loaded points be kept?
- detect invalid format and show error

## Acknowledgements

Author: [eda-abec](https://github.com/eda-abec)\
Date: 12/2020\
Based on and Thanks to:
- [OneShot](https://github.com/drygdryg/OneShot)
- [WiGLE.net](https://github.com/wiglenet)

See also [os_gps_merge](https://github.com/eda-abec/OneShot-GPS-Merge)
