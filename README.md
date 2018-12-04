# Footer-wrapper
Simple CSS to create a responsive footer with a wrapper


########## HTML & CSS ###########

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Document</title>
  <style>
    html, body {
    height: 100%;
}

body{
    display: flex;
    flex-direction: column;
    padding-top: 90px;
    background-color: #efeff0 !important;
    background-image: url("bg-kersia.jpg");
    background-repeat: no-repeat;
    background-position: top;
    background-attachment: fixed;
    margin:0px;
    /*font-family: carnas !important;*/

}

.wrapper {
    flex: 1 0 auto;
}
.footer{
    flex-shrink: 0;
    margin-top: 25px;
    left: 0;
    right: 0;
    bottom: 0;
    width: 100%;
    color: white;
    text-align: center;
}
  </style>
</head>

<body>
	<div class="wrapper">
	<p>Lorem ipsum Lorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsum</p>
	</div>
  <footer class="footer">this is a footer</footer>
</body>
</html>
