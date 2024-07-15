<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ui Web</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>

<body>
    <section>
        <header class="container">
            <div class="page-header">
                <div class="logo">
                    <a href="#">Portfolio.</a>
                </div>
                <input type="checkbox" id="click">
                <label for="click" class="mainicon">
                    <div class="menu">
                        <i class="fa-solid fa-bars"></i>
                    </div>
                </label>
                <ul>
                    <li><a href="#" class="active" style="--navAni:1">Home</a></li>
                    <li><a href="#" style="--navAni:2">About</a></li>
                    <li><a href="#" style="--navAni:3">Skills</a></li>
                    <li><a href="#" style="--navAni:4">Portfolio</a></li>
                    <li><a href="#" style="--navAni:5">Contact</a></li>
                </ul>
                <label class="mode">
                    <input type="checkbox" id="darkModeToggle">
                    <i class="fa-solid fa-moon"></i>
                </label>
            </div>
        </header>
        <div class="card">
            <div class="container">
                <div class="main">
                    <div class="detail">
                        <h3>Hi I'm</h3>
                        <h1>
                            <span style="color:#52489C;">Naga</span>
                            "Hemanth"
                        </h1>
                        <p>
                            "I'm a professional Web Developer. Our Main Goal to help & Satisficed the Local & Global Clients by Web development solutions "
                        </p>
                        <div class="social">
                            <a href="" style="--socialAni:1"><i class="fa-brands fa-linkedin-in"></i></a>
                            <a href="" style="--socialAni:2"><i class="fa-brands fa-instagram"></i></a>
                            <a href="" style="--socialAni:3"><i class="fa-brands fa-github"></i></a>
                            <a href="" style="--socialAni:4"><i class="fa-brands fa-youtube"></i></a>
                        </div>
                    </div>
                    <div class="images">
                        <img src="https://th.bing.com/th?id=OIP.JxyGHWbgPXgjta3k4PznxwHaLH&w=204&h=306&c=8&rs=1&qlt=90&o=6&dpr=1.3&pid=3.1&rm=2" alt="" class="img-w">
                    </div>
                    <section id="Skills">
                        <h1 class="subtitle"> <span>Skills</span></h1>
                        <div class="sec">
                            <div class="container1">
                                <h1 class="heading1">Coding Skills</h1>
                                <div class="Technical-bars">

                                    <div class="bar"><i class='bx bxl-html5' style="color: #c9332e;"></i>
                                        <div class="info">
                                            <span>HTML <span class="addhtml"></span></span>
                                        </div>
                                        <div class="progress-line html">
                                            <span></span>
                                        </div>
                                    </div>

                                    <div class="bar"><i class='bx bxl-css3' style="color: #147bbc;"></i>
                                        <div class="info">
                                            <span>CSS <span class="addcss"></span></span>
                                        </div>
                                        <div class="progress-line css">
                                            <span></span>
                                        </div>
                                    </div>

                                    <div class="bar"><i class='bx bxl-javascript' style="color: #c95d2e;"></i>
                                        <div class="info">
                                            <span>JavaScript <span class="addjavascript"></span></span>
                                        </div>
                                        <div class="progress-line java">
                                            <span></span>
                                        </div>
                                    </div>

                                    <div class="bar"><i class="fa-solid fa-Python" style="color: #3db2fc;"></i>
                                        <div class="info">
                                            <span>Python<span class="addc"></span></span>
                                        </div>
                                        <div class="progress-line cpls">
                                            <span></span>
                                        </div>
                                    </div>

                                </div>
                            </div>

                            <div class="container2">
                                <h1 class="heading1">Professional Skills</h1>
                                <div class="radial-bars">
                                    <div class="radial-bar">
                                        <svg x="0px" y="0px" viewBox="0 0 200 200">
                                            <circle class="progress-bar" cx="100" cy="80" r="80"></circle>
                                            <circle class="path path-1" cx="100" cy="80" r="80"></circle>
                                        </svg>
                                        <div class="percentage">80%</div>
                                        <div class="text">Problem Solving</div>
                                    </div>

                                    <div class="radial-bar">
                                        <svg x="0px" y="0px" viewBox="0 0 200 200">
                                            <circle class="progress-bar" cx="100" cy="80" r="80"></circle>
                                            <circle class="path path-2" cx="100" cy="80" r="80"></circle>
                                        </svg>
                                        <div class="percentage">70%</div>
                                        <div class="text">Creativity</div>
                                    </div>

                                    <div class="radial-bar">
                                        <svg x="0px" y="0px" viewBox="0 0 200 200">
                                            <circle class="progress-bar" cx="100" cy="80" r="80"></circle>
                                            <circle class="path path-3" cx="100" cy="80" r="80"></circle>
                                        </svg>
                                        <div class="percentage">80%</div>
                                        <div class="text">Communication</div>
                                    </div>

                                    <div class="radial-bar">
                                        <svg x="0px" y="0px" viewBox="0 0 200 200">
                                            <circle class="progress-bar" cx="100" cy="80" r="80"></circle>
                                            <circle class="path path-4" cx="100" cy="80" r="80"></circle>
                                        </svg>
                                        <div class="percentage">90%</div>
                                        <div class="text">Teamwork</div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </section>
                </div>
            </div>
        </div>
    </section>

</body>

</html>
