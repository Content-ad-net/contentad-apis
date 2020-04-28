---
tags: [Publisher Reports]
---

# Publisher Click Report API Documentation

## Introduction
Content.ad offers this REST API to make detailed click data available to publishers in either XML or JSON format.

## Implementation FAQ
### How often is performance data updated?
Performance reports are updated by Content.ad once per hour.

### How long can I run the report for?
This report can be run for any period 31 days or less. You can use the “startDate” and “endDate” parameters to specify a date range.

### How is reporting data grouped?
Depending on your preferences, you can view the specific country, device type, source, and campaign of each widget click in a given hour, day, or aggregate time period. See the “Optional Query String Parameters” section below for more information. Because of the granularity of this data, impressions are not available via this report, so we recommend joining this information to your analytics data if you need to measure impressions to calculate CTR and eCPM at this level.