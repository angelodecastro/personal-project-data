# Dairy Cow Health Event Detection Using Multimodal Data

**Author**: Angelo De Castro

**Program**: PhD in Animal Sciences, University of Florida

**Course**: ABE 6933 Special Topics in Agricultural and Biological Engineering

**Assignment**: Activity 5 Managing Data with Git

**Research Focus**: Machine Learning, Deep Learning, Precision Livestock Farming, Computer Vision

## Project Overview

This repository contains sample multimodal data for building machine learning models that detect health and reproductive events in dairy cows. By combining data from three different sensor types, the goal is to improve early event detection in precision livestock farming systems.

## Data Modalities

**Activity Sensor Data** (`activity_sensor_data.csv`)

Accelerometer-based behavioral data collected from ear or leg tags. Includes step counts, lying and standing time, rumination duration, and raw acceleration values along three axes.

**Milk Yield and Composition Data** (`milk_yield_composition.csv`)

Milking records collected at each milking session. Includes milk yield, fat and protein percentages, somatic cell count, and electrical conductivity. These indicators are commonly used to monitor udder health and reproductive status.

**Body Condition Score Data** (`body_condition_scores.csv`)

Morphometric measurements and body condition scores assessed visually or through image-based methods. Includes body weight, hip width, rump angle, and reference image filenames from overhead cameras.

## Event Labels

Each record is labeled with one of three classes used for supervised learning.

- **normal** — No health or reproductive event detected
- **estrus** — Cow is in heat
- **health_event** — A health-related condition is present such as mastitis or lameness

## Potential Applications

- Multimodal data fusion for event classification
- Time-series modeling using recurrent or transformer-based networks
- Computer vision for body condition score estimation
- Anomaly detection for early disease warning in herd management

## Dataset Summary

The sample dataset covers 4 cows recorded from January to February 2024 and is labeled at the observation level for use in supervised machine learning experiments.
