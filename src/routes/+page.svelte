<main>
    <div class="logoContainer">
        <div class="logo">
            <a href="/"><img src="./logo_white.svg" alt="logo"></a>

            <hr>
        </div>
    </div>
    <div class="linksContainer">
        <div class="links" id="links">
            <ul>
                <a href="/">Boka</a>
                <a href="/">Reseinfo</a>
                <a href="/">Tjänster</a>
                <a href="/">Luftfartyg</a>
                <a href="/">Handling</a>
                <a href="/">Kontakta</a>
                <a href="/">Om Jonair</a>
            </ul>
        </div>
    </div>
    <div class="header">
        <h1>Welcome to Jonair.se</h1>
        <div class="headerContainer">
            <h3>At yorur service, anytime, all the time.</h3>
            <a href="/">Boka Reguljärflyg</a>
        </div>
    </div>
    <div class="tjansterText">
        <h1>Flyg Äventyr för Alla Smaker</h1>
    </div>
    <div class="tjanster">
        <div class="tjansterContainer">
            <div class="card">
                <img src="./privateJetInterior.png" alt="plane interior">
                <div class="cardContainer">
                    <h1>Affärsflyg</h1>
                    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quas illo totam doloribus ab consequuntur! Harum officiis hic, et vel, quae dolor itaque vero fugit voluptatem laboriosam deserunt cumque maiores! Molestiae.</p>
                    <a href="/">Läs Mer</a>
                </div>
            </div>
            <div class="card">
                <div class="cardContainer">
                    <h1>Helikoptertur</h1>
                    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quas illo totam doloribus ab consequuntur! Harum officiis hic, et vel, quae dolor itaque vero fugit voluptatem laboriosam deserunt cumque maiores! Molestiae.</p>
                    <a href="/">Läs Mer</a>
                </div>
                <img src="./helicopter.jpg" alt="helicopter">
            </div>
            <div class="card">
                <img src="./jonair-airshow.jpg" alt="plane">
                <div class="cardContainer">
                    <h1>Jonair - Airshow</h1>
                    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quas illo totam doloribus ab consequuntur! Harum officiis hic, et vel, quae dolor itaque vero fugit voluptatem laboriosam deserunt cumque maiores! Molestiae.</p>
                    <a href="/">Läs Mer</a>
                </div>
            </div>
        </div>
    </div>
    <div class="destinations">
        <div class="dContainer">
            <div class="dCard">
                <a href="/"><img src="./ostersund.jpg" alt="Östersund"></a>
                <div class="dCardText">
                    <h3>Umeå - Östersund</h3>
                    <p>Från 695kr</p>
                </div>
            </div>
            <div class="dCard">
                <a href="/"><img src="./pajala.jpg" alt="Pajala"></a>
                <div class="dCardText">
                    <h3>Pajala - Luleå</h3>
                    <p>Från 299kr</p>
                </div>
            </div>
            <div class="dCard">
                <a href="/"><img src="./gamlastan.webp" alt="Gamla Stan"></a>
                <div class="dCardText">
                    <h3>Sveg - Arlanda</h3>
                    <p>Från 695kr</p>
                </div>
            </div>
            <div class="dCard">
                <a href="/"><img src="./mora.jpg" alt=""></a>
                <div class="dCardText">
                    <h3>Mora - Arlanda</h3>
                    <p>Från 595kr</p>
                </div>
            </div>
            <div class="dCard">
                <a href="/"><img src="./torsby.jpg" alt=""></a>
                <div class="dCardText">
                    <h3>Torsby - Arlanda</h3>
                    <p>Från 595kr</p>
                </div>
            </div>
            <div class="dCard">
                <a href="/"><img src="./hagfors.webp" alt=""></a>
                <div class="dCardText">
                    <h3>Hagfors - Arlanda</h3>
                    <p>Från 595kr</p>
                </div>
            </div>
        </div>
    </div>
    <footer>
        <div class="footerContainer">
            <div class="footerLogo">
                <a href="/"><img src="./logo_white.svg" alt="logo"></a>
            </div>
            <hr>
            <div class="footerTexts">
                <div class="fTextsContainers">
                    <h3>Hitta hit</h3>
                    <a href="/">
                        <i class="fa-regular fa-location-dot"></i> Grind 4, Umeå Airport <br>
                        Västra Esplanaden 2 <br>
                        903 26 Umeå
                    </a>
                </div>
                <div class="fTextsContainers">
                    <h3>Om Jonair</h3>
                    <a href="/">Våra Tjänster</a>
                    <a href="/">Jonairs flygflotta</a>
                </div>
                <div class="fContact">
                    <h3>Kontakta</h3>
                    <div style="display: flex; flex-direction: column; gap: 30px;">
                        <div class="a">
                            <p>Allmänna frågor samt support</p>
                            <p>Öppet helgfria vardagar mellan 8:00 - 17:00</p>
                            <a href="tel:004690121240">+(46) 090 - 12 12 40</a>
                        </div>
                        <div class="a">
                            <p>Kontakt vid bokning av eget flygplan</p>
                            <p>Öppet dygnet runt</p>
                            <a href="tel:004690121200">+(46) 090-12 12 00</a>
                        </div>
                    </div>
                </div>
            </div>
            <hr>
            <div class="copyright">
                <p>Copyright © 2024 Jonair Affärsflyg</p>
            </div>
        </div>
    </footer>
</main>

