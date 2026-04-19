# Amazon API Gateway (amazon-api-gateway)
Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-api-gateway/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Gateway, HTTP API, REST API, Serverless, WebSocket

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Amazon API Gateway REST API
RESTful APIs that are optimized for serverless workloads and HTTP backends using HTTP APIs.

**Human URL:** [https://aws.amazon.com/api-gateway/](https://aws.amazon.com/api-gateway/)

#### Tags:

 - API Management, REST, Serverless

#### Properties

- [Documentation](https://docs.aws.amazon.com/apigateway/latest/developerguide/welcome.html)
- [OpenAPI](https://docs.aws.amazon.com/apigateway/latest/api/API_Operations.html)
- [Pricing](https://aws.amazon.com/api-gateway/pricing/)
- [Getting Started](https://aws.amazon.com/api-gateway/getting-started/)
- [FAQ](https://aws.amazon.com/api-gateway/faqs/)
- [Features](https://aws.amazon.com/api-gateway/features/)
- [Developer Guide](https://docs.aws.amazon.com/apigateway/latest/developerguide/welcome.html)
- [API Reference](https://docs.aws.amazon.com/apigateway/latest/api/API_Operations.html)
- [Quotas](https://docs.aws.amazon.com/apigateway/latest/developerguide/limits.html)
- [OpenAPI](openapi/amazon-api-gateway-openapi.yaml)
- [JSONSchema](json-schema/amazon-api-gateway-accesslogsettings-schema.json)
- [JSONSchema](json-schema/amazon-api-gateway-api-schema.json)
- [JSONSchema](json-schema/amazon-api-gateway-apikey-schema.json)
- [JSONSchema](json-schema/amazon-api-gateway-apikeys-schema.json)
- [JSONSchema](json-schema/amazon-api-gateway-apistage-schema.json)
- [JSONStructure](json-structure/amazon-api-gateway-accesslogsettings-structure.json)
- [JSONStructure](json-structure/amazon-api-gateway-apikey-structure.json)
- [JSONStructure](json-structure/amazon-api-gateway-apikeys-structure.json)
- [JSONLD](json-ld/amazon-api-gateway-context.jsonld)

### Amazon API Gateway WebSocket API
Build real-time two-way communication applications with WebSocket APIs.

**Human URL:** [https://aws.amazon.com/api-gateway/](https://aws.amazon.com/api-gateway/)

#### Tags:

 - Bi-Directional, Real-Time, WebSocket

#### Properties

- [Documentation](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-websocket-api.html)
- [Getting Started](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-websocket-api-overview.html)
- [AsyncAPI](asyncapi/amazon-api-gateway-websocket-asyncapi.yml)
- [JSON-LD](json-ld/amazon-api-gateway-context.jsonld)

### Amazon API Gateway HTTP API
Lower latency and lower cost alternative to REST APIs with essential features for building HTTP-based APIs.

**Human URL:** [https://aws.amazon.com/api-gateway/](https://aws.amazon.com/api-gateway/)

#### Tags:

 - Cost Effective, HTTP, Low Latency

#### Properties

- [Documentation](https://docs.aws.amazon.com/apigateway/latest/developerguide/http-api.html)
- [Comparison](https://docs.aws.amazon.com/apigateway/latest/developerguide/http-api-vs-rest.html)

### Amazon API Gateway Management API
API for directly managing runtime aspects of deployed APIs, including sending data to connected WebSocket clients via the @connections endpoint and managing connection state.

**Human URL:** [https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-how-to-call-websocket-api-connections.html](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-how-to-call-websocket-api-connections.html)

#### Tags:

 - Connections, Management, Runtime, WebSocket

#### Properties

- [Documentation](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-how-to-call-websocket-api-connections.html)

## Common Properties

- [Blog](https://aws.amazon.com/blogs/compute/category/application-services/amazon-api-gateway/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Console](https://console.aws.amazon.com/apigateway)
- [CLIReference](https://docs.aws.amazon.com/cli/latest/reference/apigateway/)
- [SDK](https://aws.amazon.com/tools/)
- [Status](https://status.aws.amazon.com/)
- [Compliance](https://aws.amazon.com/compliance/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [Website](https://aws.amazon.com/api-gateway/)
- [Documentation](https://docs.aws.amazon.com/apigateway/)
- [Pricing](https://aws.amazon.com/api-gateway/pricing/)
- [Getting Started](https://aws.amazon.com/api-gateway/getting-started/)
- [FAQ](https://aws.amazon.com/api-gateway/faqs/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [GitHubOrganization](https://github.com/aws)
- [StackOverflow](https://stackoverflow.com/questions/tagged/amazon-api-gateway)
- [CodeExamples](https://docs.aws.amazon.com/code-library/latest/ug/api-gateway_code_examples.html)
- [SpectralRules](rules/amazon-api-gateway-spectral-rules.yml)
- [NaftikoCapability](capabilities/api-gateway-management.yaml)
- [Vocabulary](vocabulary/amazon-api-gateway-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| REST API Management | Create, configure, and manage REST APIs with resources, methods, integrations, and request/response transformations. |
| WebSocket API Support | Build real-time two-way communication applications with WebSocket APIs supporting persistent connections and message routing. |
| HTTP API Support | Deploy lightweight HTTP APIs with lower latency and cost than REST APIs, optimized for Lambda and HTTP backends. |
| Stage and Deployment Management | Manage deployment stages with canary releases, stage variables, and throttling configurations for blue/green deployments. |
| API Security and Authorization | Secure APIs with IAM authorization, Lambda authorizers, Cognito user pools, and resource-based policies. |

## Use Cases

| Name | Description |
|------|-------------|
| Serverless API Backend | Build serverless REST APIs backed by Lambda functions using API Gateway as the front door for request routing. |
| Microservices Gateway | Use API Gateway as a unified entry point for microservices, providing routing, authentication, and rate limiting. |
| Real-Time Applications | Build chat, collaboration, and live data streaming applications using WebSocket APIs with persistent client connections. |
| API Lifecycle Automation | Automate API creation, deployment, and versioning using the API Gateway control plane API in CI/CD pipelines. |

## Integrations

| Name | Description |
|------|-------------|
| AWS Lambda | Integrate API Gateway with Lambda functions for serverless request processing without managing infrastructure. |
| AWS Cognito | Use Cognito user pools and identity pools for managed authentication and authorization in API Gateway. |
| AWS WAF | Protect API Gateway endpoints with AWS WAF rules for rate limiting and protection against common web exploits. |
| AWS CloudWatch | Monitor API performance, errors, and latency using CloudWatch metrics and logs integrated with API Gateway. |

## Artifacts

### OpenAPI

- [Amazon API Gateway REST API OpenAPI](openapi/amazon-api-gateway-openapi.yaml)

### JSON Schema

- [amazon-api-gateway-accesslogsettings-schema.json](json-schema/amazon-api-gateway-accesslogsettings-schema.json)
- [amazon-api-gateway-api-schema.json](json-schema/amazon-api-gateway-api-schema.json)
- [amazon-api-gateway-apikey-schema.json](json-schema/amazon-api-gateway-apikey-schema.json)
- [amazon-api-gateway-apikeys-schema.json](json-schema/amazon-api-gateway-apikeys-schema.json)
- [amazon-api-gateway-apistage-schema.json](json-schema/amazon-api-gateway-apistage-schema.json)
- [amazon-api-gateway-authorizer-schema.json](json-schema/amazon-api-gateway-authorizer-schema.json)
- [amazon-api-gateway-authorizers-schema.json](json-schema/amazon-api-gateway-authorizers-schema.json)
- [amazon-api-gateway-basepathmapping-schema.json](json-schema/amazon-api-gateway-basepathmapping-schema.json)
- [amazon-api-gateway-basepathmappings-schema.json](json-schema/amazon-api-gateway-basepathmappings-schema.json)
- [amazon-api-gateway-canarysettings-schema.json](json-schema/amazon-api-gateway-canarysettings-schema.json)
- [amazon-api-gateway-createapikeyrequest-schema.json](json-schema/amazon-api-gateway-createapikeyrequest-schema.json)
- [amazon-api-gateway-createauthorizerrequest-schema.json](json-schema/amazon-api-gateway-createauthorizerrequest-schema.json)
- [amazon-api-gateway-createbasepathmappingrequest-schema.json](json-schema/amazon-api-gateway-createbasepathmappingrequest-schema.json)
- [amazon-api-gateway-createdeploymentrequest-schema.json](json-schema/amazon-api-gateway-createdeploymentrequest-schema.json)
- [amazon-api-gateway-createdocumentationpartrequest-schema.json](json-schema/amazon-api-gateway-createdocumentationpartrequest-schema.json)
- ... and 49 more

## Capabilities

- [Amazon API Gateway API](capabilities/shared/amazon-api-gateway.yaml) — 2 operations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [API Gateway Management](capabilities/api-gateway-management.yaml) | Amazon API Gateway REST API | 2 | API Developer, Platform Engineer |

## Vocabulary

- [Amazon API Gateway Vocabulary](vocabulary/amazon-api-gateway-vocabulary.yaml)

## Rules

- [Amazon API Gateway Spectral Rules](rules/amazon-api-gateway-spectral-rules.yml) — 5 rules

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
