The goal of RAG is to take information and pass it to LLM so it can generate output based on that information 
1. Retrival -> Find relevant information given a query e.g., "what are macronutrients and whwat do they do?" -> retrives passage of text related to query
2. Augmented - we want to take the relevant information and augment our input(prompt) to an LLM with that relevant infroamtion 
3 . Genreation - take first two steps and pass them onto a LLM for generative outptus 


why RAG?  
the main goal of RAG is to improve the outputs 
1. prevent hallucinations -  LLM are good at generating good looking text but might not be factual.
2.  work with custom data 


Uses 
1. Customer support Q&A chat 
2. Email Chain analysis 
3. Textbook q&a 


why local --> privacy,speed,cost

process 
1. Open pdf docuement 
2. format the text of pdf ready for an embedding model
3. embed all chunks of text in note and turn them into embedding which we can store for later 
4. Build retrival system that uses vector search to find relevant chunk of text based on query 
4. Create prompt that incorporates the retrived peices of text
5. Generate answer to query base on passage of textbook with lllm