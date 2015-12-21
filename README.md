# Qlik Sense Timeline Chart

## Qlik Sense Timeline Chart using the Google Chart API

Project Site: https://github.com/kaihj/qlik-sense-timeline

### Overview

The Qlik Sense Timeline Chart is a versatile chart that allows you to depict how multiple artifacts, be they projects or resources, are active or used over time in relation to each other.

Examples:

- You are managing a software project and want to illustrate who is doing what and when
- You are organising a conference and need to schedule meeting rooms
- You are running marketing campaigns and would like a scheduling overview

The Qlik Sense Timeline Chart leverages the [Google Chart API](https://developers.google.com/chart/interactive/docs/gallery/timeline).

### Usage

Use 3 or 4 dimensions (no measures):

- Dim 1 (required): Main dimension and row label
- Dim 2 (optional): Bar label
- Dim 3 (required): start date, format YYYY-MM-DD (ISO)
- Dim 4 (required): end date, format YYYY-MM-DD (ISO)

You currently need to ensure that all start and end dates exist. Dates will need to be converted to YYYY-MM-DD as required by the Google Chart API.

Three dimensions (without optional bar labels):
![image](https://cloud.githubusercontent.com/assets/1283509/11930981/79d05c8a-a7e0-11e5-9742-4366ed0b76ee.png)

### Custom settings:

Group row labels
Show row labels

![image](https://cloud.githubusercontent.com/assets/1283509/11931005/aec12122-a7e0-11e5-9dc4-0d04514df426.png)

====

Screenshot:

![image](https://cloud.githubusercontent.com/assets/1283509/11930950/429d68f2-a7e0-11e5-87bd-11d620ec2400.png)
