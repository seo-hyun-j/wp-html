# HTML 기본용어

### 태그

- HTML 페이지에 객체를 만들 때 사용함
- 시작 태그와 끝 태그가 쌍을 이룸
- 단독으로 사용하는 태그 존재 !

### 요소
- 태그를 사용해 만들어진 객체

### 속성
- 태그에 정보를 추가할 때 사용

### 주석
- HTML코드를 설명하기 위해 작성

# HTML5 페이지 구조
### !doctype
- HTML의 버전을 명시
- HTML5는 !doctype 다음에 html이라고 작성

### html 태그
- 모든 html페이지의 루트요소
- 모든 html 태그는 html 태그 내부에서 작성

### head 태그
- HTML 페이지의 여러 정보들을 제공

### body 태그
- 실제 사용자에게 보여지는 내용을 작성하는 부분
- body 태그 내부에 사용되는 태그는 매우 많으므로 강의를 통해 살펴 봄

# 글자 관련 태그
### 제목 태그
- 제목을 나타내기 위한 태그
- h1~h6

### 본문 관련 태그
- p:단락을 나타내는 태그
- br:줄바꿈 태그
- hr:수평줄을 긋는 태그

### 글자 형태 관련 태그
- b:굵은 글자
- i:기울어진 글자
- small:작은 글자
- sub:아래 첨자
- sup:위첨자

### 앵커 태그
- 페이지 내에 다른 위치로 이동할 때 사용하거나 다른 웹페이지로 이동할 때 사용
- a태그를 사용

### 목록 관련 태그
- ul:순서가 없는 목록을 만드는 태그
- ol:순서가 있는 목록을 만드는 태그
- li:순서가 없는 목록을 만드는 태그

# 표 관련 태그
### table 태그
- 표를 만들기 위한 태그
- 다른 태그보다 사용이 다소 복잡하며, 아래의 태그들이 table 태그 안에서 사용
-> caption: 표의 제목을 작성하기 위한 태그
-> thead: 표의 헤더를 만들기 위한 태그
-> tbody: 표의 몸체를 만들기 위한 태그
-> tfoot: 표의 푸터를 만들기 위한 태그
-> tr: 표의 행을 생성하는 태그
-> th: 표의 제목 셀을 생성하는 태그(tr태그 내부에서 사용)
-> td: 표의 데이터 셀을 생성하는 태그(tr태그 내부에서 사용)

### th, td태그의 속성
- rowspan: 사용하는 행의 크기를 지정하는 속성(행 병합 효과)
- colspan: 사용하는 열의 크기를 지정하는 속성(열 병합 효과)

# 멀티미디어 관련 태그
### 이미지 태그(img)
- src: 이미지의 주소 지정
- alt: 이미지를 로드할 수 없을 경우 나오는 글자 지정
- width: 이미지의 너비 지정
- height: 이미지의 높이 지정

### 오디오 태그(audio)
- src: 음악 파일의 경로 지정
- preload: 음악을 재생하기 전에 모두 불러올지 지정
- autoplay: 자동 재생 여부 지정
- loop: 반복 재생 여부 지정
- controls: 음악 재생 도구 출력 여부 지정

### 비디오 태그(video)
- src: 동영상 파일의 경로 지정
- poster: 동영상 준비 중일 때의 이미지 파일의 경로 지정
- preload: 비디오를 재생하기 전에 모두 불러올지 지정
- autoplay: 자동 재생 여부 지정
- loop: 반복 재생 여부 지정
- controls: 동영상 재생 도구 출력 여부 지정
- width: 동영상의 너비 지정
- height: 동영상의 높이 지정