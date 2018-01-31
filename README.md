
<body>
  <style>
a {color:red;}
  </style>
  
  
<h1> HTML TAG에 대한 정리</h1>
<ol>
<li> (!--...--) </li>
     -주석을 달다.
<br> ex) <!--.이건 안 읽는 건가 보네..-->  앞에 글자가 안보이게 하네
<li> (!doctype) </li>
-문서의 형식을 결정한다
<br> ex) 생략!
<li> (a href="#""/a)  </li>
 - 링크를 추가한다.
<br> ex) <a href="https://www.naver.com">네이버</a>
<li> (abbr) </li>
 - 밑에 점선 표시되면서 .... 갇다되면 주석을 알 수 가 있다. 신기 방기
<br>  ex) The <abbr title="World Health Organization">WHO</abbr> was founded in 1948
<li> (address) </li>
    -문서의 소유자를 자장한다. 멀까?
<br> ex)<address>(address)
저자 <a href="ajalskdjf@naver.com">훈남</a>.<br>
방문시 이메일로 연락을 부탁드립니다.:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
<br> #무쓸모느낌
(/address)</address>
<li> (head) </li>
 - 문서의 정보를 결정한다.
<br> 에를 들 수 없다. 걍 검색엔진이 가장 먼저 읽는 거라고 해야되나?
<li> (body) </li>
- 문서의 몸통
<li> (html) </li>
<br> 문서형식을 결정
<br> ex)
<li> (title) </li>
head와 타이틀의 차이는 뭠미
<br> ex) head안에 이것을 정의하는 것이군.
<li> (meta) </li>
-meta
<br> ex)
  (meta name="viewport" content="width=device-width, initial-scale=1.0")
  (meta charset = "UTF-8")
  -메타 요소는 일반적으로 페이지 설명, 키워드, 문서의 작성자, 마지막으로 수정 된 항목 및 기타 메타 데이터를 지정하는 데 사용됩니다.
  -메타 데이터는 브라우저 (내용 표시 또는 페이지 재로드 방법), 검색 엔진 (키워드) 또는 기타 웹 서비스에서 사용할 수 있습니다.
-즉 어떤 기술들을 불러오기 위해 사용한다는 건데
<li> (div) </li>
 -css형식을 지정하는데 사용하거나 그렇다는데 예를 살펴보니 영역에서 글씨 스타일을 확 바꾸는데 사용되네
<br> ex)<div style="color:#0000FF">
  <h3>This is a heading</h3>
  <p>This is a paragraph.</p>
</div>
<li> (a) </li>
-a 는 링크를 쓸때 사용된다
<br> ex) (a href = "https://www.naver.com">naver(/a
<br> <a href = "https://www.naver.com">naver</a>
<li> (script) </li>
-java script를 이용하기 위해 사용.
<br> ex)(script)
document.getElementById("demo").innerHTML = "Hello JavaScript!";
()/script)
<li> (link) </li>
- 멀까?
<br> ex)
  (link rel="stylesheet" type="text/css" href="theme.css")
<br> -link 태그는 문서와 외부 리소스 간의 링크를 정의합니다.
<br> -link 태그는 외부 스타일 시트에 연결하는 데 사용됩니다.
<br> <h3>이해가 안되네 나중에 이해하는 걸로 해보자</h3>
<li> (img) </li>
역시 가장 많이 쓰이는 img인데 형식은 보면 (img)
(img src="smiley.gif" alt="Smiley face" height="42" width="42")
<br> ex)<br> <img src="teddy.jpg" alt="겨울그림" height="100" width="100">
<li> (p) </li>
 - 문단에 대해 정의한다는 건데 많이 쓰이네
<br> ex)<p>This is some text in a paragraph.</p>
<li> (span) </li>
- 문서의 속성을 바꾸는데 사용하네
<br> ex)<p>My mother has <span style="color:blue">blue</span> eyes.</p>
<li> (li) </li>
-목차를 쓰는 데 사용된다.
<br> ex) 생략
<li> (ul, ol) </li>
- li tag의 어머니격 ol은 숫자 , ul 앞에 동그라미가 표현된다.
<br> ex)
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
<li> (br) </li>
- enter
<br> ex) 생략
<li> (style) </li>
- 문서 스타일 정보를 정의합니다. style 만 사용하면 head안에 넣어서 사용해야 지정하는데
<br> ex) (style)
h1 {color:red;}
p {color:blue;}
()/style)
<h1>A heading</h1>
<p>A paragraph.</p>
정의를 해서 이 형식을 사용하면 전체적인 글 모양이 바뀐다. 그래도 span을 사용하는게 지금은 편리하네
<li> (input) </li>
 (input) 태그는 사용자가 데이터를 입력 할 수있는 입력 필드를 지정합니다.
<br>(input) 요소는 사용자가 데이터를 입력 할 수있는 입력 컨트롤을 선언하기 위해 (form) 요소 내에서 사용됩니다.

입력 필드는 유형 속성에 따라 다양한 f}으로 다양합니다.
 - (form action="/action_page.php")
  First name: (input type="text" name="fname")<br>
  Last name: (input type="text" name="lname")<br>
  (input type="submit" value="Submit")
(/form)
ex)<form action="/action_page.php">
  First name: <input type="text" name="fname"><br>
  Last name: <input type="text" name="lname"><br>
  <input type="submit" value="Submit">
</form>
<li> (form) </li>
-input과 같이 쓰는것 같은데, html 양식을 설정하는데
<br> ex) 위에 똑같으니 생략
<li> () </li>
-strong 태그는 구문 태그입니다. 중요한 텍스트를 정의합니다.<br>
팁 :이 태그는 더 이상 사용되지 않지만 CSS를 사용하면 더 많은 효과를 얻을 수 있습니다.
<br> ex) <strong>Strong text</strong>
<li> (table) </li>
- table 밑에 tr, th, td  요소를 결정하는데 tr은 행을 정의하고 th 테이블 헤더를 정희하고 td 는 테이블 셀을 정의한다.
<br>
테이블 레이아웃에 테이블을 사용해서는 안됩니다! 역사적으로 일부 웹 제작자는 페이지 레이아웃을 제어하는 ​​방법으로 HTML 표를 잘못 사용했습니다. 그러나 레이아웃을 위해 주로 CSS를 사용하여 HTML 표를 사용하는 다양한 방법이 있습니다.
<br> 더욱 다양한 요소가 있는데 생략<br>
 ex)
<iframe width="560" height="315" src="https://www.youtube.com/embed/A-tKo96ays8" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe>
</body>
</html>
