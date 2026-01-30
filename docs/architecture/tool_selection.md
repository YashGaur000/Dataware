# Open-Source Tool Selection Rationale

- Language/Framework: Python/FastAPI—fast, async, type-safe (Pydantic), community-driven. Why: Scalable for microservices; alternatives like Node.js are inferior for ML integration.
- Database: PostgreSQL—ACID-compliant, scalable, open-source. Why: Handles complex queries; NoSQL like MongoDB inferior for relational data.
- Queue/Workflow: Kafka (events), Celery (tasks)—reliable, distributed. Why: Event-driven; alternatives like RabbitMQ similar but Kafka better for high throughput.
- ML: Hugging Face Transformers—pre-trained models. Why: Easy integration; alternatives like TensorFlow more complex for MVP.
- Dev Tools: Ruff (linter), Black (formatter), pytest (testing), Pre-commit (hooks). Why: Ensures code quality; alternatives like ESLint for JS inferior here.
- Infra: Docker/Kubernetes—containerized, orchestrable. Why: Cloud-ready; alternatives like VMs inferior for scalability.
- Monitoring: Prometheus/Grafana—open-source, extensible. Why: Comprehensive; alternatives like DataDog proprietary and costly.