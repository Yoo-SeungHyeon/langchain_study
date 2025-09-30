# 랭체인 공부

## 목표
PDF에서 데이터를 원하는 형태로 추출하기

## 버전
[Python 3.12.10](https://www.python.org/downloads/release/python-31210/)

## 세팅
```
python.exe -m pip install --upgrade pip
python -m venv .venv

source .venv/Scripts/activate
python.exe -m pip install --upgrade pip

pip install --upgrade langchain-core

pip freeze > requirements.txt
```

**LangSmith**를 권장하여 사용할 예정
[LangSmith](https://smith.langchain.com)
1. 회원가입
2. Settings > API Keys
3. + API Key 클릭으로 API Key 생성

```
export LANGSMITH_TRACING="true"
export LANGSMITH_API_KEY="..."
```

*혹시나 하는 생각에 jupyter notebook에 라이브러리 설치하는 코드도 작성함.
