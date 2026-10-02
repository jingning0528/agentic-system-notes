# agentic-system-notes

```
                         USER
                           ↓
                    API / Frontend
                           ↓
                ┌────────────────────┐
                │ Agent Orchestrator │
                └─────────┬──────────┘
                          ↓
                 Intent / Planning
                          ↓
                    Model Router
                    ↙           ↘
             Small Model       Large Model
                    \           /
                     ↓         ↓
                       Agent
                         ↓
        ┌────────────────┼────────────────┐
        ↓                ↓                ↓
   Retrieval          Tools/API         Memory
        ↓                ↓                ↓
Embedding Search     CRM / SQL       User/context
        ↓            Email/API
Adaptive Rerank      Internal service
        ↓
Knowledge
        └────────────────┼────────────────┘
                         ↓
                  Safety / Validation
                         ↓
                      Response

```

Observability
Tracing
Evaluation
Caching
Batching
Model serving
GPU utilization
Latency monitoring
Cost monitoring
Fallback
Retries
Access control
Privacy
