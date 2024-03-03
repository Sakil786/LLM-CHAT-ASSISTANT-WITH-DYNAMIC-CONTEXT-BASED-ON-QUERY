# LLM-CHAT-ASSISTANT-WITH-DYNAMIC-CONTEXT-BASED-ON-QUERY
## Problem Statement
Design and implement a basic LLM based chatbot of your choice to dynamically get context via external sources (via api) and documents and answer the user query.
## INTRODUCING OUR HEALTH INSURANCE CHAT BOT - YOUR ULTIMATE HEALTH COMPANION!
### About
This innovative application simplifies the management of our Health Insurance Plan, offering easy access to your policy details through a comprehensive and user-friendly Policy Document. Seamlessly integrating external data from LIC (Life Insurance Corporation of India), our chat bot expands its capabilities to provide users with real-time information about various life insurance products. With a focus on efficiency, the app enables quick resolution of policy-related queries, ensuring clarity and transparency in understanding coverage terms. Additionally, the Health Companion app fetches contact details and addresses from relevant websites, making it effortless for users to connect with their insurance provider.

## METHODOLOGY-APPLICATION DESIGN
### DATA SOURCES
To keep things straightforward, I’ve opted for two data sources.
- [PDF](https://github.com/Sakil786/LLM_Accuracy/blob/main/Health%20Companion-Health%20Insurance%20Plan_GEN617.pdf "PDF"): The initial data source is a PDF obtained through internet
- [LIC](https://licindia.in/web/guest/know-your-life-insurance "LIC") : This data source corresponds to the website link of LIC.

[LlamaIndex](https://docs.llamaindex.ai/en/stable/ "LlamaIndex") serves as a versatile and straightforward data framework designed to seamlessly integrate custom data sources with expansive language models. It equips us with essential tools to enhance ourLarge Language Model (LLM) applications by effortlessly incorporating diverse datasets.

![](https://github.com/Sakil786/LLM-CHAT-ASSISTANT-WITH-DYNAMIC-CONTEXT-BASED-ON-QUERY/blob/main/image1.png)
