# Week 3 Lab: Vision, Speech (STT/TTS) & SSL Security (Sessions 11–15)

## Objective
Add multimodal endpoints (vision, speech-to-text, text-to-speech) and protect LocalAI behind an SSL reverse proxy.

## Steps
1. Configure vision and STT/TTS backends in LocalAI.
2. Enforce static `API_KEY` authentication so unauthorized requests return `401 Unauthorized`.
3. Configure Nginx using `configs/reverse-proxy/nginx-ssl.conf` and issue a free SSL certificate via Certbot (`certbot --nginx -d ://yourdomain.com`).
4. Verify external HTTPS access with a valid Bearer token.
