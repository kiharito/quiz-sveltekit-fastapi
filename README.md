# quiz-sveltekit-fastapi

## 環境構築手順

### Frontend

```shell
cd frontend/
```
```shell
node -v # => 20.11.0
```
```shell
npm install
```
```shell
npm run dev -- --open
```

### Backend

```shell
cd backend/
```
```shell
python --version # => 3.12.2
```
```shell
python -m venv .venv
```
```shell
source .venv/bin/activate
```
```shell
pip install -r requirements.txt
```
```shell
uvicorn app.main:app --reload
```
[http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)にアクセスする。

### DB

```shell
docker compose up -d --build
```
