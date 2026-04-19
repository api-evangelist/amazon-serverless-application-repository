# Amazon Serverless Application Repository (amazon-serverless-application-repository)
The AWS Serverless Application Repository enables teams, organizations, and individual developers to find, deploy, and publish serverless applications. It enables you to quickly deploy code samples, components, and complete applications for common use cases such as web and mobile backends, data processing, and IoT applications using AWS SAM templates.

**URL:** [Visit Amazon Serverless Application Repository](https://aws.amazon.com/serverless/serverlessrepo/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Application Repository, AWS, Lambda, SAM, Serverless

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### AWS Serverless Application Repository API
The AWS Serverless Application Repository API provides programmatic access to create and manage serverless applications, application versions, and deployment configurations for publishing and sharing SAM applications.

**Human URL:** [https://docs.aws.amazon.com/serverlessrepo/latest/devguide/appendix-api-reference.html](https://docs.aws.amazon.com/serverlessrepo/latest/devguide/appendix-api-reference.html)

#### Tags:

 - Application Repository, Lambda, Serverless, SAM

#### Properties

- [Documentation](https://docs.aws.amazon.com/serverlessrepo/latest/devguide/appendix-api-reference.html)
- [OpenAPI](openapi/amazon-serverless-application-repository-openapi.yml)
- [JSONSchema - Application](json-schema/amazon-serverless-application-repository-application-schema.json)
- [JSONSchema - VersionSummary](json-schema/amazon-serverless-application-repository-version-summary-schema.json)

## Common Properties

- [Portal](https://aws.amazon.com/serverless/serverlessrepo/)
- [GettingStarted](https://aws.amazon.com/serverless/serverlessrepo/getting-started/)
- [Documentation](https://docs.aws.amazon.com/serverlessrepo/)
- [APIReference](https://docs.aws.amazon.com/serverlessrepo/latest/devguide/appendix-api-reference.html)
- [Console](https://console.aws.amazon.com/serverlessrepo/)
- [Pricing](https://aws.amazon.com/serverless/serverlessrepo/pricing/)
- [FAQ](https://aws.amazon.com/serverless/serverlessrepo/faqs/)
- [Blog](https://aws.amazon.com/blogs/compute/tag/serverless-application-repository/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Support](https://aws.amazon.com/premiumsupport/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [GitHubOrganization](https://github.com/aws)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/serverless-application-repository)

## Features

| Name | Description |
|------|-------------|
| One-Click Deployment | Deploy pre-built serverless applications with a single click from the SAR console. |
| SAM Template Support | Publish applications as AWS SAM templates with full CloudFormation resource support. |
| Semantic Versioning | Manage multiple application versions using semantic versioning for controlled updates. |
| Public and Private Sharing | Share applications publicly to the entire AWS community or privately within your organization. |
| Nested Applications | Compose complex serverless architectures using nested SAM application references. |
| Policy Sharing | Control who can deploy your application using resource-based policies. |
| License Management | Attach open source licenses to applications using SPDX license identifiers. |
| CloudFormation Integration | Deploy applications through CloudFormation changesets for full infrastructure-as-code support. |

## Use Cases

| Name | Description |
|------|-------------|
| Rapid Prototyping | Quickly deploy serverless application templates for common patterns like APIs, data processing, and IoT. |
| Internal Application Sharing | Share production-ready serverless building blocks across teams within your organization. |
| Open Source Distribution | Publish open source serverless applications to the public SAR catalog. |
| Partner Integration Patterns | Distribute serverless integration patterns to AWS partner customers. |
| Microservice Templates | Package and share reusable microservice patterns as deployable SAR applications. |
| DevOps Automation | Automate deployment of pre-vetted serverless infrastructure patterns via CI/CD pipelines. |

## Integrations

| Name | Description |
|------|-------------|
| AWS SAM | Native integration with the AWS Serverless Application Model for packaging and publishing. |
| AWS CloudFormation | Applications are deployed via CloudFormation change sets for full IaC integration. |
| AWS Lambda | The primary compute runtime for all SAR-deployed serverless applications. |
| Amazon API Gateway | Commonly bundled with SAR applications for HTTP API exposure. |
| AWS CodePipeline | Automate SAR application publishing as part of CI/CD pipelines. |
| AWS Serverless Framework | Third-party Serverless Framework plugins support SAR publishing workflows. |
| Amazon DynamoDB | Frequently included as a data store in SAR application templates. |
| Amazon S3 | Used for hosting static content and storing SAR application artifacts. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [AWS Serverless Application Repository API](openapi/amazon-serverless-application-repository-openapi.yml)

### JSON Schema

- [Application](json-schema/amazon-serverless-application-repository-application-schema.json)
- [ApplicationSummary](json-schema/amazon-serverless-application-repository-application-summary-schema.json)
- [VersionSummary](json-schema/amazon-serverless-application-repository-version-summary-schema.json)
- [ApplicationPolicyStatement](json-schema/amazon-serverless-application-repository-application-policy-statement-schema.json)

### JSON Structure

- [Application](json-structure/amazon-serverless-application-repository-application-structure.json)
- [VersionSummary](json-structure/amazon-serverless-application-repository-version-summary-structure.json)

### JSON-LD

- [Amazon SAR Context](json-ld/amazon-serverless-application-repository-context.jsonld)

### Examples

- [Application Example](examples/amazon-serverless-application-repository-application-example.json)
- [VersionSummary Example](examples/amazon-serverless-application-repository-version-summary-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon SAR API](capabilities/shared/amazon-serverless-application-repository.yaml) — 10 operations for application, version, changeset, and policy management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Serverless App Management](capabilities/serverless-app-management.yaml) | Amazon SAR | 8 | Serverless Developer, Platform Engineer |

## Vocabulary

- [Amazon SAR Vocabulary](vocabulary/amazon-serverless-application-repository-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 6 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon SAR Spectral Rules](rules/amazon-serverless-application-repository-spectral-rules.yml) — 20 rules across 9 categories enforcing Amazon Serverless Application Repository API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
