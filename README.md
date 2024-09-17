# CS 260 Web Startup
Let's get this party started
<p align="left">
  <img src="https://github.com/ethan-mcq/startup/blob/main/ref_images/cat.png" width="150" height="auto"/>
</p>

## Elevator Pitch
AI has become a trigger word. "Our popcorn machine is AI enabled!", or "Our blockchain AI app will be the next unicorn!". While I do intend to ride this wave, I do not intend to throw the word around willy-nilly. Large Language Models have grown to effectively and efficently analyze large text blocks and extract important information. I intend to use these LLM's to harness a plethora of data stored custom databases that can be used by different industries (law, automotive, healthcare, etc..) who's contents will be useful documentation, information, and news of these industries all wrapped into a neat little SQL database. In doing so, I will allow a LLM to analyze questions and produce responses to these questions without all of the 'noise' that is added from the information that is has been previously trained on. 

The goals of this project are two-fold:

**1**: Make an accessible website for clients to access a personal profile and chat history with "their" chatbot.

**2**: Create databases that will serve as references for 3 applications for the chatbot to use for specific clients (ie. Lawyers use case review database, but Dr. uses illness sympotmology database).

## Key Features
- Secure login protocol
- Data security measures ([HIPPA](https://community.openai.com/t/how-did-you-achieve-hipaa-compliance/555659/5), etc.)
- Ability to reference previous chats
- Feature to export chat results into PDF file with references cited at the bottom
- Import your own documents to be analyzed as the "text block"
- Connection to SQL database with functioning prompts
- Ability to delete user if necessary
- Connect to [Stripe](https://stripe.com/?utm_campaign=AMER_US_en_Google_Search_Brand_Stripe_EXA-20839462206&utm_medium=cpc&utm_source=google&ad_content=683853401230&utm_term=stripe&utm_matchtype=e&utm_adposition=&utm_device=c&gad_source=1&gclid=Cj0KCQjwrp-3BhDgARIsAEWJ6SztNPLBb-gTaIHuWrXlFw7aeVBBvILJJo5InV-K3_JZlfDR2aPjIpkaAr83EALw_wcB)

## Mock-up

<p align="left">
  <img src="https://github.com/ethan-mcq/startup/blob/main/ref_images/login.png" width="1000" height="auto"/>
</p>

## Technologies included in this project
**HTML**: 
  - 5 HTML pages (Welcome, Pricing/Info, Login, Chat, Account Info/Payment)
  - Correct styling and fluid structure

**CSS**: 
  - Fit to screen styling
  - Color choice (Use figma for styling)

**Python**: 
  - Process + parse PDF or other file inputs
  - Connect to OpenAI API
  - Recieve API POST

**React**:
  - Login input
  - Chat interface
  - Account information
  - Previous chats

**Service**:
  - Connection to OpenAI API

**Authentication/Payment**:
  - Login services
  - MFA
  - Stripe

**DB/Login**:
  - Store and create big-db
  - Store previous chats with ability to still export report
  
**WebSocket**:
  - API response displayed in real-time.
  - Chat logs update real-time as well
