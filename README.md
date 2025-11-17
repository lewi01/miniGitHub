# miniGitHub
mini GitHub-style platform, but with AI + DevOps + microservices + cloud + monitoring baked into it

1. API Gateway
Routing
Rate limiting
JWT validation
Logging
Load balancing
Tech: Spring Cloud Gateway
2. User Service
Accounts
JWT auth
Profiles
DB: PostgreSQL
Cache: Redis
3. Snippet Service
Code snippets
Files
Versions
Comments
DB: PostgreSQL
Storage: S3 bucket,Azure Blob (or MinIO locally)
4. AI Service
LLM endpoints:Explain code,Review code,Detect bugs
Tech:Spring Boot,OpenAI or Local LLaMA model,Embeddings for semantic search
5. Notification Service
Email notifications
WebSocket real-time updates
Queue-based async events
Tech: RabbitMQ / Kafka
DB: MongoDB (for message persistence)
6. Search Service 
Full-text + semantic search.
Tech:Elasticsearch, Vector embeddings, AI-assisted ranking

