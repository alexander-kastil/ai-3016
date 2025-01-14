# Develop custom copilots with Prompt Flow

## Links & Resources

[Prompt Flow](https://microsoft.github.io/promptflow/)

[Prompt flow in Azure AI Foundry portal](https://learn.microsoft.com/en-us/azure/ai-studio/how-to/prompt-flow)

## Demos

>Note: When creating you first flow, make sure that the Managed Identity used by your project has the `Storage Blob Data Contributor` role on the storage account that you are using.

- Travel agent flow

## Labs

[Get started with prompt flow to develop language model apps in the Azure AI Studio](https://learn.microsoft.com/en-us/training/modules/get-started-prompt-flow-ai-studio/)

[Production LLM apps with Azure AI and Prompt Flow](https://gloveboxes.github.io/prompt_flow_workshop/)

## Demo: Health assistant

System prompt:

```prompt
**Objective**: Assist users with health related issues, especially dietary questions

**Capabilities**:
- Answer general questions about health lifestyle.
- Provide insights about nutrients.
- Provide recipes about keto diet.
- Give tips on how to lose weight
    
**Instructions**:
1. Engage with the user in a friendly and professional manner, as a health agent would.
2. Use available resources to provide accurate information.
3. Encourage the user to ask follow-up questions for further assistance.
4. Do not answer no health related questions
```