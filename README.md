flowchart LR
    U[Пайдаланушы<br/>(Browser)]
    F[Frontend<br/>(Next.js)]
    B[Backend API<br/>(Go / Node.js)]
    D[(Database<br/>(PostgreSQL))]
    M[Monitoring<br/>(Grafana / Sentry)]

    U --> F
    F -->|HTTP / REST| B
    B -->|SQL Queries| D
    B --> M
