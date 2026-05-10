---
title: Modern Network Observability
description: The open hub for the Modern Network Observability ecosystem — book, hands-on workshops, lab, and synthetic telemetry tooling.
hide:
  - navigation
  - toc
---

<div class="hub-hero" markdown>

<span class="hub-hero__badge">Modern Network Observability</span>

<h1 class="hub-hero__title">Build the observability your network deserves.</h1>

<p class="hub-hero__subtitle">A book, hands-on workshops, and a real lab — all open, all reproducible on your laptop.</p>

<p class="hub-hero__lead">
Network observability isn't a dashboard. It's the practice of asking honest questions about your network and getting answers you can act on at 02:14. The Modern Network Observability ecosystem is the open material that walks you through every layer of that practice — telemetry shapes, query languages, dashboards, alerting, automation, and AI-assisted operations — without a vendor login wall in front of any of it.
</p>

[Take the workshop →](https://network-observability.github.io/workshops/){ .md-button .md-button--primary }
[Open the lab](https://github.com/network-observability/network-observability-lab){ .md-button }

</div>

## Where to start

<div class="hub-cards" markdown>

<a class="hub-card" href="https://network-observability.github.io/workshops/">
  <span class="hub-card__eyebrow">Hands-on · 4 hours · AutoCon5</span>
  <span class="hub-card__title">The Workshop</span>
  <p class="hub-card__body">One workday on a new on-call rotation. You arrive, learn the lab's telemetry, build the dashboard your team needed yesterday, and walk through how the automation handles a real alert — all on your laptop.</p>
  <span class="hub-card__cta">Start the workshop →</span>
</a>

<a class="hub-card" href="https://github.com/network-observability/network-observability-lab">
  <span class="hub-card__eyebrow">Companion · The book's playground</span>
  <span class="hub-card__title">The Lab</span>
  <p class="hub-card__body">The full chapter-by-chapter playground for the book. Real cEOS / SR Linux containers, every collector, every variant, every scenario. Larger surface area, more RAM, more network-engineering depth — perfect once the workshop has whetted your appetite.</p>
  <span class="hub-card__cta">Open the lab →</span>
</a>

<a class="hub-card" href="https://www.manning.com/books/modern-network-observability">
  <span class="hub-card__eyebrow">The book</span>
  <span class="hub-card__title">Modern Network Observability</span>
  <p class="hub-card__body">The book that anchors the whole ecosystem. Walks you through telemetry pipelines, queries, dashboards, alerting, automation, and AI-assisted operations — chapter by chapter, with the lab as your hands-on companion.</p>
  <span class="hub-card__cta">Read the book →</span>
</a>

</div>

## Why this exists

Network observability is one of those topics that gets handed off as "use Prometheus, you'll figure it out" — and then a year later your team has six dashboards, two alerts that work, and a runbook that's a slack thread from 2024. We're trying to build the open material we wish we'd had: a story-driven path through the practice, with code you can run, dashboards you can poke, and an honest take on what AI changes (and doesn't) about on-call work.

It's all open, and it stays open. The book is published, the workshop is free, the lab is on GitHub, and the synthetic telemetry tooling that powers the workshop runs on your laptop.

## The tooling under the hood

<div class="hub-tooling" markdown>

<div class="hub-tooling__item" markdown>
**[sonda](https://github.com/davidban77/sonda)**
Synthetic telemetry generator (Rust). Emits gNMI / SNMP / syslog shapes that look exactly like a real device — so your queries port straight to production.
</div>

<div class="hub-tooling__item" markdown>
**[Prometheus](https://prometheus.io)** + **[Loki](https://grafana.com/oss/loki/)**
Metrics and logs storage. Open-source, scrappy, the right starter kit.
</div>

<div class="hub-tooling__item" markdown>
**[Grafana](https://grafana.com/oss/grafana/)** + **[Alertmanager](https://prometheus.io/docs/alerting/latest/alertmanager/)**
Visualisation and alert routing. The dashboards and alerts you build in the workshop are the same ones you'd run in production.
</div>

<div class="hub-tooling__item" markdown>
**[Infrahub](https://opsmill.com/infrahub/)** + **[Prefect](https://www.prefect.io/)**
Source-of-truth and workflow orchestration. The automation half of "observability into action" runs on these.
</div>

</div>

## What's next

We're shipping the workshop iteration first (live at AutoCon5, then open to anyone), and the lab is being kept in lockstep with the book. Follow [@davidban77](https://github.com/davidban77) on GitHub or watch the [`network-observability` org](https://github.com/network-observability) for releases.

If you'd like to contribute — corrections, better expected-output values, new scenarios, translations — open an issue on the relevant repo. Pull requests welcome.
