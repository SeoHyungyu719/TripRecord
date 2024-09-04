<h1 align="center">여행을 기록하다 - <img src="https://github.com/user-attachments/assets/699ccfe0-4f3e-4847-94d4-76ff5496b5c8" width="200" height="70"></h1>
믿을 수 있는 현지인의 추천지 : 믿을 수 있는 현지인의 추천과 일정을 짜주는 서비스를 제공하여 여행 계획에 대한 스트레스와 시간 소모를 줄일 수 있도록 하며,
현지인 판매자들은 추천일정 패키지를 등록 및 판매하여 수익이 창출 가능하며,
관광지역 커뮤니티로 다른 여행자들과 소통할 수 있다<br/>
<hr/>
<h1><img src="https://github.com/user-attachments/assets/b261889f-5430-4d63-8751-f92c12926fd9" width="50" height="50">&nbsp;&nbsp;&nbsp;&nbsp;목차</h1>
1.기술스택<br/><br/>
2.프로젝트 주요 기능<br/><br/>
3.ERD 설계도<br/><br/>
4.맡은 기능<br/><br/>
5.기능별 화면 소개<br/><br/>
<hr/>
<h1>1. 사용 기술 스택</h1>
<h3 align="center">>운영체제</h3>
  <div align="center">
    <img src="https://img.shields.io/badge/window 10-3A76F0?style=flat-square" height="25">
  </div>
<h3 align="center">>FrontEnd</h3>
  <div align="center">
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" height="25">
    <img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white" height="25">
    <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white" height="25">   
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white" height="25">
  </div>
<h3 align="center">>BackEnd</h3>
  <div align="center">
    <img src="https://img.shields.io/badge/java 17-4B4B77?style=flat-square" height="25">
    <img src="https://img.shields.io/badge/oracle sql-4479A1?style=for-the-badge&logo=mysql&logoColor=white" height="25">
  </div>
<h3 align="center">>FrameWork/Library</h3>
  <div align="center">
      <img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" height="25">
     <img src="https://img.shields.io/badge/myBatis-333333?style=flat-square" height="25">
    <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" height="25">
  </div>
<h3 align="center">>DataBase</h3>
  <div align="center">
      <img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white" height="25">
  </div>
<h3 align="center">>Tool</h3>
  <div align="center">
      <img src="https://img.shields.io/badge/sqlDeveloper-4479A1?style=flat-square" height="25">
  </div>
<h3 align="center">>WAS</h3>
  <div align="center">
       <img src="https://img.shields.io/badge/apachetomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=white" height="25">  
  </div>
<h3 align="center">>Collaboration</h3>
  <div align="center">
    <img src="https://img.shields.io/badge/googledrive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white" height="25">
    <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white" height="25">
    <img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" height="25">
    <img src="https://img.shields.io/badge/erdcloud-000000?style=flat-square" height="25">
  </div>
<hr/>
<h1>2. 프로젝트 주요 기능</h1>
<table align="center">
  <tbody>
    <tr>
      <td align="center">기능</td>
      <td align="center">설명</td>
    </tr>
    <tr>
      <td align="center">메인페이지</td>
      <td align="center">
        여행지 Top5 리스트 <br>
        플래너 Top5 리스트 <br>
        일정짜기 페이지 바로가기 <br>
        관광지 Top5 리스트 <br>
      </td>
    </tr>
    <tr>
      <td align="center">회원</td>
      <td align="center">
        로그인, 회원가입 <br>
        마이페이지 <br>
        회원정보 수정 <br>
        내 게시글 관리 <br>
        프로필 사진 기능 <br>
        포인트 결제 및 환불 <br>
        작성한 여행 계획 리스트 확인 및 상세 여행 계획 조회<br>
        결제한 플랜 확인 및 구매 확정 취소
      </td>
    </tr>
    <tr>
      <td align="center">플래너</td>
      <td align="center">
        지역별 플래너 리스트 확인<br>
        판매 수익 정산<br>
        플래너 프로필 수정<br>
        플래너 별점 리뷰 작성, 수정, 삭제<br>
        플래너 좋아요 기능<br>
        신청(판매) 내역 확인 및 신청 일정 생성,취소
      </td>
    </tr>
    <tr>
      <td align="center">여행 계획 생성</td>
      <td align="center">
        여행 일정 등록<br>
        원하는 해시태그로 여행 컨셉 선택<br>
        여행 지역 선택 및 등록<br>
        일자, 시간별 여행 계획 작성 및 수정, 삭제<br>
        상세 계획별 메모, 예약 여부 등록<br>
      </td>
    </tr>
    <tr>
      <td align="center">관광장소</td>
      <td align="center">
        여행지역 Top5 리스트<br>
        오픈API를 통한 관광지 검색<br>
        관광지 상세보기<br>
        관광지 리뷰작성, 수정, 삭제<br>
        관광지 별점 관리
      </td>
    </tr>
    <tr>
      <td align="center">게시판</td>
      <td align="center">
        카테고리별 게시글 목록 조회<br>
        카테고리별 게시글 작성, 수정, 삭제<br>
        댓글 작성, 수정, 삭제<br>
        게시글 검색<br>
        지역별 게시글 목록 조회
      </td>
    </tr>
    <tr>
      <td align="center">관리자</td>
      <td align="center">
          전체 통계 확인<br>
        회원관리<br>
        문의사항관리<br>
        등급 관리<br>
        공지사항 관리<br>
        포인트 관리<br>
        게시판 관리<br>
        해시태그 관리<br>
        UI 사진 관리<br>
        일정 관리<br>
        기타 관리<br>
      </td>
    </tr>
    <tr>
      <td align="center">기타기능</td>
      <td align="center">
        자동구매확정<br>
        자동구매 취소 및 환불<br>
        문자 안내 서비스<br>
        로그인시 신청 일정에 맞는 안내 팝업
      </td>
    </tr>
  </tbody>
</table>
<h1>3. ERD 설계도</h1>
<h3>>>ERD 바로가기 : https://www.erdcloud.com/d/RgkFD5yupCSJWcuzM</h3>
<img src="https://github.com/user-attachments/assets/9d2ca369-5d39-48c7-a5d0-6ad5bea8c12c">
<h1>4.맡은 기능</h1>
  <table align="center">
  <tbody>
    <tr>
      <td align="center">기능</td>
      <td align="center">설명</td>
      <td align="center">비고</td>
    </tr>
    <tr>
      <td>회원정보 수정</td>
      <td></td>
      <td>
      </td>
    </tr>
    <tr>
      <td>내 게시글 관리</td>
      <td></td>
      <t
      </td>
    </tr>
    <tr>
      <td>프로필 사진 기능</td>
      <td></td>
      <td>
      </td>
    </tr>
    <tr>
      <td>포인트 결제 및 환불</td>
      <td></td>
      <td>
      </td>
    </tr>   
     <tr>
      <td>플래너 프로필 수정</td>
      <td></td>
      <td>
      </td>
    </tr>
    <tr>
      <td>구매확정 내역 조회</td>
      <td></td>
      <td>
      </td>
    </tr>       
  </tbody>
</table> 







