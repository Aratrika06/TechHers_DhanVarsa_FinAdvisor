# TechHers_FinAdvisor
This is India's one of the first online personalized AI based Financial Advisor 



TechStack:

Step 1: User Data Collection through Forms and Storage
Step 2: Personalized investment recommendation(Raag +LLM)
Step 3: real time sentiment analysis from market and social media( ai powered chat bot)
Step 4: Dashboard for Visual portfolio Tracking
 			
Frontend :
* NextJs : for frontend and connecting to backend.
* NextJs has a hookform  library (Using for form management )+ Axios for API calls
* UI design/ Animation:
* D3.js/ Recharts.js : for visualising Data
* Clerk Api:User authentication and Log in

Backend/AI :
* Vercel :  application deployment platform 
* FastAPI + uvicorn: Frontend , backend integration( deployment Railway)
* Crew AI : running+Management of API s for specific Purposes
* LlamaIndex : for RAG management
* ChromaDB : for vector database
* Llama 3 : GPT
* Pydantic: Data validation for API requests (Agent handling)
* MongoDB : For storing data collected through for
* Recharts :  (Library of React Js )Used for generating charts from Llm outputs









AgentsTaskModel usedData Ingestion AgentCollect user input, encrypt it & send it to MongoDBFastAPI + MongoDB
Investment AgentAnalyze user financial data, generate asset allocationsLLaMA + RAG(ChromaDB= Vector DB)Portfolio Optimization AgentRebalance portfolio based on market sentimentEfficient frontier +MPT + MVO 
Sentiment Analysis AgentFetch financial news/tweets and generate market sentimentLlama 
*Report Generation Agent1.Convert LLM outputs to interactive chats
Passing RAGs and LLMs outputs for giving charts

2.Convert LLM response into a PDF financial Report(Fall Back)
Recharts (React.js)





LLamaIndex/ PDFKit















































