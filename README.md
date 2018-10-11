# Ajax
<p>
   <h3>Ajax</h3>
   *function readMe(){} 
    readMe = function(){} 와 같은 함수는 <u>이름이 있는 함수</u>이다. <br>
   *function (response){}와 같은 함수는 이름이 없는 <strong>익명함수</strong>라고 한다. <br><br>
   
   Ajax에 사용되는 함수의 prameter값으로는 response 객체가 온다고 정의 되어있다.<br>
   <span style="color:blue;">
   fetch('html').then(callBackMe);<br>
      fetch('html').then(function(response){<br>
        console.log( response);<br>
      });
   </span><br><br>
   
   이경우, response객체가 console창에 출려된다. <br>
   status:200 이라는 말은 서버가 파일을 잘 찾아서 응답해줬다는 상태메세지.<br>
   status:404 라는 말은 파일을 찾지 못했다는 상태메세지.<br>
</p>

<p>
   <h3>fragment identifier</h3>
   북마크처럼 특정 tag에 id값을 지정하고, url뒤에 바로 #id값을 입력하면 웹페이지의 그 지점으로 한번에 이동한다.<br>
   ex. http://localhost:8080/hash.html#two<br>
   tag안에 내용은 조각을 의미하는 fragment라고 하고, id값은 fragement identifier라고 한다. <br>
   ex. #two라고 url뒤에 붙인 부분은 Ajax의 hash라고 부른다. <br><br>
</p>

<p>
   하지만, 검색엔진에 노출되지 않는 단점이 있기 때문에 현재는 사용하지 않는다. <br>
   대체제로 Pjax를 사용한다. <br>
</p>

<p>
   fetch API는 a mordern replacement for XMLHttpRequest이다. <br>
   can i use 사이트에서도 IE 11version을 제외하고는 모든 브라우저에서 쓸수 있는 미래지향적인 API이다.<br> 
</p>

<p>
   <h3>Polyfill</h3>
   버전이 맞지 않는 브라우저나, 구버전의 브라우저 모두 fatch를 사용 할 수 있도록 돕는 API.<br> 
   다운로드: https://github.com/github/fetch<br> 
   자신의 index.html이 있는 디렉토리(파일)에 넣는다.<br><br>
   
   그 후, 크롬 inspector에 가서 network를 통해 fatch.js가 잘 동작하는지 (status:200) 확인하자. <br>
</p>
