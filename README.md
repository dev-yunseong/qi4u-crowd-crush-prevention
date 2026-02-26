# QI4U Crowd Crush Prevention

[website](https://qi4uinpnu.vercel.app/)

## 1. 프로젝트 소개

이 프로젝트는 Quantum Annealing을 기반으로 군중 밀집 공간의 흐름을 최적화하여 압사 사고를 예방하는 솔루션입니다.

## 2. 기술 스택

-   **Backend**: `Python`, `FastAPI`, `NetworkX`
-   **Frontend**: `React`, `TypeScript`, `Vite`, `vis.js` (for graph visualization)
-   **Infra**: `Vercel`

## 3. 프로젝트 실행 방법

### Backend

1.  `backend` 디렉토리로 이동합니다.
    ```bash
    cd backend
    ```
2.  필요한 Python 패키지를 설치합니다.
    ```bash
    pip install -r requirements.txt
    ```
3.  FastAPI 개발 서버를 실행합니다.
    ```bash
    uvicorn main:app --host 0.0.0.0 --port 8000 --reload
    ```
    서버는 `http://localhost:8000`에서 실행됩니다.

### Frontend

1.  `frontend` 디렉토리로 이동합니다.
    ```bash
    cd frontend
    ```
2.  필요한 Node.js 패키지를 설치합니다.
    ```bash
    npm install
    ```
3.  Vite 개발 서버를 실행합니다.
    ```bash
    npm run dev
    ```
    애플리케이션은 `http://localhost:5173` 또는 다른 지정된 포트에서 실행됩니다.
