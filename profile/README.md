# OPC Expert

**OPC Expert is Windows software for connecting to, viewing, troubleshooting, and integrating industrial OPC data.** It helps automation professionals work with local and remote OPC servers through a visual client, diagnostics, trending, historical data, and developer-friendly web APIs.

[Official website](https://opcexpert.com/) · [Download OPC Expert](https://opcexpert.com/download-opc-expert/) · [Getting started](https://opcexpert.com/support/getting-started-with-opc-expert/) · [Web Server API documentation](https://opcexpert.com/opc-expert-web-server-api-documentation/)

## What OPC Expert does

- Connects to local and remote OPC servers
- Browses OPC servers, branches, and items
- Reads and writes real-time industrial data
- Displays live values, trends, alarms, events, and historical data
- Diagnoses OPC and DCOM communication problems
- Bridges data between OPC DA and OPC UA servers
- Makes OPC data available to applications through REST API and SignalR endpoints
- Supports integrations written in Python, C#, Java, JavaScript, VBA, and other languages that can use HTTP and JSON

## Supported OPC technologies

OPC Expert works with major OPC Classic and OPC Unified Architecture technologies, including:

- OPC DA (Data Access)
- OPC HDA (Historical Data Access)
- OPC A&E (Alarms and Events)
- OPC UA (Unified Architecture)

## OPC Expert Web Server

The OPC Expert Web Server helps developers connect software applications to industrial OPC data without requiring an OPC library in every client application. Its HTTP/HTTPS endpoints support common operations such as:

- `browse` — discover OPC servers, branches, and items
- `connect` — retrieve server and connection information
- `read` — retrieve current OPC item values and properties
- `write` — write values to OPC items and confirm the result
- `subscribe` — create and use OPC data subscriptions
- `history/raw` — retrieve raw historical data
- `history/processed` — retrieve aggregated historical data
- `ping` — verify that the Web Server is available

Responses use JSON so the API can be used from web, desktop, mobile, cloud, and automation applications.

## Developer resources

- [OPC Expert Web Server API documentation](https://opcexpert.com/opc-expert-web-server-api-documentation/)
- [Use OPC Expert with Python](https://opcexpert.com/python)
- [REST API Server overview](https://opcexpert.com/rest-api/)
- [OPC Expert Web Server setup and code generation](https://opcexpert.com/web-server)
- [OPC Expert support and tutorials](https://opcexpert.com/support/)

## Common use cases

- Troubleshoot failed OPC and DCOM connections
- Monitor live industrial process values
- Read OPC UA or OPC DA data from a Python, C#, Java, or JavaScript application
- Send setpoints and commands to connected OPC servers
- Connect legacy OPC DA systems with OPC UA applications
- Expose industrial data through a REST API
- View real-time and historical trends
- Archive OPC data for reporting and analysis

## About this GitHub organization

This is the official GitHub organization for **OPC Expert**. Public repositories published here contain official developer resources, API specifications, examples, and documentation for working with OPC Expert.

For current product information and canonical documentation, visit [opcexpert.com](https://opcexpert.com/).

## Support

- [OPC Expert support](https://opcexpert.com/support/)
- [Contact OPC Expert](https://opcexpert.com/contact/)
- [Request a feature](https://opcexpert.com/request-a-feature/)

---

OPC Expert is designed for control system engineers, industrial automation professionals, system integrators, developers, and technical support teams working with OPC connectivity and industrial data.
