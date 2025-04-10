---
title: A Novel Transformer-Based IMU Self-Calibration Approach through On-Board RGB
  Camera for UAV Flight Stabilization
authors:
- Danilo Avola
- Luigi Cinque
- Gian Luca Foresti
- Romeo Lanzino
- Marco Raoul Marini
- Alessio Mecca
- Francesco Scarcello
date: '2023-01-01'
publishDate: '2025-04-10T16:22:34.799299Z'
publication_types:
- article-journal
publication: '*Sensors*'
doi: 10.3390/s23052655
abstract: During flight, unmanned aerial vehicles (UAVs) need several sensors to follow
  a predefined path and reach a specific destination. To this aim, they generally
  exploit an inertial measurement unit (IMU) for pose estimation. Usually, in the
  UAV context, an IMU entails a three-axis accelerometer and a three-axis gyroscope.
  However, as happens for many physical devices, they can present some misalignment
  between the real value and the registered one. These systematic or occasional errors
  can derive from different sources and could be related to the sensor itself or to
  external noise due to the place where it is located. Hardware calibration requires
  special equipment, which is not always available. In any case, even if possible,
  it can be used to solve the physical problem and sometimes requires removing the
  sensor from its location, which is not always feasible. At the same time, solving
  the problem of external noise usually requires software procedures. Moreover, as
  reported in the literature, even two IMUs from the same brand and the same production
  chain could produce different measurements under identical conditions. This paper
  proposes a soft calibration procedure to reduce the misalignment created by systematic
  errors and noise based on the grayscale or RGB camera built-in on the drone. Based
  on the transformer neural network architecture trained in a supervised learning
  fashion on pairs of short videos shot by the UAV’s camera and the correspondent
  UAV measurements, the strategy does not require any special equipment. It is easily
  reproducible and could be used to increase the trajectory accuracy of the UAV during
  the flight.
links:
- name: URL
  url: https://www.mdpi.com/1424-8220/23/5/2655
---
