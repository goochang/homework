# 메라키 플레이스 과제 전형

## 기능 목록
### 헤더
- [x] 헤더 표시
- [x] 헤더 클릭시 팝업 표시
- [x] 헤더 팝업 UI 표시
- [x] 헤더 팝업 datepicker 표시
- [x] 헤더 팝업 검색(필터 적용)
- [x] 필터에 따른 헤더 표시
- [ ] 팝업 텍스트 입력값 체크

### 메인
- [x] 헤드라인 목록 표시
- [x] 무한스크롤
- [x] 스크랩 및 취소 기능
- [ ] 스크랩 및 취소시 시스템 메시지 표시
- [x] 스크랩 탭 표시(탭 데이터 별개)
- [x] 스크랩된 데이터 유지
- [ ] 스크랩 필터링

### 푸터
- [x] 푸터 표시(아이콘 활성화)

### 추가
- [ ] 헤더 및 메인 헤드라인 텍스트 길때 예외처리
- [x] 검색후 무한스크롤시 필터링 유지
- [ ] 스크랩탭 무한스크롤
- [ ] 기사 클릭시 이동

## 헤맨부분
1. 팝업창에서 텍스트를 입력할때 한번입력하면 input focus가 풀려서 연속적으로 입력이 안되는 문제가 생겻는데
Popup컴포넌트 내부에 선언된 styled-component가 리렌더링돼서 문제가 되는걸로 확인됨.

2. nyt api 예시를 찾아보려고 했는데 검색결과가 많이 없어서
챗gpt를 활용했다.

3. 테스트를 많이 하다보니 429에러가 나서 어려움이 있었다.
