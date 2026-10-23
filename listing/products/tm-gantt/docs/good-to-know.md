---
title: Good to know
order: 40
---
# Schedule data and limits

Tm Gantt reads schedule data and participates in Qlik selections. It does not change source data, reschedule Activities, or calculate dependencies, critical paths, or resource leveling. Qlik Cloud is the supported host; Qlik Sense Client-Managed and Desktop are not supported.

An Activity needs valid start and end dates to appear on the timeline. **Activity type** accepts `activity`, `milestone`, or `summary`. The default row cap is 5,000 and the maximum is 50,000. When a row needs more than twenty lanes, the remaining Activities are in that row's Overflow lane.

Qlik Cloud does not include third-party extensions in image, PDF, PowerPoint, or subscription reports. Use a native Qlik straight table when schedule data must appear in those reports. Tm Gantt also supports snapshots, stories, View data, XLSX data export, and supported embedding.
