# EX-5 Comparative Analysis of different types of Prompting patterns and explain with Various Test Scenarios  
### DATE: 04.09.25                                                                            
### REGISTER NUMBER : 212222040045

# Experiment:  
Test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  
Analyze the quality, accuracy, and depth of the generated responses.  

# Objective  
To compare how different prompting patterns affect the performance of AI models in terms of quality, accuracy, and depth of responses.  

---

## Scenario: "How can small businesses use AI tools to grow?"  

<img width="911" height="552" alt="_- visual selection (1)" src="https://github.com/user-attachments/assets/de30bed0-2ebd-41a0-8583-177f8e46633f" />


### 1. Instructional Pattern  
Prompt: "Explain step-by-step how a small business can use AI tools to grow revenue."  

Output:  
"1. Identify bottlenecks like slow customer support.  
2. Choose AI tools such as chatbots or CRMs.  
3. Automate repetitive tasks (emails, data entry).  
4. Use analytics AI to track sales trends.  
5. Apply AI-driven marketing personalization."  

---

### 2. Zero-shot Prompting  
Prompt: "How can small businesses use AI to grow?"  

Output:  
"Small businesses can use AI for automating customer support, improving marketing campaigns, analyzing sales data, and streamlining daily operations."  

---

### 3. Few-shot Prompting  
Prompt:  
"Example: A bakery uses AI to predict demand and reduce waste.  
Example: A retailer uses AI chatbots for customer queries.  
Now suggest more small business AI uses."  

Output:  
"Restaurants can use AI to forecast inventory.  
Gyms can use AI chatbots for scheduling.  
Local shops can use AI ads to target nearby buyers.  
E-commerce stores can personalize offers using AI."  

---

### 4. Chain-of-Thought Prompting  
Prompt: "What steps should a small business take to adopt AI tools for growth?"  

Output:  
"First, evaluate business pain points (e.g., slow responses).  
Second, research AI tools suited for that area (chatbots for customer service).  
Third, test tools on a small scale.  
Fourth, measure ROI.  
Fifth, scale adoption if results are positive."  

---

### 5. Active-prompt  
Prompt: "Give me 5 specific AI tools small businesses can use to grow."  

Output:  
"1. ChatGPT – customer support.  
2. Canva AI – marketing design.  
3. HubSpot Free CRM – sales tracking.  
4. Pictory – video marketing.  
5. Google Analytics AI – sales insights."  

---

### 6. Directional Stimulus Prompting  
Prompt: "Imagine you run a small bakery. Which AI tool would you use first to grow and why?"  

Output:  
"I would use AI demand forecasting to predict how many cakes to bake daily. This reduces waste and increases profits."  

---

### 7. Graph Prompting  
Prompt: "Create a table to show AI tools small businesses can use by function."  

Output:  

| Function            | AI Tool Example   | Benefit                         |  
|---------------------|------------------|---------------------------------|  
| Customer Support    | ChatGPT Chatbot  | Faster replies                  |  
| Marketing           | Canva AI         | Cheaper design & ads            |  
| Sales Management    | HubSpot CRM      | Better pipeline visibility      |  
| Video Promotion     | Pictory          | Quick, professional video ads   |  

---

### 8. Reverse-Engineered Prompt Generation  
Prompt: "Explain how a small business can achieve 20% revenue growth using AI, starting from the result backward."  

Output:  
"To achieve 20% growth, first ensure AI tools are automating lead capture and follow-ups. Then, use AI analytics to optimize pricing. Next, adopt AI ad targeting to attract new customers. Finally, use AI to maintain customer engagement and loyalty."  

---

### 9. Multilingual and Multimodal Prompt Engineering  
Prompt: "Explain how small businesses can use AI for growth in English and Hindi."  

Output:  

**English**: "Small businesses can use AI to automate repetitive tasks, personalize marketing, and improve customer experience."  
**Hindi**: "छोटे व्यवसाय एआई का उपयोग करके दोहराए जाने वाले कार्यों को स्वचालित कर सकते हैं, विपणन को व्यक्तिगत बना सकते हैं और ग्राहक अनुभव को बेहतर बना सकते हैं।"  

---

# Summary  

<img width="924" height="1032" alt="_- visual selection" src="https://github.com/user-attachments/assets/da483b5f-8bdd-4741-8bcb-00da99721889" />


| **Prompt Pattern**                      | **Quality of Response**                       | **Accuracy of Response**               | **Depth of Response**                  |  
|-----------------------------------------|-----------------------------------------------|----------------------------------------|----------------------------------------|  
| **Instructional Pattern**               | High, clear step-by-step guidance             | High, practical and direct              | High, structured for beginners          |  
| **Zero-shot Prompting**                 | Moderate, general ideas only                  | Moderate, lacks context                 | Low, surface-level responses            |  
| **Few-shot Prompting**                  | High, learns from examples                    | High, contextual relevance              | High, creative use-cases                |  
| **Chain-of-Thought Prompting**          | Very High, logical breakdown                  | High, stepwise reasoning                | Very High, structured decision process  |  
| **Active-prompt**                       | Moderate, actionable but narrow               | High, tool-specific                     | Low, lacks broader context              |  
| **Directional Stimulus Prompting**      | High, role-play makes response relatable      | Moderate, depends on framing            | Moderate, scenario-specific             |  
| **Graph Prompting**                     | High, visual/structured clarity               | High, functional mapping                | Moderate, tabular but not deep analysis |  
| **Reverse-Engineered Prompt Generation**| High, goal-driven and strategic               | High, outcome-focused                   | High, practical and future-oriented     |  
| **Multilingual and Multimodal**         | High, versatile across languages              | Moderate, depends on translation nuance | High, expands audience reach            |  

---

# RESULT  
Comparative analysis shows that **Chain-of-Thought** and **Few-shot** prompts deliver the deepest, most actionable insights, while **Instructional** and **Reverse-engineered** prompts balance clarity with strategy.  
Zero-shot tends to stay shallow, and Active/Stimulus prompts shine best in relatable, narrow contexts.  
