# Chatbot Project Planning

## Overview
This project aims to create a chatbot using Adaptive Cards, Power Automate, and a SharePoint list to handle various scenarios in Teams chat. The chatbot will pull data from the SharePoint list and display it in Teams using adaptive cards, integrated through Power Automate.

---

## Planning Phases

### 1. Building the SharePoint List
- **Purpose:** Store all relevant data for different scenarios.
- **Details:** 
  - Create a list with columns corresponding to the data fields that the chatbot will need (e.g., Titles, Descriptions, Dates, etc.).
  - Ensure proper permissions and access controls for data retrieval and updates.

### 2. Designing Adaptive Cards
- **Purpose:** Provide a visually engaging way to present data in Teams chat.
- **Details:**
  - Design the adaptive cards based on the data types from the SharePoint list (e.g., Text Blocks for descriptions, Action Buttons for navigation or responses).
  - Use the Adaptive Card Designer to mock up cards before implementing them.
  - Consider the scenarios where different cards will be shown based on user queries or actions.

### 3. Integrating Power Automate
- **Purpose:** Automate the flow of data from SharePoint to Teams via the chatbot.
- **Details:**
  - Set up Power Automate to trigger when certain events occur (e.g., when a new entry is added to the SharePoint list).
  - Use the appropriate connectors to pull data from the SharePoint list and insert it into adaptive cards.
  - Ensure that the flow can handle different scenarios and adapt the output accordingly.

---


