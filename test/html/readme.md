<!DOCTYPE html>

<html lang="en" class="no-js">

<head>

    <meta charset="utf-8">

    <title>

        欢迎来到登录界面

    </title> 

     <meta name="viewport"content="width=device-width,initial-scale=1.0">

     <meta name="description"content="">

     <meta name="author"content="">

     <!---CSS-->

     <link rel="stylesheet" type="text/css" href="css/supersized.css">

     <link rel="stylesheet" type="text/css" href="css/login.css">

     <link rel="stylesheet" href="css/bootstrap.min.css">

     <script src="js/jquery-1.8.2.min.js"></script>

     <script type="text/javascript"src="js/jquery.form.js"></script>

     <script type="text/javascript"src="js/tooltips.js"></script>

     <script type="text/javascript"src="js/login.js"></script>

<body>

  <div class="page-container">

  <div class="main_box">

  <div class="login_box">

  <div class="login_logo">

    <label for="j_loginname"class="t">

    <h2>

    <font color="red">

        欢迎使用登录系统

    </font>

    </h2>

    </label>

  </div>

  <div class="login_form">

    <form action="index.html"id="login_form"method="post">

        <div class="form-group">

                        <label for="j_username" class="t">邮　箱：</label> 

                        <input id="email" value="" name="email" type="text" class="form-control x319 in" 

                        autocomplete="off">

                    </div>

        <div class="form-group">

                        <label for="j_password" class="t">密　码：</label> 

                        <input id="password" value="" name="password" type="password" 

                        class="password form-control x319 in">

                    </div>

                    <div class="form-group">

                        <label for="j_captcha" class="t">验证码：</label>

                         <input id="j_captcha" name="j_captcha" type="text" class="form-control x164 in">

                        <img id="captcha_img" alt="点击更换" title="点击更换" src="images/captcha.jpeg" class="m">

                    </div>

                    <div class="form-group">

                        <label class="t"></label>

                        <label for="j_remember" class="m">

                        <input id="j_remember" type="checkbox" value="true">&nbsp;记住登陆账号!</label>

                    </div>

                    </div>

                    <div class="form-group space">

                        <label class="t"></label>　　　

                        <button type="button"id="submit_btn" 

                        class="btn btn-primary btn-lg">&nbsp;登&nbsp;录&nbsp </button>

                        <input type="reset" value="&nbsp;&nbsp;&nbsp;&nbsp;重&nbsp;置&nbsp;" class="btn btn-default btn-lg">

                    </div>

    </form>

  </div>    

  </div>

  </div>

  </div>

<script src="js/supersized.3.2.7.min.js"></script>

<script src="js/supersized-init.js"></script>

<script src="js/scripts.js"></script>

<div style="text-align:center;">

<p>来源:<a href="http://www.mycodes.net/" target="_blank"></a></p>

</div>  

</body>

</head>

</html>
