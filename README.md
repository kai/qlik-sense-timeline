# [Qlik Sense](http://global.qlik.com/uk/explore/products/sense) Timeline Chart

- GitHub URL: https://github.com/kaihj/qlik-sense-timeline
- Qlik Branch URL: http://branch.qlik.com/#/project/56728f52d1e497241ae697ef

## Screenshot

![image](https://cloud.githubusercontent.com/assets/1283509/11930950/429d68f2-a7e0-11e5-87bd-11d620ec2400.png)

## Overview

The Qlik Sense Timeline Chart is a versatile chart that allows you to depict how multiple artifacts, be they projects or resources, are active or used over time in relation to each other.

Examples:

- You are managing a software project and want to illustrate who is doing what and when
- You are organising a conference and need to schedule meeting rooms
- You are running marketing campaigns and would like a scheduling overview

The Qlik Sense Timeline Chart leverages the [Google Chart API](https://developers.google.com/chart/interactive/docs/gallery/timeline).

## Usage

Use 3 or 4 dimensions (no measures):

- Dim 1 (required): Main dimension and row label
- Dim 2 (optional): Bar label
- Dim 3 (required): start date, format YYYY-MM-DD (ISO)
- Dim 4 (required): end date, format YYYY-MM-DD (ISO)

You currently need to ensure that all start and end dates exist. Dates will need to be converted to YYYY-MM-DD as required by the Google Chart API.

Example configuration using three dimensions (without optional bar labels):

![image](https://cloud.githubusercontent.com/assets/1283509/11930981/79d05c8a-a7e0-11e5-9742-4366ed0b76ee.png)

## Custom settings:

Additional parameters can be set to change the appearance of the chart:

- Show row labels: shows or hides the row labels in column 1
- Group row labels: groups labels with the same name into a single row
 
![image](https://cloud.githubusercontent.com/assets/1283509/11931005/aec12122-a7e0-11e5-9dc4-0d04514df426.png)
