# sojeong-llm-bot

## 1. 프로젝트 세팅

- vsc
  -github 연동

## 2. 프로젝트 구성

- 가상환경을 설정 - > docker Container 개념 (공간을 따로 분리해서 관리하겠다.)
- python3.8 열심히 개발을 했어요 근데 우리가 배포할 서버가 3.3버전의 파이썬이야. =>3,8함수를 썼다면 3.3에는 없는 함수야 -> 오류 -> 배포하고 나서 알겠죠
  => 로컬에서 작업하는 환경과 호스트 서버에서 작업하는 환경을 일치시켜주기 위함.
  => Docker(virtual Machine) .. venv모듈을 사용해서 환경설정을 해주도록 하겠습니다.

> python3.10 -m venv
> Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser

.venv/Scripts/activate

## 3. 프로젝트

(1) Ollama모델 + CrewAI
(2) Flask사용해서 기본적인챗봇
pip install crewai crewai-tools
pip install langchain-ollama
