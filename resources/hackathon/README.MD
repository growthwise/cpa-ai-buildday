# Putting It All Together #

The last part of today is for you to attempt a build. Below is a basic framework to consider before you start

# Build Framework #

## Plan 

You all have domain knowledge, you know how you achieve a task. Before you actually dive into building something think of what the normal process is, or if its something brand 
new to your operations think of what the result *should* be at the end

- What are the current blockers for the task at hand? 
- What happens manually that may be able to be automated?
- What data is needed and how can it be provided? 
- What technology might be required? E.g. do you need special software/skills
- Who has to use this?
- What is an accetable output?
- Importantly as well: Don't reinvent the wheel! Consider the ROAD strategy (Rip Off And Duplicate) if there are skills that already achieve the task at hand test them first, you might be able to use it as your stepping stone to completion

At this stage you can certainly use an LLM to scaffold your plan, talk back and forth with it to surface things you may not have thought of.

## Define

Beyond your plan, you need to give your AI tool instructions. The good news here is from your plan, you've likely done most of the work. 

_Tip: if you used AI to create your plan, at the end type a prompt "Can you create a markdown file of my plan" you can then just provide this file instead of rewriting a start prompt_

When providing your instructions, you have two options

1) Directly prompt what you want *with detail*

2) Build an instructions file (CLAUDE.MD or AGENTS.MD) with instructions of what you want built. An example CLAUDE.MD file is available [here](https://github.com/growthwise/cpa-ai-buildday/blob/main/resources/build-a-site/CLAUDE.MD) the advantage of an instructions file is you can easily move between AI tools by just taking the file with you and you can update it at the refine step

Regardless of whether you choose option 1 or option 2 you should outline criteria in your prompt, aim to avoid ambiguity. Example do's and don't below

| ✅ Do | ❌ Don't |
| --- | --- |
| In the current folder is an excel file, we need to use the data in Column A (Name), Column B (Sales Value) Column M (Marketing Channel) and Column Z (Date) to generate a dashboard that shows us a breakdown of sales attributed to different marketing channels and sales over time based on the date. Output the result as a PDF File | Make me a dashboard from my spreadsheet |
| Using the account transactions report PDF stored in my folder, analyse the data and find any anomalies. Look for things such as expenses that seem to be miscategorised, are larger than expected e.g. office expenses over $1000 give me an explanation of anything found | Find whats wrong in this report |

Make sure you as well you include things like what you expect the output to be. For example if a spreadsheet will be fine make sure you define that vs if you want an easily readable website or PDF, ensure you ask for that. 

## Test

Once Cowork, or Code or event a chat has generated a result you need to test it.

This is where most people begin getting frustrated. Remember to treat the AI as a tool, not a wizard. 

When you test break down functionality and Usability and Readability. 

- Functionality: Did it do what I expected
- Usability and Readability: is it easy enough to do?

Work on one at a time, if functionality lacked - reprompt to fix that issue by itself before moving on to usability

_Tip: When refining, ask Claude "Can you keep track of issues in and issues file" this will keep track of what you've found during this process and can make it easier to remember if you have to later recommence a project or session_

In the test page you're really aiming for a minimum vial product i.e. make it work. It might look ugly and feel clunky, but the aim is to make sure it functions. 

You should expect things to break, but the break should guide your next prompt. 

## Refine 

Beyond make it work, make it better :-D

Refining is about being picky, the little things that you weren't super concerned with in the test phase belong here. For exmaple, now it works maybe you want 
to make whatever was created "on brand" to your business.

Maybe something wasn't quite right, but didnt cause enough issues at the time to require mnuch attention. Now you take the time to refine and fix further. 

## Repeat/Share

Now that you've done the hard work don't forget to turn your creation into a [skill](https://code.claude.com/docs/en/skills) so that you can re-use it, and share with your team.
