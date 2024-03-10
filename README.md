# AI Search engine

This project helps to query the latest content to the Large language model using the latest data from the web. 

## Things I learned along the way

- Scraping the data from the websites and retrieving the relevant information based on query
- Creating word embeddings using OpenAI embedding model
- Using Vector Database `Chroma` to store the word embeddings
- Retrieving the top relevant document from the vector database using similarity score
- Prompting the LLM to answer the query based on the top k relevant documents

## Scope of Improvement

- Improving the web scraper. This includes:

> - Scraping the websites which works on Client Side Rendering (CSR)
> - By passing captcha to access the website content
> - IP rotation so that our scraper will not get blocked by the website

- Improving the logic for matching most similar documents with the query
- Creating a User interface to interact with this tool

## Run the project

- Clone the repo
- Create `.env` file and place your openAI API key there

```
OPENAI_API_KEY=<your-key>
```

- Run the `main.py` notebook

- It will ask for your enter query. Enter the query you want to search