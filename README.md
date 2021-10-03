# Welcome-to-Hyewon-web
First new repository
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to Hyewon's Web</title>
</head>
<body>
    <header>
        <img src="./images/logo.jpg" alt="logo">
        <h1>Hyewon Site</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="profile">profile</a></li>
            <li><a href="portfolio">portfolio</a></li>
            <li><a href="contact">contact</a></li>
        </ul>
    </nav>
    <section>
        <div id="photo">
            <img src="./images/bigdata.jpg" alt="bigdata">
            <br>
            <h2>좋아하는 오디오</h2>
            <audio src="./media/music01.mp3" controls></audio>
            <h2>환경을 사랑합니다</h2>
            <video width="50%" height="50%" controls autoplay loop src="./media/movie.mp4"></video>
            <hr>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/rjNBpJaXEQw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            <hr>
            <iframe src="./stat.html" frameborder="0" width="70%" height="240px"></iframe>
                지원되지 않는 브라우저입니다.
        </div>
        <div id="Profile">
            <h2>Hyewon Profil</h2>
            <table border="1">
                <tr>
                    <th>일자</th>
                    <th>내용</th>
                    <th>구분</th>
                    <tr>
                        <td>현재</td>
                        <td>동아대학교 경영정보학과 재학</td>
                        <td>2학년</td>
                    </tr>
                    <tr>
                        <td>21.3~21.8</td>
                        <td>어깨동무 봉사활동</td>
                        <td>지도</td>
                    </tr>
                    <tr>
                        <td>20.3~21.7</td>
                        <td>어학연수</td>
                        <td>-</td>
                    </tr>
                </tr>
            </table>
        </div>
       <br><br><br><br><br><br><br><br><br><br>
        <div id="link">
           <a href="http://www.donga.ac.kr" target="_blank">동아대학교</a> <br>
          <a href="http://www.naver.com" target="_self">네이버</a> <br>
          <a href="start.html">start페이지이동</a><br>
          <!--문서 내 이동-->
          <a href="#photo">사진으로 이동</a>
        </div>
        <div id="login">
            <form action="#" method="GET">
                아이디 : <input type="text" name="name" > <br>
                비밀번호 : <input type="password" name="pass" id="pass"> <br>
                <input type="submit" value="확인">
                <input type="reset" value="취소" >          
            </form>
        </div>
    </section>
    <footer> &copy;  Hyewon</footer>

</body>
</html>
