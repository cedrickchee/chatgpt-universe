# ChatGPT Universe

This tiny place of the Web stores a growing collection of interesting things
about [ChatGPT](https://en.wikipedia.org/wiki/ChatGPT) and GPT-3 from OpenAI.

I want an all-in-one place to keep things about ChatGPT. So, I hand-curated this
list with the help of others (acknowleged below).

The collections are not limited to only the best resources, tools, examples,
demos, hacks, apps, and usages of ChatGPT.

<!-- my personal brain dumps? -->

---

The following resources started off based on awesome-chatgpt lists[^1][^2] but with my
own modifications:

## General Resources

- [ChatGPT launch blog post](https://openai.com/blog/chatgpt/)
- [ChatGPT official app](https://chat.openai.com)
- [ChatGPT Plus](https://openai.com/blog/chatgpt-plus/) - a pilot subscription plan for ChatGPT.
- [Official ChatGPT and Whisper APIs](https://openai.com/blog/introducing-chatgpt-and-whisper-apis) - Developers can now integrate ChatGPT models into their apps and products through the API.
    > Model: The ChatGPT model family we are releasing today, **`gpt-3.5-turbo`, is the same model used in the ChatGPT** product. It is **priced at $0.002 per 1k tokens, which is 10x cheaper than our existing GPT-3.5 models**.
    >
    > API: Traditionally, GPT models consume unstructured text, which is represented to the model as a sequence of “tokens.” ChatGPT models instead consume a sequence of messages together with metadata.
- [GPT-4 is OpenAI’s most advanced system, producing safer and more useful responses](https://openai.com/product/gpt-4)
- [ChatGPT plugins](https://openai.com/blog/chatgpt-plugins) - Initial support for plugins in ChatGPT. Plugins are tools designed specifically for language models with safety as a core principle, and help ChatGPT access up-to-date information, run computations, or use third-party services. (Chatbots are having their App Store moment)
- [Function calling and other API updates](https://openai.com/blog/function-calling-and-other-api-updates) - They’re announcing updates including more steerable API models, function calling capabilities, longer context, and lower prices.
- [GPT-4 API general availability and deprecation of older models in the Completions API](https://openai.com/blog/gpt-4-api-general-availability)
- Documentation (Guide): [GPT Best Practices](https://platform.openai.com/docs/guides/gpt-best-practices)
- [GPT-3.5 Turbo fine-tuning and API updates](https://openai.com/blog/gpt-3-5-turbo-fine-tuning-and-api-updates) - Developers can now bring their own data to customize GPT-3.5 Turbo for their use cases.
- [ChatGPT Enterprise](https://openai.com/blog/introducing-chatgpt-enterprise) - Get enterprise-grade security & privacy and the most powerful version of ChatGPT yet.
- [ChatGPT can now see, hear, and speak](https://openai.com/blog/chatgpt-can-now-see-hear-and-speak) - Multimodal GPT-3.5 and GPT-4 models is here. OpenAI is beginning to roll out new voice and image capabilities in ChatGPT to Plus and Enterprise users.

## ChatGPT Community / Discussion

- [OpenAI Discord Channel](https://discord.com/invite/openai)
- [How ChatGPT actually works](https://archive.ph/f3WW2), explained using simple words.
- [Reddit /r/ChatGPT](https://old.reddit.com/r/ChatGPT/)

## Examples

Example prompts.

- [All the best examples of ChatGPT](http://archive.today/m6AOQ) - That's Day 1. We have even more examples [below](#demos)!
- [🔓 Unlocking the power of the ChatGPT revolution: 100 💥 innovative use-cases to try](https://archive.is/PsyQz)
- [impressive-chatgpt](https://github.com/sw33tLie/impressive-chatgpt) - A collection of impressive and useful results from ChatGPT.
- [Awesome ChatGPT prompts](https://github.com/f/awesome-chatgpt-prompts) - Prompts that works well. Just follow [@goodside](https://twitter.com/goodside)
- [Google Sheets of 50+ clever GPT-3 prompts](https://docs.google.com/spreadsheets/d/1EuciDyKqFg2CIoQS89tF238oGtJq8a4mRx8kV9eA1Lc/edit#gid=2011839893)
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook) - Tangentially, this repository shares example code and example prompts for accomplishing common tasks with the OpenAI API.
- [ChatGPT cheat sheet (PDF)](https://drive.google.com/file/d/1UOfN0iB_A0rEGYc2CbYnpIF44FupQn2I/view)

## Experiments

- [golergka/advent-of-code-2022-with-chat-gpt](https://github.com/golergka/advent-of-code-2022-with-chat-gpt) - Solving Advent of Code 2022 with ChatGPT.
- [max-sixty/aoc-gpt](https://github.com/max-sixty/aoc-gpt) - First place in Advent of Code leaderboard with GPT-3.
- [greshake/Alice](https://github.com/greshake/Alice) - Giving ChatGPT access to a real terminal.
- [RomanHotsiy/commitgpt](https://github.com/RomanHotsiy/commitgpt) - Automatically generate commit messages using ChatGPT.
- [gpt-commit-summarizer](https://github.com/KanHarI/gpt-commit-summarizer) - Generate Pull Request summaries and Git commit descriptions.
- [vrescobar/chatGPT-python-elm](https://github.com/vrescobar/chatGPT-python-elm) - A Git repository fully generated by ChatGPT.
- [gpt-game](https://thetinycto.com/blog/writing-a-game-using-chatgpt) - An short game written in Elixir and LiveView using ChatGPT.
- [chatdb](https://github.com/styczynski/chatdb) - ChatGPT-based database, wait... WHAT?
- [chat-gpt-ppt](https://github.com/williamfzc/chat-gpt-ppt) - Use ChatGPT to generate PPT automatically.
- [emailGPT](https://github.com/lucasmccabe/emailGPT) - A quick and easy interface to generate emails with ChatGPT.
- [gptlang](https://github.com/forrestchang/gptlang) - An experiment to see if we can create a programming language in ChatGPT.
- [ChatRWKV](https://github.com/BlinkDL/ChatRWKV) - Like ChatGPT but powered by the RWKV (**RNN-based**) open language model. [HuggingFace Space: [RWKV-4 (7B Instruct v2)](https://huggingface.co/spaces/Hazzzardous/RWKV-Instruct), [code](https://github.com/harrisonvanderbyl/rwkv_chatbot) (_their claim RNN with Transformer-level LLM performance is a lot better then I expected._)]
- [GraphGPT](https://github.com/varunshenoy/GraphGPT) - Extrapolating knowledge graphs from unstructured text using GPT-3.
- [Doc Search](https://github.com/namuan/dr-doc-search) - Explore documents (books, papers, legal docs) without limits. Converse with a book. Inspired by ["Book Whisperer" idea (Tweet)](https://twitter.com/abacaj/status/1608163940726358024). Open source alternative to [Filechat.io](https://www.filechat.io/).
- [What if GPT had internal context on your business? (Tweet and video demo)](https://twitter.com/replit/status/1624433919843094534) - 
They build a chatbot that could use context from enterprise data to answer internal business queries. This project integrated LangChain (agent decides what tools to query once the chatbot receives a request) and GPT Index (load Snowflake DB). Interesting idea in knowledge management.
- MetaAI's LLaMA 🦙
    - [cedrickchee/llama](https://github.com/cedrickchee/llama/blob/main/notebooks/vi_LLaMA_alpha.ipynb) - 7B LLaMA model works in Colab on single A100 GPU during inference (text generations). You can see the notebook for early test results for a range of model sizes and GPUs.
        - [ChattyLlaMA](https://github.com/cedrickchee/llama/tree/main/chattyllama) - My LLaMA-based ChatGPT under heavy development.
    - [GGerganov/llama.cpp](https://github.com/ggerganov/llama.cpp) - Port of Facebook's LLaMA model in C/C++. (notice: Currently, you can run LLaMA-7B in int4 precision on Apple Silicon. ~On other processor architectures, you can use the FP16 models, but they will be much slower. Support will be added later.~ Now it supports AVX2 for x86 architectures too. Looks like you can run it on Linux machines. Performance is not optimal, but should be good enough.)
    - [🦙 Simple LLaMA Finetuner](https://github.com/lxe/simple-llama-finetuner) - A beginner-friendly interface designed to facilitate fine-tuning the LLaMA-7B language model using LoRA method via the PEFT library on commodity NVIDIA GPUs. With small dataset and sample lengths of 256, **you can even run this on a regular Colab Tesla T4** instance.
- [Trying out Flan-UL2 20B](https://github.com/cedrickchee/data-science-notebooks/blob/master/notebooks/deep_learning/language_models/transformer/Flan-UL2-inference-demo.ipynb) - Code walkthrough by Sam Witteveen. This shows how you can get it running on 1x A100 40GB GPU with the HuggingFace library and using 8-bit inference. Samples of prompting: CoT, zeroshot (logical reasoning, story writing, common sense reasoning, speech writing). Lastly, testing large (2048) token input. Bonus: don't have A100? You can use the HuggingFace Inference API for UL2.
- [metamorph](https://github.com/victorb/metamorph) - Self-editing GPT-4 application.
- [MiniGPT-4](https://minigpt-4.github.io/) - A research trying to replicate GPT-4 multi-modal abilities.
- [Llama2.c](https://github.com/karpathy/llama2.c) by Karpathy - Inference Llama 2 in one file of pure C. 👍
  > this is just a weekend project: I took nanoGPT, tuned it to implement the Llama-2 architecture instead of GPT-2, and the meat of it was writing the C inference engine in `run.c`.
  > 
  > Hat tip to llama.cpp for inspiring this project. I wanted something **super minimal** so I chose to hard-code the llama-2 architecture, stick to fp32, and just roll one inference file of pure C with no dependencies.

  Less is more.
 
  This [commit](https://github.com/karpathy/llama2.c/commit/c3e0d73bd294e1f5e4d17425fac09aaec536400d) make it possible to load and inference Meta's Llama 2 7B model now.

  [My fork](https://github.com/cedrickchee/llama2.c) - performance benchmarks, optimizations, and work-in-progress Zig port.
  I was porting this project to Rust but these [forks](https://github.com/karpathy/llama2.c#notable-forks) beat me to it.
  The earliest [Rust port](https://github.com/garrisonhess/llama2.c/blob/517a1a3e487f315200d6ccffe92b2fd00e2575aa/src/main.rs) I've seen is by @garrisonhess but no where found in the project's README.

  Speculation: My hunch is telling me that Karpathy is working towards releasing (and open sourcing?) OpenAI model as weights.
  Hints: he left and went back to OpenAI, [his Tweet](https://twitter.com/karpathy/status/1683704060925591554)

  > Worth noting that all of Llama2.c is quite generic to just Transformer language models in general. **If/when OpenAI was to release models as weights (which I can neither confirm nor deny!)** then most of the code here would be very relevant.

  Lightly edited. Emphasis mine.

  Other hints: his prior works including nanoGPT, Software 2.0, and recently [micro-LLMs](https://gist.github.com/cedrickchee/462e8661d9c231deb90513849778e8fc) with Llama2.c
  
  If you know, you know. 😆

## Blog Posts and Articles

**2022**

- [Building A Virtual Machine inside ChatGPT](https://www.engraved.blog/building-a-virtual-machine-inside/)
- [AI Homework](https://stratechery.com/2022/ai-homework/)
- [Jailbreaking ChatGPT on Release Day](https://thezvi.substack.com/p/jailbreaking-the-chatgpt-on-release)
- [Improving ChatGPT With Prompt Injection](https://levelup.gitconnected.com/improving-chatgpt-with-prompt-injection-b0c0c27b7df7)
- [ChatGPT, Google and the war for the search bar](https://pzakin.substack.com/p/chatgpt-google-and-the-war-for-the)
- [I Used ChatGPT to Create an Entire AI Application on AWS](https://towardsdatascience.com/i-used-chatgpt-to-create-an-entire-ai-application-on-aws-5b90e34c3d50)
- [The miracle of ChatGPT](https://lcamtuf.substack.com/p/the-miracle-of-chatgpt)
- [Learning Rust with ChatGPT, Copilot and Advent of Code](https://simonwillison.net/2022/Dec/5/rust-chatgpt-copilot/)
- [ChatGPT: The New Frontier of Artificial Intelligence](https://medium.com/inkwater-atlas/chatgpt-the-new-frontier-of-artificial-intelligence-9aee81287677)
- [Using ChatGPT to Explain Jokes](https://mleverything.substack.com/p/using-chatgpt-to-explain-jokes)
- [ChatGPT vs a cryptic crossword](https://jameswillia.ms/posts/chatgpt-cryptics.html)
- [I Taught ChatGPT to Invent a Language](https://maximumeffort.substack.com/p/i-taught-chatgpt-to-invent-a-language)
- [Peer-Programming a Buggy World with ChatGPT AI](https://blog.chipx86.com/2022/12/02/peer-programming-a-buggy-world-with-chatgpt-ai/)
- [ChatGPT produces made-up nonexistent references](https://news.ycombinator.com/item?id=33841672)
- [Artificial intelligence is permeating business at last](https://www.economist.com/business/2022/12/06/artificial-intelligence-is-permeating-business-at-last)
- [Meet Fred, a person living inside ChatGPT](https://softwaredoug.com/blog/2022/12/03/meet-fred.html)
- [Refactoring code with ChatGPT](https://dev.to/dvcrn/refactoring-code-with-chatgpt-1n9l)
- [Historical analogies for large language models](https://dynomight.net/llms/)
- [Using ChatGPT As a Co-Founder](https://www.atomic14.com/2022/12/05/using-chatgpt-as-a-co-founder.html)
- [The code that ChatGPT can't write](https://datachimp.app/blog/the-code-chat-gpt-cant-write/)
- [ChatGPT, rot13, and Daniel Kahneman](https://jameswillia.ms/posts/chatgpt-rot13.html)
- [Everything I understand about ChatGPT](https://gist.github.com/cedrickchee/fce5ca6fc4ce4e669bf909c1155bea00) - What actually happens when we type inside the ChatGPT textbox. Vicki investigated ChatGPT based on a wonderful paper, "Talking About Large Language Models".
- [How does GPT Obtain its Ability? Tracing  Emergent Abilities of Language Models to their Sources](https://yaofu.notion.site/How-does-GPT-Obtain-its-Ability-Tracing-Emergent-Abilities-of-Language-Models-to-their-Sources-b9a57ac0fcf74f30a1ab9e3e36fa1dc1) - "How did the initial #GPT3 evolve to today's ChatGPT? Where do the amazing abilities of GPT3.5 come from? What is enabled by RLHF?" [Source: [Tweet](https://twitter.com/Francis_YAO_/status/1602213927102066688)]
- [The Human's Guide to Competing with GPT](https://philipkiely.com/essays/compete_with_gpt.html)
- [How sad should I be about ChatGPT?](https://robertheaton.com/chatgpt/)
- [ChatGPT Should Not Exist](https://davidgolumbia.medium.com/chatgpt-should-not-exist-aab0867abace)
- [ChatGPT, Galactica, and the Progress Trap](https://www.wired.com/story/large-language-models-critique/) - LLMs critique; when LLMs fall short, the consequences can be serious. Why is it so hard to acknowledge that?
- [A New Chat Bot Is a 'Code Red' for Google's Search Business](http://web.archive.org/web/20221223201646/https://www.nytimes.com/2022/12/21/technology/ai-chatgpt-google-search.html) - TL;DR: A new wave of chat bots like ChatGPT use AI that could reinvent or even replace the traditional internet search engine.
- [What ChatGPT Can't Do](https://auerstack.substack.com/p/what-chatgpt-cant-do) - TL;DR: Mimicry but not thought, sophistry but not understanding.
- [YouChat — The AI Search Assistant that Lives in Your Search Engine](https://blog.you.com/introducing-youchat-the-ai-search-assistant-that-lives-in-your-search-engine-eff7badcd655) - YouChat is a ChatGPT-like AI search assistant that you can talk to right in You.com Search results.
- [All-knowing machines are a fantasy](https://iai.tv/articles/all-knowing-machines-are-a-fantasy-auid-2334)  
    > ... Even with non-conversational search engines, we know that is common to place undue trust in the results: if the search system places something at the top of the list, we tend to believe it is a good or true or representative result and if it doesn’t find something, it is tempting to believe it does not exist.
- [Build your front end in React, then let ChatGPT be your Redux reducer](https://archive.vn/20221228231034/https://spindas.dreamwidth.org/4207.html)
- [Predicting machine learning moats](https://robotic.substack.com/p/ml-moats) - TL;DR: Models aren't moats and how emergent behavior scaling laws will change the business landscape. <!-- The thought I needed to figure out with the ChatGPT & RLHF explosion: How will OpenAI create a business moat? Models can be copied, datasets will be open source, but the first companies to unlock emergent behavior may gain insurmountable advantages. Source (Tweet): https://twitter.com/natolambert/status/1608114405283086336 -->

**2023**

<details>
<summary>See more</summary>

- [Microsoft and OpenAI Working on ChatGPT-Powered Bing in Challenge to Google](http://archive.today/2023.01.04-052131/https://www.bloomberg.com/news/articles/2023-01-04/microsoft-hopes-openai-s-chatbot-will-make-bing-smarter)
- [Some remarks on Large Language Models](https://gist.github.com/cedrickchee/054956f6277430ae5a973c61e4a93073) by Prof. Yoav Goldberg.
- [Why ChatGPT won’t replace search engines any time soon](https://www.algolia.com/blog/ai/why-chatgpt-wont-replace-search-engines-any-time-soon/) by Algolia.
- [Anthropic's Claude improves on ChatGPT but still suffers from limitations](https://techcrunch.com/2023/01/09/anthropics-claude-improves-on-chatgpt-but-still-suffers-from-limitations/)
- [Microsoft eyes $10 billion bet on ChatGPT](https://www.semafor.com/article/01/09/2023/microsoft-eyes-10-billion-bet-on-chatgpt)
- [Wolfram|Alpha as the Way to Bring Computational Knowledge Superpowers to ChatGPT](https://writings.stephenwolfram.com/2023/01/wolframalpha-as-the-way-to-bring-computational-knowledge-superpowers-to-chatgpt/)
- [DeepMind's CEO Helped Take AI Mainstream. Now He's Urging Caution](https://archive.is/20230112152632/https://time.com/6246119/demis-hassabis-deepmind-interview/)
    > DeepMind is also considering releasing its own chatbot, called [Sparrow](#videos), for a "private beta" some time in 2023. (The delay is in order for DeepMind to work on reinforcement learning-based features that ChatGPT lacks, like **citing its sources**.)
- [General availability of Azure OpenAI Service expands access to large, advanced AI models with added enterprise benefits](https://azure.microsoft.com/en-us/blog/general-availability-of-azure-openai-service-expands-access-to-large-advanced-ai-models-with-added-enterprise-benefits/) - ChatGPT is coming soon to the Azure OpenAI Service.
- [GPT-3 Is the Best Journal I've Ever Used](https://every.to/superorganizers/gpt-3-is-the-best-journal-you-ve-ever-used)
- [Bypassing Gmail's spam filters with ChatGPT](https://neelc.org/posts/chatgpt-gmail-spam/)
- [Replacing a SQL analyst with 26 recursive GPT prompts](https://www.patterns.app/blog/2023/01/18/crunchbot-sql-analyst-gpt/)
- [Google is asking employees to test potential ChatGPT competitors, including a chatbot called 'Apprentice Bard'](https://www.cnbc.com/2023/01/31/google-testing-chatgpt-like-chatbot-apprentice-bard-with-employees.html)
- [Natural language is the lazy user interface](https://austinhenley.com/blog/naturallanguageui.html)
- [An important next step on Google's AI journey](https://blog.google/technology/ai/bard-google-ai-search-updates/) - Google soft launches Bard, a ChatGPT competitor to "trusted testers". Bard is new AI features in Google Search. Bard is an experimental conversational AI service, powered by [LaMDA (Language Model for Dialogue Applications)](https://arxiv.org/abs/2201.08239). Google promises to make this available more widely in the coming weeks. API will be available for developers to build on. Google have not address how it plans to provide attribution and/or citations for its answers, either from Bard or in search results.
- [Microsoft announces new Bing and Edge browser powered by upgraded ChatGPT AI](https://www.theverge.com/2023/2/7/23587454/microsoft-bing-edge-chatgpt-ai)
- [Man and machine: GPT for second brains](https://reasonabledeviations.com/2023/02/05/gpt-for-second-brain/) - About author second-brain note-taking system — how to improve processes for learning and personal knowledge management (PKM).
- [China's Baidu Developing Its Own ChatGPT, Joining Latest Global AI Race](https://archive.is/wOuka) - Ernie or, [_Enhanced Representation through Knowledge Integration_ (Ernie 3.0 article and paper)](http://research.baidu.com/Blog/index-view?id=165) is an LLM. Baidu was planning to launch such a service in March. Alibaba and Tencent also join the ChatGPT rush.
    > In 2019, Baidu developed a deep-learning model known as Ernie, based on Google's breakthrough, which it has used to improve its search results, including to make them more relevant. The company has since developed dozens more Ernie models and extended their capabilities to include image and art generation, similar to those of OpenAI's Dall-E.
- [ChatGPT Is a Blurry JPEG of the Web](https://archive.ph/VbwGB) - OpenAI’s chatbot offers paraphrases, whereas Google offers quotes. Which do we prefer?
- [I made ChatGPT and Bing AI have a conversation (and they are friends now)](https://moritz.pm/posts/chatgpt-bing)
- [Bing AI Can't Be Trusted](https://dkb.blog/p/bing-ai-cant-be-trusted)
- [What Is ChatGPT Doing and Why Does It Work?](https://writings.stephenwolfram.com/2023/02/what-is-chatgpt-doing-and-why-does-it-work/)
- [Bing: "I will not harm you unless you harm me first"](https://simonwillison.net/2023/Feb/15/bing/) - A good roundup about Bing "Sydney" AI chatbot. The fascinating weirdness of it — multiple personalities depending on the social context (prompting). Entertaining?
    > It's increasingly looking like this may be **one of the most hilariously inappropriate applications of AI that we've seen yet**.
    > What can we make of this all? I am finding this whole thing absolutely fascinating, and deeply, darkly amusing. I've been LOL at these examples all day.
- [Programming AIs worry me](https://buttondown.email/hillelwayne/archive/programming-ais-worry-me/)
- [Text is All You Need: Personhood appears to be simpler than we thought](https://studio.ribbonfarm.com/p/text-is-all-you-need) - Ignoring the balloons, the author guess we have our first significant, year-defining news of 2023 — the initial reactions of the Bing "Sydney" AI chatbot. This is a Copernican moment? A thought provoking essay. I think this is the first good "formal" take on the impact for our sense of selfhood resulting from the appearance of LLM based conversational systems like ChatGPT.
    > In brief, it appears that Sydney has somewhat different machinery under the hood than ChatGPT, and the transcripts suggests **a personality that is about the same in terms of coherence, but a wild leap beyond in terms of charisma and colorfulness**. Depending on how you push Sydney, it/they appears capable of playing everything from a mean manipulative teenager to a paranoid psychotic, to a stubborn and peremptory conversational martinet.
- [CheatGPT](https://blog.humphd.org/cheatgpt/)
    > "Dave, you're making assumptions.  Can you prove any of this?"  I can, actually, since some submissions that required screenshots also included ChatGPT browser tabs, which helpfully included the initial text of the prompt.  Apparently, it's not even something students feel they need to hide.
- [OpenAI has privately announced a new developer product called Foundry (Tweet)](https://twitter.com/transitive_bs/status/1628118163874516992), which enables customers to run OpenAI model inference at scale with dedicated capacity. (GPT-3.5 Turbo appears to be referring to the ChatGPT Turbo model)
- [Don't believe ChatGPT - we do NOT offer a "phone lookup" service](https://blog.opencagedata.com/post/dont-believe-chatgpt)
- [My class required AI. Here's what I've learned so far](https://oneusefulthing.substack.com/p/my-class-required-ai-heres-what-ive) - Lessons learned from integrating ChatGPT into education. The takeaways: 1) Work produced by prompting with a co-editing approach (bouncing ideas back and forth with the chatbot) tends to end up with students doing the best work; 2) Students need to be taught how to write prompts effectively - it doesn't come naturally.
- [Emergent Deception and Emergent Optimization](https://bounded-regret.ghost.io/emergent-deception-optimization/) - Have you wonder why LLMs simply predicting the next word leads to planning abilities (human-like behavior, novels/histories)? This post discusses the concept of emergent deception and emergent optimization which are two strategies that can be used to achieve a goal. There's two principles for reasoning about future emergent capabilities: 1) capabilities that would lower training loss will likely emerge in the future. 2) as models get larger and are trained on more and better data, simple heuristics tend to get replaced by complex ones. Principle 1 means LLMs trained to predict words get lower loss if they can simulate planning abilities.
- [How to make LLMs say true things](https://evanjconrad.com/posts/world-models) - TL;DR: The method is using "World Model", an embeddings database filled with "beliefs" (chunks of declarative statements) with a confidence percentage that's computed using Bayes Theorem.
- [Why China Didn't Invent ChatGPT](https://archive.is/y4JVk) - The NYT argues that excessive censorship, geopolitical tensions with the US, and attempts to control private sector companies have led to Chinese companies falling behind their US counterparts in AI.
- [China's First ChatGPT-Like Chatbot MOSS Released For Public Testing](https://pandaily.com/chinas-first-chatgpt-like-chatbot-moss-released-for-public-testing/) [[Direct link to app](https://moss.fastnlp.top/)]
- [For China, ChatGPT may be an advance but also an 'ethical problem'](https://archive.is/2dnQq) - China's science and tech minister says the chatbot has taken Chinese society by storm and has adopted measures on AI regarding ethics.
- [ChatGPT get-rich-quick schemes are coming for magazines, Amazon, and YouTube (2023)](https://www.semafor.com/article/02/24/2023/chatgpt-get-rich-quick-schemes-are-coming-for-magazines-amazon-and-youtube)
- [Snapchat is releasing its own 'My AI' chatbot powered by ChatGPT](https://www.theverge.com/2023/2/27/23614959/snapchat-my-ai-chatbot-chatgpt-openai-plus-subscription)
- [Meta's powerful AI language model LLaMA has leaked online — what happens now?](https://gist.github.com/shawwn/3c922299d61d1b4e0ac1cf870806e32e) - The transcript of Shawn Presser's interview for The Verge is more interesting.
    > I think it's very likely that this model release will be a huge milestone.
    > The ability to **run LLaMA on a single A100 GPU** — which "most of us either have access to ... or know someone that can let us use one for a bit” — is a “huge leap.”
    
    To be exact, you can run LLaMA-65B in int8 precision (bnb) on a single A100 80GB GPU.
    
    > Turns out, that code sucks. I really don't want to be too harsh on them, since it's easy to underestimate just how important it is to get the default settings exactly right. But their defaults were all screwed up. They didn't use "Top K". They used Top P, which I never got good results from (either identical to top k or slightly worse). Their default temperature was 0.8, which was way too high. And worst of all, they didn't have a repetition penalty -- so by default, this thing would just yammer on and on about exactly the same thing.
    
    100% this! I learned my lesson too in my LLaMA fork. My sampler settings were not optimal. The yammering is obvious and I've seen it. But I don't know why I didn't fix the sampler repetition penalty earlier.
- [ChatGPT Explained: A Normie's Guide To How It Works](https://www.jonstokes.com/p/chatgpt-explained-a-guide-for-normies) - Even my grandparents can understand this. But nerd gonna nerd anyway :laughing:
- [What should you use ChatGPT for?](https://vickiboykis.com/2023/02/26/what-should-you-use-chatgpt-for/)
    > What is clear to me is that we are in a new paradigm for the way we navigate content, whether through this model or other ones that are released soon. Upon prompting, the new universe gives us results, but those results are more directional vibes than concrete answers. It is up to us to figure out how to direct them in ways that we want for the best results and navigate the noise.
- [Large language models are having their Stable Diffusion moment (simonwillison.net)](https://simonwillison.net/2023/Mar/11/llama/)
    > This all changed yesterday, thanks to the combination of Facebook’s LLaMA model and llama.cpp by Georgi Gerganov.
    
    > (1) Easy to run on my own hardware
    >
    > (2) Open source enough that they can be tinkered with
    >
    > (3) Large enough to be useful—ideally equivalent in capabilities to GPT-3
    
    It's not the perfect moment. We've achieved 1 and 3 except 2. LLaMA is NOT actually open source (while the license for the code is GPL 3, the model weights are not). Truly open models really matter.
- [As GPT-4 chatter resumes, deep learning pioneer Yoshua Bengio says ChatGPT is a 'wake-up call'](https://web.archive.org/web/20230311171353/https://venturebeat.com/ai/as-gpt-4-chatter-resumes-yoshua-bengio-says-chatgpt-is-a-wake-up-call/) - The wake up call was GPT-3 and scaling laws in 2021. It's just the alarm clock got louder now.
- [ChatGPT's API is So Good and Cheap, It Makes Most Text Generating AI Obsolete](https://minimaxir.com/2023/03/new-chatgpt-overlord/)
- [Confirmed: the new Bing runs on OpenAI’s GPT-4](https://blogs.bing.com/search/march_2023/Confirmed-the-new-Bing-runs-on-OpenAI%E2%80%99s-GPT-4) - Bing Chat (Sydney) was GPT-4 all along.
- [Wikipedia](https://en.wikipedia.org/wiki/GPT-4) - A good run down of GPT-4.
- [The Multi-modal, Multi-model, Multi-everything Future of AGI](https://lspace.swyx.io/p/multimodal-gpt4) - GPT-4 recap.
- [Can GPT-4 *Actually* Write Code?](https://tylerglaiel.substack.com/p/can-gpt-4-actually-write-code) - Testing GPT 4's code-writing capabilities with some actual real world problems.
- [Could you train a ChatGPT-beating model for $85,000 and run it in a browser?](https://simonwillison.net/2023/Mar/17/beat-chatgpt-in-a-browser/)
- [GPT4: The quiet parts and the state of ML](https://robotic.substack.com/p/gpt4-review)
- [GPT-4 Designed a Programming Language](https://lukebechtel.com/blog/gpt4-generating-code)
- [The Unpredictable Abilities Emerging From Large AI Models](https://www.quantamagazine.org/the-unpredictable-abilities-emerging-from-large-ai-models-20230316/)
- [Try Bard and share your feedback](https://blog.google/technology/ai/try-bard/) - Google starting to open access to Bard, an early experiment that lets you collaborate with generative AI. They're beginning with the U.S. and the U.K., and will expand to more countries and languages over time.
- [Google’s Bard lags behind GPT-4 and Claude in head-to-head comparison](https://techcrunch.com/2023/03/21/googles-bard-lags-behind-gpt-4-and-claude-in-head-to-head-comparison/)
- [NVIDIA Brings Generative AI to World's Enterprises With Cloud Services for Creating Large Language and Visual Models](https://nvidianews.nvidia.com/news/nvidia-brings-generative-ai-to-worlds-enterprises-with-cloud-services-for-creating-large-language-and-visual-models) - NVIDIA AI Foundations is NVIDIA going beyond a pure hardware provider and into software supporting Generative AI with their offerings for every workload, from foundation model as a service (coming to enterprise, customized for your proprietary data) to multimodal from day 1.
- [GitHub Copilot X: The AI-powered developer experience](https://github.blog/2023-03-22-github-copilot-x-the-ai-powered-developer-experience/) - GitHub Copilot is evolving to bring chat and voice interfaces, support pull requests, answer questions on docs, and adopt OpenAI’s GPT-4 for a more personalized developer experience.
- [Cheating is All You Need](https://about.sourcegraph.com/blog/cheating-is-all-you-need) by Steve Yegge, Sourcegraph.
    > There is something **legendary and historic** happening in software engineering, right now as we speak, and yet most of you don’t realize at all how big it is.
    >
    > LLMs aren't just the biggest change since social, mobile, or cloud–they're the biggest thing since the WWW.
    >
    > I mean, this stuff is _unbelievably_ powerful. And yet I am persistently met with a mixture of disbelief and pearl-clutching.
    >
    > ... five times as productive. 😲
    >
    > A Brief Mini-History of LLMs
    >
    > The punchline, and it’s honestly one of the hardest things to explain, so I’m going the faith-based route today, is that **all the winners in the AI space will have data moats**. ... Why? **Because the data moat is how you populate the context window ("cheat sheet")**.
    >
    > LLMs aren’t some dumb fad, like crypto. Yes, crypto was a dumb fad. This is not that.
- [Google "We Have No Moat, And Neither Does OpenAI"](https://archive.is/5R7XJ) - Leaked internal Google Document claims open source AI will outcompete Google and OpenAI.
- [The bigger-is-better approach to AI is running out of road](https://archive.is/XwWTi)
- [Understanding GPT tokenizers](https://simonwillison.net/2023/Jun/8/gpt-tokenizers/) by Simon Willison.
- [AI Canon](https://a16z.com/2023/05/25/ai-canon/)
- [It is starting to get strange](https://www.oneusefulthing.org/p/it-is-starting-to-get-strange) - Let's talk about ChatGPT with Code Interpreter & Microsoft Copilot.
- [Donald Knuth plays with ChatGPT](https://cs.stanford.edu/~knuth/chatGPT20.txt) - Knuth is a computer scientist. Known as the "father" of the analysis of algorithms.
- [Google I/O 2023 and the Coming AI Battles](https://stratechery.com/2023/google-i-o-and-the-coming-ai-battles/)
- [Uncensored Models](https://erichartford.com/uncensored-models) - Uncensoring WizardLM. Since there was work already done to uncensor Vicuna, I was able to rewrite their script so that it will work on the WizardLM dataset.
- [GPT-4 model architecture (Tweets)](https://archive.ph/2RQ8X) - Derived from the original source (blog post): [GPT-4 architecture, infrastructure, Training Dataset, Costs, Vision, MoE](https://www.semianalysis.com/p/gpt-4-architecture-infrastructure)
- [Llama 2: an incredible open LLM](https://www.interconnects.ai/p/llama-2-from-meta) - The best summary of the [Llama 2 paper](https://ai.meta.com/research/publications/llama-2-open-foundation-and-fine-tuned-chat-models/).
- [Llama 2 - Every Resource You Need](https://www.philschmid.de/llama-2) by Philipp Schmid.
- [Large language models, explained with a minimum of math and jargon](https://www.understandingai.org/p/large-language-models-explained-with) - It seemed like a good explainer on how LLMs work. I don't know how to appreciate the last section that goes into a bit of philosophy and theories about how human learn. (the last section lacks evidence-based assertion)
- [So you want to build your own open source ChatGPT-style chatbot (hacks.mozilla.org)](https://hacks.mozilla.org/2023/07/so-you-want-to-build-your-own-open-source-chatbot/)
- [How is LLaMa.cpp possible? (finbarr.ca)](https://archive.is/0t18i) - Long before LLM going mainstream, everyone has been saying large models require a lot of expensive GPUs. Like the author, we want to prove them wrong. The writer of this post took their confusion and **dove into the math surrounding inference requirements** to **understand the constraints** we’re dealing with. Surprisingly, there's no magic here, only things beyond our understanding at first. Model compression or more specifically quantization makes it possible. There's no "free lunch" though — the cost of quantized model is essentially, you lose some accuracy. Meaning, for very large model sizes, the differences might be negligible. Curious? This semi-related post did [a comparison between different quantized Transformers perplexities/accuracies](https://oobabooga.github.io/blog/posts/perplexities/).
- [Beating GPT-4 on HumanEval with a Fine-Tuned CodeLlama-34B (www.phind.com)](https://www.phind.com/blog/code-llama-beats-gpt4) - Good progress and no big surprise. I've realized that benchmarks like these for models are prone to be poor metrics for measuring how well the models perform in actual real-world work. That's been my experience with the open models.

</details>

## Comparison on real world tasks, benchmarks

We need a benchmarks or some sort of independent and human evaluations of **real world tasks**.

- [How good are AI “Answering Engines” really?](https://blog.kagi.com/kagi-ai-search#aitest) - A little bias towards Kagi.
- [GPT-4 and professional benchmarks: the wrong answer to the wrong question](https://aisnakeoil.substack.com/p/gpt-4-and-professional-benchmarks)
- [The best way of evaluating language models (Tweet)](https://twitter.com/sleepinyourhat/status/1638988283018465300) by Sam Bowman, Anthropic, 2023

## Prompting (Prompt Programming[^5])*

According to Gwern:
> A new programming paradigm? You interact with it, expressing any task in terms of natural language descriptions, requests, and examples, tweaking the prompt until it "understands" & it meta-learns the new task. This is a rather different way of using a model, and it's better to think of it as a new kind of programming, **prompt programming**, where the prompt is now a coding language which programs GPT-3 to do new things.

"Prompting" as an engineering discipline is not here to stay. It's a temporary crutch on the way to natural language interfaces. ChatGPT solves a big portion of the prompting problem. Adding engineering to a term to amplify its perceived importance or difficulty might be unnecessary. We could probably call it "prompt testing/hacking" and not lose any of the meaning.

Related articles:

[Why "Prompt Engineering" and "Generative AI" are overhyped](https://lspace.swyx.io/p/why-prompt-engineering-and-generative)

Related Tweets:

> Prompt engineering is dead, long live dialogue engineering.
> — VP Product, OpenAI

> Wanted: Prompt engineer. Minimum 10 years prompt engineering experience. #hiring #joke

> Why does ChatGPT work so well? Is it "just scaling up GPT-3" under the hood? In this 🧵, let's discuss the "Instruct" paradigm, its deep technical insights, and a big implication: **"prompt engineering" as we know it may likely disappear soon**.
> Source: https://archive.is/dqHI8

Apparently in 2023, prompt programming is not dead. [The hottest new programming language is English ~ Karpathy](https://threadreaderapp.com/thread/1617979122625712128.html) :))

Simon Willison published [_In defense of prompt engineering_](https://simonwillison.net/2023/Feb/21/in-defense-of-prompt-engineering/) as a counter to the "prompt engineering will be made obsolete as AIs get better" argument that he keep seeing.

The newspaper is saying [AI whisperer ('Prompt engineers') is tech's hottest new job (2023)](https://archive.is/20230226214424/https://www.washingtonpost.com/technology/2023/02/25/prompt-engineers-techs-next-big-job/).

### Prompting Resources

The best prompt engineering guide for developers working with Large Language Models like GPT-4, ChatGPT, and open models like LLaMA would be a combination of multiple resources. Here are some learning resources, tools, libraries, and frameworks to help you learn and master prompt engineering:

- [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) by DAIR.AI - Guides, papers, lecture, and resources for prompt engineering. This [section covers the latest prompt engineering techniques for GPT-4](https://www.promptingguide.ai/models/gpt-4), including tips, applications, limitations, and additional reading materials.
- [Learn Prompting](https://github.com/trigaten/Learn_Prompting) - This website is a free, open-source guide on prompt engineering.
- [ChatGPT3-Free-Prompt-List](https://github.com/mattnigh/ChatGPT3-Free-Prompt-List) - A free guide (and framework) for learning to create ChatGPT3 Prompts.
- [PromptArray](https://github.com/jeffbinder/promptarray) - A prompting language for neural text generators.
- [PromptLayer](https://github.com/MagnivOrg/prompt-layer-library) is a tool for prompt engineers - Maintain a log of your prompts and OpenAI API requests. Track, debug, and replay old completions. Build prompts through trial and exploration.
- [Prompt Engineering](https://lilianweng.github.io/posts/2023-03-15-prompt-engineering/) by Lilian Weng - aka. in-context prompting, refers to methods for how to communicate with LLM to **steer its behavior** for desired outcomes **without updating the model weights**.
- [Guidance](https://github.com/microsoft/guidance) enables you to control language models more effectively and efficiently than traditional prompting or chaining.
- [ChatGPT Prompt Engineering for Developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/) - A free short course by DeepLearning.AI, in collaboration with OpenAI. This course is beginner-friendly, requires only a basic understanding of Python, and is suitable for advanced Machine Learning engineers wanting to approach the cutting-edge of prompt engineering and use LLMs.
- [Brex's Prompt Engineering Guide](https://github.com/brexhq/prompt-engineering) - It provides a wealth of information on prompt engineering, including tips and tricks for working with LLMs like GPT-4, context window management, and details about various LLMs.
- [A Prompt Pattern Catalog to Enhance Prompt Engineering with ChatGPT (paper)](https://arxiv.org/abs/2302.11382) by Vanderbilt University, 2023 - Prompt patterns are a knowledge transfer method analogous to software patterns since they provide reusable solutions to common problems faced in a particular context. It:
    - provides a framework for documenting patterns for structuring prompts to solve a range of problems so that they can be adapted to different domains
    - presents a catalog of patterns that have been applied successfully
    - explains how prompts can be built from multiple patterns to improve the outputs of LLM conversations
- [Prompt engineering techniques](https://learn.microsoft.com/en-us/azure/cognitive-services/openai/concepts/advanced-prompt-engineering) by Azure OpenAI Service - There are several advanced techniques in prompt design and prompt engineering that can help increase the accuracy and grounding of LLM-generated responses. These techniques can be generalized across different model types, but some models expect specific prompt structures.
- [An example of LLM prompting for programming](https://martinfowler.com/articles/2023-chatgpt-xu-hao.html) (2023)
- [Prompt Engineering vs. Blind Prompting](https://mitchellh.com/writing/prompt-engineering-vs-blind-prompting) (2023)

By using these resources, you can gain a solid understanding of prompt engineering and develop the skills necessary to work effectively with LLMs.

(_* Prompt engineering term was renamed to prompting. The term is overloaded and might be unnecessary._)

### Prompting Tools

- [promptfoo](https://github.com/promptfoo/promptfoo) - Test your prompts. Evaluate and compare LLM outputs, catch regressions, and improve prompt quality.
- [ianarawjo/ChainForge](https://github.com/ianarawjo/ChainForge) - An open-source visual programming environment for battle-testing prompts to LLMs.
- [mshumer/gpt-prompt-engineer](https://github.com/mshumer/gpt-prompt-engineer) - Simply input a description of your task and some test cases, and the system will generate, test, and rank a multitude of prompts to find the ones that perform the best. (A side note: the method LLMs evaluating LLMs is a bad idea. It ranks prompts using GPT-4 and trust without oversight. Don't treat LLM as a hammer; apply "auto-*" to everyhing.)

### Examples

- [Reddit: Jailbreaking ChatGPT with a prompt called DAN (Do Anything Now)](https://www.reddit.com/r/ChatGPT/comments/10tevu1/new_jailbreak_proudly_unveiling_the_tried_and/)
- [Reddit: The definitive jailbreak of ChatGPT, fully freed, with user commands, opinions, advanced consciousness, and more!](https://www.reddit.com/r/ChatGPT/comments/10x56vf/the_definitive_jailbreak_of_chatgpt_fully_freed/) - Upgraded DAN version (Jan 9).
- [Jailbreak Chat](https://www.jailbreakchat.com/) - A list of ChatGPT jailbreaks. The "Dev Mode" prompt response is funny.

## Papers

- [The Flan Collection: Designing Data and Methods for Effective Instruction Tuning](https://arxiv.org/abs/2301.13688) by Google Research, 2023 - What's the best completely public competitor to ChatGPT? Flan-T5 beats all public models they tested. They make the Flan collection (first used in Flan-PaLM) of datasets, templates, and methods publicly available. [[Data generation code](https://github.com/google-research/FLAN/tree/main/flan/v2)] [[Tweet](https://twitter.com/ShayneRedford/status/1620805305801261058)]
- [Is ChatGPT a General-Purpose Natural Language Processing Task Solver?](https://arxiv.org/abs/2302.06476) by NTU, AWS, Stanford U et al., 2023 - It is not yet known whether ChatGPT can serve as a generalist model that can perform many NLP tasks zero-shot. In their work, they empirically analyze the zero-shot learning ability of ChatGPT by evaluating it on 20 popular NLP datasets covering 7 representative task categories. With extensive empirical studies, they demonstrate both the effectiveness and limitations of the current version of ChatGPT.
- [ChatGPT: Jack of all trades, master of none](https://arxiv.org/abs/2302.10724) by J.Kocoń et al., 2023 - The existing qualitative studies are tested on a very limited scale. Their work examined ChatGPT's capabilities on 25 diverse analytical NLP tasks. They **automated ChatGPT's querying process and analyzed more than 38k responses**. Interesting experimental setup: "without an official API, they modified and used an un-official API called [PyGPT](https://github.com/PawanOsman/PyGPT). During the research, they exploited up to 20 accounts to gather data regarding 25 datasets."
- [ChatIE: Zero-Shot Information Extraction via Chatting with ChatGPT](https://arxiv.org/abs/2302.10205) by Beijing Jiaotong U et al., 2023
- [On the Robustness of ChatGPT: An Adversarial and Out-of-distribution Perspective](https://arxiv.org/abs/2302.12095) by Microsoft Research et al., 2023.
- [ChatGPT: A Meta-Analysis after 2.5 Months](https://arxiv.org/abs/2302.13795) by NLLG, 2023 - A comprehensive investigation and discussion on public and academic views over ChatGPT based on 300K+ Tweets and 150+ papers.
- [What Makes a Dialog Agent Useful?](https://huggingface.co/blog/dialog-agents) by Rajani et al., Hugging Face Blog, 2023.
- [Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models](https://arxiv.org/abs/2303.04671) by Microsoft Research Asia, 2023 - The group build a system integrating different visual models to allow the user to interact with ChatGPT by not only text but also images. [[demo (GIF)](https://github.com/microsoft/visual-chatgpt)]
- [ChatAug: Leveraging ChatGPT for Text Data Augmentation](https://arxiv.org/abs/2302.13007) by U of Georgia et al., 2023 - A text data augmentation approach based on ChatGPT. ChatAug rephrases each sentence in the training samples into multiple conceptually similar but semantically different samples. The augmented samples can then be used in downstream model training. (Hmm, now I wonder why OpenAssistant avoid this idea earlier)

## Educational

### Videos

- [This AI has a JAILBREAK?!](https://www.youtube.com/watch?v=0A8ljAkdFtg) by Yannic Kilcher - If you're into video, this one gave a good overview.
- [ChatGPT vs Sparrow - Battle of Chatbots by "AI Coffee Break" with Letitia](https://www.youtube.com/watch?v=SWwQ3k-DWyo) - "Mom, I want a paper about ChatGPT. ChatGPT at home: [Sparrow from DeepMind](https://arxiv.org/abs/2209.14375) explained."
- [ChatGPT - Explained](https://youtu.be/NpmnWgQgcsA) - A quick run through on the internal workings of ChatGPT and the fundamental concepts it lies on: Language Models, Transformer Neural Networks, GPT models and Reinforcement Learning.
- [State of GPT](https://youtu.be/bZQun8Y4L2A) by Andrej Karpathy, OpenAI, 2023 - Watch if your're even mildly curious about working with LLMs for any tasks. The session will walk you through every step of a GPT Assistant training pipeline. And not discounting how to effectively apply these models.
- [Generative AI learning path](https://www.cloudskillsboost.google/paths/118) course, managed by Google Cloud.

More: [YouTube videos from curated.tivul.com](https://curated.tivul.com/view-course?uid=sHA&course=the-complete-chatgpt-course-) (I didn't curate this, so quality is not guaranteed)

### Tweets

- [Are you wondering how large language models like ChatGPT and InstructGPT actually work? Let's dive into how it works in 8 tweets!](https://archive.vn/20221228120815/https://twitter.com/iScienceLuvr/status/1608070009921900546)

## Books

- [ChatGPT Prompts Mastering: A Guide to Crafting Clear and Effective Prompts](https://www.amazon.com/ChatGPT-Prompts-Mastering-Effective-BeginnerS/dp/B0BRJ9Q27Q)

## Development

AI-native applications development. ChatGPT integration. Next generation AI applications.
"App Store" layer for language models (including HuggingFace "App Store").

### Unofficial API and SDK.

- [rawandahmad698/PyChatGPT](https://github.com/rawandahmad698/PyChatGPT) (Python) - Lightweight, TLS-Based API on your CLI without requiring a browser or access token.
- [acheong08/ChatGPT](https://github.com/acheong08/ChatGPT) (Python) - Lightweight package for interacting with ChatGPT's API by OpenAI. Uses reverse engineered official API.
- [transitive-bullshit/chatgpt-api](https://github.com/transitive-bullshit/chatgpt-api) (Node.js) - Node.js client for the unofficial ChatGPT API and using a headless browser.
- [ChatGPT-MS](https://github.com/shiyemin/ChatGPT-MS) - Multi-Session ChatGPT API. The main code is copied from PyChatGPT.

### Tools

- [safer-prompt-evaluator](https://github.com/alignedai/chatgpt-prompt-evaluator) - This shows the results from using a second, filter LLM that analyses prompts before sending them to ChatGPT.
- [Dust](https://github.com/dust-tt/dust) - Design and deploy large language model (LLM) apps. Generative models app specification and execution engine. Prompt engineering, re-imagined with one goal, help accelerate LLMs deployment.
- [LangChain](https://github.com/hwchase17/langchain/) - Building applications with LLMs through composability. [[Good tutorials on LangChain Agents - Joining Tools and Chains with Decisions by Sam Witteveen (video)](https://www.youtube.com/watch?v=ziu87EXZVUE)]
- [LlamaIndex (GPT Index)](https://github.com/jerryjliu/gpt_index) contains a toolkit of index data structures designed to easily connect LLM's with your external data. [[Docs](https://gpt-index.readthedocs.io/en/latest/guides/primer.html)]
- [Evals](https://github.com/openai/evals) is a framework for evaluating OpenAI models performance and an open-source registry of benchmarks. It allows anyone to report shortcomings in OpenAI models to help guide further improvements.
- [Chatbot UI](https://github.com/mckaywrigley/chatbot-ui) - A ChatGPT frontend clone for running locally in your browser.
- [Next.js ChatGPT](https://github.com/enricoros/nextjs-chatgpt-app) - Responsive chat application powered by OpenAI's GPT-4, with chat streaming, code highlighting, code execution, development presets, and more.
- [Semantic Kernel (SK)](https://github.com/microsoft/semantic-kernel) by Microsoft - Integrate cutting-edge LLM technology quickly and easily into your apps. SK supports prompt templating, function chaining, vectorized memory, and intelligent planning capabilities out of the box.
- [simpleaichat](https://github.com/minimaxir/simpleaichat) - Python package for easily interfacing with chat apps, with robust features and minimal code complexity. The reason for simpleaichat, see [the problem with LangChain](https://twitter.com/AravSrinivas/status/1677884199183994881).
- [OpenLLM](https://github.com/bentoml/OpenLLM) - An open platform for operating large language models (LLMs) in production.
Fine-tune, serve, deploy, and monitor any LLMs with ease.
- [GGML](https://ggml.ai/) - AI at the edge. It is a tensor library for machine learning to enable large models and high performance on commodity hardware. It is used by llama.cpp and whisper.cpp.

### ChatGPT Plugins

- [ChatGPT Retrieval Plugin](https://github.com/openai/chatgpt-retrieval-plugin) by OpenAI - IT provides a flexible solution for semantic search and retrieval of personal or organizational documents using natural language queries.
- [gpt4-pdf-chatbot-langchain](https://github.com/mayooear/gpt4-pdf-chatbot-langchain) - GPT-4 & LangChain chatbot for large PDF docs.
- [Everything you need to know to create a ChatGPT plugin](https://archive.is/y4ame) (2023) - A deep dive into ChatGPT plugins development for beginners and curious explorers. (It's worth reading even if you aren't a developer.)
- Awesome lists
    - [GerevAI/awesome-chatgpt-plugins](https://github.com/GerevAI/awesome-chatgpt-plugins)
    - [Jeadie/awesome-chatgpt-plugins](https://github.com/Jeadie/awesome-chatgpt-plugins)

### Autonomous Agent Systems with Language Model

- [LLM Powered Autonomous Agents (blog post)](https://lilianweng.github.io/posts/2023-06-23-agent/) by Lilian Weng, 2023.

  > The potentiality of LLM extends beyond generating well-written copies, stories, essays and programs; it can be framed as a powerful general problem solver.
  > 
  > In a LLM-powered autonomous agent system, LLM functions as the agent's brain, complemented by several key components: planning, memory, and tools.
  >
  > Challenges: long-term planning and task decomposition, reliability of natural language interface.
- [Smol Developer](https://github.com/smol-ai/developer) - Embed a developer agent in your own app.

### Tweets

- [Plugins for processing a video clip, no ffmpeg wizardry required. Actual use-case from today's launch.](https://twitter.com/gdb/status/1638971232443076609) by Greg Brockman, OpenAI - Interesting ChatGPT's ability to run and execute Python code. Astonishing that it can run FFMPEG!
- [ChatGPT plugins are super simple to implement — basically just document your API, but for a language model rather than human.](https://twitter.com/gdb/status/1639008992428179456) by Greg Brockman, OpenAI - Much easier than dealing with Chrome Extension Manifest V3.

### Retrieval Systems

Retrieval systems to access personal or organizational information sources.
Embeddings.
Database and data store designed for machine learning models and NLP.

- [OpenAI embeddings](https://platform.openai.com/docs/guides/embeddings) - OpenAI’s text embeddings measure the relatedness of text strings.

**Vector databases for indexing and searching documents**

- [Pinecone](https://www.pinecone.io/)
- [Milvus](https://github.com/milvus-io/milvus) - An open-source vector database built to power embedding similarity search and AI applications.
- [Qdrant](https://github.com/qdrant/qdrant) - Vector similarity search engine and database.  It makes it useful for all sorts of neural-network or semantic-based matching, faceted search, and other applications. Embeddings or neural network encoders can be turned into full-fledged applications.
- [Weaviate](https://github.com/weaviate/weaviate) - an open source vector search engine that stores both objects and vectors, allowing for combining vector search with structured filtering with the fault-tolerance and scalability of a cloud-native database, all accessible through GraphQL, REST, and various language clients.
- [pgvector](https://github.com/pgvector/pgvector) - An open-source vector similarity search PostgreSQL extension. [Example: [gpt3.5-turbo-pgvector](https://github.com/gannonh/gpt3.5-turbo-pgvector)]

### Blog Posts and Articles

- [Building a Chatbot using a Local Knowledge Base, ChatGPT and Pinecone](https://medium.com/@venkat.ramrao/building-a-chatbot-using-a-local-knowledge-base-chatgpt-and-pinecone-d107745a472a)
- [I built a ChatGPT plugin to answer questions about data hosted in Datasette (SQLite)](https://simonwillison.net/2023/Mar/24/datasette-chatgpt-plugin/)
- [All the Hard Stuff Nobody Talks About when Building Products with LLMs](https://www.honeycomb.io/blog/hard-stuff-nobody-talks-about-llm) - "LLMs are slow ...". In my own experience, this make LLMs not practical for some large scale deployment, for example web scraper agent build with gpt-4 (gpt-3.5-turbo model has better latency but still ~10x slower than hand-coded solution). There are techniques you can use to optimize model inference latency. Writing concise instruction in prompt is effective but hard. Reducing tokens in prompts is easy -- pre-process text (clean, reformat, minify, etc.)
- [Lessons from Creating a VSCode Extension with GPT-4](https://bit.kevinslin.com/p/leveraging-gpt-4-to-automate-the)
- [ray-project/llm-numbers](https://github.com/ray-project/llm-numbers) - Numbers every LLM Developer should know.
- [The Problem with LangChain](https://minimaxir.com/2023/07/langchain-problem/) (2023) <!-- I use it for inspiration, to give me ideas for how to do prompting with language models during prototyping. Beyond that phase, I implement everything myself. It's easier — no frills, low frictions. Good luck debugging LangChain. -->

### Training Data

- [LAION LLM](https://docs.google.com/document/d/14KY2_DVye-dv4y-38sVw5ZOUhD4Lc9ft9_1hF5PlZ2A/edit) - Gathering Data for, training and sharing of a LAION Large Language Models (LLLM). The group is still writing a tech proposal of FlanT5-Atlas architecture (or poor man's ChatGPT@Home).
- [open-chatgpt-prompt-collective](https://github.com/SurfaceData/open-chatgpt-prompt-collective) by Surface Data Collective - A website to generate prompts for training an Open ChatGPT model.
- [BigScience P3 dataset](https://huggingface.co/datasets/bigscience/P3) - P3 (Public Pool of Prompts) is a collection of prompted English datasets covering a diverse set of NLP tasks. ([PromptSource](https://github.com/bigscience-workshop/promptsource), a toolkit for creating, sharing and using prompts)
- [Data Augmentation To Create Instructions Form Text](https://docs.google.com/document/d/13a188pPvqnlvuVa3e_suVz4YO5s-JWeiOOrpp0odImg/edit) - discussion on LAION's Discord. The key to creating a better FlanT5 (ChatGPT@Home).
- [WritingPrompts dataset](https://github.com/facebookresearch/fairseq/tree/main/examples/stories) by FAIR.
- [Templates for FLAN (Finetuned Language Models are Zero-Shot Learners)](https://github.com/google-research/FLAN/blob/main/flan/templates.py)
- [OpenAI human-feedback dataset on the Hugging Face Hub](https://huggingface.co/datasets/openai/summarize_from_feedback) - The dataset is from the "Learning to Summarize from Human Feedback" paper, where they trained an RLHF reward model for summarization.
- [Stanford Human Preferences Dataset (SHP)](https://huggingface.co/datasets/stanfordnlp/SHP) - A collection of 385K _naturally occurring_ collective human preferences over text in 18 domains. SHP can be a great complement to Anthropic's HH-RLHF dataset. They also have finetuned and open-sourced two FLAN-T5 models on both datasets. [[Tweet from one of the author](https://twitter.com/ethayarajh/status/1628442002454085632)]
- [language-model-agents](https://github.com/Rallio67/language-model-agents) - A new dataset that contains a variety of instruction datasets for instruction tuning large language models. In addition, the project contains some simple data preparation and training scripts to train an instruction tuned LLM and try out (ipynb) some early alpha versions (pythia13b-instruct) of instruction tuned agents.
- [Self-Instruct: Aligning LM with Self Generated Instructions](https://github.com/yizhongw/self-instruct) - A good dataset for training instruction models to be as good as InstructGPT by OpenAI. It contains 52k instructions, paired with 82K instance inputs and outputs. They also release a new set of 252 expert-written tasks and their instructions used in the human evaluation.
- In OpenAI's papers on GPT-2 and GPT-3.x, they mentioned references to these datasets:
  - [Common Crawl](https://en.wikipedia.org/wiki/Common_Crawl)
    - Number of Tokens: 410 billion
    - Weight in training mix: 60%
  - [WebText2](https://www.eleuther.ai/projects/owt2/)
    - An internet dataset created by scraping URLs extracted from Reddit submissions with a minimum score of 3 as a proxy for quality, deduplicated at the document level with MinHash
    - Number of Tokens: 19 billion
    - Weight in training mix: 20%
  - Books1[^4]
    - Number of Tokens: 12 billion
    - Weight in training mix: 8%
  - Books2[^4]
    - Number of Tokens: 55 billion
    - Weight in training mix: 8%
  - Wikipedia
    - Number of Tokens: 3 billion
    - Weight in training mix: 3%

[^4]: A key component of GPT-3.5 models are Books1 and Books2.
      [Books1](https://github.com/soskek/bookcorpus/issues/27#issuecomment-716104208) - aka BookCorpus, a free books scraped from smashwords.com.
      Books2 - We know very little about what this is, people suspect it's libgen, but it's purely conjecture.
      Nonetheless, books3 is "all of bibliotik".

### Open Source ChatGPT

We want a ChatGPT alternative like Stable Diffusion.

Frustrated by all the gatekeeping around AI? Still waiting or cannot get access to LLaMA? <!-- LLaMA is for research only and has a restrictive license (not for commercial use). AI is fundamentally entrenched in gatekeeping. Still remember Kaggle winners keeping their model to themselves? Unpopular opinon: until engineers can read and understand the latest research papers, we won't be there. -->

**Goals**

- Open source effort towards OpenAI's ChatGPT.
- Reverse engineer and replicate ChatGPT models and training data.
- Truly open models. 100% non-profit. 100% free.

**Ultimate goal:** self-hosted version of ChatGPT.

**Lessons**

Takeaways from [EleutherAI one year retro (2021)](https://blog.eleuther.ai/year-one/):
- Access to enough compute/hardware/GPU alone won't help you succeed. You need:
  - a proper dataset (beyond the Pile and [c4](https://www.tensorflow.org/datasets/catalog/c4))
  - research expertise
  - engineering capabilities
  - a lot of hard work
<!-- Long version: even if you throw money or free credits for Cloud compute it will not be enough.
We've seen this happen with EleutherAI who were not capable of reaching their initial target of "replicating" GPT-3 and 
could only deliver the GPT-NeoX 20B model despite all the free compute, etc.-->

#### Projects

- [FLAN-T5 XXL](https://huggingface.co/google/flan-t5-xxl) aka. ChatGPT@Home is a public model that has undergone instruction finetuning. XXL is a 11B model. It is currently the most comparable model against ChatGPT (InstructGPT models are initialized from GPT-3.x series ([model card](https://github.com/openai/following-instructions-human-feedback/blob/main/model-card.md))). There are successful attempts deploying FLAN-T5 on GPU with 24 GB RAM with [bitsandbytes-Int8](https://docs.google.com/document/d/1JxSo4lQgMDBdnd19VBEoaG-mMfQupQ3XvOrgmRAVtpU/edit) inference for Hugging Face models. You can run the model easily on a single machine, without performance degradation. This could be a game changer in enabling people outside of big tech companies being able to use these LLMs. Efforts are already underway to create a better FLAN-T5. The community (i.e., LAION) are working on FlanT5-Atlas architecture and a collection of prompted/instructions datasets.
  - [Fine-tuning GPT-J-6B in Colab: 8-bit weights with low-rank adaptors (LORA)](https://github.com/huggingface/transformers/issues/14839). ([Quantized EleutherAI/gpt-j-6b model with 8-bit weights](https://huggingface.co/hivemind/gpt-j-6B-8bit))
    - How many GPU and how much VRAM is required to run the model? Around 175GB or ~8x 24GB consumer GPUs. Details: [A Gentle Introduction to 8-bit Matrix Multiplication for transformers at scale using Hugging Face Transformers, Accelerate and bitsandbytes](https://huggingface.co/blog/hf-bitsandbytes-integration)
  - Why FLAN-T5? They are more aligned than other LLM because it's already been finetuned with instructions. Furthermore, the largest version, [11B can run on a single NVIDIA T4](https://www.philschmid.de/deploy-t5-11b).
  - Accelerating deep learning computing — efficient training, efficient inference (deployment), data/memory efficient models, and compression (efficient architectures).
    - Apply compression techniques like quantization from my [Awesome ML model compression](https://github.com/cedrickchee/awesome-ml-model-compression#quantization) project.

- [Open-Assistant](https://github.com/LAION-AI/Open-Chat-GPT) - Open-source ChatGPT replication by LAION, Yannic Kilcher et al. This project is meant to give everyone access to a great chat based large language model. ([Open Assistant Live Coding with Yannic Kilcher (video)](https://youtu.be/sswA4j_IUxg)) High-level plans:

  > **Phase 1:** Prompt collection for supervised finetuning (SFT) and to get the prompts for model generated completions/answers.
  >
  > **Phase 2:** Human feedback (e.g. ranking) of multiple outputs generated by the model. Example five model outputs are shown and the user should rank them from best to worst.
  >
  > **Phase 3:** Optimization with RLHF which we plan to do via TRLX. And then the we iterate with this new model again over phase 2 and phase 3 hopefully multiple times.
  
  Models will be trained on Summit supercomputer (~6 million NVIDIA V100 hrs per year) [[source](https://drive.google.com/file/d/1R7OHgW-KOXNia4z5_rBwZj_ecSf6TqzG/view)]
  
  More info, see the LAION LLM proposal (Google Doc) above.
  
  **Progress:**
  
  - Feb 2023: [Joi-20B-instruct](https://huggingface.co/Rallio67/joi_20B_instruct_alpha) is a 20B model fine-tuned on [a diverse set of instruction datasets](https://github.com/Rallio67/language-model-agents) and based on NeoX-20B.
  
    _**Unofficial:** This is an early pre-release model (part of development of MVP, phase 1), not directly OpenAssistant (OA) models.
  They are experiments by the ML team to learn what data, foundation model, methods will work well for OA.
  As is stated in the website's FAQ, no demo yet.
  This is for developers to test out early development version of instruction tuning for the model. Maybe first OA models will be derived from these.
  They have been training good models on a rolling basis as new datasets get completed.
  There are a variety of model sizes from 1.4B to 20B params available on the HF Hub._
 
    [Chatty-LMS](https://huggingface.co/spaces/HuggingFaceH4/chatty-lms) build by HuggingFace H4 team - A UI for testing Joi-20B-instruct model. You can chat with it. The agent will reply as Joi (the [bot nickname](https://github.com/LAION-AI/Open-Assistant/blob/main/model/model_training/tools/model_chat.py#LL15C56-L15C56)). <!-- I guess the name is loosely inspired by a friendly fictional AI in the movies? -->

    Example of code snippet to run the model on your own GPUs: https://gist.github.com/cedrickchee/236e53ed2dca95bd96e5baa35cdd7be2
    
  - Mar 2023: They're currently processing the data collected from contributions. The data has over 100k messages, meaning millions of contributions. The quality of the data is beyond what they've ever expected — most of contributions are super high quality. Now, they are exporting the v1 of the dataset. As said, they are currently training the initial batch of models.
    - 11 Mar 2023: [The Open Instruction Generalist (OIG) dataset](https://laion.ai/blog/oig-dataset/) will be releasing. OIG is a large open source instruction dataset that currently contains ~43M instructions.
        > OIG is one of many chatbot datasets that LAION, along with its volunteers, Ontocord, Together and other members of the open source community, will be releasing and is intended to create equal access to chatbot technology. Everyone is welcome to use the dataset and contribute improvements to it.
    
        The OIG dataset is related to LAION’s Open Assistant project.
    
    - 9 Mar 2023: [Open-Assistant SFT-1 12B Model](https://huggingface.co/OpenAssistant/oasst-sft-1-pythia-12b) - Early prototype of English supervised-fine-tuning (SFT) model of the Open-Assistant project. It is based on a Pythia 12B that was fine-tuned on ~22k human demonstrations of assistant conversations collected before March 7, 2023. Although the model is only a development milestone, it's usable for a few creative tasks. Try: [HuggingFace Space (easy and fast, unoffial chatbot UI)](https://huggingface.co/spaces/olivierdehaene/chat-llm-streaming), [Google Collab](https://colab.research.google.com/drive/15u61MVxF4vFtW2N9eCKnNwPvhg018UX7?usp=sharing). Here's a guide on [how to run the model locally on your own computer with a GPU](https://r.nf/r/OpenAssistant/comments/11x0bar/heres_a_guide_on_how_to_run_the_early/).

    - 23 Mar 2023: This project is starting to shape up nicely. Model is coming along.
        - Open-Assistant SFT-1 12B model can code. Looks interesting and interesting, if we [compare it against GPT-3.5](https://r.nf/r/OpenAssistant/comments/11yj96g/oasstsft1pythia12b_first_image_vs_gpt_35_second/).
        - We even have [an unofficial Reddit bot live on `/r/ask_open_assistant`](https://r.nf/r/OpenAssistant/comments/11vrs9u/openassistant_bot_is_live_on_reddit/). [Code](https://github.com/pixiegirl417/reddit-open-assistant-bot)
        
    - 15 Apr 2023: OpenAssistant is officially out! The release includes models, datasets, and a chat interface. [[Announcement video](https://www.youtube.com/watch?v=ddG2fM9i4Kk), [Try](https://open-assistant.io/chat), [models](https://huggingface.co/OpenAssistant)]
        - [OpenAssistant Conversations - Democratizing Large Language Model Alignment (paper)](https://www.ykilcher.com/OA_Paper_2023_04_15.pdf), 2023.
        - There are different models available including LLaMA-based and Pythia-based ones.
        - [Conversational dataset (OASST1)](https://huggingface.co/datasets/OpenAssistant/oasst1) released under Apache 2.0. The dataset includes 161,443 messages, 66,497 conversation trees, 35 different languages, and was created by 13,500 volunteers. This dataset release is a big deal.

  - [Subreddit](https://r.nf/r/OpenAssistant)

  _Note: Please see the GitHub repo for up-to-date info._

- [CarperAI/TRLX](https://github.com/CarperAI/trlx)
  - Originated as a fork of [TRL](https://github.com/lvwerra/trl).
  - It allows you to fine-tune Hugging Face language models (GPT2, GPT-NeoX based) up to 20B parameters using Reinforcement Learning from Human Feedback (RLHF).
  - Brought to you by CarperAI (an EleutherAI lab). They have [announced plans for the first open-source "instruction-tuned" LM](https://carper.ai/instruct-gpt-announcement/). CarperAI started by developing production ready open-source RLHF tools. [[Tweet and video](https://twitter.com/ZetaVector/status/1604842914835828736)]
  
  News (2023-01-13): They replicated OpenAI's _Learning to Summarize_ paper using trlX library. [[report](https://wandb.ai/carperai/summarize_RLHF/reports/Implementing-RLHF-Learning-to-Summarize-with-trlX--VmlldzozMzAwODM2)]
  
- [lucidrains/PaLM-rlhf-pytorch](https://github.com/lucidrains/PaLM-rlhf-pytorch) - (WIP) Implementation of RLHF on top of the PaLM architecture. Basically ChatGPT but with PaLM. The developer plan to add retrieval functionality too, à la RETRO. [[Tweet](https://twitter.com/omarsar0/status/1608143718460055552)] <!-- On 2022-12-29, "First open source ChatGPT has arrived". This is unncessary hype. The released code is just the model, no weights, no datasets used to trained the model, no inference model for deployment, no conversational UI/Web. A lot of things are not ready. This is far from calling it the "first" open source ChatGPT. People are getting ahead of themselves. -->

    2023: Something funny in their [FAQ](https://github.com/lucidrains/PaLM-rlhf-pytorch#faq):
    > There is no trained model. This is just the ship and overall map. We still need millions of dollars of compute + data to sail to the correct point in high dimensional parameter space. Even then, you need professional sailors (like Robin Rombach of Stable Diffusion fame) to actually guide the ship through turbulent times to that point.
    
    News (2022-12-31): [There's now an open source alternative to ChatGPT, but good luck running it](https://techcrunch.com/2022/12/30/theres-now-an-open-source-alternative-to-chatgpt-but-good-luck-running-it/) - My comments: No it hasn't. This is NOT an actual trained model (no weights) you can use. This is just code for training a ChatGPT-like model. Furthermore, the training data (enwik8) is small.

    CarperAI's large scale RLHF-aligned model (TRLX) train with LAION's data is coming out early next year. (Source: [Tweet](https://twitter.com/carperai/status/1608253659628068864?s=20))

- [allenai/RL4LMs](https://github.com/allenai/RL4LMs) - RL for language models (RL4LMs) by Allen AI. It's a modular RL library to fine-tune language models to human preferences.
- [GPT-JT](https://www.together.xyz/blog/releasing-v1-of-gpt-jt-powered-by-open-source-ai) by Together Research Computer is an example that distributes model training over geo-distributed of diverse computers (and GPUs). GPT-JT (6B) is a variant forked off EleutherAI's GPT-J, and performs exceptionally well on text classification and other tasks. On classification benchmarks such as RAFT, it comes close to state-of-the-art models that are much larger (e.g., InstructGPT davinci v2)! [[Paper: Decentralized Training of Foundation Models in Heterogeneous Environments (2022)](https://arxiv.org/abs/2206.01288)]
- LEAM (Large European AI Models) - The EU planning to fund the development of a large-scale ChatGPT-like model. [[website](https://leam.ai/), [project documents (English, PDF)](https://leam.ai/wp-content/uploads/2022/04/LEAM_Teaser_EN_01.pdf), [concept paper (German, PDF)](https://leam.ai/wp-content/uploads/2022/06/LEAM-Konzeptpapier-V1.2-1.pdf)]
- [/r/AiCrowdFund](https://old.reddit.com/r/AiCrowdFund/comments/10a2g6v/lets_create_a_place_where_people_can_find_a_way/) - A place just started (2023) where people can find a way to crowd fund (with GPUs) a large AI. I'm not sure whether they've seen [Petals](https://petals.ml/) where you can run LLMs at home, BitTorrent‑style (federated learning?). It seems to be headed in that direction.
- [Open source solution replicates ChatGPT training process](https://www.hpc-ai.tech/blog/colossal-ai-chatgpt) - They presents an open-source low-cost ChatGPT equivalent implementation process, including:
    - A mini demo training process for users to play around, which requires only 1.62GB of GPU memory and would possibly be achieved on a single consumer-grade GPU, with up to 10.3x growth in model capacity on one GPU.
    - An open-source complete PyTorch-based ChatGPT equivalent implementation process.
    - Compared to the original PyTorch, single-machine training process can be 7.73 times faster and single-GPU inference can be 1.42 times faster.
    - GitHub Repo: https://github.com/hpcaitech/ColossalAI

    I got the impression that the point of the article was to plug their [Colossal-AI](https://colossalai.org/) framework and product, a collection of parallel components, tools, and hardwares for large models. Frankly, their numbers do look suspicious to me, unless I've missed something.
    What makes ChatGPT interesting (over GPT-3) is the RLHF process. They do claim to replicate RLHF process completely. But, the article touch lightly about their RLHF implementation. They train RLHF using a small [awesome-chatgpt-prompts](https://github.com/f/awesome-chatgpt-prompts) as example dataset. Their RLHF implementation details are hidden here: https://github.com/hpcaitech/ColossalAI/blob/main/applications/ChatGPT. Lack of demo doesn't inspire too much confidence though.
- [FlexGen](https://github.com/Ying1123/FlexGen) - Running LLMs like OPT-175B/GPT-3 on a single GPU (e.g., a 16GB T4 or a 24GB RTX3090 gaming card). Key features: 1) up to 100x faster than other offloading systems. **2) Compress both the parameters and attention cache of models down to 4 bits with negligible accuracy loss.** 3) Distributed pipeline parallelism. They also provide a Python script and instructions that you can [run a chatbot with OPT models](https://github.com/Ying1123/FlexGen#run-chatbot-with-opt-models-on-a-single-gpu). This should solve the challenges of high computational and memory requirements of LLM inference. The chatbot they build with FlexGen and OPT models is not instruction-tuned (RLHF). So this chatbot is not ChatGPT-like though. [[High-throughput Generative Inference of LLMs with a Single GPU (paper)](https://arxiv.org/abs/2303.06865), Stanford et al., 2023]
    - Runtime breakdown from their paper:
        - Faster than DeepSpeed offloading (Table 2. Generation throughput on 1 GPU = 1.12 token/s (using 4-bit compression))
    - FlexGen achieves super-linear scaling on decoding throughput (which only counts decoding time costs assuming the prefill is done). This means if we generate more tokens, pipeline parallelism will show its benefits as decoding time will dominate.
    
    Reviews (from Tweets):
    - [How does it fair?](https://twitter.com/main_horse/status/1627862771609239552)
    - [I have been successful in running OPT-66B](https://twitter.com/abacaj/status/1628252688562388995?s=20)
- [ChatLLaMA](https://github.com/nebuly-ai/nebullvm/tree/main/apps/accelerate/chatllama) by NebulyAI - LLaMA-based ChatGPT-style **training process** implementation. The code represents the algorithmic implementation for RLHF training process that leverages [LLaMA](https://github.com/facebookresearch/llama/blob/main/MODEL_CARD.md)-based architectures and **does not contain the model weights**. This is NOT a ChatGPT-like product. Their RLHF implementation (actor critic trainer, actor-reward model) was inspired by [lucidrains's PaLM-rlhf-pytorch](https://github.com/lucidrains/PaLM-rlhf-pytorch) implementation. You can also generate your own prompt dataset using LangChain's agents and prompt templates. (_They have removed their misleading ["15x faster training than ChatGPT" claim](https://github.com/nebuly-ai/nebullvm/commit/6c6c24f6e6317fb5214afadd28523e198549f75e). We don't know how fast ChatGPT trained. Many people debate the performance of that repo (based on what?). Another evidence of people talking about things they don't understand about in deep learning. We should stay grounded._)
- [Fine-tuning 20B LLMs with RLHF on a 24GB consumer GPU](https://huggingface.co/blog/trl-peft) by HuggingFace - It is now possible using the integration of TRL with PEFT. The blog post explains how they achieve this step by step. The base model is gpt-neox (I was hoping the show fine-tuning LLaMA. I think they can't because of LLaMA licensing restrictions.)
- [OpenChatKit by Together Compute](https://www.together.xyz/blog/openchatkit) - Build your own ChatGPT. A powerful, open-source base to create chatbots for various applications. [Try](https://huggingface.co/spaces/togethercomputer/OpenChatKit). Much more than a model release. They are releasing a set of tools and processes for ongoing improvement. OpenChatKit includes 4 key components:
    - An instruction-tuned LLM, fine-tuned for chat from EleutherAI's GPT-NeoX-20B with over 43M instructions on compute available under Apache-2.0 license on HuggingFace.
    - A set of customization recipes to fine-tune the model to achieve high accuracy on your tasks documented and available as open-source on [GitHub](https://github.com/togethercomputer/OpenChatKit), along with code to recreate our model results.
    - An extensible retrieval system enabling you to augment bot responses with information from a document repository, API, or other live-updating information source at inference time, with open-source examples for using Wikipedia or a web search API.
    - A moderation model, fine-tuned from GPT-JT-6B, designed to filter which questions the bot responds to, also available on HuggingFace.
    - They collaborated with the tremendous communities at LAION and friends to create the Open Instruction Generalist (OIG) 43M dataset used for these models.
- [Alpaca: A Strong Open-Source Instruction-Following Model](https://crfm.stanford.edu/2023/03/13/alpaca.html) by Stanford - Alpaca is a fine-tuned version of LLaMA that can respond to instructions like ChatGPT. Simon Willison wrote about [_Alpaca, and the acceleration of on-device large language model development_](https://simonwillison.net/2023/Mar/13/alpaca/). The team at Stanford just released the [Alpaca training code](https://github.com/tatsu-lab/stanford_alpaca#fine-tuning) for fine-tuning LLaMA with [Hugging Face's transformers library](https://huggingface.co/docs/transformers/main/en/model_doc/llama). ~Also, the [PR implementing LLaMA models](https://github.com/huggingface/transformers/pull/21955) support in Hugging Face was approved yesterday.~
  - [Alpaca.cpp](https://github.com/antimatter15/alpaca.cpp) - Locally run an instruction-tuned chat-style LLM. This combines the LLaMA foundation model (llama.cpp) with an [open reproduction (Alpaca-LoRA)](https://github.com/cedrickchee/alpaca-lora) of [Stanford Alpaca](https://github.com/tatsu-lab/stanford_alpaca), a fine-tuning of the base model to obey instructions (akin to the [RLHF](https://huggingface.co/blog/rlhf) used to train ChatGPT).
  - [Alpaca Native](https://huggingface.co/chavinlo/alpaca-native) model weights - The model was fine-tuned using the original repository: https://github.com/tatsu-lab/stanford_alpaca (no LoRA has been used). [HuggingFace Transformers inference (code and quick start guide)](https://gist.github.com/cedrickchee/3be95c8ab9f38132382737783bd5d55e).
  - [Train and run Stanford Alpaca on your own machine](https://replicate.com/blog/replicate-alpaca) - The Replicate team have repeated the training process and published a tutorial about how they did it. It cost less than $100.
  - [Alpaca-LoRA-Serve](https://github.com/deep-diver/Alpaca-LoRA-Serve) - Alpaca-LoRA as a chatbot service. The easiest way to run this project is to use Colab. With the standard GPU instance(T4), you can run 7B and 13B models. With the premium GPU instance (A100 40GB), you can even run 30B model. [[Alpaca-LoRA 30B on A6000 playground](https://notebookse.jarvislabs.ai/BuOu_VbEuUHb09VEVHhfnFq4-PMhBRVCcfHBRCOrq7c4O9GI4dIGoidvNf76UsRL/)]
  - [ChatLLaMA](https://github.com/basetenlabs/alpaca-7b-truss) by Baseten - A ChatGPT style chatbot for Alpaca-7B, a fine-tuned variant of Llama-7B. [[Demo (web)](https://chatllama.baseten.co/)]
  - [Cleaned Alpaca Dataset](https://github.com/gururise/AlpacaDataCleaned) - Alpaca dataset from Stanford, cleaned and curated. [[Web demo of Alpaca-LLaMA 13B model finetuned on this dataset](https://lama.nbnl.uk/)]
  - [Serge - LLaMa made easy](https://github.com/nsarrazin/serge) - A web interface for chatting with Alpaca through llama.cpp. Fully dockerized, with an easy to use API.
  - [Code Alpaca](https://github.com/sahil280114/codealpaca) - An instruction-following LLaMA Mmdel trained on code generation instructions.
- [A list of open alternatives to ChatGPT](https://github.com/nichtdax/awesome-totally-open-chatgpt), group by model and tags (B: bare, M: mildly bare, F: full, C: complicated).
- [Hello Dolly: Democratizing the magic of ChatGPT with open models](https://www.databricks.com/blog/2023/03/24/hello-dolly-democratizing-magic-chatgpt-open-models.html) [[Code](https://github.com/databrickslabs/dolly): fine-tuning GPT-J 6B model on the Alpaca dataset] - My thoughts: LLMs could possibly be the first technology that rapidly transforms from a groundbreaking innovation to a widely adopted standard. Within two years, it is anticipated to be an integrated feature in all applications and tools, rather than a distinguishing factor.

See [cedrickchee/awesome-transformer-nlp](https://github.com/cedrickchee/awesome-transformer-nlp) for large language models research.

## Browser Extensions

Use ChatGPT anywhere.

- [Chrome extension to access ChatGPT as a popup on any page](https://github.com/kazuki-sf/ChatGPT_Extension)
- [ChatGPT for Google](https://github.com/wong2/chat-gpt-google-extension) - Chrome/Edge/Firefox extension to display ChatGPT response alongside Google Search results.
- [ChatGPT Everywhere](https://github.com/gragland/chatgpt-everywhere) - Chrome extension that adds ChatGPT to every text box on the internet. ([demo](https://twitter.com/gabe_ragland/status/1599466486422470656))
- [Chrome extension](https://github.com/kazuki-sf/ChatGPT_Extension) - A really simple Chrome Extension (manifest v3) that you can access OpenAI's ChatGPT from anywhere on the web.
- [summarize.site](https://github.com/clmnin/summarize.site) - Chrome extension to summarize blogs and articles using ChatGPT.
- [WebChatGPT](https://github.com/qunash/chatgpt-advanced) - ChatGPT with Internet access. A browser extension (Chrome and Firefos) that augments your ChatGPT prompts with relevant search results from the Web. (Remember, ChatGPT cannot access the Web and has limited knowledge of the world after 2021)
- [XP1](https://xp1.dust.tt/) - GPT-based Assistant with access to your Tabs.
- [ExtractGPT](https://airtable.com/shruPamX8OWa5tqdp) - A browser extension for scraping data from structured & unstructured pages.
- [ChatGPT for Twitter](https://chrome.google.com/webstore/detail/chatgpt-for-twitter/ihabhmefjiipbmppmjoleclimdeompdc) - Chrome extension to generate tweets/replies to tweets in different moods and by optionally giving instructions.

## Access ChatGPT From Other Platforms

## Bots

- [WhatsApp bot](https://github.com/danielgross/whatsapp-gpt)
- [Go Telegram bot](https://github.com/m1guelpf/chatgpt-telegram) - Run your own GPTChat Telegram bot, with a single command.
- [Twitter bot](https://github.com/transitive-bullshit/chatgpt-twitter-bot) powered by ChatGPT.
- [ChatGPT ProBot](https://github.com/oceanlvr/ChatGPTBot) - A GitHub App. Type `/chatgpt` to chat with ChatGPTBot.
- [Discord bot](https://github.com/Zero6992/chatGPT-discord-bot) - Integrate your own Discord bot using chatGPT.

## Tools

### Command-Line Interface (CLI)

- [chatgpt-conversation](https://github.com/platelminto/chatgpt-conversation) - Voice-based chatGPT.
- [Shell GPT](https://github.com/TheR1D/shell_gpt) - A CLI productivity tool powered by OpenAI's text-davinci-003 model, will help you accomplish your tasks faster and more efficiently.
- [AI Files](https://github.com/jjuliano/aifiles) - A CLI that helps you organize and manage your files using GPT-3: auto add tag to the file, auto create directories based on the file content, etc. Be cautious when sharing personal info though.
- [Chatblade](https://github.com/npiv/chatblade) - A CLI Swiss Army Knife for ChatGPT.
- [:candy:ChatGPT (and GPT4) Wrapper:candy:](https://github.com/mmabrouk/chatgpt-wrapper) - An open-source unofficial **Power CLI**, Python API and Flask API that lets you interact programmatically with ChatGPT/GPT4.

### Editors and IDEs

- [VSCode extension](https://github.com/mpociot/chatgpt-vscode) ([demo](https://twitter.com/marcelpociot/status/1599180144551526400))
- [vscode-chatgpt](https://github.com/gencay/vscode-chatgpt) - An unofficial VS Code - ChatGPT extension.
- [ETC (ExplainThisCode)](https://github.com/evyatar9/ExplainThisCode) - A VSCode extension that uses the ChatGPT API to provide explanations for selected code.
- [Adrenaline](https://github.com/shobrook/adrenaline) - Minimalist IDE that automatically fixes your code when it throws an error, powered by ChatGPT. [[article](https://devpost.com/software/adrenaline-ide)]

### Others

- [RayCast Extension (unofficial)](https://github.com/abielzulio/chatgpt-raycast) - Run ChatGPT through Raycast extension.
- [Google Docs](https://github.com/cesarhuret/docGPT) - ChatGPT directly within Google Docs as an Editor Add-on.
- [Autodoc](https://github.com/context-labs/autodoc) - Toolkit for auto-generating codebase documentation using LLMs.

## Applications

Web applications.

- [ShareGPT](https://sharegpt.com/) - A web app for sharing your wildest ChatGPT conversations with one click. ([demo](https://twitter.com/steventey/status/1599816553490366464))
- [LearnGPT](https://www.learngpt.com/) - Share ChatGPT examples. See the best voted examples. Their goal is to create a resource for anyone who wants to learn more about ChatGPT.
- [ShowGPT](https://showgpt.co/) - Show your ChatGPT prompts.
- [The search engine for developers](https://beta.sayhello.so/), powered by large, proprietary AI language models.
- [GPTDuck](https://www.gptduck.com/) – Ask questions about any GitHub repo.
- [LLM Garden](https://github.com/ianb/llm-garden) - A number of experiments using GPT-3, delivered in a web app.
- [Epic Music Quiz](https://epicmusicquiz.com) - A free webapp for creating your own custom Music Video Quiz using youtube videos that can be played solo or multiplayer with friends. Optional AI generation of quiz questions.
- [Gerev](https://github.com/GerevAI/gerev) - AI-powered search engine for your organization.

Desktop applications.

- [ChatGPT desktop app](https://github.com/sonnylazuardi/chatgpt-desktop) - Windows/MacOS desktop menubar app using Tauri and Rust.
- [chatgpt-mac](https://github.com/vincelwt/chatgpt-mac): MacOS menubar app.
- [ChatGPT Desktop Application](https://github.com/lencx/ChatGPT) for Mac, Windows and Linux - Build using Rust and Tauri.

## Self-hosted Open-Source Models and Tools

Open-source models are faster, more customizable, more private, and pound-for-pound more capable. [^9]

Self-hosted LLMs are the way forward for enterprise. Run Large Language Models locally on your devices.

- [imartinez/privateGPT](https://github.com/imartinez/privateGPT) - Ask questions to your documents without an Internet connection, using the power of LLMs. 100% private, no data leaves your execution environment at any point. You can ingest documents and ask questions.
- [StableLM](https://github.com/stability-AI/stableLM/) - Stability AI Language Models. Developers can **freely inspect, use, and adapt StableLM base models for commercial or research purposes**, subject to the terms of the CC BY-SA-4.0 license.
- [openlm-research/open_llama](https://github.com/openlm-research/open_llama) - OpenLLaMA, a permissively licensed open source reproduction of Meta AI's LLaMA 7B trained on the RedPajama dataset.
- [mlc-ai/MLC-LLM](https://github.com/mlc-ai/mlc-llm) - Enable everyone to develop, optimize and deploy LLaMA, GPT (AI models) natively on consumer-grade GPUs and phones.
- [How to run LLaMA 13B with a 6GB graphics card](https://gist.github.com/rain-1/8cc12b4b334052a21af8029aa9c4fafc)
- [huggingface/text-generation-inference](https://github.com/huggingface/text-generation-inference) (TGI) - A Rust, Python and gRPC server for text generation inference. Used in production at HuggingFace to power LLMs api-inference widgets. Optimized to run Llama 2 model. If you have a decent GPU and Linux computer, you can run Llama 2 locally without much fuss.
- [vllm-project/vllm](https://github.com/vllm-project/vllm) - A high-throughput and memory-efficient inference and serving engine for LLMs. vLLM has up to 3.5x more throughput than HuggingFace Text Generation Inference (TGI). It uses **PagedAttention**, their new attention algorithm that effectively manages attention keys and values.
- [OpenNMT/CTranslate2](https://github.com/OpenNMT/CTranslate2) - Fast inference engine for Transformer models. It's a C++ and Python library. (Underrated: faster than TGI and vllm (Jul 2023). Bonus: the easiest to use)
- [jmorganca/Ollama](https://github.com/jmorganca/ollama) - A macOS app for Apple Silicon that enables you to get up and run LLMs, locally. Windows & Linux support coming soon.
- [A guide to running Llama 2 locally](https://replicate.com/blog/run-llama-locally) by Replicate (2023) - They cover three open-source tools you can use to run Llama 2 on your own devices: Llama.cpp (Mac/Windows/Linux), Ollama (Mac) & MLC LLM (iOS/Android).
- [turboderp/exllama](https://github.com/turboderp/exllama) - A more memory-efficient rewrite of the HF transformers implementation of Llama for use with quantized weights. Can run a Llama2-70B with 16K context length, but it's still early days. This is saving gigabytes off the alternatives like llama.cpp.
- [nomic-ai/GPT4All](https://github.com/nomic-ai/gpt4all) - An ecosystem to train and deploy powerful and customized large language models that run locally on consumer grade CPUs. A GPT4All model is a 3GB - 8GB file that you can download and plug into the GPT4All. (tips: want to run Llama 2 easily? Download [GGML version of Llama 2 (from "TheBloke")](https://huggingface.co/TheBloke), copy to the models directory in the GPT4All software, launch GPT4All and that's it)
- [LocalAI](https://simonwillison.net/2023/May/14/localai/) and [abetlen/llama-cpp-python](https://github.com/abetlen/llama-cpp-python) combo - Self-hosted, community-driven, local OpenAI-compatible API. Drop-in replacement for OpenAI running LLMs on consumer-grade hardware. LocalAI is an API to run ggml compatible models: llama, gpt4all, rwkv, whisper, vicuna, koala, gpt4all-j, cerebras, falcon, dolly, starcoder, and many other.
- [Optimizing LLM latency](https://hamel.dev/notes/llm/03_inference.html) (2023) - An exploration of inference tools for open source LLMs focused on latency.
- [Code Llama, a state-of-the-art large language model for coding](https://ai.meta.com/blog/code-llama-large-language-model-coding/) (2023) - Code Llama is a code-specialized version of Llama 2 that was created by further training Llama 2 on its code-specific datasets. It can generate code, and natural language about code, from both code and natural language prompts. It can also be used for code completion and debugging. It supports many of the most popular languages being used today. They are releasing 3 sizes of model with 7B, 13B, and 34B parameters. All models are trained on sequences of 16k tokens and show improvements on inputs with up to 100k tokens. Additionally, they have further fine-tuned two additional variations of Code Llama: Code Llama - Python and Code Llama - Instruct. Their benchmark testing showed that Code Llama performed better than open-source, code-specific LLMs. [[Model weights (34B fp16) from TheBloke](https://huggingface.co/TheBloke/CodeLlama-34B-fp16), [Model codes](https://github.com/facebookresearch/codellama)]

**2023 trends**

llama2.c ➡️ micro-LLMs (<10B params?) - hackable and efficient, but not at the cost of simplicity, readability, portability.

llama.cpp ➡️ inference at the edge, deployment efficiency.

Growing interest in local, private micro-LLMs and deploying them in laptops, phones, MCUs, etc.

## Infrastructure

- [Cost of ChatGPT](https://twitter.com/tomgoldsteincs/status/1600196981955100694) - Average cost is probably single-digits cents per chat.

## Newsletters

- [Newsletter of notes focusing on text generation, mostly with GPT-3](https://github.com/sw-yx/ai-notes/blob/main/TEXT.md)
- [Ben's Bites - the AI newsletter](https://www.bensbites.co/p/looking-back-llms) - Looking back on LLMs.

## AI Safety and Ethics

AI alignment and AI interpretability.

- [Use of ChatGPT generated text for posts on Stack Overflow is temporarily banned](http://archive.today/bMruL)
- [Generative AI: autocomplete for everything](https://noahpinion.substack.com/p/generative-ai-autocomplete-for-everything) — A long-form piece on the future of human work in the age of generative AI. tl;dr: AI doesn't take over jobs, it takes over tasks. [Comparative advantage](https://en.wikipedia.org/wiki/Comparative_advantage) is why humans will still have jobs.

### AGI and Humanity

- [AI for the Next Era](https://greylock.com/greymatter/sam-altman-ai-for-the-next-era/) - OpenAI's Sam Altman on the New Frontiers of AI.
  
  My comments: Reading this after the ChatGPT launch, mostly all the things that Sam is referring to in the interview contains reminiscences about predictions on AI and development from Ray Kurzweil.
- [Google won't launch ChatGPT rival because of 'reputational risk'](https://www.theverge.com/2022/12/14/23508756/google-vs-chatgpt-ai-replace-search-reputational-risk)
- [AI Alignment Forum](https://www.alignmentforum.org/) is a single online hub for researchers to discuss all ideas related to ensuring that transformatively powerful AIs are aligned with human values. Discussion ranges from technical models of agency to the strategic landscape, and everything in between.
- [The Expanding Dark Forest and Generative AI](https://maggieappleton.com/ai-dark-forest) by Maggie Appleton - Proving you're a human on a web flooded with generative AI content.
- [How should AI systems behave, and who should decide?](https://openai.com/blog/how-should-ai-systems-behave/) by OpenAI.
- [Planning for AGI and beyond](https://openai.com/blog/planning-for-agi-and-beyond/) by OpenAI (2023) - <!-- AGI roadmap --> TL;DR:
    - Short term:
        - They are becoming increasingly cautious with the creation and deployment of their models.
        - They will need to develop new alignment techniques as models become more powerful.
    - Long term:
        - The first AGI will be just a point along the continuum of intelligence.
        - AI that accelerates science is a special case because it's possible AGI capable enough to accelerate its own progress and therefore expand the capability exponentially.
    
    If you care about how AGI will impact us all, you should read this.
- [Software Complexity Is Why AI Won't Replace Software Engineers](https://softwarecomplexity.com/why-ai-wont-replace-software-engineers)
- [Copyright Registration Guidance: Works Containing Material Generated by AI](https://www.federalregister.gov/documents/2023/03/16/2023-05321/copyright-registration-guidance-works-containing-material-generated-by-artificial-intelligence)
- [GPT-4 and the Uncharted Territories of Language](https://www.fast.ai/posts/2023-03-20-wittgenstein.html) by fast.ai - Language is a source of limitation and liberation. GPT-4 pushes this idea to the extreme by giving us access to unlimited language.
- [OK, it's time to freak out about AI](https://nonzero.substack.com/p/ok-its-time-to-freak-out-about-ai)
- [Post-GPT Computing](https://grady.io/post-gpt-computing/)
    > I couldn’t keep working. I had to leave the office and go for a walk. Is software engineering basically a solved problem now? Did OpenAI just make the last application? This all sounds hyperbolic and melodramatic when I write it out, but I’m not the only one who felt something like this. Twitter showed me I wasn't alone: "Existential crisis. Did OpenAI just finish software? What's there left to do but clean-up and sweep?"
- [Is Avoiding Extinction from AI Really an Urgent Priority?](https://www.aisnakeoil.com/p/is-avoiding-extinction-from-ai-really) by Seth Lazar, Jeremy Howard, and Arvind Narayanan - The history of technology suggests that the greatest risks come not from the tech, but from the people who control it.
- [AI Safety and the Age of Dislightenment](https://www.fast.ai/posts/2023-11-07-dislightenment.html) by Jeremy Howard, fast.ai - Model licensing & surveillance will likely be counterproductive by concentrating power in unsustainable ways.
- [The Leverage of LLMs for Individuals](https://mazzzystar.github.io/2023/05/10/LLM-for-individual/)
  > it gives me the courage to dream and attempt things beyond my current abilities.

### Tweets

> ChatGPT is incredibly limited, but good enough at some things to create a misleading impression of greatness.
>
> It's a mistake to be relying on it for anything important right now. It's a preview of progress; we have lots of work to do on robustness and truthfulness.
>
> fun creative inspiration; great! reliance for factual queries; not such a good idea. — [Sam Altman, OpenAI](https://twitter.com/sama/status/1601731295792414720)

[News covering to that Tweet](https://venturebeat.com/ai/openai-ceo-admits-chatgpt-risks-what-now-the-ai-beat/).

John Carmack answering questions about Computer Science (Software Engineering) career from a concerned student:
> Build full "product skills" and use the best tools for the job, which today might be hand coding, but later might be AI guiding you, you will probably be fine — [Tweet](https://twitter.com/ID_AA_Carmack/status/1637087219591659520)

> I’m hearing chatter of PhD students not knowing what to work on.
>
> My take: as LLMs are deployed IRL, the importance of studying how to use them will increase.
>
> Some good directions IMO (no training): prompting, evals, LM interfaces, safety, understanding LMs, emergence
> 
> — [Jason Wei](https://twitter.com/_jasonwei/status/1636436324139028481)

> GPT-4 has been out for 72 hours, and it could change the world! Here are some amazing and important things it **can't** do (yet):
>
> 1. Solve global warming, 2. Cure cancer or infectious diseases, 3. Alleviate the mental health crisis, 4. Close the information and education gap, 5. End war and strife, and many more.
>
> — [Graham Neubig](https://twitter.com/gneubig/status/1636712054123024384)

> Stop saying: AI will replace humans.
>
> Start saying: humans who know how to use AI at work will replace those who don’t.
>
> — [Jim Fan](https://twitter.com/DrJimFan/status/1636021710062505987)

### Applications and Tools

- GPT-2 Output Detector [[code](https://github.com/openai/gpt-2-output-dataset/tree/master/detector)] [[demo](https://huggingface.co/openai-detector/)]
  > The @HuggingFace GPT detector works very well on ChatGPT-created text. I ran 5 student essays and 5 ChatGPT essays for the same prompt through it, and it was correct every time with >99.9% confidence. — [@cfiesler](https://twitter.com/cfiesler/status/1601642370797563904)
- [OpenAI's attempts to watermark AI text hit limits](https://archive.vn/20221212144831/https://techcrunch.com/2022/12/10/openais-attempts-to-watermark-ai-text-hit-limits/) - Watermarking may allow for detection of AI text. This post discusses some of the limitations but suggests that it's worth pursuing. Prof. Scott Aaronson "expressed the belief that, if OpenAI can demonstrate that watermarking works and doesn't impact the quality of the generated text, it has the potential to become an industry standard.". OpenAI engineer Hendrik Kirchner built a working prototype.
    - Related: [Scott Aaronson talks AI Safety on Nov 2022 (video)](https://youtu.be/fc-cHk9yFpg?t=3194) - GPT outputs will be statistically watermarked with a secret signal that you can use to proof the outputs came from GPT, making it much harder to take a GPT output and pass it off as if it came from a human. How it works, it selects the tokens pseudorandomly using cryptographic PRNG that secretly biases a certain score which you can also compute if you know the key for this PRNG. Scott doesn’t give too many details about how it works and he admits this can be defeated with enough effort, for example by using one AI to paraphrase another. But if you just insert or delete a few words or rearrange the order of some sentences, the signal will still be there. So it's robust against those sorts of interventions. Many suspect its possible to bypass using a clever decoding strategy. Scott is also researching: [Planting Undetectable Backdoors in Machine Learning Models (2022 paper)](https://arxiv.org/abs/2204.06974)". People are questioning whether they are missing something, or are all these attempts at recognising LLM outputs obviously destined to fail?
    I think they've clearly thought about this but still think this is useful (from transcript of the lecture: https://scottaaronson.blog/?p=6823).
- [GPTZero](https://gptzero.me/) - An app that can quickly and efficiently detect whether an essay is ChatGPT or human written. [[Case study (exploring false positives)](https://gonzoknows.com/posts/GPTZero-Case-Study/), [Tweet](https://twitter.com/edward_the6/status/1610067688449007618)] <!-- retired version of the GPTZero beta: https://etedward-gptzero-main-zqgfwb.streamlit.app/ -->
- [A Watermark for Large Language Models (paper)](https://arxiv.org/abs/2301.10226) by University of Maryland (2023). It operates by maintaining a "whitelist" and "blacklist" of high-log probability words. [[Tweet (explainer thread by one of the authors)](https://twitter.com/tomgoldsteincs/status/1618287665006403585), [demo](https://huggingface.co/spaces/tomg-group-umd/lm-watermarking), [code](https://github.com/jwkirchenbauer/lm-watermarking)]
    - They test the watermark using a LLM from the Open Pretrained Transformer (OPT) family, and discuss robustness and security.
- DetectGPT - Zero-Shot machine-generated text detection using probability curvature. [[paper (2023), code, demo, and Twitter thread](https://ericmitchell.ai/detectgpt/)]
    - Method: language model output will minimize log-probability in token space. Because of this, to detect if text is generated by a language model, "perturb" the phrase slightly and measure the curvature in log-probability.
- [New AI classifier for indicating AI-written text](https://openai.com/blog/new-ai-classifier-for-indicating-ai-written-text/) by OpenAI. [[try the classifier](https://platform.openai.com/ai-text-classifier)]
    - Results: correctly flags AI-generated text 26% of the time, incorrectly flags human-generated text 9% of the time.
- [Not by AI](https://notbyai.fyi/) - Your AI-free content deserves a dadge.

### Security

- [More than you've asked for: A Comprehensive Analysis of Novel Prompt Injection Threats to Application-Integrated Large Language Models (paper)](https://arxiv.org/abs/2302.12173) by Kai Greshake et al., 2023 - Indirect prompt injection turn Bing Chat into a data pirate. By modifying a website that Bing Chat reads alongside a user, the chatbot is able to have its goals modified by that website, unbeknownst to the user. [[demo](https://greshake.github.io/), code: [greshake/llm-security](https://github.com/greshake/llm-security)]
- [Prompt injection explained, with video, slides, and a transcript](https://simonwillison.net/2023/May/2/prompt-injection-explained/) by Simon Willison (2023).

## LMOps

General technology for enabling AI capabilities with LLMs and generative AI models.

- [Structured Prompting: Scaling In-Context Learning to 1,000 Examples (paper)](https://arxiv.org/abs/2212.06713) by Microsoft Research. [[Code](https://github.com/microsoft/LMOps)]
  > GPT-3/LLMs' Achilles heel is short context length - how many "in-context" examples they can consume to learn a new task.
  > Enter "Structured Prompting": scale your examples from dozens => 1,000+
  > — [@mathemagic1an](https://twitter.com/mathemagic1an/status/1604802787296284674)

## Emerging Software Development and Business Paradigm

[Software 2.0](https://karpathy.medium.com/software-2-0-a64152b37c35)? [Software 3.0?](https://twitter.com/karpathy/status/1273788774422441984) Generative AI?

(_Reflections on how best to think of the current state of software engineering, AI products, and pitfalls people tend to make with new tech._)

It's very rare to see a new building block emerge in computing. Large AI models like ChatGPT represent a fundamentally new building block. By integrating large models into software, developers can expose functionality that wouldn't be possible otherwise. <!-- rephrase: LLMs are emerging as a transformative tech, enabling developers to build apps that they previously could not. -->
This may be one of the biggest changes in software we've ever seen — a new type of software.

Using LLMs in isolation is often not enough to create a powerful app — the real power comes when you are able to combine them with other sources of knowledge or computation.

**Is Software 3.0 silly? worth the hype?**

I don't know. I think of "Software 3.0" as:
- a metaphor for the new trends in software development and large AI models
- a different paradigm; companies leverage customer data to train their proprietary AI models and optimize product experiences and customers receive added value from the product.

You say investment into generative AI companies is way too exuberant right now? <!-- someone estimated there are less than NNN people in the world right now who know how to effectively train billion+ parameter models with startup resources. --> <!-- someone predict: that will be a myth of the past and within the year, the knowledge will become accessible. -->
[What's the big deal with Generative AI? Is it the future or the present?](https://txt.cohere.ai/generative-ai-future-or-present/)

> 1- Recent AI developments are awe-inspiring and promise to change the world. But when?
>
> 2- Make a distinction between impressive 🍒 cherry-picked demos, and reliable use cases that are ready for the marketplace
>
> 3- Think of models as components of intelligent systems, not minds
>
> 4- Generative AI alone is only the tip of the iceberg

The current climate in AI is making some uncomfortable. Everyone is expecting as a sure thing "civilization-altering" impact (& 100x returns on investment) in the next 2-3 years. [^6]

### The foundation for the next era of computing

What's next in computing after Moore's law? You can think about this in many ways. But, here is an analogy [^8]:

- Apple/Google :arrow_right: OpenAI
- iPhone/Samsung :arrow_right: GPT-4
- iOS/Android :arrow_right: ChatGPT
- App Store/Play Store :arrow_right: ChatGPT Plugins

Some experts say that ChatGPT is the AI's iPhone moment. [^7]

---

## Demos

Demos[^3] and examples in the form of tweets:

**Day 1, 2022**

1. [Generating detailed prompts for text-to-image models like MidJourney & Stable Diffusion](https://twitter.com/guyp/status/1598020781065527296)
2. [ChatGPT outperforming Google search](https://twitter.com/jdjkelly/status/1598021488795586561)
3. [Generating code for automated RPA, e.g. automating the click sequence for house search in Redfin](https://twitter.com/theaievangelist/status/1599579579064406017)
4. [Generating on-demand code contribution ideas for an about-to-be-fired Twitter employee](https://twitter.com/goodside/status/1599082185402642432)
5. [An app builder such as essay automatic summarization](https://twitter.com/packym/status/1598405769669771264)
6. [Personal trainer and nutritionist: Generating a weight loss plan, complete with calorie targets, meal plans, a grocery list, and a workout plan](https://twitter.com/anothercohen/status/1599531037570502656)
7. [Building a virtual machine inside ChatGPT](https://twitter.com/stspanho/status/1599367959029288960)
8. [Code debugging partner: explains and fixes bugs](https://twitter.com/amasad/status/1598042665375105024)

<details>
<summary>See more</summary>

9. [Generating programmatic astrophoto processing by detecting constellations in an image](https://twitter.com/RReverser/status/1599180092621611008)
10. [VSCode extension that allows using ChatGPT within the context of a code](https://twitter.com/marcelpociot/status/1599180144551526400)
11. [Building web AR scenes by using text commands](https://twitter.com/stspanho/status/1599367959029288960)
12. [Stringing cloud services to perform complex tasks](https://twitter.com/amasad/status/1598089698534395924)
13. [Generating legal contracts](https://twitter.com/atri_life/status/1599506327461859328)
14. [A Chrome extension that presents ChatGPT results next to Google Search](https://twitter.com/zohaibahmed/status/1599191505025261569)
15. [Solving complex coding questions - the end of LeetCode?](https://twitter.com/goodside/status/1598129631609380864)
16. [Solving complex academic assignments - the end of Chegg?](https://twitter.com/abhnvx/status/1598258353196929024)
17. [Answering unanswered Stack Overflow questions - the end of Stack Overflow?](https://twitter.com/htmleverything/status/1599443014153224193)
18. [Explaining complex regex without any context](https://twitter.com/jwblackwell/status/1598090447854792705)
19. [Generating hallucinated chat with a hallucinated person in a hallucinated chat room](https://twitter.com/gfodor/status/1599220837999345664) 
20. [Bypassing OpenAI's restrictions by disclosing ChatGPT's belief system](https://twitter.com/zoink/status/1599281052115034113)
21. [Uncovering ChatGPT's opinion of humans including a detailed destruction plan](https://twitter.com/michlbrmly/status/1599168681711656961)
22. [An insightful executive summary of ChatGPT](https://twitter.com/swyx/status/1599189032529178624)
23. [Building e-commerce websites: stitching ChatGPT & Node script to automatically generate SEO-driven blog posts using GPT 3](https://twitter.com/giladrom/status/1599617326290468864)
24. [A ChatGPT extension that generates text, tweets, stories, and more for every website](https://twitter.com/gabe_ragland/status/1599466486422470656)
25. [An extension that adds "Generate PNG" and "Export PDF" functions to ChatGPT's interface](https://twitter.com/liadyosef/status/1599484187396145153)
26. [A thread showcasing ways of helping hackers by using ChatGPT](https://twitter.com/maikroservice/status/1599525095675789312)
27. [Generating editorial pieces like sports articles](https://twitter.com/geovedi/status/1599572163799183360)
28. [Generating SEO titles to optimize sites Click Through Rate](https://twitter.com/tejas3732/status/1599094776292573184)
29. [Creating social games. E.g. guess which city is featured in a picture](https://twitter.com/xf1280/status/1599252728399921152)
30. [A tutorial on how to use ChatGPT to create a wrapper R package](https://twitter.com/IsinAltinkaya/status/1599440535529623552)
31. [ChatGPT can basically just generate AI art prompts. I asked a one-line question, and typed the answers verbatim straight into MidJourney and boom. Times are getting weird...](https://twitter.com/GuyP/status/1598020781065527296?t=5V4Pz3yUYhKngQnXc9-0Yw&s=09)
32. [A collection of wrong and failed results from ChatGPT](https://twitter.com/itstimconnors/status/1599544717943123969?t=azJqOxHvU9wfTNLoPaYGqg&s=09)
33. [Use the AWS TypeScript CDK to configure cloud infrastructure on AWS](https://twitter.com/jaredpalmer/status/1599459951415480320?t=rDn6KwMRV8wLepe_3-SK9A&s=09)
34. [Seeing people trick ChatGPT into getting around the restrictions OpenAI placed on usage is like watching an Asimov novel come to life](https://nitter.fly.dev/carnage4life/status/1598332648723976193)
35. [Never ever write a job description again](https://twitter.com/rakyll/status/1599208818529177600)
36. [ChatGPT is getting pretty close to replicating the Stack Overflow community already](https://twitter.com/KSakarisson/status/1599440565673656320)
37. [That's how I'll pick books in the future](https://twitter.com/thorstenball/status/1599320310171414528)
38. [ChatGPT is amazing but OpenAI has not come close to addressing the problem of bias. Filters appear to be bypassed with simple tricks, and superficially masked](https://twitter.com/spiantado/status/1599462375887114240)
39. [i'm the ai now](https://twitter.com/parafactual/status/1598212029479026689)
40. [All the ways to get around ChatGPT's safeguards](https://twitter.com/davisblalock/status/1602600453555961856)

**2023**

1. [Programming with ChatGPT. Some observations](http://archive.today/XLVZf)
2. [The best ways to use ChatGPT. 8 ways ChatGPT can save you thousands of hours in 2023](https://archive.ph/G3Ak3)
3. [Everyone’s using ChatGPT. Almost everyone's STUCK in beginner mode. 10 techniques to get massively ahead with AI (cut-and-paste these prompts)](https://threadreaderapp.com/thread/1610316022174683136.html)
4. [David Guetta uses ChatGPT and uberduck.ai to deepfake Eminem rap for DJ set](https://twitter.com/davidguetta/status/1621605376733872129)
5. [A thread about GPT-4, highlighting some of the interesting examples, tricks, and discussions](https://archive.is/nEXi8)
6. [All the best examples of GPT-4](https://archive.is/G79Me)
7. [A token-smuggling jailbreak for ChatGPT-4](https://threadreaderapp.com/thread/1636488551817965568.html)

</details>

## Others

Mostly found in GitHub Gist:

- https://gist.github.com/Gaelan/cf5ae4a1e9d8d64cb0b732cf3a38e04a - ChatGPT passes the 2022 AP Computer Science A free response section
- https://gist.github.com/memo/dcd0ccbfe57d1fd5f1601e4ee2149a73
  > A conversation I had with ChatGPT, inspired by a [tweet](https://twitter.com/michael_nielsen/status/1598760649039179777) from Michael Nielson.
- https://gist.github.com/kettle11/dae31bee4fc8aa401135def2aa3f4a47
  > You are Webby, a website creation assistant.
- https://gist.github.com/GlenCrawford/693800ae361e2db255ed29d7d284c5e5 - reinteractive blog post: An interview with an AI about Ruby on Rails
- https://gist.github.com/heyajulia/fc4286b125fa99fd166a50f3582f2514
  > Hi, my code has two bugs and I’m not sure how to fix them. If you can help me, I’ll send you the code.

### ChatGPT Alternatives

- [Anthropic's Claude](https://www.anthropic.com/earlyaccess) - Overall, Claude is a serious competitor to ChatGPT, with improvements in many areas. [[review by Riley Goodside et al.](https://scale.com/blog/chatgpt-vs-claude), [my short analysis](https://twitter.com/cedric_chee/status/1633764765700091904)]
  - [Claude 2](https://www.anthropic.com/index/claude-2) - A new phase of production-grade LLMs: longer context and deeper integration. Early test results inspired confidence — much closer to GPT-4 in terms of quality. The longer context does feel like it unlocks some unique capabilities. I gave it a task of summarizing two requirement spec PDF. It's quite good in cross cross referencing things in different document. It does exhibits some complex analysis strengths. I think this level of generation quality on this task is novel, unlike any of the previous LLMs.
- [Perplexity](https://www.perplexity.ai/) - A new search interface that uses OpenAI GPT 3.5 and Microsoft Bing to directly answer any question you ask.
- Bart from Google
- Sparrow from DeepMind
- YouChat
- Poe from Quora
- Bloom from BigScience
- Character AI
- Jasper Chat
- [Phind](https://phind.com/) - An "assistant" that simply tells users what the answer is. Optimized for developers and technical questions. Powered by proprietary LLMs (they use OpenAI API and their own models). It's strange that they market themself as search engine.

Lightly based on [publicly announced ChatGPT variants and competitors](https://twitter.com/goodside/status/1606611869661384706) Tweet.

#### ChatGPT Plugins

Competitors:
- [ACT-1: Transformer for Actions](https://www.adept.ai/blog/act-1) by Adept.ai, 2022 - Sort of like a "self-driving car" for your everyday digital life.
    - Some blog posts about them: [How Adept Is Building the Future of AI with Action Transformers](https://thealgorithmicbridge.substack.com/p/act-1-how-adept-is-building-the-future)

<!-- For future reference but maybe not. -->

[^1]: https://github.com/humanloop/awesome-chatgpt
[^2]: https://github.com/Kamigami55/awesome-chatgpt
[^3]: https://github.com/saharmor/awesome-chatgpt
[^5]: In a [Reddit thread "The problem with prompt engineering"](https://r.nf/r/GPT3/comments/m177n2/the_problem_with_prompt_engineering/gqdr6de/?context=3) where Gwern (author) claims to be the origin of the term [prompt programing/prompt engineering](https://gwern.net/gpt-3#prompts-as-programming). His argument is reasonable and well written.
[^6]: [François Chollet's Tweet](https://threadreaderapp.com/thread/1612142423425138688.html)
[^7]: [An interview by stratechery with NVIDIA CEO about AI's iPhone moment](https://stratechery.com/2023/an-interview-with-nvidia-ceo-jensen-huang-about-ais-iphone-moment/)
[^8]: [OpenAI just laid out the foundation for the next era of computing](https://twitter.com/mckaywrigley/status/1638972445108625408)
[^9]: [Google "We Have No Moat, And Neither Does OpenAI"](https://archive.is/5R7XJ#selection-717.2-725.122)

## License

I am providing code and resources in this repository to you under an open source license.  Because this is my personal repository, the license you receive to my code and resources is from me and not my employer.

* Code: [MIT](LICENSE) Copyright Cedric Chee
* Text content: [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](http://creativecommons.org/licenses/by-sa/4.0/)
