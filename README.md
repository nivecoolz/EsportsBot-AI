# EsportsBot AI

> **Your instant, LLM-powered gateway to esports earnings, players, and tournaments.**

EsportsBot AI is a chatbot that connects users to real-time esports data, including player rankings, tournament results, and top earners. It uses a Large Language Model (Google’s Gemini 2.0 Flash) to understand natural language queries, dynamically fetch live data from the Esports Earnings API, and summarize it into user-friendly responses — all through an interactive Streamlit interface.

---

## 🚀 Features

- **Natural Language Understanding**  
  Ask questions like *"Who’s the top CS:GO earner this year?"* or *"Show me the top 5 players from The International 2023"* — no manual data digging required.

- **Real-Time Esports Data**  
  Integrated with the [Esports Earnings API](https://www.esportsearnings.com) to fetch up-to-date player, team, game, and tournament statistics.

- **Smart Summarization**  
  LLM-powered data summarization for quick, conversational responses.

- **Responsive UI**  
  Built with Streamlit for a smooth, interactive experience.

---

## 🛠️ How It Works

1. **Query Parsing**  
   User inputs a question → LLM interprets it → Determines the correct API call.

2. **Data Retrieval**  
   Esports Earnings API returns relevant stats (players, earnings, tournaments, etc.).

3. **Summarization**  
   LLM processes and formats the results into concise, clear answers.

4. **Presentation**  
   Results are displayed instantly in the Streamlit web app.

---

## ⚙️ Tech Stack

- **LLM**: [Google Gemini 2.0 Flash](https://deepmind.google/technologies/gemini/)
- **Backend**: Python
- **Frontend/UI**: Streamlit
- **API**: Esports Earnings API
- **Other Tools**: Prompt Engineering, CSV-based Game ID Lookups

---

## 🧩 Challenges

- **API Constraints**: Limited/missing data and SSL issues required fallback handling.
- **Prompt Engineering**: Ensuring LLM generates valid JSON for API calls.
- **Dynamic Game IDs**: Avoided hardcoding by implementing flexible lookup logic.

---

## 🏆 Accomplishments

- Successfully integrated LLM with real-time esports API.
- Created a clean, user-friendly chatbot experience.
- Built robust error handling and fallback mechanisms.

---

## 📚 What We Learned

- **LLM Development Best Practices**: Prompt chaining, context handling.
- **Data Handling**: Balancing semantic queries with real API limitations.
- **Scalability**: Using caching and optimized API calls to handle repeated queries.

---

## 🔮 What’s Next

- Advanced analytics: player trends, deeper tournament breakdowns, and live visualizations.
- User personalization: alerts, recommendations, and saved preferences.
- Contextual memory: enabling follow-up questions without restating context.
- Scaling for global users and integrating more data sources.

---

## ▶️ Try It Out
- **Demo Video**: [Vimeo Link](https://youtu.be/0X0e5HItrkk)
- **Live Demo**: [Live Link](https://esportsbot-ai-hdgezdkrmftbhdvjg5besw.streamlit.app/)
