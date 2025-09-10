# Prompt Engineering in AI with the CLEAR Framework


## **About Me**
Erich Purpur

    Research Librarian for Science & Engineering
    epurpur@virginia.edu

I'm a part of a group called [research data services](https://data.library.virginia.edu/) and I do these things:
    
    1. Serve as Liaison to various departments in the sciences & engineering
    2. Teach workshops and classes (like this one)
    3. Help people with research projects
    4. Random other things as they come up

## Welcome to the UVA Library
* [Research Data Services](https://data.library.virginia.edu/)
* [Workshop Series](https://data.library.virginia.edu/training/)

## Upcoming Python Workshops
| Workshop | Date | Time |
| ---- | ---- | ---- |
| Intro to Python pt 1                                                |       Tuesday 9/2   |  11:00 - 12:30am
| Intro to Python pt 2                                                |       Tuesday 9/9   |  11:00 - 12:30am
| Python Data Analysis & Visualization                                |       Tuesday 9/16  |  11:00 - 12:30am
| AI Prompt Engineering for Python                                    |       Thursday 9/18 |  1:00 - 2:30pm

## Upcoming AI Workshops
| Workshop | Date | Time |
| ---- | ---- | ---- |
| Using Large Language Models Locally                                 |       Thursday 9/4   |  1:00 - 2:30pm
| AI Prompt Engineering w/ CLEAR Framework                            |       Thursday 9/11  |  1:00 - 2:30pm
| AI Prompt Engineering for Python                                    |       Thursday 9/18  |  1:00 - 2:30pm


## Prompt Engineering 
The process of crafting effective inputs to guide large language models and other AI systems towards generating desired outputs. AI tools like ChatGPT, CoPilot, etc. create output based on predicting the most likely sequence of words based on patterns they've learned from huge sets of training data. They predict these patterns using statistical methods. It is easy to get generative AI tools to produce an output. That is what they are meant to do. However, that output can be misleading, off target, untruthful, too long, too short, not specific, or otherwise non-optimized in many ways. Through effective prompt engineering you can get better outputs! 

## AI Resources at UVA
#### [Microsoft Copilot Login](https://virginia.service-now.com/its?id=itsweb_kb_article&sys_id=dbe41947dbe3f91066d98f38139619db)
While most of this material is available to anyone, whether you are a part of the University of Virginia or not, these resources are available to UVA-affiliated people through our ITS department. UVA ITS maintains a page with up-to-date information of their current AI offerings, found [here](https://virginia.service-now.com/its?id=itsweb_kb_article&sys_id=dbe41947dbe3f91066d98f38139619db).

UVA is a Microsoft Campus and for that reason, I will be teaching this workshop using Microsoft's Generative AI tool, Copilot. However, results should be very similar using any other AI chatbot tool such as ChatGPT, Gemini, etc. 

**Disclaimer**
If you are a UVA-affiliated person, make sure to log into Copilot through the [UVA ITS](https://virginia.service-now.com/its?id=itsweb_kb_article&sys_id=dbe41947dbe3f91066d98f38139619db) portal. Because UVA has a site license with Microsoft, UVA's instance of Copilot will protect personal information, your chat history, etc.

#### [Consensus Login](https://guides.lib.virginia.edu/consensus)
Consensus is an academic search engine, using AI to find scholarly research to assist with your research. UVA has a licensed version of Consensus for affiliated users. 

## Misuse of AI. When is the right and wrong time to use it?

While there are many valid downsides of AI tools, and I don't want to diminish those, Generative AI such as Copilot and ChatGPT gets a lot of flack for producing misinformation when maybe the real problem is people's misuse of the software. At least in the context of this workshop, I always try to keep in mind that if you are making a decision that relies on factual information, **there always needs to be a human involved in the decision-making process**. The human is there to make a final decision based on the input the AI has given, which must be considered and evaluated. However, there are times when you don't neccessarily need 100% factually correct information. Situations like this include...   

#### When you don't know enough to craft a good prompt or search
Maybe you are researching a topic you aren't familiar with and don't know where to start? AI can help you figure out a list of keywords to search, ideas to brainstorm, or resources to check out on a topic. Ex: *fashion*

#### First Drafts
If you are like me, you find it easier to edit or revise something that exists even if it is terrible. The first draft is a starting point for refinement. It doesn't need to be perfect or completely accurate. Ex: *Letter to apply to grad school*

#### Summarizing complex ideas for they layman
Similar to the first example, if you don't know anything about quantum physics, reading a quick AI summary can at least clue you in. The summary may not be totally factual but it will probably be good enough to get started. Ex: *quantum physics*

#### Roleplaying or Simulation
Simulating a situation such as practicing an interview or an upcoming difficult conversation can help you prepare ahead of time. Ex: *Prep for a job interview for a data scientist role*

#### Recipes
This is a fun thing I use AI for. I tell the AI what I have in the kitchen and the AI creates a recipe for me. I know there are other services available that do this but I just find it easier to do it in GenAI. As every recipe leaves room for interpretation, there is usually not a "right way" to make most recipes. Ex: *I have olive oil, noodles, carrots, and chicken*

## AI is overconfident
Have you ever been given some misinformation by an AI chatbot? This [news article](https://www.cmu.edu/dietrich/news/news-stories/2025/july/trent-cash-ai-overconfidence.html) explains the phenomenon. LLMs don't learn from their mistakes. When asked follow up questions about their answers, AI will confidently reply with a follow up. This page of [AI follies](https://www.tomshardware.com/tech-industry/artificial-intelligence/cringe-worth-google-ai-overviews) is good for a laugh.


## The CLEAR Path: A Framework for Prompt Engineering
When AI chatbots like ChatGPT came into the fold in 2022, there was a flurry of activity to explore these tools and see what they can do. While they create new opportunities, like any tool it is more powerful when wielded correctly. If you don't know how to drive a car, you might crash into a ditch? AI tools also have their own best practices, though there is no AI-tool users license. So what is the right way to use them?

In 2023, UVA Library Dean [Leo Lo](https://library.virginia.edu/news/2025/leo-lo-named-uva-librarian-and-dean-libraries) published the article: [The CLEAR path: A framework for enhancing information literacy through prompt engineering](https://www.sciencedirect.com/science/article/abs/pii/S0099133323000599). This article is a logically organized method for interacting with AI chatbots in order to get the best results possible. When writing prompts, the five points to keep in mind are...


| Letter   | Description |
| -------- | ------- |
| C | Concise. Brevity and Clarity in prompts               |
| L | Logical. Structured and coherent prompts              |
| E | Explicit. Clear output specifications                 |
| A | Adaptive. Flexibility and customization in prompts    |
| R | Reflective. Continuous evaluation and improvement of prompts    |

#### C. Concise
Brevity is important in crafting prompts. A concise prompt removes superfluous information and allows the LLM to focus on the most important aspects of a prompt. Clarity is important as unclear instructions may result in bad responses. Writing effective prompts requires ensuring that the question is specific and directed toward the desired response.

*Bad:* Can you please provide me with a detailed explanation of the process of photosynthesis and why it is important in the grand scheme of things?.

*Good:* Explain the process of photosynthesis and its significance. 

You see the second example is much more to the point without the fluff of the first question. 

#### L. Logical
Logical prompts enables AI models to better comprehend the context and relationships between various concepts, resulting in more accurate and coherent outputs. Ensure that the information provided follows a natural progression and that the relationship between concepts are evident.

*Bad:* I am learning about the scientific method and don't know how to go about conducting a scientific experiment. How do I do that?

*Good:* Describe the steps in the scientific method, starting with forming a hypothesis and ending with drawing a conclusion.

The second example gives well defined expectations for the AI to follow.

#### E. Explicit
Explicit prompts underscore the need for clear output specifications in the queries posed to AI language models. Explicit prompts provide precise instructions regarding the desired output format, content, or scope, thereby reducing the likelihood of receiving unanticipated or irrelevant responses from the AI model. 

*Bad:* Tell me about the French Revolution

*Good:* Provide a short overview of the French Revolution, emphasizing its causes, major events, and consequences. 

Similar to logical, this gives clear instructions to the AI about what output to produce and how it should be structured. 

#### A. Adaptability
Adaptability entails experimenting with various prompt formulations, phrasing, and settings (if available) in order to establish a balance between creativity and concentration. When crafting prompts, be flexible and willing to attempts new approaches based on the performance of the model. 

*Example:* If the results of a prompt such as "Discuss the impact of social media on mental health" is too general, consider a more focused and adaptable prompt

*Improvement:* Examine the relationship between social media usage and anxiety in adolescents

#### R. Reflective
**In my opinion, this is the most important of the 5 steps to good prompt engineering**. There must always be a human in the loop to evaluate the output produced by the AI! Adopting a reflective perspective puts gives users agency to evaluate the performance of the AI model, identifying areas for improvement and adjusting their approach accordingly. Make it a habit to examine the AI-generated content and apply insights to future prompts. This includes fact checking! Be aware that the AI doesn't always know what it is talking about and don't accept it's answers as truth. 

## Follow Up

UVA Library maintains a page where we do our best to stay current on trends in the AI field, best practices, and helpful resources. To see more on prompt engineering, [go to this link](https://guides.lib.virginia.edu/c.php?g=1340987&p=10541661). 
