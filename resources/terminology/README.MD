Top 30 AI Terms for Accountants
Foundations
1. Artificial Intelligence (AI) The umbrella term for machines mimicking human cognitive functions like reasoning, pattern recognition, and decision-making.
2. Machine Learning (ML) Systems that learn from data instead of being explicitly programmed. Why your accounting platform gets smarter at coding "Gong Cha" to staff amenities over time.
3. Deep Learning A subset of machine learning using layered neural networks. Drives the smartest features in modern accounting software.
4. Natural Language Processing (NLP) AI's ability to understand and generate human language. Lets you ask "show me all overdue invoices for ABC Pty Ltd" instead of writing SQL.
5. Computer Vision AI that interprets images and video. Powers receipt scanning, invoice OCR, and document classification in tools like Hubdoc and Dext.
6. Generative AI (GenAI) AI that creates new content (text, images, code, audio) rather than just analysing existing data.
Models and Tools
7. Large Language Model (LLM) The engine behind ChatGPT, Claude, and Gemini. Trained on huge amounts of text to understand context and generate answers.
8. Model The trained AI itself, for example GPT-5, Claude Opus 4.7, or Gemini 2.5 Pro. Different models have different strengths and price points.
9. ChatGPT OpenAI's flagship chat application built on GPT models. Often the first AI tool accountants try.
10. Claude Anthropic's AI assistant, popular for nuanced writing, analysis, and document review.
11. Copilot Microsoft's AI assistant embedded across Word, Excel, Outlook, and Teams. Useful for drafting emails, summarising threads, and analysing spreadsheets.
12. Multimodal AI that handles text, images, audio, and video together. Hand it a PDF bank statement and a verbal instruction in one go.
How AI Works Under the Hood
13. Training Data The information used to teach a model. Quality, recency, and bias of training data directly affect output quality.
14. Fine-Tuning Adjusting a pre-trained model on your specific data to improve performance, for example training a model on Australian tax law.
15. Token The chunks of text AI processes. Pricing and context limits are measured in tokens, so understanding them helps you manage costs.
16. Context Window How much information an AI can hold in memory during one conversation. Bigger windows mean you can drop in a full ledger or tax ruling.
17. Embeddings A way of turning words and documents into numbers so AI can compare meaning. The magic behind "find similar transactions" features.
18. Vector Database A specialised database storing embeddings, used for semantic search. Sits behind tools that let you "ask your documents" questions.
Working with AI in Practice
19. Prompt Engineering The skill of writing clear instructions to get useful AI output. The difference between rubbish results and gold.
20. Retrieval-Augmented Generation (RAG) AI that pulls from a verified knowledge base (your firm's templates, ATO rulings, client files) before answering. Reduces hallucinations significantly.
21. Structured vs Unstructured Data Structured sits neatly in rows and columns (your GL). Unstructured is everything else (emails, PDFs, voice notes). AI is brilliant at unlocking the latter.
22. Optical Character Recognition (OCR) Tech that reads text from images and PDFs. The foundation of automated data capture in bookkeeping.
23. Predictive Analytics Using historical data to forecast outcomes like cash flow, churn, or audit risk.
Automation and Agents
24. Agent (AI Agent) Software that executes financial workflows independently using rules, data inputs, and conditional logic. Think transaction categorisation or reconciliations running while you sleep.
25. Agentic AI AI that takes action on your behalf rather than only generating text. It plans, decides, and completes multi-step tasks like chasing overdue invoices end-to-end.
26. Orchestration Coordinating multiple AI components into one workflow. Tools like Zapier, n8n, and Make stitch agents, models, and apps together.
27. API (Application Programming Interface) The plumbing that lets one app talk to another. It's how Xero, Dext, and your AI tools share data without copy-paste.
Risk, Trust, and Governance
28. Hallucination When an AI confidently produces something that's wrong or invented. The reason you always verify AI output before lodging anything.
29. Bias When an AI reflects unfair patterns from its training data. Relevant for credit scoring, hiring, and lending decisions you may advise clients on.

# Terminology #

Its important to understand the different terminology used for these tools. We covered them on the day but here is a summary as well

### Models ###

You likely will have heard of these names in the news, Opus, Sonnet, GPT-4o, Spud these are all models. 

Different models normally have different capabilities that use benchmark testing to determine performance.

### Parameters ###

This isn't normally published for commercial models, in simple terms it refers to how many different things a model can refer to for generating a response, think of it like neuron's in your brain. For example the open source model Qwen7B the B stands for billion, and the preceding number the paramters so 7B = 7 billion paramets.

Normally, the larger the parameters the greater the capability although its not an exact science. This though is why large models require large data centres, their size alone requires significant hardware not only to run, but just to load.

Since parameters aren't normally published for commercial models people will refer to things like the test SWE-BENCH https://www.swebench.com/ for performance in software coding or, in our industry https://aimultiple.com/finance-llm

### Tokens ###

This is the "cost" of input and output of a model. Think of each token as something that had to be worked on to be generated

Input tokens: You had to write the prompt, using your energy and knowledge. 

Output tokens: The model used its compute power to give you a response

This is why prompting is important, if you are simple and generic your token usage will increase due to the model having to determine amiguity.

### Token Economics ###

Think of this as "bang for buck" e.g. for each dollar I spend, what amount of tokens and type am I getting access to? This is something you will hear people refer to when they may use a "lower cost" model for certain tasks or "model switching". If you don't need state of the art, you can use models that have a lower token cost. 

### Schedules ###

Claude CoWork has scheduling. This simply means defining "at a specified time, do something" the trigger is time. 

The downside of schedules, at least currently is that they run locally on your own computer. So if you're away from work, or you turn your 
computer off, they don't run.

Anthropics answer to this was (Routines)

### Routines ###

Routines are tasks that can be initiated either by a trigger or by time, with the benefit being they run in Anthropics infrastructure.

If your computer is off, a routine doesn't care it will still run. 

### Vibe Coding ###

This just refers to creating an application where you define what you want and let the AI build, basically empowering people with no
actual software coding skills to go from idea to usable app in a short period of time. 

