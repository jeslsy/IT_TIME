# IT_TIME

## 프로젝트 소개
> IT TIME은 IT정보공학과 학생들 간의 정보를 공유하는 사이트로 자유게시판에서 학교나 학과의 정보를 자유롭게 공유할 수 있으며, 강의 평가 게시판에는 IT정보공학과 수업에 대한 평가를 남겨 수업 정보를 공유할 수 있다. 또 공지사항 페이지에는 IT정보공학과 홈페이지의 최근 공지사항을 크롤링해서 보여주어 학과 공지사항을 쉽게 확인할 수 있으며 제목으로 원하는 공지사항을 검색하여 볼 수 있다. 

## 개발 배경
> 1. 운영체제, 데이터베이스, 컴퓨터 구조, 컴퓨터 네트워크, 프로그래밍 언어 등 이론적인 학교 교육과정 과목 이외에 실용성을 요구하는 웹 개발을 공부할 필요성이 있었다. 웹 개발은 주로 python을 이용한 장고, javascript를 이용한 node.js로 나뉘는데 최근에 학습했던 javascript 언어를 이용하고자 node.js 소프트웨어 플랫폼을 활용해 개발하였다.
> 2. 학생으로서 가장 필요하고 자주 접하는 학과 사이트를 만들어 보고자 했다. 첫 개발 시도이므로 ‘학교 사이트 만들기’와 같이 예제가 많은 주제를 선택하게 되었으며, 필요에 따라 기존의 사이트 기능에서 추가로 기능을 더해 실제 학생 친구들이 편리하게 사용할 수 있도록 만들고자 하였다.   

## 기대 효과
> 저희가 자주 사용하는 학과 사이트에 여러 부가 기능들을 더하여 해당 사이트를 이용하는 학생들이 더욱 편리하게 이용하도록 하는 것이 최종목표였습니다. 
기존의 학과 사이트에 질문게시판과 강의 평가 게시판을 추가하여 여러 사이트들을 둘러볼 필요 없이 한 사이트 안에서 정보를 얻을 수 있도록 편리성을 높였습니다. 
추후, 해당 사이트에 더 많은 기능을 추가한다면 시간을 낭비하지 않고 학과에 대한 정보를 쉽게 얻을 수 있을 것 입니다. 

## 느낀 점 
> 1. 개발에 대한 디딤돌 역할 
    - 개발이라는 분야에 대해 처음으로 직접 작성해봄으로써 이론으로만 접했던 컴퓨
      터 전공 지식이 실제 프로그램에 어떻게 적용되는지 확인하여 응용력을 키울 수 
      있었다.
> 2. 전반적인 이해
    - 각 페이지에 대한 세부적인 부분까지 개발하지는 못했지만, 웹 개발에 대한 전
      반적인 흐름과 큰 틀에서의 구조를 확인함으로써 웹 개발에 대한 이해도를 높일 
      수 있었다. 
> 3. 아쉬운 점, 더 공부가 필요한 부분을 확인 
    - 프로그램을 작성하면서 이론적인 부분이나 흐름을 인지하고 습득하지 못한 부분
      을 확인하여 추가로 학습하여 앞으로 개발프로젝트를 위해 대비할 수 있게 되었
      다.
      
## 진행 과정
> 1) 계획 및 학습
>   - html/css, nodejs 등 생활코딩 영상으로 학습하기
>   - 게시판 만들기 예제로 기본기 다지기
> 2) 개발
>   - 기본 틀이 되는 화면 레이아웃 html/css로 작성하기
>   - 표지화면, 질문 게시판, 강의평가 게시판, 공지사항으로 나누어 개발 진행
> 3) 마무리
>   - html/css 다듬기
>   - 최종발표 및 최종보고서 작성  
 
