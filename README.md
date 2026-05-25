# Formant

Formant — robotics and physical-operations cloud for fleet management, teleoperation, telemetry ingestion, and AI-driven incident management.

San Francisco–based platform spanning an on-robot Agent (ROS / ROS 2 / non-ROS adapters), a REST Admin API at `https://api.formant.io/v1/admin`, a Python package (`pip install formant`) bundling Cloud SDK + Agent SDK, a JavaScript/TypeScript Data SDK for custom modules and embedded views, the `fctl` CLI for SSH / SCP / port-forwarding over Formant's P2P network, and Formant Metaphysics — the AI incident-management layer.

## APIs

- **Formant Admin API** — REST API for devices, fleets, streams, views, commands, events, annotations, files, intervention requests, key-value storage, roles, users, schedules, analytics, presence/online monitoring, and usage metrics
- **Formant Agent SDK** — on-robot Python client (`formant.sdk.agent.v1.Client`) for telemetry ingestion, command handling, and teleoperation hooks
- **Formant Cloud SDK** — Python client (`formant.sdk.cloud.v1.Client`) wrapping the Admin API for programmatic ingest and query
- **Formant Data SDK** — JavaScript / TypeScript SDK powering custom modules, custom views, embedded views, and real-time video

## Resources

- Website: https://formant.io
- Docs: https://docs.formant.io
- API & SDK Reference: https://docs.formant.io/reference
- GitHub: https://github.com/FormantIO
- PyPI: https://pypi.org/project/formant/
- llms.txt: https://docs.formant.io/llms.txt