<style>
    main {
        width: 100%;
        height: 200vh;
    }

    /* Navbar */

    .logoContainer {
        display: flex;
        justify-content: center;
        width: 100%;
        background-color: #000;

    }

    .logoContainer hr {
        margin: 20px 0 0px 0;
    }

    .logo {
        width: 60%;
        box-sizing: border-box;
        padding: 20px 20px 0 20px;
        background: black;
    }

    .logo a img {
        width: 157px;
    }

    .linksContainer {
        position: sticky;
        display: flex;
        justify-content: center;
        top: 0px;
        width: 100%;
        background-color: #000;
    }

    .links {
        box-sizing: border-box;
        width: 60%;
        
        background-color: #000;
        z-index: 1000;
        padding: 20px;
    }

    .links ul {
        display: flex;
        gap: 20px;

        margin: 0;
        padding: 0;
        list-style: none;
    }

    a {
        text-decoration: none;
    }

    .links ul a {
        color: var(--links);

        transition: all 0.3s ease-in-out;
    }

    .links ul a:hover {
        color: white;
    }

    /* Header */

    .header {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;

        width: 100%;
        height: 60vh;

        background: url('./header.jpg');
        background-position: center;
        background-size: cover;
    }

    .header h1 {
        font-size: 72px;
        color: white;
    }

    .headerContainer {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 20px;
        
        background: rgba(0, 0, 0, 0.3);
        box-shadow: 5px 5px 10px 5px rgba(0, 0, 0, 0.1);
        padding: 20px;
        border-radius: 20px;
    }

    .headerContainer h3 {
        font-size: 24px;
        color: white;
        margin: 0;
    }

    .headerContainer a {
        padding: 12px;
        background: #000;
        box-shadow: 5px 5px 10px 5px rgba(0, 0, 0, 0.1);
        color: white;

        border-radius: 8px;
        font-weight: bold;

        transition: all 0.3s ease-in-out;
    }

    .headerContainer a:hover {
        size: 1.05;
    }

    /* Services */

    .tjansterText {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;

        background-color: var(--bg);

        padding: 100px 0 0;
    }

    .tjansterText h1 {
        font-size: 50px;
        color: #333333;

        margin: 0;
    }

    .tjanster {
        display: flex;
        flex-direction: column;
        align-items: center;

        background: var(--bg);
    }

    .tjansterContainer {
        width: 60%;
        display: flex;
        flex-direction: column;
        gap: 100px;
        margin: 100px 0;
    } 

    /* Services Cards */

    .card {
        display: flex;
        align-items: center;
        gap: 80px;
    }

    .card img {
        height: 383px;
        border-radius: 20px;
        box-shadow: 5px 5px 10px 5px rgba(0, 0, 0, 0.1);
    }

    .cardContainer h1 {
        color: #333333;
        font-size: 38px;
    }

    .cardContainer p {
        color: #888888;
        line-height: 1.5em;
        font-size: 18px;
    }

    .cardContainer a {
        padding: 12px;
        background: #000;
        box-shadow: 5px 5px 10px 5px rgba(0, 0, 0, 0.1);
        color: white;

        border-radius: 8px;

        font-size: 14px;
        font-weight: bold;
    }

    .destinations {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 100%;

        padding: 100px 0;
    }

    .dContainer {
        display: flex;
        justify-content: space-between;
        flex-wrap: wrap;
        gap: 60px;
        width: 60%;
        padding: 0;
    }

    .dCard {
        display: flex;
        flex-direction: column;
        gap: 30px;
    }

    .dCard a img {
        object-fit: cover;
        object-position: center;
        height: 293px;
        width: 293px;

        border-radius: 20px;
        box-shadow: 5px 5px 10px 5px rgba(0, 0, 0, 0.1);
    }

    .dCardText {
        display: flex;
        flex-direction: column;
        gap: 10px;
    }

    .dCardText h3 {
        color: #333333;
        font-size: 24px;
        font-weight: bold;
        margin: 0;
    }

    .dCardText p {
        color: var(--p);
        font-size: 18px;
        margin: 0;
    }

    /* Footer */

    footer {
        box-sizing: border-box;

        display: flex;
        justify-content: center;
        align-items: center;
        
        width: 100%;
        background: var(--footer);
    }

    .footerContainer {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;

        padding: 40px;
        width: 60%;
    }

    .footerContainer hr {
        width: 100%;
        margin: 40px;
    }

    .footerTexts {
        display: flex;
        width: 100%;
        justify-content: space-between;
    }

    .fTextsContainers {
        display: flex;
        flex-direction: column;
        gap: 5px;
    }

    .fTextsContainers a {
        color: var(--p);

        transition: all 0.3s ease-in-out;
    }

    .fTextsContainers a:hover {
        color: white;
    }

    .footerContainer h3,
    .footerContainer p {
        margin: 0;
    }

    .footerContainer h3 {
        color: white;
        padding-bottom: 20px;

        font-size: 24px;
    }

    .footerContainer p,
    .footerContainer a {
        color: var(--p);
        
        transition: all 0.3s ease-in-out;
    }

    .footerContainer a:hover {
        color: white;
    }

    .footerLogo img {
        width: 300px;
        
    }

    .fContact .a {
        display: flex;
        flex-direction: column;
        gap: 5px;
        user-select: none;
    }

    .fContact .a a {
        color: var(--p);
        text-decoration: underline;

        transition: all 0.3s ease-in-out;
    }

    .fContact .a a:hover {
        color: white;
    }

    @media (min-width: 1921px) {
        .logo,
        .links,
        .tjansterContainer,
        .dContainer {
            width: 45%;
        }

        .tjansterContainer p {
            font-size: 20px;
        }

        .dCardText p {
            font-size: 20px;
        }
    }
       
    :root {
        /* Colors */

        --bg: #F7F7F7;
        --links: #999999;
        --p: #888888;
        --text-color: #333333;
        --footer: #222222;
    }
</style>