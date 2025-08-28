# 🚀 My First n8n Workflow - NASA Solar Flare Alerts  

This project shows how I built my **first workflow in n8n** to fetch and process real-time **NASA Solar Flare data**.  
It uses trigger nodes, API credentials, logic handling, and external requests.  

---

## 🔑 Key Concepts
- Starting workflows with **trigger nodes**  
- Configuring **API credentials**  
- Fetching data from **NASA DONKI Solar Flare API**  
- Processing data using **If node**  
- Sending results to external services  

---

## 🛠️ Steps in the Workflow
1. **Schedule Trigger** → Runs weekly (Monday, 9 AM).  
2. **NASA Solar Flare Node** → Fetches real-time solar flare data using API Key.  
3. **If Node** → Splits data into "High Classification (X-class)" and "Lower Classification (A, B, C, M)".  
4. **Send Request** → Sends processed data to external service (like Postbin / Webhook).  

---

## 📸 Screenshot
[![Screenshot-2025-08-29-001748.png](https://i.postimg.cc/5Nv014Hk/Screenshot-2025-08-29-001748.png)](https://postimg.cc/w7qHQdQh)

---

## 🌐 Reference
This workflow is based on the official n8n tutorial:  
👉 [Your First Workflow (n8n Docs)](https://docs.n8n.io/try-it-out/tutorial-first-workflow/#step-six-test-the-workflow)  

---

## 🏁 How to Use
1. Clone this repo  
2. Open the workflow in [n8n](https://n8n.io/)  
3. Add your **NASA API Key**  
4. Run or schedule the workflow 🚀  

---

### 🎉 Outcome
With this workflow, you get **automated weekly reports of solar flare events** from NASA directly into your system.  

---
