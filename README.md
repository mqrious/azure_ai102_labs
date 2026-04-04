# Azure AI Services Lab & AI-102 Study

This repository is a personal lab for experimenting with **Azure AI Services** and preparing for the **AI-102 Azure AI Engineer Associate** exam.

## ⚠️ AI-102 Retirement
This certification is scheduled to retire on June 30, 2026. More info:
- https://learn.microsoft.com/en-us/credentials/support/retired-certification-exams
- https://techcommunity.microsoft.com/blog/skills-hub-blog/the-ai-job-boom-is-here-are-you-ready-to-showcase-your-skills/4494128

## ⚠️ Disclaimer

At the time of this writing, Azure is continuously updating its AI concepts and services to keep up with the rapidly evolving AI landscape. As a result, some SDK packages, APIs, or functions may not work as expected or could be deprecated without notice. 

This repository is intended for learning and experimentation—please validate official documentation when building production-grade solutions.

## 🎯 AI-102 Focus Areas (Skills measured as of April 30, 2025)

### Plan and manage an Azure AI solution (20–25%)

- Generative AI solution: Azure AI Foundry, Azure OpenAI.
- Computer vision solution: AI Vision.
- Natural language processing solution: AI Language, AI Translator.
- Speech solution: AI Speech (speech-to-text, text-to-speech, speaker identification, speaker verification, diarization).
- Information extraction solution: Content Understanding (Document Intelligence, Video Indexer).
- Knowledge mining solution: Content Understanding, AI Search.
- Monitor Azure AI resources: specific AI resource, unified resource (AI Foundry).
- Manage costs: Cost Management.
- Manage authentication and authorization: Key & Endpoints, Microsoft Entra ID, RBAC.
- Implement Responsible AI: Content safety, Content filter/blocklist, Prompt shields, Harm detection.
- Implement container deployments.
- Utilize the appropriate SDKs and APIs

### Implement generative AI solutions (15–20%)

- **Responsible AI** ([genai_responsible_ai.md](genai_responsible_ai.md)): Identify, mitigate and manage potential harms.
- **Prompt flow** ([genai_prompt_flow.md](genai_prompt_flow.md)): Basic flow concepts, types and components. LLM evaluation metrics (Groundessness, Relevance, Coherence, Fluency, Similarity).
- **Working with Multimodal Models** ([genai_multimodal_models.ipynb](genai_multimodal_models.ipynb)): Prompting with audio and image files.
- **Image generation** ([genai_image_generation.ipynb](genai_image_generation.ipynb)): Generate image using DALL-E 3.
- **RAG with AI Search** ([genai_rag_with_ai_search.ipynb](genai_rag_with_ai_search.ipynb)): Key-word search, Vector search.
- **Fine-tune AI models** ([genai_model_fine_tuning.md](genai_model_fine_tuning.md)): Fine-tune AI model on Azure AI Foundry.
- **Model performance Evaluation** ([genai_model_performance_evaluation.md](genai_model_performance_evaluation.md)): Model benchmarks, Manual & AI-assisted evaluation, NLP metrics (F1-score, BLEU, METEOR, ROUGE).

### Implement an agentic solution (5–10%)

- **AI Agents overview** ([aigents_overview.md](aigents_overview.md)): Agent development on Azure platform, Agent components, Agent use-cases, and Agent resources (tools, knowledge, model).
- **AI Agent development with Foundry Agent Service** ([aiagents_first_agent.ipynb](aiagents_first_agent.ipynb)): Simple agent with CodeIntepreter tool to analyze an uploaded data file.
- **AI Agent with Custom tools** ([aiagents_custom_tools.ipynb](aiagents_custom_tools.ipynb)): Simple agent with Function calling tool (Python function).
- **Semantic Kernel** ([aiagents_semantic_kernel.ipynb](aiagents_semantic_kernel.ipynb)): Experiment building AI agents with Semantic Kernel.
- **Agent orchestration** ([aiagents_agent_orchestration.ipynb](aiagents_agent_orchestration.ipynb)): Experiment on orchestration a multi-agent system using Semantic Kernel, the orchestration follows pre-defined logics.
- **Connected Agents** ([aiagents_connected_agents.ipynb](aiagents_connected_agents.ipynb)): Another way to build multi-agent solutions, the main agent uses natural language (prompts) and tools to orchestrate.
- **MCP Integration** ([aiagents_mcp_tools.ipynb](aiagents_mcp_tools.ipynb)): Experiment with Agents using MCP server/client.

### Implement computer vision solutions (10–15%)

- **AI Vision** ([ai_vision.ipynb](ai_vision.ipynb)): 
    - Image analysis (Caption, Dense caption, Tags, Objects, People, Smart crops, Read text).
    - Face analysis (Head pose, Occlusion, Accessories, Glasses, Exposure...).

### Implement natural language processing solutions (15–20%)

- **AI Language** ([ai_language.ipynb](ai_language.ipynb)): Language detection, Sentiment analysis, Key phrase extraction, Entity recognition, Linked entities extraction, PII recognition, Summarization.
- **AI Translator** ([ai_translator.ipynb](ai_translator.ipynb)): Translation, Transliteration.
- **AI Speech** ([ai_speech.ipynb](ai_speech.ipynb)): Audio transcription, Speech synthesis with SSML, Speech translation, Transcription with real-time Diarization.

### Implement knowledge mining and information extraction solutions (15–20%)

- **Content Understanding** ([genai_content_understanding.ipynb](genai_content_understanding.ipynb)): Document (invoice) analysis, Audio analysis, Create a custom analyzer.
- **AI Search** ([ai_search.ipynb](ai_search.ipynb)): Querying an index.

# 📝 Personal review on the exam

I took the AI-102 on 18/07/2025, these are the main takeaways:
- The exam has 3 sections: 50 standalone questions, then 3 (or 5?) questions that are related to each other (a series), and finally 6 case-study questions. Once I went through a section, I cannot go back to the previous.
- The topics are very close to the [Change log table of the study guide](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/ai-102#change-log). Beside all the services that you've learned, you should focus more on the topics listed on "Skill area as of April 30, 2025" column.
- Take the [Practice assessment](https://learn.microsoft.com/en-us/credentials/certifications/azure-ai-engineer/?practice-assessment-type=certification) multiple times, it has questions that will appear in the exam.
- I personally practice on the [Azure AI Engineer Associate AI-102 : Practice Tests (2025) by Nahid Perween on Udemy](https://www.udemy.com/course/azure-ai-engineer-associate-ai-102-practice-tests-new/), the final case-study questions in the exam are **exactly the same** to the questions in this course. I wonder if Microsoft only have these in their question bank? The standalone questions in this course are also very very helpful.
- The standalone questions ask about Semantic Kernel and Azure AI Foundry Agent Service, which are kinda new, so you should pay attention to these too.
- Before the exam, I have read about [the exam experiment and try the demo exam page](https://learn.microsoft.com/en-us/credentials/support/exam-duration-exam-experience) to be familiar with it.

After finishing the exam, I got the result on screen, then a confirmation email from Microsoft about an hour later.

I got 902/1000 on the exam, good luck to you guys! 🍀
