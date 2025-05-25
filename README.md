# Exno.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### DATE: 01/05/2025                                                                           
### REGISTER NUMBER : 212222050028              # NAME: KALYANE SREE M
### Aim: 
To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts.

### Algorithm:  1. Direct Instruction Prompts
# Objective: Guide the chatbot to respond concisely to customer inquiries.
# 1. Prompt Pattern:
Prompt: "When a customer asks for the status of their order, reply with: 'Your order is currently being processed and will be delivered by [date].'"

Use Case: Best suited for simple, transactional queries like order tracking or FAQs.

# 2.	Contextual Prompting Objective: Use customer interaction history to tailor responses based on recent messages.
Prompt Pattern:

"If the customer previously mentioned that they haven't received their order, say: 'I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly."'

Use Case: Maintains coherence and empathy in multi-turn conversations.

# 3.	Persona-Based Prompting Objective: Make interactions more engaging by adopting a friendly, helpful personality.
Prompt Pattern:

"Pretend you are a friendly, helpful customer service representative. Use a conversational tone, such as: 'Hey there! I'm here to help with any questions you might have. Let's get your issue sorted!"'

Use Case: Humanizes the chatbot, especially useful in customer service where warmth matters.
# 4.	Few-Shot Prompting Objective: Demonstrate the type of response expected using a few examples so the model can generalize.
Prompt Pattern:

"Here are some examples of how to handle technical questions: 'My phone isn't charging.'
--+ 'Have you tried using a different cable? If that doesn't work, it may be an issue with the port.' 'The screen is flickering.' --+ 'It sounds like a display issue. Have you tried restarting the device?' Now, respond to: 'My app keeps crashing."'

Use Case: Enables intelligent responses to technical queries without writing explicit rules for every scenario.
# 5.	Chain of Thought Prompting Objective: Use step-by-step reasoning to solve complex issues logically.
Prompt Pattern:

"When a customer reports their laptop overheating, guide them through the following steps:
 
Ask if they are using the laptop on a soft surface.

Suggest moving the laptop to a flat, hard surface for better airflow. Ask if they've cleaned the vents recently.
Recommend restarting the device to see if the issue persists. Now, solve: 'My laptop fan is making a loud noise."'

Use Case: Best for issues that require diagnostic or procedural instructions.

# 6.	Instruction with Constraints Objective: Craft replies within specific boundaries-such as tone, length, or complexity.
Prompt Pattern:

"Respond to order inquiries in no more than 50 words and avoid using technical jargon. Example: 'Your order is on the way and should arrive by [date]. Feel free to reach out if you need anything else."'

Use Case: Improves accessibility and ensures consistency in tone and clarity.

# 7.	Reflective Prompting Objective: Reflect the user's query before answering to ensure understanding and build clarity.
Prompt Pattern:

"When a customer asks for help, first reflect their question back to them. Example: 'How can I reset my password?' -+ 'You're asking how to reset your password, correct? Here's how you can do it."'

Use Case: Reduces miscommunication and validates user intent in sensitive or technical queries.


# Result: Thus the Prompts were exected succcessfully .

