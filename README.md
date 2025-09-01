# n8n Automation Playground

## Quick Start

This project can be deployed in two ways:

1. **Local Development Environment**
    
    Prerequisites:
    - [Docker](https://docs.docker.com/get-started/get-docker/) installed on your machine
    
    Setup steps:
    1. Create your environment file by copying the example:
       ```bash
       cp .env.example .env
       ```
    2. Configure the environment variables in `.env`
    3. Start the containers:
       ```bash
       docker compose up -d
       ```
    4. Access the n8n interface at [http://localhost:5678](http://localhost:5678)

2. **Cloud Deployment**
    - AWS deployment guide (Coming soon)
