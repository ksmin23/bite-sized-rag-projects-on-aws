# Bite-sized RAG Projects on AWS
![Stats](https://img.shields.io/badge/13-RAG_CDK_Projects-blue?style=for-the-badge)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

Collection of the bite-sized RAG(Retrieval Augmented Generation) projects implemented on AWS

- Simple, easy to learn RAG Architectures
- Deployable by IaC (AWS CDK)
- Various combinations of Vector Store, LLMs, and Embedding Models


| Vector store | Hosting LLM, Embedding Model | Git Url | Architecture |
|--------------|------------------------------|---------|--------------|
| opensearch | bedrock | [rag-with-amazon-bedrock-and-opensearch](https://github.com/aws-samples/aws-kr-startup-samples/tree/main/gen-ai/rag-with-amazon-bedrock-and-opensearch) | ![](./images/rag_with_bedrock_and_opensearch_arch.svg) |
| opensearch | sagemaker | [rag-with-amazon-opensearch-and-sagemaker](https://github.com/aws-samples/rag-with-amazon-opensearch-and-sagemaker) | ![](./images/rag_with_opensearch_and_sagemaker_arch.svg) |
| opensearch serverless | bedrock | [rag-with-amazon-bedrock-and-opensearch-serverless](https://github.com/aws-samples/aws-kr-startup-samples/tree/main/gen-ai/rag-with-amazon-bedrock-and-opensearch-serverless) | ![](./images/rag_with_bedrock_and_opensearch_serverless_arch.svg) |
| opensearch serverless | sagemaker | [rag-with-amazon-opensearch-serverless-and-sagemaker](https://github.com/aws-samples/rag-with-amazon-opensearch-serverless-and-sagemaker) | ![](./images/rag_with_opensearch_serverless_and_sagemaker_arch.svg) |
| postgresql + pgvector | bedrock | [rag-with-amazon-bedrock-and-postgresql-using-pgvector](https://github.com/aws-samples/aws-kr-startup-samples/tree/main/gen-ai/rag-with-amazon-bedrock-and-postgresql-using-pgvector) | ![](./images/rag_with_bedrock_and_postgres_pgvector_arch.svg) |
| postgresql + pgvector | sagemaker | [rag-with-amazon-postgresql-using-pgvector-and-sagemaker](https://github.com/aws-samples/rag-with-amazon-postgresql-using-pgvector) | ![](./images/rag_with_postgres_pgvector_and_sagemaker_arch.svg) |
| documentdb | bedrock | [rag-with-amazon-bedrock-and-documentdb](https://github.com/aws-samples/rag-with-amazon-bedrock-and-documentdb) | ![](./images/rag_with_bedrock_and_docdb_arch.svg) |
| documentdb | sagemaker | TBD |
| memorydb | bedrock | [rag-with-amazon-bedrock-and-memorydb](https://github.com/aws-samples/rag-with-amazon-bedrock-and-memorydb) | ![](./images/rag_with_bedrock_and_memorydb_arch.svg) |
| memorydb | sagemaker | TBD | |
| kendra | bedrock | [rag-with-amazon-bedrock-and-kendra](https://github.com/aws-samples/qa-app-with-rag-using-amazon-bedrock-and-kendra) | ![](./images/rag_with_bedrock_and_kendra_arch.svg) |
| kendra | sagemaker | [rag-with-amazon-kendra-and-sagemaker](https://github.com/aws-samples/aws-kr-startup-samples/tree/main/gen-ai/rag-with-amazon-kendra-and-sagemaker) | ![](./images/rag_with_kendra_and_sagemaker_arch.svg) |
| knowldege base + opensearch serverless | bedrock | [rag-with-knowledge-bases-for-amazon-bedrock-using-opensearch-serverless (CDK L3 Constructs Version)](https://github.com/aws-samples/aws-kr-startup-samples/tree/main/gen-ai/rag-with-knowledge-bases-for-amazon-bedrock-using-gen-ai-cdk-constructs) | ![](./images/rag_with_kb_for_bedrock_opensearch_serverless_cdk_L3_arch.svg) |
| |  | [rag-with-knowledge-bases-for-amazon-bedrock-using-opensearch-serverless (CDK L1 Constructs Version)](https://github.com/aws-samples/aws-kr-startup-samples/tree/main/gen-ai/rag-with-knowledge-bases-for-amazon-bedrock) | ![](./images/rag_with_kb_for_bedrock_opensearch_serverless_cdk_L1_arch.svg) |
|knowldege base + postgresql | bedrock | [rag-with-knowledge-bases-for-amazon-bedrock-using-aurora-postgresql](https://github.com/aws-samples/aws-kr-startup-samples/tree/main/gen-ai/rag-with-knowledge-bases-for-amazon-bedrock-using-aurora-postgresql) | ![](./images/rag_with_kb_for_bedrock_aurora_postgresql_pgvector_arch.svg) |


## References

[RAG Architecture: From Concepts to Implementations (slides)](https://speakerdeck.com/ksmin23/rag-akitegceo-gaenyeombuteo-guhyeonggaji)

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/zI7rin2S_Ak/0.jpg)](https://www.youtube.com/watch?v=zI7rin2S_Ak)