## 세부 기능 설명
> ### 홈 화면 
>> 웹페이지의 시작화면은 전북대학교 사진을 출력하고 있다. 
>>
>> ![image](https://user-images.githubusercontent.com/60471550/105709652-5c49ca80-5f59-11eb-9d7f-070157565e83.png)

> ### 질문 게시판 화면
>> 질문 게시판과 강의 평가 게시판 중 질문 게시판 목록을 보여주는 페이지이다. 
>> 1) 글쓰기 버튼을 클릭하여 게시판에 글을 작성할 수 있다. 
>> 2) 게시판에 작성된 글을 10개씩 나누어 페이지에 출력한다. [1] 페이지의 글을 읽으면 URL이 localhost:3000/Q&ABoard/page_q&a_board/1가 되고, [2] 페이지의 글을 읽으면 localhost:3000/Q&Aboard/page_q&a_board/2로 변화하는 것을 살펴 볼 수 있다. 
>> 3) 작성된 글의 제목, 작성자, 작성한 날자, 조회수를 볼 수 있다.
>>
>> ![image](https://user-images.githubusercontent.com/60471550/105709870-a632b080-5f59-11eb-9afb-602397330d0b.png)

> ### 질문 게시판 글쓰기 화면
>> 목록에서 글쓰기 버튼을 클릭하여 글 제목, 작성자, 내용과 글 수정 및 삭제를 위한 패스워드를 입력하여 글을 작성한다. 
>>
>> ![image](https://user-images.githubusercontent.com/60471550/105710048-e8f48880-5f59-11eb-81d6-76f444f32f33.png)


> ### 질문 게시판 글 상세 화면
>> 질문 게시판의 글을 클릭하여 글의 내용을 상세하게 확인 할 수 있다. 
>> 1) 작성할 때 입력한 패스워드를 정확히 입력하고 글 삭제 버튼을 클릭하여 글을 삭제 할 수 있다.
>> 2) 작성할 때 입력한 패스워드를 정확히 입력하고 내용을 수정한 후 글 수정 버튼을 클릭하여 글을 수정할 수 있다. 
>>
>> ![image](https://user-images.githubusercontent.com/60471550/105710082-f7db3b00-5f59-11eb-85d1-869d1521fd40.png)

> ### 강의 평가 게시판
>> 질문 게시판과 강의 평가 게시판 중 강의 평가 게시판 목록을 보여주는 페이지이다. 질문 게시판과 동일한 기능을 가지고 있으며, 작성된 글의 과목명, 교수명, 작성된 날짜, 별로 표현된 평가 점수가 출력되고 있다. 
>>
>> ![image](https://user-images.githubusercontent.com/60471550/105710227-26591600-5f5a-11eb-9c10-fb34848ce1eb.png)

> ### 강의 평가 게시판 글쓰기
>> 목록에서 글쓰기 버튼을 클릭해 평가할 강의의 교수, 과목명, 평가점수(1점에서 5점까지 존재), 내용, 글 삭제 및 수정을 위한 패스워드를 입력할 수 있다.
>>
>> ![image](https://user-images.githubusercontent.com/60471550/105710343-51dc0080-5f5a-11eb-85a3-7201728328e7.png)

> ### 강의 평가 게시판 글 상세 화면
>> 강의 평가 게시판의 글을 클릭하여 평가 내용을 상세하게 확인 할 수 있다. 
>> 1) 작성할 때 입력한 패스워드를 정확히 입력하고 평가삭제 버튼을 클릭하여 평가를 삭제 할 수 있다.
>> 2) 작성할 때 입력한 패스워드를 정확히 입력하고 내용을 수정한 후 평가수정 버튼을 클릭하여 평가를 수정할 수 있다. 
>>
>> ![image](https://user-images.githubusercontent.com/60471550/105710507-910a5180-5f5a-11eb-8b21-16228d9666d1.png)

> ### 공지사항 페이지
>> IT정보공학과 홈페이지의 공지사항을 크롤링하여 개발한 웹페이지에서도 확인 할 수 있는 페이지이다.
>> 1) 공지의 제목과 작성된 날짜를 확인 할 수 있다. 
>> 2) 검색을 통해 원하는 문자가 포함된 제목의 공지를 볼 수 있다. 
>>
>> ![image](https://user-images.githubusercontent.com/60471550/105710625-b39c6a80-5f5a-11eb-83dd-9df2877a2f45.png)

> ### 공지사항 상세 페이지
>> 원하는 공지를 클릭하면 다음과 같이 상세한 공지사항 내용을 IT정보공학과 홈페이지를 통해 전달받을 수 있다. 
>>
>> ![image](https://user-images.githubusercontent.com/60471550/105710690-cc0c8500-5f5a-11eb-883f-e25d588a2eb1.png)




