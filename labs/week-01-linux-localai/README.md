# Week 1 Lab: Deploy LocalAI & Run Your First API Call (Sessions 1–5)

## Objective
Deploy LocalAI on an Ubuntu Linux VPS without a GPU and verify an OpenAI-compatible API response.

## Steps
1. **Verify VPS Resources:** Check CPU cores and RAM (`free -h && nproc`).
2. **Start LocalAI Container:** Run `docker compose up -d` using `configs/docker/docker-compose.yml`.
3. **Check Health Endpoint:**
   ```bash
   curl http://127.0.0
   ```
4. **Test Chat Completion Endpoint:**
   ```bash
   curl http://127.0.0 \
     -H "Content-Type: application/json" \
     -H "Authorization: Bearer YOUR_API_KEY" \
     -d '{
       "model": "gpt-4o-mini",
       "messages": [{"role": "user", "content": "Confirm LocalAI is running on Ubuntu."}]
     }'
   ```
