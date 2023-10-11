﻿<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
    <style>
        .nav {
            background-color: #33b5e5;
        }

        * {
            box-sizing: border-box;
        }

        .row::after {
            content: "";
            clear: both;
            display: block;
        }

        [class*="col-"] {
            float: left;
            padding: 15px;
        }

        html {
            font-family: "Lucida Sans", sans-serif;
        }

        .box {
            background-color: #9933cc6b;
            color: #ffffff;
            padding: 15px;
            width: 50%;
        }

        .menu ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        .menu li {
            padding: 8px;
            margin-bottom: 7px;
            background-color: #cc66ff;
            color: #ffffff;
            box-shadow: 0 1px 3px rgba(0, 0, 0, 0.12), 0 1px 2px rgba(0, 0, 0, 0.24);
        }

        .menu li:hover {
            background-color: #99ccff;
        }

        .aside {
            background-color: #cc66ff;
            padding: 15px;
            color: #ffffff;
            text-align: center;
            font-size: 14px;
            box-shadow: 0 1px 3px rgba(0, 0, 0, 0.12), 0 1px 2px rgba(0, 0, 0, 0.24);
        }

        .no {
            background-color: #33b5e5;
            padding: 16px;
            box-sizing: inherit;
            display: block;
        }
        .no:hover {
            background-color: #99ccff;
        }

        .col-6 {
            color: #ffffff;
            text-align: justify;
        }

        .footer {
            color: #ffffff;
            text-align: center;
            font-size: 12px;
            padding: 15px;
        }

        /* For desktop: */
        .col-1 {
            width: 8.33%;
        }

        .col-2 {
            width: 16.66%;
        }

        .col-3 {
            width: 25%;
        }

        .col-4 {
            width: 33.33%;
        }

        .col-5 {
            width: 41.66%;
        }

        .col-6 {
            width: 50%;
        }

        .col-7 {
            width: 58.33%;
        }

        .col-8 {
            width: 66.66%;
        }

        .col-9 {
            width: 75%;
        }

        .col-10 {
            width: 83.33%;
        }

        .col-11 {
            width: 91.66%;
        }

        .col-12 {
            width: 100%;
        }

        @media only screen and (max-width: 768px) {

            /* For mobile phones: */
            [class*="col-"] {
                width: 100%;
            }
        }
    </style>
    </body>
</head>

<body class="nav">
    <div class="box">
        <h1>
            <img src="hhh.jpg" alt=" Phạm Thị Huệ" class="box">
            <p>Phạm Thị Huệ </p>
        </h1>
    </div>

    <div class="row">
        <div class="col-3 menu">
            <ul>
                <li><i class="fa fa-briefcase fa-fw w3-margin-right w3-large w3-text-teal"></i> student </li>
                <li><i class="fa fa-home fa-fw w3-margin-right w3-large w3-text-teal"></i> Việt Nam </li>
                <li><i class="fa fa-envelope fa-fw w3-margin-right w3-large w3-text-teal"></i> phamhue10122003@gmail.com
                </li>
                <li><i class="fa fa-phone fa-fw w3-margin-right w3-large w3-text-teal"></i> 0348198802 </li>
            </ul>
        </div>

        <div class="col-6">
            <h1> Tóm tắt bản thân </h1>
            <p>Tôi là một người tự hào về khả năng làm việc độc lập và sở hữu tinh thần cầu tiến. Tôi luôn đam mê trong
                việc học hỏi và phát triển bản thân để đạt được mục tiêu cá nhân và chuyên môn. Với sự tập trung cao và
                khả năng giải quyết vấn đề linh hoạt, tôi cam kết mang lại hiệu suất làm việc tối ưu và đóng góp tích
                cực cho môi trường làm việc.</p>
        </div>

        <div class="col-3 right">
            <div class="aside">
                <h1> Kỹ năng </h1>
                <h2> Giao Tiếp </h2>
                <p class="no"> 50% </p>
                <h2> Phân Tích Dữ Liệu </h2>
                <p class="no"> 70% </p>
                <h2> Công nghệ </h2>
                <p class="no"> 70% </p>
                <h2> Lãnh Đạo </h2>
                <p class="no"> 80% </p>
            </div>
        </div>
    </div>

    <div class="footer">
        <i class="fa-brands fa-facebook"></i> 
        <i class="fa-brands fa-tiktok"></i>
        <i class="fa-brands fa-instagram"></i> 
        <i class="fa-brands fa-facebook-messenger"></i>
            <i class="fa-brands fa-twitter"></i>

    </div>

</body>

</html>
