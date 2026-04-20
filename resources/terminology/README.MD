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

