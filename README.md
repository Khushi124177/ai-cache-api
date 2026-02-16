# AI Cache API

This is a FastAPI-based caching system for an AI customer support chatbot.

## Features
- Exact match caching using MD5 hash
- Query normalization
- Analytics endpoint

## Endpoints
### POST /
Send a query and get an answer (cached or fresh)

### GET /analytics
Returns cache hit rate, misses, cache size, and strategies used.

## Deployment
Deployed using Render.
