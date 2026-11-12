# AWS serverless

AWS's own skills to design and build Lambda, API Gateway and Step Functions and to estimate cost before a deploy, with the AWS Knowledge, IaC, Pricing and Serverless MCP servers.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/aws-serverless

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install aws-serverless@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add aws-serverless@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Serverless on AWS with AWS's own skills: Lambda design, packaging, debugging and observability, API Gateway and Step Functions, and a deploy skill that analyses the code and estimates cost before anything ships. Approve every deploy and stack deletion yourself. The Knowledge server needs no account; the IaC, Pricing and Serverless servers use your `AWS_PROFILE` and `AWS_REGION`, and the Serverless server runs without `--allow-write`, so it stays read-only.

## Skills

- `aws-lambda`: Design, build, deploy, test, and debug serverless applications with AWS Lambda. Triggers on phrases like: Lambda function, event source, serverless application,…
- `api-gateway`: Build, manage, and operate APIs with Amazon API Gateway (REST, HTTP, and WebSocket). Triggers on phrases like: API Gateway, REST API, HTTP API, WebSocket API, c…
- `aws-step-functions`: Build workflows with AWS Step Functions state machines using the JSONata query language. Covers Amazon States Language (ASL) structure, state types, variables,…
- `deploy`: Deploy applications to AWS. Triggers on phrases like: deploy to AWS, host on AWS, run this on AWS, AWS architecture, estimate AWS cost, generate infrastructure.…

## MCP servers

- **AWS Knowledge**: AWS's official knowledge server: AWS documentation, API references, What's New posts and regional availability. No account needed.
- **AWS IaC**: AWS's infrastructure-as-code server: CloudFormation and CDK documentation, template validation and deployment troubleshooting. Needs uv and AWS credentials.
- **AWS Pricing**: AWS's pricing server: service prices and cost estimates from the AWS Price List API. Needs uv and AWS credentials.
- **AWS Serverless**: AWS's serverless server in its default read-only mode: SAM guidance, Lambda and event-source details, logs and metrics. Needs uv and AWS credentials.

All skills are copied unchanged from [awslabs/agent-plugins](https://github.com/awslabs/agent-plugins) under Apache 2.0; each skill folder includes its licence and `SOURCE.md` with the source commit.
