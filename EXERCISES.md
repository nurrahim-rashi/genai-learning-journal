# Daily exercises

One small exercise per day, taken from the assignments, challenges, and notebooks in Microsoft's [Generative AI for Beginners](https://github.com/microsoft/generative-ai-for-beginners), after a short review of my bootcamp topics from two of Microsoft's other beginner courses. The order follows the progress list in the [README](./README.md).

How a day works:

1. Do the one exercise for the day. Stop there, even if it was short.
2. Write it up in `notes/day-NN-name.md` (copy [`notes/_template.md`](./notes/_template.md)).
3. Put any code in `experiments/day-NN-name/`. `NN` is the day number below, so both folders sort in the order I did things.
4. Tick the box here, and tick the lesson in the README once all of its days are done.

Tags: **[course]** is the lesson's own assignment, challenge, or notebook. **[mine]** is one I added: either the lesson has no assignment and I built one from what it covers, or it is a "bridge" that reuses something from my bootcamp.

Most notebooks come in three versions: `githubmodels-*` (GitHub Models), `oai-*` (OpenAI API), and `aoai-*` (Azure OpenAI). Pick whichever one you have a key for.

## Bootcamp review

A short pass over what my bootcamp covered, using two other Microsoft courses: [ML for Beginners](https://github.com/microsoft/ML-For-Beginners) and [AI for Beginners](https://github.com/microsoft/AI-For-Beginners).

### Image classification
- [ ] Day 1: Work through the ConvNets notebook, PyTorch or TensorFlow ([lesson](https://github.com/microsoft/AI-For-Beginners/tree/main/lessons/4-ComputerVision/07-ConvNets)). **[course]**
- [ ] Day 2: Case study: classify 5 kinds of flowers from real colour photos (`tf_flowers`), first with my own CNN, then with transfer learning. **[mine]**
- [ ] Day 3: Lab: build a transfer learning classifier on the Oxford-IIIT pets dataset, 35 breeds of cats and dogs ([lesson](https://github.com/microsoft/AI-For-Beginners/tree/main/lessons/4-ComputerVision/08-TransferLearning)). **[course]**

### Sentiment analysis
- [ ] Day 4: Challenge: use sentiment polarity with TextBlob to find out whether *Pride and Prejudice* has more absolutely positive sentences than absolutely negative ones ([lesson](https://github.com/microsoft/ML-For-Beginners/tree/main/6-NLP/3-Translation-Sentiment)). **[course]**
- [ ] Day 5: Assignment: assign sentiment with NLTK on a dataset other than the lesson's hotel reviews, and document the data processing ([lesson](https://github.com/microsoft/ML-For-Beginners/tree/main/6-NLP/5-Hotel-Reviews-2)). **[course]**

### Classification and clustering
- [ ] Day 6: Assignment "Parameter play": pick one classifier from the lesson, retrain it with different parameter values, and explain why some changes help and others hurt ([lesson](https://github.com/microsoft/ML-For-Beginners/tree/main/4-Classification/3-Classifiers-2)). **[course]**
- [ ] Day 7: Assignment: cluster a dataset with a method that is not K-Means. The assignment allows data from elsewhere, so my fraud detection data works here ([lesson](https://github.com/microsoft/ML-For-Beginners/tree/main/5-Clustering/2-K-Means)). **[course]**

## Bridge to generative AI

Three lessons from AI for Beginners that connect the deep learning above to the LLMs below.

- [ ] Day 8: Work through the Embeddings notebook ([lesson](https://github.com/microsoft/AI-For-Beginners/tree/main/lessons/5-NLP/14-Embeddings)). **[course]**
- [ ] Day 9: Work through the Transformers notebook ([lesson](https://github.com/microsoft/AI-For-Beginners/tree/main/lessons/5-NLP/18-Transformers)). **[course]**
- [ ] Day 10: Read the lesson on pre-trained large language models and run `GPT-PyTorch.ipynb` ([lesson](https://github.com/microsoft/AI-For-Beginners/tree/main/lessons/5-NLP/20-LangModels)). **[course]**

## Concepts

Skipped as daily exercises. My bootcamp already covered the ML and deep learning foundations (image classification, sentiment analysis, clustering and classification for fraud detection), so these three are a skim, not a day each. The knowledge check at the end of each lesson works as a quick self-test.

- 01 Introduction to Generative AI and LLMs ([lesson](https://github.com/microsoft/generative-ai-for-beginners/tree/main/01-introduction-to-genai))
- 02 Exploring and comparing different LLMs ([lesson](https://github.com/microsoft/generative-ai-for-beginners/tree/main/02-exploring-and-comparing-different-llms))
- 03 Using Generative AI responsibly ([lesson](https://github.com/microsoft/generative-ai-for-beginners/tree/main/03-using-generative-ai-responsibly))

## Prompting

### 04 Prompt engineering fundamentals ([lesson](https://github.com/microsoft/generative-ai-for-beginners/tree/main/04-prompt-engineering-fundamentals))
- [ ] Day 11: Read the lesson and set up the environment (`.env`, notebook kernel). **[course]**
- [ ] Day 12: Work through the first half of the assignment notebook in `python/`. **[course]**
- [ ] Day 13: Finish the notebook and add at least one cell of your own experiment. **[course]**
- [ ] Day 14: Challenge: try the "cue" technique with `Complete the sentence "Show me an image of red car of make Volvo and "`. What comes back, and how would you improve it? **[course]**

### 05 Advanced prompts ([lesson](https://github.com/microsoft/generative-ai-for-beginners/tree/main/05-advanced-prompts))
- [ ] Day 15: Read the lesson and answer the knowledge check on chain-of-thought. **[course]**
- [ ] Day 16: Apply the "self-refine" technique to the lesson's small Flask API with an AI assistant. Save each round in `experiments/`. **[course]**
- [ ] Day 17: Challenge: use self-refine on a program you wrote yourself. Was the result better or worse? **[course]**

## First apps

### 06 Text generation apps ([lesson](https://github.com/microsoft/generative-ai-for-beginners/tree/main/06-text-generation-apps))
- [ ] Day 18: Read the lesson and get the first completion running from your own script. **[course]**
- [ ] Day 19: Build the recipe generator from the lesson. **[course]**
- [ ] Day 20: Assignment: build one of your choice: an improved recipe generator, a "study buddy", or a history bot. **[course]**
- [ ] Day 21: Challenge: run your app at temperature 0, 0.5, and 1. Which works best, and why? **[course]**

### 07 Chat applications ([lesson](https://github.com/microsoft/generative-ai-for-beginners/tree/main/07-building-chat-applications))
- [ ] Day 22: Read the lesson and run the `*-assignment-simple` notebook in `python/`. **[course]**
- [ ] Day 23: Work through the full `*-assignment` notebook (chat prompts, classifying, summarizing). **[course]**
- [ ] Day 24: Bridge: run the sentiment dataset from my bootcamp through an LLM with a zero-shot prompt, then compare its accuracy with the classifier I trained. **[mine]**

## Core techniques

### 08 Search applications and embeddings ([lesson](https://github.com/microsoft/generative-ai-for-beginners/tree/main/08-building-search-applications))
- [ ] Day 25: Read the lesson and explain embeddings and cosine similarity in your own words. **[course]**
- [ ] Day 26: Set up an embedding model and start the assignment notebook in `python/`. The lesson's own setup steps use an Azure subscription; `oai-assignment.ipynb` is the OpenAI version. **[course]**
- [ ] Day 27: Finish the notebook, run a few of your own search queries, then compare with the solution notebook. **[course]**
- [ ] Day 28: Bridge: embed a small set of texts, cluster the vectors with k-means, and check whether the clusters make sense. **[mine]**

### 11 Function calling ([lesson](https://github.com/microsoft/generative-ai-for-beginners/tree/main/11-integrating-with-function-calling))
- [ ] Day 29: Read the lesson and run the assignment notebook in `python/`. **[course]**
- [ ] Day 30: Add more parameters to the function to help learners find more courses. **[course]**
- [ ] Day 31: Add a second function call that takes more information from the learner, such as their native language. **[course]**
- [ ] Day 32: Add error handling for when the function call or the API returns no suitable courses. **[course]**

### 15 RAG and vector databases ([lesson](https://github.com/microsoft/generative-ai-for-beginners/tree/main/15-rag-and-vector-databases))
- [ ] Day 33: Read the lesson and draw the RAG flow (chunk, embed, retrieve, generate) from memory. **[course]**
- [ ] Day 34: Work through `notebook-rag-vector-databases.ipynb`. **[course]**
- [ ] Day 35: Assignment: build a small front-end for the RAG application in a framework of your choice. **[course]**
- [ ] Day 36: Assignment: recreate the application with LangChain or Semantic Kernel. **[course]**

### 17 AI agents ([lesson](https://github.com/microsoft/generative-ai-for-beginners/tree/main/17-ai-agents))
- [ ] Day 37: Read the lesson and note what makes something an agent rather than a chat app. **[course]**
- [ ] Day 38: Assignment, part 1: write system messages for different departments of an education startup, each with its own persona and priorities. **[course]**
- [ ] Day 39: Assignment, part 2: simulate the meeting. The user pitches a product idea and each department asks follow-up questions to refine it. **[course]**

## Going further

### 09 Image applications ([lesson](https://github.com/microsoft/generative-ai-for-beginners/tree/main/09-building-image-applications))
- [ ] Day 40: Read the lesson and generate your first image from code. **[course]**
- [ ] Day 41: Assignment: build an app that generates images of monuments in different, creative contexts, then compare with the reference solution. **[course]**

### 10 Low-code AI applications ([lesson](https://github.com/microsoft/generative-ai-for-beginners/tree/main/10-building-low-code-ai-applications))
- [ ] Day 42: Build the student assignment tracker app with Copilot in Power Apps. **[course]**
- [ ] Day 43: Homework: use Copilot to automate the email that goes to students when they submit an assignment. **[course]**
- [ ] Day 44: Assignment #2: build the invoice processing flow with AI Builder in Power Automate. **[course]**

### 12 UX for AI applications ([lesson](https://github.com/microsoft/generative-ai-for-beginners/tree/main/12-designing-ux-for-ai-applications))
- [ ] Day 45: Read the lesson, pick an app from `experiments/`, and list what you would change for pleasantness, usability, trust and transparency, and control. **[course]**
- [ ] Day 46: Implement at least two of those changes, for example clearer error messages and a data collection opt-in/opt-out. **[course]**

### 13 Securing AI applications ([lesson](https://github.com/microsoft/generative-ai-for-beginners/tree/main/13-securing-ai-applications))
- [ ] Day 47: Read the lesson and answer the knowledge check. **[course]**
- [ ] Day 48: Challenge: read the linked material on governing and protecting sensitive information, and note what applies to your own apps. **[course]**

### 14 The generative AI application lifecycle ([lesson](https://github.com/microsoft/generative-ai-for-beginners/tree/main/14-the-generative-ai-application-lifecycle))
- [ ] Day 49: Read the lesson and explain the shift from MLOps to LLMOps in your own words. **[mine]**
- [ ] Day 50: Map one app from `experiments/` onto the LLM lifecycle stages from the lesson. Which stages did you skip? **[mine]**

### 16 Open source models ([lesson](https://github.com/microsoft/generative-ai-for-beginners/tree/main/16-open-source-models))
- [ ] Day 51: Read the lesson and write down the benefits and trade-offs of open models. **[mine]**
- [ ] Day 52: Use the lesson's "How to choose" section to pick an open model for one of your apps, and justify the choice. **[mine]**

### 18 Fine-tuning ([lesson](https://github.com/microsoft/generative-ai-for-beginners/tree/main/18-fine-tuning))
- [ ] Day 53: Read the lesson and write down when fine-tuning is worth it and when it isn't. **[course]**
- [ ] Day 54: Assignment: pick one tutorial from the lesson's "Fine-Tuning In Action" table and start it (prepare the data). **[course]**
- [ ] Day 55: Finish the tutorial and compare the fine-tuned model with the base model. **[course]**

### 19 Small language models ([lesson](https://github.com/microsoft/generative-ai-for-beginners/tree/main/19-slm))
- [ ] Day 56: Read the lesson and write down how SLMs differ from LLMs and where they fit. **[mine]**
- [ ] Day 57: Run one of the Phi demo notebooks in `python/`, or run a Phi model locally as the lesson describes. **[mine]**

### 20 Mistral models ([lesson](https://github.com/microsoft/generative-ai-for-beginners/tree/main/20-mistral))
- [ ] Day 58: Read the lesson and run its Mistral Small vs Mistral Large comparison. **[mine]**
- [ ] Day 59: Run the tokenizer comparison from the lesson on a few sentences of your own. **[mine]**

### 21 Meta models ([lesson](https://github.com/microsoft/generative-ai-for-beginners/tree/main/21-meta))
- [ ] Day 60: Read the lesson and run the Llama 3.1 native function calling example. **[mine]**
- [ ] Day 61: Run the Llama 3.2 multimodal example with an image of your own. **[mine]**
