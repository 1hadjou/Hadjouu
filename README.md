<!DOCTYPE html>
<html lang="ar" dir="rtl">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>هدية إلى أختي ❤️</title>

    <style>

        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            min-height: 100vh;

            display: flex;
            justify-content: center;
            align-items: center;

            font-family: Arial, Tahoma, sans-serif;

            background:
                radial-gradient(circle at top,
                #24245a,
                #0b0b22 60%,
                #020208);

            overflow: hidden;
            color: white;
        }


        /* النجوم */

        .star {
            position: absolute;
            color: white;
            animation: twinkle 2s infinite alternate;
        }

        @keyframes twinkle {

            from {
                opacity: 0.2;
                transform: scale(0.7);
            }

            to {
                opacity: 1;
                transform: scale(1.3);
            }

        }


        /* صندوق الهدية */

        .gift {

            position: relative;

            width: 90%;
            max-width: 700px;

            text-align: center;

            padding: 50px 20px;

            background:
                rgba(255, 255, 255, 0.08);

            border-radius: 30px;

            border:
                1px solid
                rgba(255, 255, 255, 0.2);

            backdrop-filter: blur(10px);

            box-shadow:
                0 0 50px
                rgba(120, 100, 255, 0.3);
        }


        /* القمر */

        .moon-container {

            width: 220px;
            height: 220px;

            margin: auto;

            display: flex;
            justify-content: center;
            align-items: center;

            animation:
                rotateMoon
                8s
                linear
                infinite;
        }


        .moon {

            width: 160px;
            height: 160px;

            background:
                #fff8d1;

            border-radius: 50%;

            position: relative;

            box-shadow:
                0 0 30px #fff5b0,
                0 0 70px #fff5b0,
                0 0 120px rgba(255,245,176,0.6);
        }


        /* حفر القمر */

        .moon::before {

            content: "";

            position: absolute;

            width: 35px;
            height: 35px;

            border-radius: 50%;

            background:
                rgba(190, 180, 140, 0.25);

            top: 35px;
            left: 40px;

            box-shadow:
                50px 30px 0
                rgba(190,180,140,0.2),

                20px 80px 0
                rgba(190,180,140,0.2);
        }


        @keyframes rotateMoon {

            from {
                transform: rotate(0deg);
            }

            to {
                transform: rotate(360deg);
            }

        }


        /* العبارة */

        .message {

            position: relative;

            margin-top: 30px;

            font-size: 32px;

            font-weight: bold;

            line-height: 1.8;

            color: #ffffff;

            text-shadow:
                0 0 10px #ff6b9d,
                0 0 25px #ff6b9d;

            animation:
                messageGlow
                2s
                infinite
                alternate;
        }


        @keyframes messageGlow {

            from {

                text-shadow:
                    0 0 10px #ff6b9d;

            }

            to {

                text-shadow:
                    0 0 20px #ff6b9d,
                    0 0 50px #ff6b9d;

            }

        }


        /* القلوب حول العبارة */

        .heart {

            position: absolute;

            font-size: 28px;

            animation:
                floatHeart
                3s
                ease-in-out
                infinite;

        }


        .heart1 {
            top: -30px;
            right: 5%;
        }

        .heart2 {
            top: 20px;
            left: 5%;
            animation-delay: 1s;
        }

        .heart3 {
            bottom: -30px;
            right: 20%;
            animation-delay: 0.5s;
        }

        .heart4 {
            bottom: -35px;
            left: 20%;
            animation-delay: 1.5s;
        }


        @keyframes floatHeart {

            0% {
                transform:
                    translateY(0)
                    scale(1);
            }

            50% {
                transform:
                    translateY(-20px)
                    scale(1.25);
            }

            100% {
                transform:
                    translateY(0)
                    scale(1);
            }

        }


        /* رسالة إضافية */

        .small-message {

            margin-top: 30px;

            font-size: 18px;

            line-height: 2;

            color: #ffe7f0;

        }


        /* زر */

        button {

            margin-top: 25px;

            padding:
                14px 28px;

            border: none;

            border-radius:
                30px;

            background:
                linear-gradient(
                    135deg,
                    #ff4f81,
                    #b84dff
                );

            color: white;

            font-size:
                17px;

            cursor: pointer;

            box-shadow:
                0 0 20px
                rgba(255, 79, 129, 0.5);

            transition: 0.3s;

        }


        button:hover {

            transform:
                scale(1.1);

        }


        /* الرسالة المخفية */

        #secret {

            display: none;

            margin-top: 25px;

            padding: 20px;

            border-radius: 20px;

            background:
                rgba(255,255,255,0.1);

            font-size: 19px;

            line-height: 2;

        }

    </style>

</head>


<body>


<!-- النجوم -->

<div class="star" style="top:10%; left:10%;">✦</div>
<div class="star" style="top:20%; left:80%;">✦</div>
<div class="star" style="top:70%; left:15%;">✦</div>
<div class="star" style="top:80%; left:85%;">✦</div>
<div class="star" style="top:40%; left:5%;">✦</div>
<div class="star" style="top:15%; left:50%;">✦</div>


<div class="gift">


    <!-- القمر -->

    <div class="moon-container">

        <div class="moon"></div>

    </div>


    <!-- العبارة والقلوب -->

    <div class="message">

        <span class="heart heart1">❤️</span>

        <span class="heart heart2">💕</span>

        أختي، أنتِ أجمل من القمر 🌙

        <span class="heart heart3">❤️</span>

        <span class="heart heart4">💖</span>

    </div>


    <div class="small-message">

        لأن القمر يضيء السماء في الليل،
        أما أنتِ يا أختي فتضيئين حياتي دائمًا ❤️✨

    </div>


    <button onclick="showLove()">

        اضغطي هنا يا أختي ❤️

    </button>


    <div id="secret">

        أحبكِ يا أختي ❤️<br><br>

        مهما تغيرت الأيام،
        ستبقين دائمًا شخصًا جميلًا وغاليًا في قلبي.

        🌙❤️✨

    </div>


</div>


<script>

function showLove() {

    let message =
    document.getElementById("secret");

    if (
        message.style.display === "block"
    ) {

        message.style.display = "none";

    } else {

        message.style.display = "block";

    }

}

</script>


</body>

</html>
