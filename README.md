# PulseWatch

**PulseWatch** is an API monitoring platform focused on service availability, response times, and endpoint health.

## Overview

PulseWatch aims to help developers check the current state of their HTTP APIs through on-demand diagnostics and a live dashboard, without installing an agent in the monitored application.

Endpoints can be configured manually or selected from an OpenAPI specification. The initial focus is on immediate feedback, with room to expand into historical metrics, incident tracking, and alerts in the future.

## Core Goals

- Check endpoint availability, HTTP responses, and response times.
- Configure expected results, timeouts, and safe request parameters.
- Import documented API operations from OpenAPI specifications.
- Display the latest check results in a web dashboard.

## Technology Stack

- **Web:** Angular and TypeScript
- **API:** NestJS and TypeScript
- **Persistence (when needed):** PostgreSQL

Additional infrastructure will be introduced as project requirements evolve.

## License

No open-source license is currently granted. All rights reserved.
