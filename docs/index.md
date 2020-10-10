<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Start</title>
    <link rel="stylesheet" href="css/style.css">
</head>

<body>

    <div class="container">

        <p>
            <span class="prompt">
                devops@devops
            </span>

            <img src="./img/ubuntu.svg">
            ~/
            <img src="./img/home.svg">
            /startpage
            <img src="./img//straight-right-arrow.svg"> cat
            <span class="prompt-text">
                index.js
            </span>
            <span class="prompt  clock-area" style="float: right; margin-top: 5px;">
                <img src="./img/wall-clock.svg">
                <span class="clock"></span>
            </span>
        </p>

        <p>
            <span class="syn">
                const
            </span>
            <span class="name">
                app
            </span>
            <span class="symbol">:</span>
            <span class="types">Startpage</span>
            <span class="syn">
                = new
            </span>
            <span class="types">
                StartPage({
            </span>

            <ul>
                <li>
                    <span class="name">el:</span>
                    <span class="value">'#start'</span>
                    <span class="name">,</span>
                </li>
                <li>
                    <span class="name">pinned: {</span>
                    <ul>
                        <li>
                            <a href="https://github.com" rel="noreferrer">
                                <span class="name">github:</span>
                                <span class="value">'github.com'</span>
                                <span class="name">,</span>
                            </a>
                        </li>
                        <li>
                            <a href="https://reddit.com" rel="noreferrer">
                                <span class="name">reddit:</span>
                                <span class="value">'reddit.com'</span>
                                <span class="name">,</span>
                            </a>
                        </li>
                        <li>
                            <a href="https://mail.google.com" rel="noreferrer">
                                <span class="name">gmail:</span>
                                <span class="value">'mail.google.com'</span>
                                <span class="name">,</span>
                            </a>
                        </li>
                        <li>
                            <a href="https://figma.com" rel="noreferrer">
                                <span class="name">figma:</span>
                                <span class="value">'figma.com'</span>
                                <span class="name">,</span>
                            </a>
                        </li>
                        <li>
                            <a href="https://bitbucket.com" rel="noreferrer">
                                <span class="name">bitbucket:</span>
                                <span class="value">'bitbucket.com'</span>
                                <span class="name">,</span>
                            </a>
                        </li>
                        <li>
                            <a href="https://youtube.com" rel="noreferrer">
                                <span class="name">youtube:</span>
                                <span class="value">'youtube.com'</span>
                                <span class="name">,</span>
                            </a>
                        </li>
                        <li>
                            <a href="https://dev.to" rel="noreferrer">
                                <span class="name">dev.to:</span>
                                <span class="value">'dev.to'</span>
                                <span class="name">,</span>
                            </a>
                        </li>
                        <li>
                            <a href="https://news.google.com" rel="noreferrer">
                                <span class="name">news:</span>
                                <span class="value">'news.google.com'</span>
                                <span class="name">,</span>
                            </a>
                        </li>
                        <li>
                            <a href="https://draw.io" rel="noreferrer">
                                <span class="name">draw.io:</span>
                                <span class="value">'draw.io'</span>
                                <span class="name">,</span>
                            </a>
                        </li>
                        <li>
                            <a href="https://twitter.com" rel="noreferrer">
                                <span class="name">twitter:</span>
                                <span class="value">'twitter.com'</span>
                                <span class="name">,</span>
                            </a>
                        </li>
                    </ul>
                </li>
                <li>
                    <span class="name">}</span>
                </li>
            </ul>
            <span class="name">
                )}
            </span>
        </p>

        <p>
            <form action="https://duckduckgo.com/" method="get">
                <span class="prompt">
                    devops@devops
                </span>

                <img src="./img/ubuntu.svg">
                ~/
                <img src="./img/home.svg">
                /startpage
                <img src="./img//straight-right-arrow.svg"> d
                <input type="search" placeholder="Enter keywords" name="q" autofocus>
            </form>
        </p>
    </div>

</body>
<script>
    function currentTime() {
        var date = new Date();
        var hour = date.getHours();
        var min = date.getMinutes();
        var sec = date.getSeconds();
        hour = updateTime(hour);
        min = updateTime(min);
        sec = updateTime(sec);
        document.querySelector(".clock").innerHTML = hour + ":" + min + ":" + sec;
        var t = setTimeout(function () {
            currentTime()
        }, 1000);
    }

    function updateTime(k) {
        if (k < 10) {
            return "0" + k;
        } else {
            return k;
        }
    }

    currentTime();
</script>

</html>
