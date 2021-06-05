# Mobee

5월 27일: 프로젝트 제출



프로젝트 제출 후 아쉬웠던 점들을 정리 후 수정 및 보완, 추가하고 싶은 기능들을 추가해 보고자 한다.



### 기능

- 좋아요 기능: 리뷰 및 댓글에 좋아요 기능
  - 좋아요 순으로 표출
- 팔로우 기능
  - 프로필 페이지 추가
    - 유저가 남긴 리뷰와 댓글에서 프로필로 이동할 수 있는 기능 추가
    - 리뷰, 댓글 모아보기
      - 리뷰, 댓글 모아보기 권한 설정하기 (공개, 나를 팔로우, 서로 팔로우)
- 영화 카드에 마우스 호버시 추가적인 정보 표출



### 내부 로직

- cdn 대신 django의 static 파일로 관리하기
- 새로고침 시 페이지 오류 수정
- 현재 영화를 받아오는 방법: django에 url를 만들어두어 해당 url로 요청을 보내야 함
  - 다르게 하는 방법?
- TMDB에서 받아온 정보 내부의 별점 정보를 보여주는데, Mobee 사이트 내부 평점 표시
  - 해당 로직 최적화; 미리 계산된 값을 저장하면 요청마다 쿼리할 필요가 없지 않을까



### 계획

7월부터는 새로이 프로젝트에 참여해야 하므로 6월 중으로 시간이 되는 대로 하나씩 도전!

수정한 부분들은 기록을 남겨보자.
