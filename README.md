# LangChain


Using RAG LangChain Embeddings LECL 
ddd


LLM chain 
using gpt
Prompt template

using moderator

not supporting on local need to use machine with 16gb ram



efyyy
dd
1)langchain. The revolutionary framework to build apps using large language models.

2)sentence_transformers. necesary to create the embeddings we are going to store in the vector database.

3)chromadb. This is our vector Database. ChromaDB is easy to use and open source, maybe the most used Vector Database used to store embeddings.

4)CharacterTextSplitter: we will use it to group the information contained in different blocks.

5)HuggingFaceEmbeddings: it will create the embeddings in the format that we will store in the database.

->We use HuggingFacePipeline class to create a pipeline for a specific Hugging Face language model. Let's break down the code:

 1)model_id: This is the ID of the Hugging Face language model you want to use. It typically consists of the model name and version.
 2)task: This parameter specifies the task that you want to perform using the language model. It could be "text-generation", "text2text-generation", "question-answering", or other tasks supported by the model.
 3)model_kwargs: Allows you to provide additional arguments specific to the chosen model. In this case, it sets "temperature" to 0 (indicating deterministic output) and "max_length" to 256, which limits the maximum length of generated text to 256 tokens.
4)pipeline_kwargs: Allows you to provide extra information related to the pipeline.


#PromptTemplate: provide the functionality to create prompts with parameters.

#LLMChain: To create chains, where the prompts or the results can pass from one step to another inside the chain.

SequentialChain is used to link different chains and parameters.


facing problem in 

ned some toi
need some rework

