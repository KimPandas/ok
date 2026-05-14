# 📊 파이썬 및 데이터 분석 패키지 설치 가이드

---

## 파이썬 설치 가이드(Python 3.11.9)

### 파이썬 다운로드(Python 3.11.9)

* [파이썬 공식 홈페이지 다운로드 페이지](https://www.python.org/downloads/windows/)에 접속합니다.
* 목록에서 **Python 3.11.9**를 찾습니다. (`Ctrl` + `F`를 누르면 쉽습니다.)
* Windows용 설치 파일(Installer)을 다운로드합니다. **(일반적으로 64-bit 버전을 선택)**
* 다운로드된 파일을 실행합니다.

<img src=https://i.postimg.cc/BZpJXtcJ/image.png, width=600>

---

### 설치 시 주의사항 (핵심!)

설치 파일을 실행하면 나타나는 첫 화면이 가장 중요합니다.

<img src=https://i.postimg.cc/R0WTn3nN/image.png, width=600>

- **[필수 선택] Add Python 3.11 to PATH**: 이 체크박스를 반드시 선택해야 합니다.
    - **이유:** 체크하지 않으면 터미널(CMD)에서 `python` 명령어를 입력해도 컴퓨터가 파이썬을 찾지 못합니다.
 
---

### 설치 완료 및 확인

설치가 끝나면 `Setup was successful`이라는 문구가 뜹니다. 이제 설치가 잘 되었는지 검증해야 합니다.

#### **0. CMD창 띄우는 법**
1. 키보드의 **[Windows 로고 키 + R]**을 누른 뒤, 실행 창에 `cmd`를 입력하고 엔터를 누릅니다.
2. 또는 작업표시줄 검색창에 **'CMD'** 혹은 **'PowerShell'**을 검색하여 실행합니다.
3. **예시:**
<img src=https://i.postimg.cc/bJ3bCpbP/image.png, width=600>

#### **1. 0번에 따라 명령 프롬프트(CMD) 또는 PowerShell을 새로 엽니다. (이미 열려있던 창은 닫아야 합니다.)**

#### 2. 아래 명령어를 입력합니다.

```python
python --version
```

<img src=https://i.postimg.cc/7PNDRb5v/image.png, width=600>

Python 3.11.9라면 제대로 설치되었습니다.

---

 
