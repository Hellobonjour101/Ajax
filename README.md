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
