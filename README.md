<!DOCTYPE html>
<html>

<head>
    <title>Mansion design</title>
    <link rel="stylesheet" href="style.css">






</head>

<body>
    <div class="header">
        <div class="navbar">
            <img src="Mansion.jpg" alt="" srcset="logo">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Bedroom</a></li>
                <li><a href="#">Dining</a></li>
                <li><a href="#">Kitchen</a></li>
                <li><a href="#">Backyard</a></li>

            </ul>

        </div>

        <div class="content">
            <h1>DESIGN YOUR MANSION</h1>
            <P>It is easier than ever follow our courses and,<br> pursued your career as House designer.</P>
            <div>
                <button type="button"><span></span>SIGNIN</button>
                <button type="button"><span></span>LOGIN</button>
            </div>


        </div>

    </div>







</body>

</html>

* {
    margin: 0;
    padding: 0;
}

.header {
    background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(./images/MANSION.jpg);
    height: 100vh;
    width: 100%;
    background-repeat: no-repeat;
    background-size: cover;
}

.navbar {
    width: 85%;
    margin: auto;
    padding: 35px 0;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.navbar ul li {
    list-style: none;
    display: inline-block;
    margin: 0 20px;
    position: relative;
}

.navbar ul li a {
    text-decoration: none;
    color: #fff;
    text-transform: uppercase;
}

.navbar ul li::after {
    content: '';
    height: 3px;
    width: 0;
    background: #009688;
    position: absolute;
    left: 0;
    bottom: -10px
}

.content {
    width: 100%;
    position: calc(cover);
    top: 50%;


    text-align: center;
    color: #fff;

}

button {
    width: 200px;
    padding: 15px 0;
    text-align: center;
    margin: 20px 10px;
    border-radius: 25px;
    font-weight: bold;
    border: 2px solid #009688;
    background: transparent;
    color: #fff;
    cursor: pointer;
    position: relative;
    overflow: hidden;

}

span {
    background: #009688;
    height: 100%;
    width: 0;
    border-radius: 25px;
    position: absolute;
    left: 0;
    bottom: 0;
    z-index: -1;
    transition: 0.5s;
}

button:hover span {
    width: 100%;
}

button:hover {
    border: none;
}


