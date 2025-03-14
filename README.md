# python_vscode_setting
### Python - VS Code 가상환경 세팅 방
--------------------------------------------------
<p>$\color{#5ad7b7}**** Window 기준 ****$</p>


__1. miniconda를 다운__

<https://www.anaconda.com/download/success>

__2. VS Code 다운__

<https://code.visualstudio.com/Download>

__3. VS Code 설치 후 열기__

__4. 보기 > 터미널 클릭__

__5. 터미널 우측상단 > powershell > command prompt로 변경__

__6. 터미널에 명령어 입력__
```
설치된 아나콘다 확인 : conda
```

```
호출된 아나콘다 확인: pip list
```

```
가상공산 생성 : conda create -n BAF521 python=3.12
Proceed ([y]/n)? 가 뜬다면 y 입력
```

```
가상공간활성화 : conda activate BAF521
```

__7. BAF521환경 추가 확인__

ℹ️ <sub>만약 환경이 추가되어 있지 않다면
         컨트롤 + 시프트 + p > reload Wondow 
          reaload 후 재확인 
</sub>

__8. 가상환경설정확인__

컨트롤 + 엔터 후 코드 실행 

추가 install 진행
