<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=PT+Sans+Narrow:wght@400;700&family=Playfair+Display:ital,wght@0,400;0,500;0,600;0,700;0,800;0,900;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
        rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    <title>Bohdan Gankevich</title>
</head>

<body>
    <header class="header">
        <nav class="header__menu">
            <ul class="header__menu_list">
                <li><a href="#contacts">My contacts</a></li>
                <li><a href="#basic">About me</a></li>
                <li><a href="#skills">Skill</a></li>
                <li><a href="#examplecode">Example code</a></li>
                <li><a href="#experience">Experience</a></li>
                <li><a href="#education">Education</a></li>
            </ul>
        </nav>
        <div class="header__info">
            <img src="img/download.png" alt="My photo" class="header__img">
            <div class="header__description">
                <h1 class="header__description_title">
                    Богдан
                </h1>
                <h2 class="header__description_subtitle">Front end-developer</h2>
            </div>
        </div>
    </header>
    <main class="main" id="main">
        <aside class="aside">
            <div class="contacts" id="contacts">
                <h2>My contacts</h2>
                Phone:<a href="tel:380638673124"> 380638673124</a> <br>
                E-mail:<a href="email:Твій емейл">gankevichbog@gmail.com</a> <br>
                Telegram:<a href="https://t.me/телеграм">My Telegram</a> <br>
            </div>

            <div class="experience" id="experience">
                <h2>My experience</h2>
                <p>There is currently no commercial experience</p>
            </div>
            <div class="languages">
                <div class="languages__descr">
                    <h2 class="languages__descr_title">languages</h2>
                    <ul class="languages__descr_list">
                        <li>Ukrainian - Upper advanced level</li>
                        <li>English - Lower intermediate level</li>
                    </ul>
                </div>
            </div>
            <div class="project">
                <h2 class="project__title">practical projects</h2>
                <ul class="project__list">
                    <li><a href="https://gituservn.github.io/uber/">UBER</a></li>
                    <li><a href="http://willow.com.ua/">PULS SHOP</a></li>
                </ul>
            </div>
        </aside>
        <hr class="divider">
        <div class="basic" id="basic">
            <div class="basic__information">
                <h2 class="basic__information_title">About me</h2>
                <p class="basic__information_about">
                    I live in Ukraine in the city of Kiev. He studied at the school in 10 clas. He is married. I am currently studying programming languages. I'm
                    still learning
                    English. I'm working to make you a front-end specialist. I adapt and learn quickly. I know how to
                    find a way out of the
                    most difficult situations. Not conflicted and quite calm.
                </p>
            </div>
         
            </div>
            <div class="basic__examplecode" id="examplecode">
                <h2 class="basic__examplecode_title">Example code</h2>

                <pre>
                $('[data-modal=consultation]').on('click', function () {
                $('.overlay, #consultation').fadeIn('slow');
                });
                        
                        
                        
                $('.modal__close').on('click', function () {
                $('.overlay, #consultation, #order, #thanks').fadeOut('slow');
                });
                        
                $('.button_mini').each(function (i) {
                $(this).on('click', function () {
                $('#order .modal__descr').text($('.catalog-item__subtitle').eq(i).text());
                $('.overlay, #order').fadeIn('slow');
                });
                });
                    </pre>
            </div>
            <div class="basic__education" id="education">
                <h2 class="basic__education_title">Education</h2>
                <div class="basic__education_links">
                    <a href="https://www.udemy.com/course/webdeveloper/"><img src="img/webdev.jpg"
                            alt="webdeveloper"></a>
                    <a href="https://www.udemy.com/course/intensive-js/"><img src="img/js.jpg" alt="intensive-js"></a>
                    <a href="https://www.udemy.com/course/javascript_full/"><img src="img/jsreact.jpg"
                            alt="javascript_full"></a>
                </div>
            </div>
        </div>
    </main>
    <footer class="footer">
        <div class="footer__links">
            <a class="footer__links_link" href="https://github.com/Gituservn"><img src="img/github.png"
                    alt="github"></a>
            <a class="footer__links_link" href="https://www.youtube.com/c/rollingscopesschool"><img
                    src="img/youtube.png" alt="youtube"></a>
            <a class="footer__links_link" href="https://app.rs.school/"><img src="img/logo-rsschool3.png"
                    alt="rsschool"></a>

        </div>
    </footer>
</body>

</html>

