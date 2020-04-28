---
tags: [Publisher Reports]
---

# Traffic-Sources-Report-API-Documentation

Please note that this feature requires a unique API key and password. Please contact your account representative for more information.

## Introduction
Content.ad offers this REST API to make the data in the Traffic Sources Report in a publisher's account login available in either XML or JSON format.

## Implementation FAQ
###How do I configure my sources and campaigns so that they appear in this report?
See our FAQ on setting up the Traffic Sources Report.

### How often is performance data updated?
Performance reports are updated by Content.ad once per hour.

### How long can I run the report for?
This report can be run for any period 31 days or less. You can use the "startDate" and "endDate" parameters to specify a date range.

### How is reporting data grouped?
This report can group data by hour, day or aggregate time period and groups performance by widget, source (clientID) and campaign (clientID2). See the “Optional Query String Parameters” section below for more information.