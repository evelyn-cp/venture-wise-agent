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
- **Clear weather during daytime and rain/snow during nighttime response**  
<img width="1557" height="1261" alt="image" src="https://github.com/user-attachments/assets/a7bdb641-cc11-4259-a1e2-8b7070efe5bf" />


## 🚀 Step‑by‑Step Setup
1) Creation of a resource group in the Azure portal;
2) Creation of an AI Foundry resource;
3) Deployment of a base AI model (gpt‑4o‑mini);
4) Creation of an AI agent in Azure AI Foundry:
    AI agent configuration:
      Agent name
      Deployment
      Instructions
      Agent description
5) Configuration of an Azure Logic App in the "Actions" section (Get today’s weather forecast via MSN Weather);
6) Configuration of a data source in the "Knowledge" section (Tripadvisor);
7) Testing the agent in the playground.

## 🔗 References
- [Microsoft Azure](https://azure.microsoft.com/en-us)
- [Microsoft AI Foundry](https://azure.microsoft.com/en-us/products/ai-foundry)
- [Azure Frontier Girls](https://www.maismulheres.tech/courses/azure-frontier-girls)

## 👩‍💻 Contributors
Developed by Evelyn Pereira as part of the Azure Frontier Girls AI Challenge.
