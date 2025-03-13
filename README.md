# akvomezurilo

Meaning `water meter` in esperanto.

This is a small project that uses computer vision to read an image of a water meter.


## Goal

Parse image like ![water_meter_raw_01.jpg](img/water_meter_raw_01.jpg) to extract numeric values.

## ToDo

- [ ] Determine which crate to use
- [ ] Set up pipeline to open image / do the required image process on it
- [ ] Isolate sections holding important values
- [ ] Read/Extrapolate the value from those sections
- [ ] Push readings over mqtt