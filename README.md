# RAG-based AI App using Azure AI Foundry

This project was developed as part of Module 5 of the Microsoft AI Skills Challenge: Create agentic AI solutions with Azure AI Foundry. It showcases a Retrieval-Augmented Generation (RAG) application that enables querying custom PDF data using OpenAI models deployed on Azure.

## What I Learned

• How to upload and manage custom datasets in Azure AI Foundry  
• How to configure and use Azure AI Search for information retrieval  
• How to implement hybrid search (semantic + keyword) with vector indexing  
• How to integrate OpenAI's embedding and chat models in a RAG pipeline  
• How to use .env for securely managing credentials and configuration  
• How Retrieval-Augmented Generation (RAG) improves factual accuracy in LLM outputs  

## Project Highlights

• Uploaded travel brochures (PDFs) as custom data into Azure AI Foundry  
• Created a vector index using Azure AI Search, enabling semantic retrieval  
• Configured hybrid search to combine vector similarity and keyword scoring  
• Used text-embedding-ada-002 for generating embeddings  
• Passed search results as context to a gpt-4o chat model for enriched answers  
• Configurations were managed using a .env file and excluded via .gitignore  
• Screenshots included to demonstrate outputs in Azure  

## Screenshots

• (assets/configuration-file.png)  
• (assets/chat-demo.png)  
• (assets/chat-code-powershell.png)  

## Reference

• Microsoft Learn: [https://microsoftlearning.github.io/mslearn-ai-studio/Instructions/04-Use-own-data.html](https://learn.microsoft.com/en-gb/collections/50wkaqtq50egz3?ref=collection&listId=60yka7t2o8od52&sharingId=6A9F03F25E12DA9E&wt.mc_id=aiskillsfest_msftlearn_training_wwl_challenge_tech)
