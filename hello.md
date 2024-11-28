# hello git

## git 명령어 요약

- clone : 원격 저장소 복사
- add : 스테이지 영역에 작업 파일 추가
- commit: 세이브, 스테이지 영역의 파일들을 가지고 커밋(=세이브) 를 만들 수 있다.
- push : 원격 저장소에 커밋을 업로드한다.

## 파일의 내용 되돌리기

- 코드 뭉치 버리기 : 특정 파일의 내용을 마지막 커밋으로 돌리고 싶다면 해당 파일 선택 후 `코드 뭉치 버리기` 선택.

## 브랜치 변경하기

- 브랜치란: 기존 내용을 유지한 채 새로운 내용을 추가하고 싶을 때 사용.
- 체크아웃: 특정 브랜치(혹은 커밋) 으로 돌아가고 싶을 때 사용.
- 소스트리의 체크아웃: 브랜치 이름을 더블 클릭하는 것 만으로 체크아웃.

## 병합하기 1

- 헤드 브랜치에 변경사항이 없고
- 병합 대상 브랜치가 헤드로 부터 시작된 경우
- 아주 쉽게 병합 가능 = Fast-forward

## 병합하기 2
- 헤드 브랜치에 추가적인 커밋이 생기는 경우
- 진짜 병합이 필요해 진다.
- 충돌이 나지 않으면 좋지만, 충돌이 나도 겁내지 말자.