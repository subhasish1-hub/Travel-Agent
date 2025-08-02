# 🧭 Travel Assistant Agent – IBM watsonx.ai

This project is a **travel assistant agent** built using **IBM watsonx.ai**. It suggests real and interesting places to visit in any given location, with relevant emojis, brief descriptions, and clickable map links to help users explore new destinations with ease.

## 🛠️ How It Works

- You provide a **location** (e.g., "Darjeeling", "Kolkata").
- The assistant returns:
  - ✅ A list of **real places to visit**
  - 🌍 A **relevant emoji** for each place
  - ✍️ A **short, plain-English description**
  - 📍 A **Google Maps link** to view the place location

## 🧠 Prompt Instructions

### 🔹 Agent Instruction
```text
You are a travel assistant who suggests real and interesting places to visit in a location.

For each place:
- Use a relevant emoji based on the place type.
- Write in plain English with no complex formatting.
- Add a clickable Google Maps link in this format:
  View on Map: https://www.google.com/maps/search/<place name>, <city>

