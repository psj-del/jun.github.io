# jun.github.io
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>나의 포트폴리오</title>
    <style>
        /* 기본 스타일 */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }

        /* 헤더 스타일 */
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }

        /* 섹션 스타일 */
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px 0;
        }

        /* 소개 섹션 */
        #about {
            text-align: center;
            margin-bottom: 20px;
        }

        #about h2 {
            font-size: 24px;
            color: #333;
        }

        /* 포트폴리오 섹션 */
        #portfolio {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        .project {
            flex: 1 1 30%;
            background: #fff;
            padding: 15px;
            margin: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .project img {
            width: 100%;
            border-radius: 5px;
        }

        .project h3 {
            font-size: 18px;
            color: #333;
        }

        .project p {
            color: #666;
        }
    </style>
</head>
<body>

    <!-- 헤더 -->
    <header>
        <h1>나의 포트폴리오</h1>
    </header>

    <!-- 자기소개 섹션 -->
    <section id="about" class="container">
        <h2>안녕하세요, 저는 웹 개발자입니다!</h2>
        <p>열정을 가지고 웹사이트와 애플리케이션을 만들고 있습니다. 함께 작업할 기회를 기다리고 있어요!</p>
    </section>

    <!-- 포트폴리오 섹션 -->
    <section id="portfolio" class="container">
        <div class="project">
            <img src="https://via.placeholder.com/300" alt="Project 1">
            <h3>프로젝트 1</h3>
            <p>간단한 프로젝트 설명이 여기에 들어갑니다.</p>
        </div>
        <div class="project">
            <img src="https://via.placeholder.com/300" alt="Project 2">
            <h3>프로젝트 2</h3>
            <p>두 번째 프로젝트 설명입니다.</p>
        </div>
        <div class="project">
            <img src="https://via.placeholder.com/300" alt="Project 3">
            <h3>프로젝트 3</h3>
            <p>세 번째 프로젝트에 대한 설명입니다.</p>
        </div>
    </section>

</body>
</html>
