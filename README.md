# AWS X-Ray

AWS X-Ray is a service that helps developers analyze and debug distributed applications by providing end-to-end tracing of requests as they travel through the application, identifying performance bottlenecks and errors. It is now part of Amazon CloudWatch Application Signals for unified observability.

## APIs

### AWS X-Ray API
Distributed tracing API for collecting, analyzing, and visualizing traces from your application.
- **Documentation**: https://docs.aws.amazon.com/xray/latest/devguide/aws-xray.html
- **OpenAPI**: [openapi/aws-x-ray-openapi.yml](openapi/aws-x-ray-openapi.yml) (22 operations)
- **API Reference**: https://docs.aws.amazon.com/xray/latest/api/Welcome.html

## Artifacts

| Directory | Contents |
|---|---|
| [openapi/](openapi/) | 1 OpenAPI specification (22 operations) |
| [json-schema/](json-schema/) | 19+ JSON Schema files |
| [json-structure/](json-structure/) | 19 JSON Structure files |
| [json-ld/](json-ld/) | 1 JSON-LD context file |
| [examples/](examples/) | 19 example files |
| [rules/](rules/) | Spectral ruleset |
| [capabilities/](capabilities/) | Naftiko capability definitions |
| [vocabulary/](vocabulary/) | Domain vocabulary |

## Features

- **End-to-End Tracing** — Trace requests from client to backend across all services.
- **Service Map** — Visualize service dependencies and real-time health indicators.
- **Trace Analytics** — Filter, search, and analyze traces using filter expressions and groups.
- **Sampling Rules** — Control trace collection rates with dynamic sampling rules.
- **Annotations and Metadata** — Add indexed annotations and non-indexed metadata to traces.
- **Error Analysis** — Identify errors, faults, and throttling across distributed services.
- **Latency Analysis** — Identify performance bottlenecks with latency histograms.
- **CloudWatch Integration** — Integrated with CloudWatch Application Signals.
- **SDK Support** — Instrument applications with SDKs for Java, Python, Go, Node.js, Ruby, and .NET.

## Use Cases

- **Performance Optimization** — Identify and resolve latency bottlenecks in distributed applications.
- **Error Debugging** — Trace errors to their root cause across service boundaries.
- **Dependency Analysis** — Understand service dependencies and impact of downstream failures.
- **SLA Monitoring** — Monitor request latency and error rates against service level objectives.
- **Microservices Visibility** — Gain observability into complex microservices architectures.

## Links

- **Website**: https://aws.amazon.com/xray/
- **Getting Started**: https://aws.amazon.com/xray/getting-started/
- **Pricing**: https://aws.amazon.com/xray/pricing/
- **FAQ**: https://aws.amazon.com/xray/faqs/
- **Status**: https://health.aws.amazon.com/health/status

## Maintainers

- **Kin Lane** — kin@apievangelist.com
