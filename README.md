#  SetlistSage

An agentic concert recommendation service. Give it your Spotify username, a city, and a date range — it tells you which concerts to attend and why.

## Stack
- Python 3.13 + FastAPI
- OpenRouter (LLM gateway)
- Spotify, Ticketmaster, Setlist.fm APIs

## Run locally
```bash
pip install -r requirements.txt
uvicorn app.main:app --reload
```