.NET / C#, React + TypeScript, PostgreSQL. Some Go.

Building self-hosted alternatives to SaaS-only ops tooling. The three are built to chain: pulsewatch to detect, sluice to route webhooks, flare to run the incident.

- **[pulsewatch](https://github.com/LindqvistMartin/pulsewatch)** — reliability dashboard: probes, SLOs, error budgets, public status pages ([live demo](https://pulsewatch-ui.onrender.com))
- **[sluice](https://github.com/LindqvistMartin/sluice)** — webhook fan-out daemon in front of the incident tools (Go, [v0.1.0](https://github.com/LindqvistMartin/sluice/releases))
- **[flare](https://github.com/LindqvistMartin/flare)** — incident management: append-only timeline, auto-drafted postmortems, MTTR/MTTA ([live demo](https://flare-ui.onrender.com))
