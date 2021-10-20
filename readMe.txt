[헤리터 쇼핑몰 갤러리 리스트 게시판]

1. 사이트URL
https://heriter.co.kr/category/all/44/

2. 작업내용
 1) 갤러리 리스트 페이지의
     작업구간을 동일하게 구현합니다.
 2) 로고영역 헤더와 갤러리리스트만 구현합니다.
 3) 로고영역 헤더는 아래로 스크롤할 때 
    함께 아래로 이동합니다.

3. 작업에 관련된 자료는 개발자도구를 활용합니다.

4. 홈디렉토리, 폴더, 파일 및 기타 작업관련내용은 
   작업자가 임의판단하여 제작합니다.


내용 끝.



---------------------------------------------------------


홈디렉토리 => 
D:\JSP_BigData_0616\zzupd\ex\bbs
   \p02_GalleryBBS
html파일 => /bbs/gallery.html
css파일 => /style/style.css
                       /style_Reset.css
script파일 => /script/jquery-3.6.0.min.js
                           /script.js
images파일 => /images



Josefin Sans
Jost


---------------------------------------------
[형상관리]
=> 버전(Version) 관리

CVS, Git(깃)
=> 히스토리를 관리할 수 있다.


임의의 파일  2021.10.18. 19:59:20
test.txt         내용 => test

해당 임의의 파일  2021.10.18. 20:03:16
test.txt         내용 => test
                              가나다

해당 임의의 파일  2021.10.19. 15:47:07
test.txt         내용 => 123
                              Sample
결국엔 최종 결과만 남아있음.
즉 과정에 대한 프로그램 제작단계가
기록되어 있지 않음




형상관리 프로그램 => 깃(Git)
프로그램 형상관리 저장 => 깃허브(Github)


git 다운로드 URL
https://www.git-scm.com

GNU (그누, 누) : 무료 라이센스, 오픈 소스
                     라이브러리, 실제 코드,
                     수정, 배포, 사용 무료
                      -------------------------
                       임의 수정하거나 또는
                       그대로 판매 불가


MINGW64, MINGW32
밍위, 밍더블유, 민지


Join (회원가입)    =>   Sign UP
LogIn  (로그인)   =>    Sign IN


사용자 이름 = 깃허브 ID
user.name  =>  zzupd

사용자 이메일 =깃허브 Email
user.email  => zzupd@naver.com


[본인의 컴퓨터 시작버튼 => 
 깃배쉬(Git-Bash)에서
 사용자 이름, 사용자 이메일 전역 등록]

1. 사용자 등록
git config --global user.name 본인의ID
2. 이메일 등록
git config --global user.email 본인의Email


[깃허브 사이트에서 인증용 토큰 발급받기]
1. 로그인
2. 우측 상단 [마이페이지] 아이콘 클릭
    => [Settings] 항목 클릭
3. [Public profile] 페이지 왼쪽에 있는
   [본인아이디 Your personal account] 메뉴
   하단에 있는 [Developer settings] 항목 클릭
4. [GitHub Apps] 페이지 왼쪽에 있는
   [Personal access tokens] 항목 클릭
5. [Personal access tokens] 페이지에서
   오른쪽 [Generate new token] 버튼 클릭
6. [New personal access token] 페이지
   1) Note => 토큰 이름 설정.
                   본인이 알 수 있는 
                    임의의 이름 설정
         보기.  A_B_C_D
             A : 토큰만든 사람
             B : 생성날짜
             C : 업무명 또는 팀명
             D : 기타 작성내용(선택사항)
        =>   zzupd_211018_Silsp_개인인증토큰

   2) Expiration(엑스퍼레이션) => 만료일
                                        (= 유효기간)
         => 원하는 날짜 선택
  
   3) Select scopes (셀렉트 스쿱스)
                    => 허용 범위, 허용 대상
                 (인증 토큰으로 
                  접속할 수 있는 항목 지정)
                   
          => repo  (리파지터리, 리포지터리,
                        저장소) 만 선택                      

    1)~3) 입력 후 아래쪽에 있는 
      [Generate token] 버튼 클릭

7. [Personal access tokens] 페이지에서
   생성된 토큰 확인
   => 추후 삭제하고 새롭게 만들 수 있음
  
본인 토큰 보관
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


여기까지 깃으로 깃허브를 사용하기위한 공통사항
-------------------------------------------------------


