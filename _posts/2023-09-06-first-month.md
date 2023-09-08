---
title: "🎉 One Month in Singapore's AI Scene 🤖"
date: 2023-09-06
permalink: /posts/2023-09-06-first-month/
tags:
  - AI
  - Machine Learning
  - Data Engineering
  - Singapore
  - Learning
---

It’s been an action-packed first month in Singapore for me, settling into the new country and immersing myself in the vibrant AI community here! Here’s an overview of what I’ve been up to and my main takeaways from 24 hours of meetups and conferences on Generative AI, Machine Learning for finance, and Data Engineering.

These events were on the following topics:
1. Autonomous Agents with Large Language Models (LLMs)
2. Generative AI: Improving Patient Care with AI and LLMs
3. Data Tuesdays #1
4. World AI Show
5. dbt meetup
6. How to break into AI Careers
7. OCBC Data Engineering Revolution
8. BrightRaven.ai launch party
9. Application of ML and GenAI in Finance
10. Data Tuesday #2 - Quantum Computing
11. Why Vector Search is Important

![Data Tuesday #1](/images/blog/2023-08_data-tuesday-1.jpeg)
*Members at the first ever Data Tuesday Singapore. Photo by [Ville](https://www.meetup.com/data-ai-singapore/photos/33805877/514928034/)*

### 27th July - 🤖 Autonomous Agents with Large Language Models (LLMs) at Google Developers Space
At [Machine Learning Singapore's](https://www.meetup.com/machine-learning-singapore/) event, [Sam Witteveen](https://www.linkedin.com/in/samwitteveen/) from [RedDragon.ai’s](http://reddragonai.com/) presented:
* how to build LLM agents that can make their own decisions and act upon them
* how these agents have components which differ from the typical LLM stack, such as planning / task orchestration, self-reflection, and data ingestion with browser interaction tools such as [MultiOn](https://multion.ai/) and [browserless.io](https://www.browserless.io/)
* his own example of a business email agent that can send 1000s of cold emails and generate replies that push the recipient towards a desired outcome
* existing agents such as [Auto-GPT](https://github.com/Significant-Gravitas/Auto-GPT), [BabyAGI](https://github.com/yoheinakajima/babyagi), and [GPT Engineer](https://github.com/AntonOsika/gpt-engineer)
* how we will likely see a future of multi-agents - where several agents are working together and there being a universal language between them, i.e. specific APIs developed for bots/agents rather than broad APIs designed for developers

Sam’s [YouTube channel](https://www.youtube.com/@samwitteveenai) is a goldmine for anyone keen on the latest GenAI developments. 

[Martin Andrews](https://www.linkedin.com/in/martinandrews/), fellow co-founder, shared:
*  how you can incrementally improve LLM-powered agents though:
    * fine-tuning - using methods such as [Parameter Efficient Fine-Tuning (PEFT)](https://huggingface.co/blog/peft), [Low-Rank Adaption of LLMs (LoRA)](https://huggingface.co/docs/diffusers/main/en/training/lora), and Mixture of LoRAs (MoLoRA)
    * self-critiquing - self-refinement, self-debug, and self-reflection
    * tool use - such as using a search tool for [ReAct](https://react-lm.github.io/)
* however, the real improvements in Open-Ended tasks / systems will come from innovation and not incrementalism. Martin provided the fun thought experiment of reaching the moon - you wouldn't focus on a ladder, a red herring, and incrementally building it higher, instead you would need to explore unknown areas and innovate (**novelty search**), which in hindsight may lead to the goal.

Check out Martin's insightful presentation at [https://redcatlabs.com/2023-07-27_MLSG_OpenEnded/#/openended-talk](https://redcatlabs.com/2023-07-27_MLSG_OpenEnded/#/openended-talk).

![Sam presenting Autonomous Agents with LLM](/images/blog/2023-08_MLSG.jpeg)
*Sam presenting Autonomous Agents with LLMs*

### 28th July - 🏥 Generative AI: Improving Patient Care with AI and LLMs
[H2O.ai](https://h2o.ai/) hosted a session on **Real-life use-cases of Generative AI: Improving Patient Care with AI and LLMs**. [Jong Hang](https://www.linkedin.com/in/jong-hang-siong-a7b31415/) demonstrated 4 practical examples in the hospital and military sectors and how you can use chain-of-thought prompting for instruction design to combat hallucinations and ensure the GPT only answers questions within its domain / task. 

[Vishal Sharma](https://www.linkedin.com/in/vishal-sharma-phd-34221127/) showcased two open-source H2O.ai tools: 
1. h2oGPT - harness LLM’s fine-tuned by the world's best Kaggle Grandmasters. Have a play online at [https://gpt.h2o.ai/](https://gpt.h2o.ai/) or clone and run locally at [https://github.com/h2oai/h2ogpt](https://github.com/h2oai/h2ogpt). 
2. LLM Studio for fine-tuning your LLMs in a no-code GUI with your own data, with LoRA, QLoRA, and even RLHF. Available to clone at [https://github.com/h2oai/h2o-llmstudio](https://github.com/h2oai/h2o-llmstudio).

### 1st August - 💽 Data Tuesday #1
Kicked off the first-ever [Data Tuesday](https://www.meetup.com/data-ai-singapore/) by [Ville Kulmala](https://www.linkedin.com/in/villekulmala/). It's a relaxed space for genuine data discussions, you'll know where to find me every month!

### 2nd & 3rd August - 🌏 [World AI Show](https://worldaishow.com/) at the Marina Bay Sands Exhibition Center
It's hard to summarise the 14 talks I attended across the two day AI conference (this could easily have its own blog post). The standout session for me was the panel discussion on **AI and Data Driven Decision Making** between [Robert Hollinger](https://www.linkedin.com/in/rahollinger/), [Adrien Chenailler](https://www.linkedin.com/in/adrien-c-b035602a/), [Jeannette Pang](https://www.linkedin.com/in/jeannette-pang-0020666b/), and  [Ram Thilak](https://www.linkedin.com/in/ramthilak/). They explained how they are making an impact for their customers in the banking and automotive sectors with AI and ML through: 
* fraud / anomaly detection
* real-time recommendations, price positions, and personalisations for product offerings 
* operational chatbots 
* churn prediction
* building dashboards that answer real questions.

Underpinning all this, I was glad to hear how much emphasis they put on data ethics, through:
* data governance
* model assessment to avoid biases and discrimination before deployment
* model interpretability and explainability

<details>
<summary><b>Full list of topics covered</b></summary>

1. Synergey of Digital Transformation and AI: Powering Organisational Growth
2. Embarking on a Journey to Democratise AI at Scale
3. Make Data Science a Team Sport
4. The Emergence of AI
5. Revolutionising Customer Experience with Conversational AI
6. Automation in Data Management: Enhancing Efficiency & Saving Time
7. AI and Data Driven Decision Making Panel Discussion
8. Generative AI: A Game Changer?
9. The Why, Where and How of Enterprise AI Adoption
10. Sustainable AI for Humanity
11. Blockchain for Healthcare
12. Emergence of Web3 and Gaming and Virtual Worlds
13. Building Trustworthy and Ethnical AI Panel Discussion
14. Securing the Future of AI: Addressing Privacy, Security, and Compliance in LLMs

</details>  

<br/>

![Intro to World AI Show](/images/blog/2023-08_world-AI-show.jpeg)
*Opening event to World AI Show*

### 2nd August - 🛠️ dbt meetup
I learnt about SQL-centric data engineering at a [dbt SG meetup](https://www.meetup.com/singapore-dbt-meetup/). Two Data Engineers from Teleport showcased how [dbt](https://www.getdbt.com/) revolutionised their workflow, with the following examples:
* rapid SQL compilation and query times
* ability to data version control 
* automating freshness checks
* optimising clustering and partitioning tables to reduce cloud computing costs and dashboards loading times
* change logs which makes changes transparent and trackable with Git - allowing for asynchronous collaboration 
* project structure is a more organised as models can be stored
* aligned logic being inbuilt into tests to ensure smooth pipelines
* preprocessing and feature engineering with Jinja templates
* deployment and monitoring - can easily toggle between real-time streaming and batching of data

I'll definitely be experimenting with this open-source tool and seeing how it can applied to my future workflows.

### 3rd August - 🧠 How to break into AI Careers

[Thu Ya Kyaw](https://www.linkedin.com/in/thuyakyaw/) ([SideQuest](https://www.meetup.com/sidequest/) founder), [Koo Ping Shung](https://www.linkedin.com/in/koopingshung/) (co-founder of [DataScienceSG](https://www.meetup.com/datascience-sg-singapore/)) and [Poh Wan Ting](https://www.linkedin.com/in/pohwanting/) and [Michelle Lim](https://www.linkedin.com/in/michellelimsh/) (Mastercard Lead/Senior Data Scientists) shared their unique journeys on **How to break into AI careers**. My takeaways were:
* to focus on impact and ROI by productionising models and deploying Proof of Concepts - as model development is only makes up 10% of a data scientists role, the rest of the time is spent on cleaning data, exploring data, deployment code, and maintenance
* to have good fundamentals of writing production-ready scalable code, testing code, statistics, and being able to explain models
* learn how to learn (pedagogy), have good time management, and have a growth mindset to be a great data scientist
* newsletters are a great way to keep up to date with the latest data science advancements, such as [MIT Technology Review](https://www.technologyreview.com/), [Data Engineering Weekly](https://www.dataengineeringweekly.com/), [TLDR AI](https://tldr.tech/ai), and [Koo's substack](https://koopingshung.substack.com/).

### 16 August - 👷‍♂️ OCBC Data Engineering Revolution

[Periyasamy Sivakumar](https://www.linkedin.com/in/periyasamy-sivakumar-b7ab2282/) gave a great deep dive into **OCBC’s modern Data Engineering tech stack**, at [Data Engineering SG meetup](https://www.meetup.com/data-engineering-sg/). This tech stack consists of:
* [dbt](https://www.getdbt.com/) for rapid SQL compilation
* [trino](https://trino.io/) for virtualisation and efficiently serve data from multiple data platforms through a single entry point
* and, [dagster](https://dagster.io/) for the data orchestration and to handle dependencies. 

It was great to hear the full story on:
* **What** the problem was - OCBC have so much data (4000TB), 90K daily jobs, 1M attributes, so they needed a scalable and controllable solution
* **Why** these tools were selected
    * you can write SQL in dbt, compile and run it in Trino, this alone can manage your entire data lifecycle
    * jobs can be rerun should there be errors, such as network errors
* The **considerations in tool selection**
    * they have lots of legacy systems so it takes time to migrate 20 years of business rules
    * they have an in-house team looking for new technology solutions
* The **future** of data engineering being real-time streaming
    * in banking - every millisecond counts to help the customer, for example fighting fraud
    * use Kafka for data API and Flink for real-time processing
* The **downstream AI/ML use cases**:
    * hyper personalisation
    * nudges - send customers mobile notifications to do their tax returns
    * chatbots
    * real-time fraud detection, money-laundering detection
    * real-time help - imagine your card was swallowed by an ATM you could receive an SMS with advice, rather than calling a call centre

![OCBC Data Engineering](/images/blog/2023-08_OCBC.jpeg)
*How OCBC utilise data*

### 18 August - 🦅 Launch of BrightRaven.ai!

Celebrated Singapore’s newest AI startup [BrightRaven.ai](https://brightraven.ai/) fantastic launch party at the Mondrian Duxton. It was great mingling with [Bertrand Lee](https://www.linkedin.com/in/bertrandlee/) (founder) and co and hearing their wealth of experience, whilst enjoying the rooftop view! Best wishes to the team on their AI consultancy journey!

### 21 August - 💵 Application of ML and GenAI in Finance with Fullerton Fund Management
[Kai Xin](https://www.linkedin.com/in/thiakx/) (co-founder of [DataScienceSG](https://www.meetup.com/datascience-sg-singapore/)) wonderfully explained the LLM stack using a burger analogy. Where the bun is analogous to the static components, such as prompt engineering and Retrieval-Augmented Generation (RAG), and the burger patty representing the re-useable components that can be swapped for different 'flavours' of fine-tuned LLM models. This is made possible through the use of adapters which can identify and switch to the correct fine-tuned model based on the user input. Kai Xin's slides can be found at [bit.ly/practical-genai-ft](bit.ly/practical-genai-ft).

Kai Xin also showed easy it is do to **Practical Generative AI Fine-Tuning**. In his live-demo he fine-tuned a Flan-T5 model for **financial sentiment analysis** in just 8 minutes for free in a [Colab notebook](bit.ly/practical-genai-ft-colab), using HuggingFace’s implementation of [Quantised LoRA (QLoRA)](https://huggingface.co/blog/4bit-transformers-bitsandbytes).

[Chao Jen](https://www.linkedin.com/in/chao-jen-chen-9493123/) shared how they use clustering models to **model the Global Macro Regime** in combination with a second model for regime transitions - to help their portfolio managers with asset relocation by considering the current global situation. The model outputs were very clearly and intuitively visualised by stacked bar charts showing the probability distributions for each regime. It was impressive to hear how they've trained 1000s of models, but there is still a strong need for domain knowledge and judgement between the data scientists and portfolio managers.

[Shi Hui](https://www.linkedin.com/in/limshihui/) shared the importance of using **[time-based cross-validation](https://towardsdatascience.com/time-based-cross-validation-d259b13d42b8)** for **predicting winners in the stock market** - not to use Scikit-Learn’s method which can introduce bias and has a limitation of assuming one observation per day. For this type of analysis, ideally you'd have at least two cycles of the economy, so at least 5-7 years. Some useful predictive external signals include estimates data for company fundamentals, news sentiment, and investor company visits. 

[Yan Rong](https://www.linkedin.com/in/yan-rong-chng/) shared how to predict the **U.S. Treasuries Yield Curve with PCA Decomposition** for global market simulation. YTC is the rate that U.S. banks can borrow money. Yan Rong showed how you can reduce from 11 features to 3 components and still capture 99% of the variance. You can isolate these components in line charts to understand the intuition in the YTC movements and do scenario simulations. The code and slides by the Fullerton data scientists can be found at [https://github.com/shihuiFFMC/dssg_aug2023](https://github.com/shihuiFFMC/dssg_aug2023).

![Kai Xin at DataScience Singapore](/images/blog/2023-08_DSSG.jpeg)
*Kai Xin summarising the LLM landscape*

### 29 August - ⚛️ Data Tuesday #2 - Quantum Computing
Caught up again with some familiar faces and also new faces at The Terrace again, this time discussing Quantum Computing. Some thoughts that I left with:
* Quantum Computing is still many years from being practical and decrypting our modern encryption algorithms, like RSA. But we may begin to see services offering quantum computing encryption in the near future.
* Quantum computing won't create as many startups as GenAI - due to the barrier of entry being so high - requiring millions of R&D in hardware, software, and algorithm development, versus GenAI where the cost of entry is so cheap.
* How AIs in the western world already differ versus China and will continue to drift apart. LLMs are predominantly trained on data in the languages of their associated markets, so there are already substantial differences and biases from the model pretraining. Next, there will be differences due to activity and advancements from their respective open-source community. This split is further exacerbated with the U.S. restrictions on advanced AI chips, like A100, on China and Russia, where these AI researchers will be unable to build upon the latest architecture.
* Will NVIDA maintain its dominance in the AI GPU space? Or can the cheaper alternatives from AMD, Intel, or China (if they aren't sanctioned) can compete? A big reason for NVIDIA's dominance is because they were first-to-market in the space and the open-source community has developed everything on their architecture. Ultimately it depends on how much development there is in porting to non-NVIDIA architecture. Perhaps due to NVIDIA's inability to meet demand, companies may be forced to resort to competitors.

### 31 August - 🔍 Why Vector Search is Important
[Yoshi Kimoto](https://www.linkedin.com/in/yoshinobukimoto/) from [Datastax](https://www.datastax.com/) explained **Why Vector Search is Important** for LLMs. Yoshi explained how:
* lack of context is the major reason for hallucinations
* any data that could be contextually relevant can be vectorised using embeddings
* vector search allows for efficient content retrieval from your existing data
* vector search allow LLMs to find similar content in large document collections, using linear algebra techniques such as cosine similarity and dot product
* with storage attached indexing, Lucene can be used for document retrieval in combination with vector similarity search
* Datastax is built on Cassandra and can handle data streaming and ingestion, which opens the possibility for LLMs with the power of real-time RAG

You can test Datastax's vector search demo in your browser [here](https://docs.datastax.com/en/astra-serverless/docs/vector-search/quickstarts.html).

![Yoshi presenting Why Vector Search is Important](/images/blog/2023-08_vector-search.jpeg)
*Yoshi on the LLM stack*

## Wrapping up

It's been a whirlwind month, and it’s been energising to learn and mingle with the brightest AI minds in Singapore. I’m looking forward to applying these insights and sharing more with you all. After all, education without action is simply entertainment!

Lastly, a big thanks to my talented ex-colleagues in the UK civil service at the [Department of Health and Social Care](https://www.gov.uk/government/organisations/department-of-health-and-social-care) for having me in your teams [Lucy Vickers](https://www.linkedin.com/in/lucy-vickers-377bb079/), [Phil Walmsley](https://www.linkedin.com/in/philip-walmsley/), [Mariana](https://www.linkedin.com/in/marianadatascience/), Graeme, and [Anita Brock](https://www.linkedin.com/in/anita-brock-0a816483/).

Thanks for reading and making it all the way down here!  If you fancy a chat about any of these topics, drop me an email. 

Cheers! 

Vince