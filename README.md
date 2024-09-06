# Awesome AWS Bedrock [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of tools and resources for working with [AWS Bedrock](https://aws.amazon.com/bedrock), the fully managed service for foundation models (FMs) like Claude, Stability AI, and Amazon's own Titan models. This list includes both open-source and proprietary tools that make it easier to integrate and utilize AWS Bedrock in your projects.

## Contents
- [Code Libraries](#code-libraries)
- [Integrations](#integrations)
- [Development Tools](#development-tools)
- [Model Management](#model-management)
- [Compute Optimization](#compute-optimization)

---

## Code Libraries

- **[LangChain](https://github.com/hwchase17/langchain)** - A popular open-source framework for building applications powered by language models. LangChain supports advanced AI tasks such as RAG, prompt orchestration, and integrating AWS Bedrock models.  
  - **License**: Open-source  
  - **Category**: LLM Workflow Orchestration

- **[Boto3 (AWS SDK for Python)](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/bedrock.html)** - The official AWS SDK for Python, with methods for interacting with Amazon Bedrock models. You can invoke models, manage responses, and seamlessly integrate Bedrock models like Claude and Titan into Python applications.  
  - **License**: Open-source  
  - **Category**: SDK, AI Integration

- **[AWS CDK (Cloud Development Kit)](https://github.com/aws/aws-cdk)** - A framework that lets developers define cloud infrastructure in code. With the **Generative AI Constructs Library**, developers can quickly deploy Bedrock models and build scalable generative AI applications.  
  - **License**: Open-source  
  - **Category**: Infrastructure as Code

- **[Amazon Bedrock Samples](https://github.com/aws-samples/amazon-bedrock-samples)** - This repository contains examples for getting started with Amazon Bedrock, covering use cases such as fine-tuning models, prompt engineering, and retrieval-augmented generation.  
  - **License**: Open-source (MIT-0)  
  - **Category**: Code Samples, AI Integration

- **[LangSmith](https://github.com/langchain-ai/langsmith)** - A companion library to LangChain for monitoring and improving LLM applications. It helps manage prompts and track usage of foundation models integrated with AWS Bedrock.  
  - **License**: Open-source  
  - **Category**: LLM Application Management

## Integrations

- **[MuleSoft Bedrock Connector](https://aws.amazon.com/blogs/apn/announcing-mulesofts-open-source-connector-for-amazon-bedrock/)** - MuleSoft's open-source connector for integrating Amazon Bedrock into workflows via the Anypoint platform. Useful for enterprise solutions such as CRM, ERP, and supply chain management.  
  - **License**: Open-source  
  - **Category**: Enterprise, API Integration

## Development Tools

- **[Continue](https://continue.dev)** - A fully configurable code assistant that integrates with VSCode and Jetbrains IDEs. Supports direct configuration for AWS Bedrock, allowing you to streamline code generation and AI development workflows.  
  - **License**: Proprietary  
  - **Category**: Code Assistant, IDE Integration

- **[Dify](https://github.com/wl4g-ai/dify-with-enhanced)** - An open-source AI workflow platform that supports AWS Bedrock models such as Claude (Anthropic), allowing for the rapid development and deployment of AI apps.  
  - **License**: Open-source  
  - **Category**: LLM App Development, RAG, Workflow Automation

## Model Management

- **[Open Artifacts for Bedrock](https://github.com/aws-samples/open_artifacts_for_bedrock)** - This open-source project allows developers to interact with Anthropic's Claude model using Amazon Bedrock, offering features like code generation, text processing, and multimodal support (e.g., spreadsheets and PDFs).  
  - **License**: Open-source  
  - **Category**: Model Management, AI App Development

## Compute Optimization

- **[AWS Trainium and Inferentia](https://www.amazon.science/latest-news/amazon-bedrock-offers-access-to-multiple-generative-ai-models)** - Proprietary accelerators designed to enhance the performance of training and inference for large models, offering better cost-performance ratios for AWS Bedrock deployments.  
  - **License**: Proprietary  
  - **Category**: Hardware Accelerator, AI Compute

---

## Contributing

Feel free to contribute to this list by opening a pull request or suggesting new tools in the Issues section!

---

## License

[CC0-1.0](LICENSE)
