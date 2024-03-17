# scooter-demand-prediction

A Scooter sharing scheme is a service in which scooters are made available for shared use to individuals for a short period of time at a cost or for free.

dataset includes

* instant：The unique identifier of the record, incrementing from 1 in chronological order.
* dteday：date in the format dd-mm-yyyy.
* season：Season, the value is 1~4, indicating spring, summer, autumn and winter respectively.
* yr：Year, the value is 0 or 1, indicating 2018 and 2019 respectively.
* mnth：Month, the value is 1~12, representing January to December respectively.
* holiday：Whether it is a holiday, the value is 0 or 1.
* weekday：Day of the week, the value is 0~6, representing Sunday to Saturday respectively.
* workingday：Whether it is a working day, the value is 0 or 1, where 1 indicates that the day is a working day.
* weathersit：Weather conditions, value is 1~3
* temp：Celsius Temperature in degrees Celsius.
* atemp：Feeling temperature in degrees Celsius.
* hum：Relative humidity, expressed as a percentage.
* windspeed：Wind speed in kilometers per hour.
* casual：The number of bicycles rented by non-registered users.
* registered：The number of bicycles rented by registered users.
* cnt：The total number of bicycles rented is equal to casual + registered。
