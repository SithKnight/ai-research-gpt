# AI Research GPT Agent
## Building and Deploying an AI Research GPT Agent

**Getting Started**
To get started with the app:

```py
git clone [https://github.com/SithKnight/ai-research-gpt.git](https://github.com/SithKnight/ai-research-gpt.git)
pip install -r requirements.txt 
streamlit run app.py
```
## Tools Used
* browseless
* serpapi
* openai

## Automation and Cloud Rendering
The app leverages:

* Render (render.com) for API generation
* Make (make.com) for automation tasks

## Testing Locally
To run and test the FastAPI app locally:

```py
uvicorn app:app --host 0.0.0.0 --port 10000
python test_server.py
```