The goal of RAG is to take information and pass it to LLM so it can generate output based on that information 
1. Retrival -> Find relevant information given a query e.g., "what are macronutrients and whwat do they do?" -> retrives passage of text related to query
2. Augmented - we want to take the relevant information and augment our input(prompt) to an LLM with that relevant infroamtion 
3 . Genreation - take first two steps and pass them onto a LLM for generative outptus 


why RAG?  
the main goal of RAG is to improve the outputs 
1. prevent hallucinations -  LLM are good at generating good looking text but might not be factual.