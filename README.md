# pygame-class

- Terminal -> New Terminal
```shell
`python -m venv .venv` (생략 ㅆㄱㄴ)
```
- Command Prompt열기
```shell
`.\.venv\Scripts\activate.bat`    `.\.venv\Scripts\activate.bat`
```
- ---> (.venv)가 보여야 함.


#처음 패키지 설치
```shell
pip install pygame -ce
pip install black isort
pip freeze > requirements.txt
```
#패키지 재설치 (requirements.txt가 이미 있을경우)
```shell
pip install -r requirements.txt
```
