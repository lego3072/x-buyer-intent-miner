# X Buyer-Intent Miner

Find high-intent buying language, rank lead urgency, and route opportunities into your agent outreach workflows.

## Run locally
```bash
pip install -r requirements.txt
uvicorn app.main:app --reload --port 8000
```

## Endpoints
- `/`
- `/docs-page`
- `/health`
- `/v1/public/config`
- `/llms.txt`
