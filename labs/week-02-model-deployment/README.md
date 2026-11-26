# Week 2 Lab: Quantized GGUF LLMs & Image Generation (Sessions 6–10)

## Objective
Configure a quantized GGUF model with `llama.cpp` parameters and test text-to-image generation.

## Steps
1. Copy `configs/models/llama-cpp-chat.yaml` into your LocalAI `models/` volume.
2. Adjust `threads` and `context_size` to fit your VPS RAM budget.
3. Query the chat endpoint via `curl` or Postman and benchmark tokens/second.
4. Enable a Stable Diffusion-compatible backend and test `/v1/images/generations`.
