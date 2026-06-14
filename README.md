.NET / C#, React + TypeScript, PostgreSQL. Some Go.

Building self-hosted alternatives to SaaS-only ops tooling. The three are built to chain: pulsewatch to detect, sluice to route webhooks, flare to run the incident.

- **[pulsewatch](https://github.com/LindqvistMartin/pulsewatch)** — reliability dashboard: probes, SLOs, error budgets, public status pages ([live demo](https://pulsewatch-ui.onrender.com))
- **[sluice](https://github.com/LindqvistMartin/sluice)** — webhook fan-out daemon in front of the incident tools (Go, early)
- **[flare](https://github.com/LindqvistMartin/flare)** — incident management: append-only timeline, auto-drafted postmortems, MTTR/MTTA ([live demo](https://flare-ui.onrender.com))

In .NET OSS, my [OrderedHashSet sweep](https://github.com/apache/lucenenet/pull/1313) was merged into Apache Lucene.NET; I have an open PR in [Npgsql](https://github.com/npgsql/npgsql/pull/6589).
