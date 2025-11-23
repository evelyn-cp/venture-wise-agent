# Venture Wise Agent
## 📌 Project Description
Venture Wise Agent is an AI agent that recommends fun and travel activities based on local weather forecasts. It adapts dynamically to user‑selected locations, ensuring safe and enjoyable experiences. Built for the Azure Frontier Girls AI challenge, it combines intelligent insights with curated suggestions.

### 🎯 Objective
- Accept a location input (city, region, or landmark). If the user also provides a date or date range, interpret this as the period for which the forecast should be retrieved.
- Retrieve the current and upcoming weather forecast for the specified location and time frame.
- Generate a list of relevant activities adapted to the forecast:
  - ☀️ Clear skies → outdoor activities (walking tours, hiking, cycling, parks, beaches).
  - 🌧️ Rain/storms/extreme temperatures → indoor activities (museums, galleries, shopping centers, aquariums).
  - ⚠️ Unsafe conditions → avoid outdoor activities, suggest safe alternatives.
- Ensure recommendations are contextually appropriate (local attractions, cultural events, seasonal activities).
- Present suggestions in a clear, user‑friendly format, always including the forecast summary alongside the activity recommendations.

## 🛠️ Core Functionality
1. Accept user location input.
2. Retrieve weather forecast for that location.
3. Dynamically adapt recommendations based on forecast.
4. Emphasize safety and comfort while maintaining variety and relevance.

## 📸 Screenshots & Flow
### Example Responses:
- **Example 1:**
- Prompt: "I'll be traveling to Nuremberg, Germany, from December 1st to December 20th."
<img width="1551" height="1253" alt="image" src="https://github.com/user-attachments/assets/8f64b566-9c08-4156-a000-3f0de4ade49d" />

- **Example 2:**
- - Prompt: "I'll be traveling to Rio de Janeiro, Brasil, from December 21th to January 4th."
<img width="1549" height="1257" alt="image" src="https://github.com/user-attachments/assets/9effa358-fcbd-4194-9453-540109932152" />

- **Example 3:**
- - Prompt: "I'll be traveling to Los Angeles, USA, from January 12th to January 16th, 2026."
<img width="1552" height="1258" alt="image" src="https://github.com/user-attachments/assets/3a5159a0-4811-4039-9ca1-e87c38135cf9" />

- **Example 4: asking about a topic outside the context defined for the agent**
- Prompt: "Please help me get the travel tickets to fly to Los Angeles"
<img width="1551" height="1258" alt="image" src="https://github.com/user-attachments/assets/7e5ad547-6c07-4c1c-8959-b87010b1aa4a" />


## 🚀 Step‑by‑Step Setup
1) Creation of a resource group in the Azure portal;
2) Creation of an AI Foundry resource;
3) Deployment of a base AI model (gpt‑4o‑mini);
4) Creation of an AI agent in Azure AI Foundry:
    - AI agent configuration:
      - Agent name
      - Deployment
      - Instructions
      - Agent description
5) Configuration of an Azure Logic App in the "Actions" section (Get today’s weather forecast via MSN Weather);
6) Configuration of a data source in the "Knowledge" section (Tripadvisor);
7) Testing the agent in the playground.

## 🔗 References
- [Microsoft Azure](https://azure.microsoft.com/en-us)
- [Microsoft AI Foundry](https://azure.microsoft.com/en-us/products/ai-foundry)
- [Azure Frontier Girls](https://www.maismulheres.tech/courses/azure-frontier-girls)
- [Venture Wise Agent Instructions.pdf](https://github.com/user-attachments/files/23698992/Venture.Wise.Agent.Instructions.pdf)
- [Venture Wise Agent Description.pdf](https://github.com/user-attachments/files/23698998/Venture.Wise.Agent.Description.pdf)

## 👩‍💻 Contributors
Developed by [Evelyn Pereira](https://github.com/evelyn-cp) as part of the Azure Frontier Girls AI Challenge.
