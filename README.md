# Ecommerce-Chatbot-Intelligent-Customer-Support-with-Dialogflow

An intelligent, 24/7 customer support chatbot for a luxury chocolate ecommerce website. This project demonstrates my skills in conversational AI, Dialogflow, and seamless website integration—delivering instant, personalized assistance to online shoppers.

## 🚀 Project Overview

**Objective:**  
Create and deploy a Dialogflow chatbot that enhances customer experience by answering FAQs, guiding purchases, and supporting users on a luxury chocolate website.

**Key Features:**
- Instantly answers product, order, and brand-related queries
- Personalized recommendations for gifts and dietary needs
- Embedded directly on the website for real-time support

## 🛠️ Technologies Used

- **Google Dialogflow:** Natural language understanding and chatbot logic
- **HTML/CSS:** Website structure and chatbot integration
- **Dialogflow Messenger:** Embedding chatbot via iframe for smooth user experience

## 💡 How It Works

1. **User Interaction:**  
   Visitors ask questions about products, orders, or the brand using the chatbot widget.

2. **Intent Recognition:**  
   Dialogflow processes queries, matching them to custom intents (e.g., product inquiry, order, return info).

3. **Smart Responses:**  
   The chatbot provides detailed, friendly answers, recommends chocolates, and helps with support requests.

4. **Website Integration:**  
   The chatbot is seamlessly embedded on the luxury chocolate website, providing 24/7 assistance[1].

## 🗂️ Step-by-Step Setup Guide

### 1. Create a Dialogflow Agent

- Go to the [Dialogflow Console](https://dialogflow.cloud.google.com/).
- Click **Create Agent** on the left sidebar.
- Enter your agent’s name (e.g., “ChocolateBot”), default language, and time zone.
- Link to a Google Cloud project (create a new one if needed).
- Click **Create**.

*This agent will understand and respond to customer queries about chocolates, orders, and more.*

### 2. Add Intents (User Questions)

- In the Dialogflow console, select your agent.
- Click **Intents** > **Create Intent**.
- Name your intent (e.g., "Product Inquiry").
- Under **Training Phrases**, add different ways users might ask about products:
    - “What kinds of chocolates do you offer?”
    - “Tell me about your chocolate collection.”
    - “Do you have vegan chocolates?”
- Under **Responses**, enter how the bot should reply:
    - “We offer a curated selection of dark, milk, white, and assorted chocolates. Would you like recommendations?”

*Repeat this process for each major topic (Order Tracking, Allergens, Shipping, Gifts, etc.), adding at least 5 varied questions and responses per intent for realism and coverage.*

### 3. Enhance with Entities (Optional)

- For details like chocolate types or allergies, create **Entities** (e.g., @chocolate_type, @allergen).
- Use these in intents to extract and use specific information from user queries.

### 4. Test Your Chatbot

- Use the **Try it now** panel in Dialogflow to simulate user conversations.
- Refine intents and responses until the bot handles questions naturally and accurately.

### 5. Integrate Dialogflow Chatbot into Your Website

- In Dialogflow, go to **Integrations** > **Dialogflow Messenger**.
- Enable it and copy the provided iframe code.
- Open your website’s HTML (e.g., `S3Website.html`)[1].
- Paste the iframe code where you want the chatbot to appear, typically before the closing <body>tag.

Go Through my S3Website_with_Chatbot.html and change the <script> in last with your iframe code.
```<!-- Example integration -->
<iframe
  allow="microphone;"
  width="350"
  height="500"
  src="YOUR_DIALOGFLOW_MESSENGER_URL">
</iframe>

```

- Save and deploy your website. (Optional: Use AWS S3 and CloudFront for hosting and global delivery[2].)

## 🗂️ Example User Questions

- What kinds of chocolates do you offer?
- Can you recommend a unique chocolate for gifting?
- Are your chocolates suitable for people with nut allergies?
- How do I track my order after purchase?
- What makes your luxury chocolates special compared to others?

## 🌟 Why This Project Stands Out

- **Real-World Impact:**  
  Solves the challenge of providing instant, always-on customer service for ecommerce.

- **Personalization:**  
  Offers tailored recommendations and allergy-safe suggestions to match individual needs.

- **Professional Integration:**  
  Demonstrates end-to-end skills: chatbot design, intent engineering, and live website deployment.

- **Scalable & Secure:**  
  (Optional) Hosted on AWS S3 and delivered via CloudFront for reliability and speed[2].

## 📝 How to Use

1. Visit the luxury chocolate website.
2. Click the chatbot icon to start a conversation.
3. Ask any question about products, orders, or gifting.
4. Receive instant, helpful responses—anytime!

## 📈 Skills Demonstrated

- Conversational AI & Dialogflow
- Website integration
- Customer-centric problem solving

**Thank you for reviewing my project!**
