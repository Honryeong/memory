<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en">
  <head>
    <title>memory</title>
  </head>
  <body>
    <script src="https://code.jquery.com/jquery-1.12.4.js"></script>
      <style>
        body{
        -webkit-transition: all 7s;
        -moz-transition: all 7s;
        -ms-transition: all 7s;
        -o-transition: all 7s;
        transition: all 7s;
        }
      </style>
    <script>
      $(function(){
        $(window).scroll(function(){
        if( $(this).scrollTop() <= 1000 ){
          $('body').css('background-color','white');
        }else if( $(this).scrollTop() <= 5000 ){
          $('body').css('background-color','gray');
        }else if( $(this).scrollTop() <= 10000 ){
          $('body').css('background-color','black');
        }
       });
      });
    </script>
      <div style='height:25px;'>
      </div>
      <h2>
        <p style="margin-left:500px;" style="margin-right:500px;">
          <i>memory</i>
        </p>
      </h2>
    <br>
    <br>
    <br>
    <br>
      <p style="margin-left:500px;" style="margin-right:500px;">
        <img src="1.jpg" width="900" height="12000" alt="prologue">
          <a href="(회차 목록 사이트 주소 삽입 예정)"target="_blank"type="image">
            <img src="title.jpg" width="900" height="900" alt="memory">
          </a>
      </p>
    <br>
    <br>
    <br>
    <br>
  </body>
</html>
