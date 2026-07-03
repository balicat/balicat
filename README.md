# David Linton

Data platform engineer — 15 years building the data systems traders and analysts decide with, six of them on the oil trading desk at Cargill in Geneva.

**Now:** I design, build and run [EnergyScope.io](https://energyscope.io) end-to-end — an energy-markets data platform. Arrow Flight (gRPC) serving 1.4M time series sub-second from a Parquet / DuckDB lakehouse, Dagster ingestion from 18 vendors, a .NET Excel add-in (~50 functions), a Python SDK, and 56 server-side analytics tools. Currently adopting Apache Iceberg — energy data arrives revised, and honest backtests need the data *as it was known at the time*.

**I like going a layer deeper than most:**

- Contributing to **Apache Arrow .NET** — [IPC compression support for Flight clients](https://github.com/apache/arrow-dotnet/pull/285) (3.5× faster large queries against our production server)
- **Measured evaluations of columnar formats** — Vortex (FastLanes / ALP / FSST) vs Parquet vs Arrow IPC on 73M rows of real energy-market data: storage, serving latency, and object-storage behaviour
- Reverse-engineered QlikView's undocumented QVD binary format and wrote [**qvd-dotnet**](https://github.com/balicat/qvd-dotnet) — a zero-dependency .NET reader/writer, header symbol tables + bit-stuffed index tokens, dual values, CLI included. Not my first: in the '90s Microsoft told me the Works database format was proprietary, so I worked it out myself in Borland C — change one value, diff the binary, repeat. Dictionary encoding got to me early.

**Stack:** Python · C++ · C# / .NET · SQL · Rust — Arrow, Parquet, Iceberg, DuckDB, DataFusion, Polars, Dagster, Snowflake

📍 Geneva → Madrid · [LinkedIn](https://www.linkedin.com/in/davidlinton1) · [energyscope.io](https://energyscope.io)
