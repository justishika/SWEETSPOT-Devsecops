# SWEETSPOT-Devsecops

### File structure
```
sweetspot-devops/
│
├── backend/                       # Express backend
│   ├── routes/                    # Route handlers (e.g., auth, products)
│   ├── models/                    # Mongoose schemas
│   ├── controllers/              # Business logic
│   ├── middleware/               # Auth, logging, etc.
│   ├── config/                   # DB config, env loader
│   ├── utils/                    # Helper functions
│   ├── tests/                    # Unit tests
│   ├── .env                      # Local backend environment variables
│   ├── Dockerfile                # Docker setup for backend
│   └── index.js                  # Entry point
│
├── frontend/                     # React frontend
│   ├── public/
│   ├── src/
│   │   ├── components/           # Reusable UI components
│   │   ├── pages/                # Page components
│   │   ├── services/             # API calls (Axios)
│   │   ├── hooks/                # Custom React hooks
│   │   ├── App.js
│   │   └── index.js
│   ├── .env                      # Local frontend env
│   ├── Dockerfile                # Docker setup for frontend
│   └── tailwind.config.js
│
├── infra/                        # Infrastructure as Code
│   ├── terraform/                # Terraform scripts for AWS
│   │   ├── eks/
│   │   ├── vpc/
│   │   └── outputs.tf
│   ├── k8s/                      # Kubernetes manifests
│   │   ├── backend-deployment.yaml
│   │   ├── frontend-deployment.yaml
│   │   ├── ingress.yaml
│   │   └── secrets.yaml
│   └── vault/                    # Vault policies & secrets config
│
├── .github/                      # GitHub Actions
│   └── workflows/
│       ├── backend-ci.yml
│       ├── frontend-ci.yml
│       └── deploy.yml
│
├── monitoring/                   # Monitoring & logging setup
│   ├── prometheus/
│   ├── grafana/
│   ├── loki/
│   └── alertmanager/
│
├── docker-compose.yml            # For local development
├── README.md
├── LICENSE
└── .gitignore
```
