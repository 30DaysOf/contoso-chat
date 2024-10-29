# Welcome to Contoso Chat!

!!! info "Self-Guided vs. Instructor-Led Lab Sessions"

    This guide contains step-by-step instructions that can be completed at home (self-guided) or in-venue (instructor-guided). The main difference lies in the **setup process**. 
    
    - Instructor-led sessions provide a pre-provisioned Azure subscription so you can dive straight into ideation.
    - Self-guided sessions require you to have an Azure subscription and provision infrastructure yourself, first.

## About The Workshop

This hands-on workshop teaches you how to **build, evaluate, and deploy a retail copilot** code-first on Azure AI, with step-by-step instructions that take you from prompt to production.

- Our solution use the [Retrieval Augmented Generation (RAG) pattern](https://learn.microsoft.com/azure/ai-studio/concepts/retrieval-augmented-generation) to ground chat AI responses in the retailer's product catalog and cusomer data.
- Our implementation uses [Prompty](https://prompty.ai) for ideation, [Azure AI Studio](https://ai.azure.com) as the platform for code-first copilot development, and [Azure Container Apps](https://aka.ms/azcontainerapps) for hosting the deployed copilot.
- Our development environment uses [Dev Containers](https://containers.dev) to give you a pre-built workspace in the cloud (with GitHub Codespaces) or on device (with Docker Desktop) with minimal effort.
- Our codebase is structured as an `azd-template`, using the [Azure Developer CLI](https://aka.ms/azd) to provision infrastructure and deploy the solution, with a single command (`azd up`).

