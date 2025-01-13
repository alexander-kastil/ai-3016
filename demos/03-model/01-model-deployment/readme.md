# Model Deployment

- Show Deployment of a model in Azure AI Foundry
- Show Model Deployment using Bicep in `ai.yaml`

    ```yaml
    - name: gpt-4o-mini
    model:
        format: OpenAI
        name: gpt-4o-mini
        version: "2024-07-18"
    sku:
        name: Standard
        capacity: 50    
    ```