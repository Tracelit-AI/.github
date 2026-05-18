<div align="center">
  <img src="https://pub-6b1af3935caa42cbaa9d275f9e5e289b.r2.dev/Landing%20Page/logo.png" alt="Tracelit" width="240" />

  <br /><br />

  **AI-powered platform analytics and auto-resolutions.**

  [![Website](https://img.shields.io/badge/Website-tracelit.io-orange?style=flat-square)](https://tracelit.io)
  [![Twitter](https://img.shields.io/badge/Twitter-@tracelitai-1DA1F2?style=flat-square&logo=twitter)](https://x.com/tracelitai)
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-Tracelit-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/company/traceltai)
  [![Email](https://img.shields.io/badge/Email-hey@tracelit.io-EA4335?style=flat-square&logo=gmail)](mailto:hey@tracelit.io)

</div>

---

## Watch the Demo

<div align="center">
  <a href="https://pub-6b1af3935caa42cbaa9d275f9e5e289b.r2.dev/Landing%20Page/New%20Tracelit%20Dashboard.mp4">
    <img src="https://pub-6b1af3935caa42cbaa9d275f9e5e289b.r2.dev/Landing%20Page/logo.png" alt="Watch the Tracelit Dashboard Demo" width="600" />
    <br />
    ▶ Click to watch the dashboard walkthrough
  </a>
</div>

> GitHub's markdown renderer does not support inline video playback. Click the link above to watch the full demo.

---

## What is Tracelit?

Tracelit is an AI-powered observability platform that automatically detects, traces, and resolves issues across your stack — before they impact your users.

Gone are the days of digging through logs, manually correlating traces, and waking up to production fires at 3am. Tracelit watches your platform continuously, understands what's normal, and surfaces anomalies with full context and suggested fixes — automatically.

---

## Key Features

| Feature | Description |
|---------|-------------|
| **AI Auto-Resolution** | Tracelit doesn't just alert — it diagnoses root causes and suggests (or applies) fixes automatically |
| **Distributed Tracing** | End-to-end request tracing across microservices, queues, and databases |
| **Real-Time Analytics** | Live dashboards with performance metrics, error rates, and latency breakdowns |
| **Multi-Language SDKs** | First-class support for Node.js, Ruby, Go, and .NET |
| **Anomaly Detection** | ML-based baseline modeling that learns your system's normal behavior |
| **Alerting & Runbooks** | Configurable alerts with automated runbook execution to reduce MTTR |

---

## What We're Building

| SDK | Language | Status |
|-----|----------|--------|
| [tracelit-node](https://github.com/tracelit-ai/tracelit-node) | Node.js / TypeScript | 🟢 Active |
| [tracelit-ruby](https://github.com/tracelit-ai/tracelit-ruby) | Ruby | 🟢 Active |
| [tracelit-go](https://github.com/tracelit-ai/tracelit-go) | Go | 🟢 Active |
| [tracelit-dotnet](https://github.com/tracelit-ai/tracelit-dotnet) | C# / .NET | 🟢 Active |

---

## Get Started

```bash
# Node.js
npm install @tracelit/node

# Ruby
gem install tracelit

# Go
go get github.com/tracelit-ai/tracelit-go

# .NET
dotnet add package Tracelit
```

Then instrument your app in just a few lines:

```typescript
import { Tracelit } from '@tracelit/node';

Tracelit.init({
  apiKey: process.env.TRACELIT_API_KEY,
  serviceName: 'my-service',
});
```

Visit [tracelit.io](https://tracelit.io) to create a free account and grab your API key.

---

## Why Tracelit?

- **Reduce alert fatigue** — AI filters noise and surfaces only what matters
- **Faster incident response** — from detection to resolution in minutes, not hours
- **Zero config tracing** — auto-instrumentation means you're set up in under 5 minutes
- **Built for scale** — handles high-throughput distributed systems with ease

---

## Contributing

We welcome contributions across all SDKs. Check the `CONTRIBUTING.md` in each repo, open an issue, or reach out at **hey@tracelit.io**.

---

<div align="center">
  <sub>Built with ☕ · <a href="https://tracelit.io">tracelit.io</a></sub>
</div>
