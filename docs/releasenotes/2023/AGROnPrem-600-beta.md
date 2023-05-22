### AnalyticsGate OnPrem Reporting

*New Features*
- Completely redesigned installer
- Full Microsoft .NET 6 support
- All application dependencies have been updated
- Implement new filter logic for excluded values
- HTTP/2 protocol support
- New Chromium browser engine for chart rendering
- Support of new license types
- New output format of the report as Png and Jpg file
- New handling of selection of excluded values

*Fixed Bugs*
- General bug fixes to optimize processing
- Session pool optimization

### AnalyticsGate OnPrem Management Console

*New Features*
- Improved handling of values in static selections
- Improved communication with reporting service
- Insert warning when session limit is exeeded
- Download button for shared content
- New Property in selections to handle excluded values
- Add Report count on dashboard

*Fixed Bugs*
- Fix pagination in app list
- Fix modal dialog for synchronize apps
- Fix link to connected applications
- Fix handling of virtual proxies in mashup url

### AnalyticsGate OnPrem OnDemand Extension

*New Features*
- switch to turn of regular status call's against the reporting connector (qlik session will be closed after timeout, and is not held up open)
