### Django Mahjong Site 🀄️
- 장고와 vue를 사용한 마작 정보 사이트
- 장고 실습 및 vue를 사용한 프로젝트로 제작해 보고자 함
- 처음엔 구름 쓰려다가 로컬 환경에서 제작하기로 함. 아무래도 이 쪽이 더 편하다.
- 프로젝트 시작일 : 21년 7월 11일

##### 210712 (월)
- 가상환경 실행 : `source myvenv/bin/activate`
- 데이터 베이스는 sqlite3로 미리 설정 되어 있음 -> 데이터 베이스 설치 : `python manage.py migrate`
- 포트 변경 매번 수동으로 해줘야 하는듯 `python manage.py runserver 8080`

##### 210713 (화)
- 앱 이름으로 main 같은 흔한 이름 썼다가 `ModuleNotFoundError` 에러만남. 앞으론 흔하지 않은 이름을 사용하도록 하겠음