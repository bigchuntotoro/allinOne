1. maria pom.xml 추가

2. KISA 검증 (2019년 11월) - 중요정보 암호화


Globals.mysql.Password 는 com01 을 암호화한 것으로 https://www.egovframe.go.kr/wiki/doku.php?id=egovframework:rte2:fdl:crypto_simplify_v3_8 참조할 것


Globals.mysql.Password = com01 처럼 평문을 사용하려면 context-crypto.xml 에서 initial="false" crypto="false" 로 설정하고, 


context-datasource.xml 에서 Globals.mysql.Password}"/> 로 바꾸어 주어야 함

3. 프로젝트명 설정 일치 시켜주기

   
프로젝트 명을 eGove_one이라고 지정하였으므로 일치시켜주어야 합니다.



ctrl + H 를 눌러서 egovframework-all-in-one 를 검색합니다.

4. 프로젝트 우클릭 -> Run As -> Maven Install
