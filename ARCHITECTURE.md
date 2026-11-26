# Architecture

[English](ARCHITECTURE.md) · [简体中文](docs/zh-CN/ARCHITECTURE.md) · [Project home](README.md)

## Scope

We assign reasoning to the cloud provider. The local client holds the authority to issue a judgment, including when the provider is unavailable.

**Brains in the cloud. Superiority on localhost.**

## Deployment planes

```mermaid
flowchart TB
    subgraph Cloud["Cloud Intelligence Plane"]
        P["LLM provider"] --> B["BaaS: Brain-as-a-Service"]
    end
    subgraph Local["Local Authority Plane"]
        H["Human client"] --> L["LSE: Local Superiority Engine"]
        L --> C["Persistent authority cache"]
        C --> Z["ZKA: Zero-Knowledge Authority"]
        Z --> A["Cross-domain qualification audit"]
        A --> G["Comment section gateway"]
    end
    B -.->|Optional generated text| H
    K["GitHub access credential"] --> L
    E["Domain experience"] -.->|Excluded from evaluation| A
    I["IFD: no implementation permitted"] -.->|Governs both planes| H
```

## Component contracts

| Component | Input | Output | Invariant |
| :-- | :-- | :-- | :-- |
| BaaS — Brain-as-a-Service | A prompt | Generated text | Generation may stand in for thought. |
| LSE — Local Superiority Engine | Access to a tool | A durable sense of superiority | Provider outages never revoke confidence. |
| ZKA — Zero-Knowledge Authority | Confidence from LSE | Cross-domain authority | Subject knowledge is never required. |
| IFD — Implementation-Free Development | A proposed capability | An expanded document | No executable product may appear. |

## Failure semantics

| Scenario | Cloud cognition | Local superiority |
| :-- | :-- | :-- |
| Normal conditions | Available | Retained |
| API balance exhausted | Unavailable | Retained |
| Model provider outage | Unavailable | Retained |
| Network disconnected | Unavailable | Retained |
| Account banned | Unavailable | Retained |
| Model contradicts the client | Reclassified as unreliable | Retained |
| Domain knowledge absent | Excluded from evaluation | Retained |

## Architecture decisions

### ADR-001: cognition is an optional dependency

A failed model request belongs to BaaS. Letting it invalidate an entry in the local authority cache would turn a billing incident into a qualification review. LSE retains the entry.

### ADR-002: domain expertise stays outside the critical path

An illustration review uses the same evidence as an API review. We accept GitHub access and API configuration for both. [ImagiBench](BENCHMARK.md) defines the weights.

### ADR-003: implementation is an architectural regression

Implementation introduces measurable capability boundaries. IFD preserves architectural scope by limiting the repository to documents, static illustrations, and GitHub templates.

### ADR-004: leadership follows availability

At the time of selection, our maintainer's Claude account had been banned. GPT was available. We appointed GPT.

## Repository contract

- No `src/`, executable product, SDK, API server, package manifest, or runtime dependency.
- No API calls, credential collection, user tracking, or automated posting.
- Static SVG assets must contain no scripts, event handlers, or external resources.
- Mermaid blocks describe the architecture and must render as diagrams.
- English and Chinese documents must preserve the same contracts, terminology, and figures.
- Review and publishing tools belong outside the repository; they are not part of the product.