[깃을 사용한 깃허브에 형상관리 과정]
                              ---------------
                            = 인터넷 저장소에서 
                               버전별 저장 및 관리

1. 깃허브에서 저장소 생성
                  --------
                 Repository, 리포지터리, 리파지터리

   1) 로그인 상태에서 우측 상단 
       [마이페이지]아이콘 클릭
   2) [Your repositories] 항목 클릭
   3) 우측 상단 [New] 녹색 버튼 클릭
   4) Create a new repository
      (신규 저장소 생성)
       (1) Repository name
             => 한글안됨, 공백안됨
               가급적 영어,숫자,밑줄로 구성하여 만듬
           형식 => 날짜_실습명   또는
                       날짜_작업명  또는
                       날짜_프로젝트명 으로 작성함.
                        단, 본인이 원하는대로 
                            임의변경가능 
        (2) Description (optional)
             설명, 선택사항이므로 입력안해도 무관        
        (3) 저장소 사용 허가 범위
            Public / Private
           공용(누구나)    나만(개인용)
     5) [Create repository] 버튼 클릭       

------------------------------------------------------

#wrap => 폭 1000 
                                                이미지 최종크기
이미지 크기 => 818x900               320
     img요소의 width속성 => 320
상품 1개 표시영역 => 320X480

320 * 3 => 960





------------------------------------------

[천단위 구분]

    let money = 1234567890;   //   10억 => 1,234,567,890  
    console.log(typeof money);   
    let res = money.toLocaleString();  // 숫자형 자료에만 천단위 구분이 적용됨
                                                      // 문자형 자료에는 안됨!                 
    console.log("res : " + res);
    let resFeedBack = res.replace(/,/g, "");

    console.log("resFeedBack : " + resFeedBack);


--------------------------------------------------


  <table class="goodsTbl">
                <tbody>
                    <tr>
                        <td>
                            <img src="../images/goods01.jpg" alt="상품이미지1" 
                               width="320">
                        </td>
                        <!-- 상품이미지 -->
                    </tr>
                    <tr>
                        <td class="goodsName">헤리터 시그니처 칼도마세트 (월넛)</td>
                        <!-- 상품명 -->
                    </tr>
                    <tr>
                        <td class="goodsDesc">월넛 색상의 해리터 식과도&도마 세트</td>
                        <!-- 상품설명 goods Describe -->
                    </tr>
                    <tr>
                        <td class="goodsPrice">
                            <span class="basicPrice numComma">355000</span>
                            <!-- 기본판매가격  numComma : 천단위 구분 쉼표 -->
                            <span class="salePrice numComma">298000</span> 
                            <!-- 할인가격 -->
                        </td>
                    </tr>
                    <tr>
                        <td><span class="replyCnt numComma">0</span></td>
                        <!-- 댓글 수 -->
                    </tr>
                </tbody>
            </table> 

-----------------------------------------------------------



[
["goods01.jpg", "헤리터 시그니처 칼도마세트 (월넛)",
"월넛 색상의 헤리터 식과도&도마 세트",
355000, 298000, 5487],

["goods02.jpg", "헤리터 시그니처 칼도마세트 (하드메이플)",
"하드메이플 색상의 헤리터 식과도&도마 세트",
355000, 288000, 243],

["goods03.png", "헤리터 칼 3종 세트",
"", 278000, 228000, 2054],

["goods04.jpg", "헤리터 칼 2종 세트",
"주방용 식도 + 과도",
118000, 99000, 3148],

["goods05.jpg", "헤리터 비건 에이프런",
"자체개발 페브릭 앞치마",
99000, 69000, 159],

["goods06.png", "STANDARD CHINA 160"
"헤리터 중식도", 160000, 139000, 151],

["goods07.png", "헤리터 시그니처 팔각도마",
"도마 + 도마프레임 + 칼블럭",
237000, 206000, 1535],

["goods08.jpg", "헤리터 키친 크로스 SET",
"강화에서 온 소창행주",
26000, 26000, 388],

["goods09.png", "STANDARD 180(7\")",
"주방용 식도"
79000, 79000, 1731],

["goods10.jpg", "STANDARD 106(4\")"
"주방용 과도",
39000, 39000, 160"],

["goods11.png", "우드그레인 키친트레이",
"", 39000, 35000, 2],

["goods12.png", "차콜스톤 워싱바", "",
29700, 26800, 8]
]




 











