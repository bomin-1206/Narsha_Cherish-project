# Narsha_Cherish-project

개발관련 자료

--- 사이트 기능 정리
메인페이지 : 검색기능, 공지사항(사이트)
회원가입 / 로그인 / 회원정보수정 / 회원정보확인 / 로그아웃 / 회원탈퇴 / 비밀번호 찾기 / 아이디 찾기 / 카카오톡 연동하기
(금액) 기부 : 기부할 곳을 검색 -> 기관정보 확인 -> 기부할 금액 결정 -> 자동이체 신청 -> 
기부 받은 단체 : 단체정보(주소, 전화번호, 대표자명...), 기부한 사람 명단보기, 기부된 금액, 계좌관리(등록, 삭제 등등), 기부 내역 공개, 최저 금액 지정, 공지사항(단체별)
검색기능 : 카테고리별 검색 가능, 단체이름을 직접 입력 검색, 대기관별 작은 기관 검색 및 카테고리도 출력, 
(물품) 기부 : 기부할 곳을 검색 -> 기관정보 확인 -> 기부할 물품 목록 작성 -> 물품 전달 방법 확인(직접 방문 또는 수거)
사용방법 안내 레이어 : 기부페이지 등등
문의 : 개인별문의(기관이나 웹사이트측에 문의 후 기관 담당자나 웹사이트 운영자가 답변)

---- 사이트맵
메인페이지 : 검색기능, 공지사항(사이트에서 공지사항), 회원가입, 로그인, 로그아웃, 마이페이지
회원가입 : 개인 또는 단체로 구분해서 회원가입하도록 / 아이디, 패스워드, 이름, 이메일, 전화번호, 아이디 중복검사, 회원가입버튼/ 취소 / 카카오톡연동하기
로그인 : 아이디, 패스워드 / 로그인 / 아이디 찾기 / 비번찾기 / 카카오톡으로 로그인하기 / 취소
마이페이지 : 회원정보수정(아이디 제외), 취소 / 회원탈퇴 / 로그아웃 / 
기부 받을 단체 – 회원가입 : 한국명, 영문명, 전화번호, 주소, 대표자명, 사업자등록번호, 아이디, 패스워드, 카테고리 입력가능(최대 3개까지 입력가능하게)
기부 받을 단체 마이페이지 – 회원정보수정 : 수정가능(대표자명, 주소, 전화번호, 패스워드) 수정불가능(아이디, 사업자등록번호, 한국명, 영문명) / 계좌번호, 은행명, 예금주명 / 기부 만들기(소개, 정보, 최소기부금액, 기부될 곳의 정보, 카테고리 지정, 금액 또는 물품 기부를 선택할 수 있도록) / 
기부 받을 단체 – 로그인 : 
검색 : 카테고리(사이트에서 카테고리를 선택할 수 있게 해주면, 단체가 가입할 때 선택할 수 있도록), 단체이름 선택가능
카테고리별 검색 결과 : 해당 카테고리로 기부를 생성한 모든 기부들을 보여준다. / 특정 기부를 선택하면 기부상세페이지로 이동해서 기부를 할 수 있다.
단체명으로 검색 결과 : 해당 단체에서 생성한 기부가 있으면 단체정보와 생성한 기부가 있으면 기부 정보를 표시, 없으면 단체 정보만
기부만들기(금액) : 기부_idx(Primary key), 해당 단체 g_idx(Foreign Key), 기부에 대한 정보 입력, 기부이름, 최소기부금액, 은행명, 계좌번호, 예금주, 관련 이미지(3개) 업로드한 주소(3대), 코멘트작성, 댓글, 카테고리(3개)
기부만들기(물품)
기부상세페이지 - 금액: 단체정보, 관련 이미지, 현재까지 기부된 금액, 계좌정보, 예금주, 최소기부금액, 무조건 단건으로 처리, 정기후원 아님, 코멘트 작성과 하나의 댓글 (크라우드펀딩 벤치마킹 해야 할 듯)
기부상세페이지 – 물품 : 단체정보, 관련 이미지, 기부 받고 싶은 물품 목록, 현재까지 기부된 물품 목록, 직접 방문 기부, 단체에서 수거 기부, 택배로 기부(기부 방법 선택할 수 있도록), 개인이 기부할 물품 목록 작성하기, 단체에서 필요한 물품 기부를 승인할 수 있도록, 주의사항도 꼭 올려야 한다.(기부가 거절될 수 있다는 공지 등)
사용방법 안내 레이어 : 회원가입 후 첫 번째 로그인하면 띄워줌
문의 : 웹사이트에서 문의할 경우 메인페이지 등에 노출해서 사이트측에 문의하고, 각 단체별 문의사항은 단체 정보 페이지에서 개별 문의가 가능하도록 하고, 단체별 마이페이지에서 해당 문의사항을 처리할 수 있도록 해준다.
