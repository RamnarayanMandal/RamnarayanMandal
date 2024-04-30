<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: sans-serif;
            text-decoration: none;
        }

        .img-container {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            width: 100%;
        }

        .img1 {
            border-radius: 10px;
            width: 500px;
            height: 500px;
        }

        h1 {
            color: black;
            text-align: center;
            font-size: 30px;
            font-family: sans-serif;
            margin-top: 20px;
            margin: 20px;
        }

        .details {
            margin-left: 40px;
            margin-right: 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            width: 100%;

        }

        .details p {
            padding-left: 20px;
            font-size: 25px;
            color: black;
            margin-bottom: 10px;
        }

        .img2-container {
            border-radius: 10px;
            width: 50%;
            margin-top: 20px;
        }

        #img2 {
            width: 500px;
            border-radius: 10px;
            height: 500px;
            background-size: cover;
            background-repeat: no-repeat;
        }

        ul {
            margin: 10px;
            list-style: none;
            font-size: 20px;
            padding-left: 20px;
        }

        ul li {
            color: black;
            font-size: 20px;
        }

        .skill {
            margin-top: 20px;
            margin-left: 40px;
            margin-right: 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            width: 100%;
        }

        .skill ul {
            gap: 10px;
            margin: 10px;
            list-style: none;
            font-size: 20px;
            padding-left: 20px;
            display: grid;
            grid-template-columns: repeat(6, 1fr);
            /* 5 items per column */
            justify-content: space-between;
            align-items: center;

        }

        li {
            color: black;
            font-size: 20px;
            margin-bottom: 10px;
            padding-left: 20px;
            padding-right: 20px;
            padding-top: 10px;
            padding-bottom: 10px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0px 0px 10px 0px rgba(0, 0, 0, 0.2);
            min-width:200px ;
            height: 100px;
            text-align: center;
            font-family: sans-serif;
            font-weight: bold;
            font-size: 20px;
           display: flex;
           justify-content: center;
           align-items: center;

        }
    </style>
</head>

<body>
    <div class="img-container">
        <img class="img1"
            src="https://camo.githubusercontent.com/700f2ecd2ca652d02ff0705ebdf8c4ee71dfbbe0d67fc02950f84eb251242ab9/68747470733a2f2f666972656261736573746f726167652e676f6f676c65617069732e636f6d2f76302f622f666c6578692d636f64696e672e61707073706f742e636f6d2f6f2f64656d706769372d35323066386435662d363364342d343435332d383832322d6462633134396165323766382e6769663f616c743d6d6564696126746f6b656e3d39316330633762322d393363332d343032392d623031312d316138373033633537333064"
            style="border-radius: 10px">
    </div>
    <h1>👋 Hi, I’m @RamnarayanMandal front-end developer</h1>
    <hr>
    <h1>about me</h1>
    <div class="details">
        <div>
            <p>👀 I’m interested in coding</p>
            <p>🌱 I’m currently learning Node.js</p>
            <p>💻 I’m looking to collaborate on front-end projects</p>
            <p>📧 How to reach me:</p>
            <ul>
                <li>Email: ramnaraya847230@gmail.com</li>
                <li>YouTube: <a href="https://youtu.be/iGzGE7T1Upc">https://youtu.be/iGzGE7T1Upc</a></li>
            </ul>
            <p>😄 Pronouns: he/him</p>
            <p>⚡ Fun fact: I love hiking and photography</p>
        </div>
        <div class="img2-container">
            <img id="img2"
                src="https://camo.githubusercontent.com/9c1a1939a5fe670fc434a5948f3aa959068c24d3e6b575bbe4112ab60c427d11/68747470733a2f2f63646e2e6472696262626c652e636f6d2f75736572732f313136323037372f73637265656e73686f74732f333834383931342f6d656469612f33323039383461396361353862336337333237346339323539656366366465382e676966"
                alt="">
        </div>
    </div>
    <h1>Skills</h1>
    <hr>
    <div class="skill">
        <ul>
            <li>HTML</li>
            <li>CSS</li>

            <li>Bootstrap</li>
            <li>Tailwind css</li>

            <li>JavaScript</li>
            <li>Node.js</li>
            <li>React</li>
            <li>MongoDB</li>
            <li>Express</li>
            <li>Github</li>
            <li>java</li>
            <li>jdbc</li>
            <li>Hibernate</li>
            <li>mysql</li>

            <li>C++</li>
            <li>C</li>



        </ul>
    </div>
</body>

</html>
