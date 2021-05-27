# melon2vibe
[melon](https://www.melon.com/) 음원 스트리밍 사이트의 좋아요 목록을 [Vibe](https://vibe.naver.com/)로 옮겨주는 툴

selenium을 이용하여 크롤링 하였음

melonCrawl.py를 이용하여 음원 목록을 musicList.txt 파일로 로컬에 생성한 후에, vibeAdd.py를 이용하여 다시 vibe에 추가하는 방식을 채택함.

중간에 오류가 나는 음원은 따로 errorList2.txt 파일을 생성하여 사용자가 검토할 수 있게끔 함.

추후에 각종 음원 스트리밍 사이트 간의 좋아요 리스트 동기화를 위한 프로젝트 구상중
