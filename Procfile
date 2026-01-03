web: uvicorn app.main:app --host 0.0.0.0 --port $PORT
worker: python -m app.workers
shopify-app: cd shopify-app && npm install && npm run build && npm start

