# ElasticDash

ElasticDash is an open-source platform for regression testing of Large Language Model (LLM) applications. It enables you to gather detailed traces of LLM interactions and use them to run automated regression tests, helping you ensure the reliability and quality of your LLM-powered systems as they evolve.

## Key Features

- **LLM Tracing SDKs**: Instrument your Python or JavaScript/TypeScript applications to capture granular traces of LLM calls, tool executions, and custom logic for regression testing.
- **Centralized Logger**: Store and manage all traces in a scalable backend, powered by ClickHouse for high-performance analytics.
- **Automated Regression Testing**: Run automated regression tests on gathered traces and test cases, surfacing results in a user-friendly dashboard.
- **Dashboard for Test Management**: Explore, filter, and analyze traces, test cases, and test runs to monitor regression and quality over time.
- **Open Architecture**: Modular components for logger, backend, and dashboard, allowing flexible deployment and integration into your stack.

## Use Cases

- Automated regression testing for LLM-powered applications
- Monitoring for regressions and quality issues as models or prompts change
- Running and managing test cases for LLM outputs
- Auditing and compliance for AI-driven systems

## Getting Started

1. Deploy the ElasticDash Logger to start collecting traces from your applications.
2. Integrate the ElasticDash SDK into your LLM app for seamless trace collection.
3. Deploy the backend and dashboard to run regression tests and visualize results.

See the documentation in [our documentation](https://github.com/ElasticDash/ElasticDash-Doc) for detailed setup and usage instructions.

## Collaborate with Us

If you are interested in contributing to the projects, feel free to raise issues and make PRs in our repositories! We will constantly review all issues and PRs raised.

If you have any questions, please don't hesitate to contact us via <contact@elasticdash.com>.
