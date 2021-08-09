---
title: An Approach for the Localization Method of Autonomous Vehicles in the
  Event of Missing GNSS Information
publication_types:
  - "1"
authors:
  - Eraraya
author_notes:
  - Equal contribution.
abstract: The swift development of autonomous car raises concern about its
  safety, although in theory, it has potential to be safer compared to human
  driver. Reliable system for localization is one of the most important factor
  in the safety of autonomous car. A combination of Inertial Measurement Unit
  (IMU), wheel encoder, and Global Navigation Satellite System (GNSS) is
  commonly used to estimate the car position. However, GNSS is prone to
  disconnection because of its high dependency to the external environment and
  low sampling rate. This paper proposes assisted GNSS localization system to
  address the problem. This system utilizes Error-state Kalman Filter (ESKF) and
  Residual Long Short-Term Memory (Residual LSTM) as an estimator for the car’s
  position when GNSS disconnection happens. A neural-network model approach with
  Residual LSTM is independent to external environment and easily accessible
  locally, making it a more reliable replacement for estimating position in the
  event of GNSS’s disconnection. Implementation in CARLA Simulator shows the
  system could reduce the deviation in position estimation caused by the absence
  of GNSS. By having a localization system that works in fully offline mode
  without meaningful additional cost, the proposed idea is expected to enable a
  low-cost, reliable global navigation system in the future.
draft: false
featured: false
tags:
  - Deep Learning
image:
  filename: featured
  focal_point: Smart
  preview_only: false
summary: Utilizing ESKF as the state‑estimator and Residual LSTM to make the
  localization of an autonomous car more reliable in the absence of GPS data (an
  improvement to our [previous
  publication](https://doi.org/10.1109/ICEVT48285.2019.8993992)).
date: 2021-08-09T20:00:38.236Z
---
