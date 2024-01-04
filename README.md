WORK SPACE 프로젝트
======================================
결재 시스템/게시판 시스템 그룹웨어
-------------------------------------
개발 기간 2023/12/12 - 2024/01/04
-------------------------------------

## 핵심 기능
- 로그인      : 해당 세션이 유지되는 동안 로그인 사용 기능
- 검색        : 서류와 게시판 각각 검색 가능
- 기안 작성   : 결재라인 선택, 첨부파일 업로드
- 내 결재함   : 로그인한 유저가 작성한 문서만 조회 가능, 페이지네이션
- 진행 결재함 : 현재 결재 상태가 진행중인 서류 중 해당 결재라인에 해당하는 담당자와 다음 결재자에게만 표시, 페이지네이션
- 반려 결재함 : 서류가 반려될 시 최초 작성자에게만 반려 사항이 보여짐, 페이지네이션
- 완료 결재함 : 해당 결재라인의 모두가 완료된 결재서류를 열람 가능, 페이지네이션
- 게시판      : 사용자들이 자유롭게 작성 가능한 사내 게시판
- 내 게시글   : 로그인한 유저의 게시글만 보임
- 휴지통      : 결재가 완료된 결재서류만 삭제/복원 기능, 페이지네이션

## 서류 조회
- 해당 서류가 진행중인 결재라인의 담당자 이름 상황 표시
- 해당 서류의 첨부파일 다운로드/수정/삭제 기능
- 결재 승인/반려/의견작성(반려시) 버튼
- 수정버튼   : 결재라인이 작성자일때, 반려가 아닐때 활성화
- 휴지통이동 : 해당 작성자이거나 진행중이 아닐때 활성화
- 반려시 의견작성한 내용 함께 표시

----------------------------------------
# 담당 작업 내용
- Front : 헤더/사이더, 결재함 전반
- Back : 문서 조회, 결재함 상태/사용자별 조회, 검색, 첨부파일 업로드/다운로드, 페이지네이션
