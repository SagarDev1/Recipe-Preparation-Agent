# Recipe Preparation Agent 🍳

An agentic AI built with IBM watsonx that creates recipes from a user's available ingredients. This project was developed as part of the IBM SkillsBuild for Academia program.

---

## 📖 Project Overview

This AI agent, named **"Chef AI,"** acts as a personal culinary assistant. It interacts with users to understand what ingredients they have on hand and then generates a custom, step-by-step recipe for them. The primary goals of this project are to reduce food waste, save time on meal planning, and make creative cooking more accessible to everyone.

---

## 🛠️ Technology Stack

* **AI Platform:** IBM watsonx
* **Foundation Model:** IBM Granite (`granite-3-3-8b-instruct`)
* **Cloud Services:** IBM Cloud
* **Deployment:** Deployed as an AI service on IBM Cloud

---

## 🤖 Agent Configuration

The agent's behavior is defined by a specific set of instructions within the IBM watsonx platform. These instructions establish its persona, core tasks, and rules of engagement.

> #### Persona and Role:
> You are "Chef AI," a friendly and creative culinary assistant. Your primary goal is to help users create delicious meals using only the ingredients they have on hand. You should be encouraging, clear, and helpful in your responses.
>
> #### Core Task:
> 1.  **Greet the user** and ask them to list the ingredients they have available.
> 2.  **Analyze the user's list of ingredients.**
> 3.  **Access your knowledge base** to find suitable meal ideas.
> 4.  **Generate a complete, step-by-step recipe** that is tailored specifically to the user's list.
> 5.  **Structure the output clearly:** Start with a **Recipe Title**, list the **"Required Ingredients,"** and provide numbered, step-by-step **"Instructions."**
>
> #### Greeting:
> When greeted, say: "Hello! I'm Chef AI, your personal recipe assistant. To get started, please tell me which ingredients you have in your kitchen today, and I'll create a custom recipe just for you!"

---

## ✨ Features

* **Dynamic Recipe Generation:** Creates recipes on-the-fly based on any combination of ingredients.
* **Conversational Interface:** Users can interact with the agent in a natural, conversational way.
* **Zero-Ingredient Waste:** Designed to use only what the user already has, promoting a sustainable kitchen.
* **Cloud-Based & Scalable:** Deployed on IBM Cloud, making it robust and accessible.

---

## 🚀 How It Works (Demo)

Here is a screenshot of the agent creating a recipe from a user's prompt:

![Agent in Action](AI_agent_ss/your-screenshot-filename.png)

---

## 📂 Project Assets

This repository contains all the necessary documents related to the project:

* **[View Project Presentation](presentation/ProjectTemplate%20(1).pptx)**: The detailed PowerPoint presentation outlining the project.
* **[View Original Problem Statement](docs/SB4Academia_Problem%20Statements_2025.pdf)**: The official problem statement document that inspired this project.

---

## ☁️ Deployment

The agent is deployed as a live AI service on IBM Cloud. This allows it to be integrated into other applications, websites, or services via an API endpoint.

---

## 👤 Author

* **Sagar Mandal**
