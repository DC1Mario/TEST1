<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Dark Captains ~ Steel Diver: Sub Wars</title>
  <style>
    /* smooth scroll */
    html { scroll-behavior: smooth; }

    /* dynamic header gap (JS will set --header-h) */
    :root { --header-h: 0px; }

    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f5f5f5;
      color: #333;
    }

    header {
      background-color: #eee;
      text-align: center;
      padding: 1em 0;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    header h1 {
      font-size: 1.8em;
      margin: 0.2em 0;
    }

    nav {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      background-color: #ddd;
      padding: 0.5em;
    }

    nav ul {
      list-style: none;
      margin: 0;
      padding: 0;
      display: flex;
      gap: 1em;
    }

    nav li {
      position: relative;
    }

    nav a {
      text-decoration: none;
      color: #0044cc;
      font-weight: bold;
      padding: 10px 15px;
      display: block;
    }

    nav li:hover > a {
      background-color: #ccc;
    }

    /* Dropdown styles */
    nav ul ul {
      display: none;
      position: absolute;
      top: 100%;
      left: 0;
      min-width: 160px;
      background-color: #f1f1f1;
      box-shadow: 0 8px 16px rgba(0,0,0,0.2);
      z-index: 1;
      flex-direction: column;
      gap: 0;
    }

    nav ul li:hover > ul {
      display: flex;
    }

    nav ul ul li a {
      color: #000;
      padding: 10px;
    }

    nav ul ul li a:hover {
      background-color: #ddd;
    }

    main {
      max-width: 800px;
      margin: 2em auto;
      padding: 1em;
      background: white;
      box-shadow: 0 0 5px rgba(0,0,0,0.1);
      /* ensure anchored sections aren't hidden under the header */
      scroll-margin-top: calc(var(--header-h) + 10px);
    }

    /* If you later add other sections with their own ids, they will get the same scroll-margin */
    section { margin-bottom: 1.25em; }

    h3 { color: #cc0000; }

    .contact h3 {
      color: #ffff00;
      background-color: #333;
      padding: 0.5em;
    }

    .rate {
      background-color: yellow;
      text-align: center;
      padding: 1em;
      margin-top: 2em;
    }

    footer {
      text-align: center;
      font-size: 0.9em;
      color: #777;
      padding: 1em 0;
    }
  </style>
</head>
<body>

  <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Dark Captains ~ Steel Diver: Sub Wars</title>
  <style>
    /* reset + basic styles */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f5f5f5;
      color: #333;
    }

    header {
      background-color: #eee;
      text-align: center;
      padding: 1em 0;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    header h1 {
      font-size: 1.8em;
      margin: 0.2em 0;
    }

    nav {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      background-color: #ddd;
      padding: 0.5em;
    }

    nav ul {
      list-style: none;
      margin: 0;
      padding: 0;
      display: flex;
      gap: 1em;
    }

    nav li {
      position: relative;
    }

    nav a {
      text-decoration: none;
      color: #0044cc;
      font-weight: bold;
      padding: 10px 15px;
      display: block;
      cursor: pointer;
    }

    nav li:hover > a {
      background-color: #ccc;
    }

    /* Dropdown styles */
    nav ul ul {
      display: none;
      position: absolute;
      top: 100%;
      left: 0;
      min-width: 160px;
      background-color: #f1f1f1;
      box-shadow: 0 8px 16px rgba(0,0,0,0.2);
      z-index: 1;
      flex-direction: column;
      gap: 0;
    }

    nav ul li:hover > ul {
      display: flex;
    }

    nav ul ul li a {
      color: #000;
      padding: 10px;
    }

    nav ul ul li a:hover {
      background-color: #ddd;
    }

    /* page system */
    .page {
      display: none;        /* hide all pages by default */
      min-height: 100vh;    /* full viewport height */
      padding: 1em;
      box-sizing: border-box;
      overflow-y: auto;     /* allow scrolling inside page */
      background: white;
    }

    .page.active {
      display: block;       /* only active page is visible */
    }

    section { margin-bottom: 1.25em; }

    h3 { color: #cc0000; }

    .contact h3 {
      color: #ffff00;
      background-color: #333;
      padding: 0.5em;
    }

    .rate {
      background-color: yellow;
      text-align: center;
      padding: 1em;
      margin-top: 2em;
    }

    footer {
      text-align: center;
      font-size: 0.9em;
      color: #777;
      padding: 1em 0;
    }
  </style>
</head>
<body>

  <header>
    <h1>Đark ©aptains ~ Steel Diver: Sub Wars</h1>
    <nav>
      <ul>
        <li><a data-page="home_page">HOME PAGE</a></li>

        <li><a href="#">Our Members</a>
          <ul>
            <li><a href="#">Members' List</a></li>
            <li><a href="#">Ex Members</a></li>
            <li><a data-page="dc_list_4">ĐC List #4 (11.02.2017)</a></li>
            <li><a href="#">FaceBook + Amino</a></li>
            <li><a href="#">Unknown if they are members</a></li>
          </ul>
        </li>

        <li><a href="#">Clan Leadership</a>
          <ul>
            <li><a href="#">Current Leadership</a></li>
            <li><a href="#">Older Co-Leaders</a></li>
            <li><a href="#">DC1 MarioMV</a></li>
            <li><a href="#">DC1/4 Matisse</a></li>
          </ul>
        </li>

        <li><a href="#">Important Info</a>
          <ul>
            <li><a href="#">Our History</a></li>
            <li><a href="#">Important Dates</a></li>
            <li><a href="#">DC Mottos</a></li>
            <li><a href="#">DC Official Flag</a></li>
            <li><a href="#">DC Alliances</a></li>
            <li><a href="#">DC Youtube Channel</a></li>
          </ul>
        </li>

        <li><a href="#">Events</a>
          <ul>
            <li><a href="#">HELLO</a></li>
          </ul>
        </li>

        <li><a href="#">Anniversaries</a>
          <ul>
            <li><a href="#">Clan Info</a></li>
            <li><a href="#">Clan Info</a></li>
          </ul>
        </li>

        <li><a href="#">PUZZLES</a>
          <ul>
            <li><a href="#">HELLO</a></li>
            <li><a href="#">HELLO</a></li>
          </ul>
        </li>

        <li><a href="#">Extras</a>
          <ul>
            <li><a href="#">DC Mottos</a></li>
          </ul>
        </li>
      </ul>
    </nav>
  </header>

  <!-- HOME PAGE -->
  <main id="home_page" class="page active">
    <section>
      <p><strong>Đ©</strong> is the short name of the clan, <strong>Đ©</strong> stands for <strong>Đark ©aptains</strong></p>
      <p>Đ© clan was one of the first clans in SDSW community of Miiverse. It started from Đ©Seba_Ω at August 18th of 2014, along with Tristan, Zepher(Pilot) and Leo.</p>
      <p>In order to join, you needed to be Lv.20+ and have a winstreak of 5+. These requirements stopped after 3 months, making it easier for people to join.</p>
      <p>Đ© was making many Chat-Rooms and Tournaments, in which everyone could be part.</p>
      <p>Sometimes, some special contests were taking place, like "Drawing Contests" and "Co-Leader Of The Week", in which Đ© members were selecting a number between 0–10 and the winner could be Co-Leader for 7 days.</p>
      <p>Đ© clan officially stopped in 8 November of 2017, when Nintendo shut down Miiverse, counting 188 members on its list.</p>
      <p>Now Đ© continues unofficially in Facebook and in Amino. Find us there!<br>The clan today has <strong>191 members</strong>.</p>
    </section>

    <section class="contact">
      <h3>In case you want to communicate or join us:</h3>
      <ol>
        <li>Sub Wars FaceBook chat: <strong>ask <a href="https://www.facebook.com/ladaspanos13">Mario</a></strong></li>
        <li>Sub Wars FaceBook group: <a href="https://www.facebook.com/groups/subwars">https://www.facebook.com/groups/subwars</a></li>
        <li>Sub Wars Amino: <a href="https://aminoapps.com/c/SteelDiver/home/">https://aminoapps.com/c/SteelDiver/home/</a></li>
        <li>Email: <strong>steeldiversubwars3@gmail.com</strong></li>
      </ol>
    </section>

    <section>
      <h3>Trivia / Fun facts about Đ©:</h3>
      <ul>
        <li>Đ© is considered the 3rd biggest clan in the history of EU community.
          <ul>
            <li>FS is the biggest team with 350+ members.</li>
            <li>RS was the 2nd biggest clan with 200+ members.</li>
          </ul>
        </li>
        <li>Đ© made the most Tournaments in the history of EU community.</li>
        <li>F1Ray stated for Đ©: "DC is a high-honor society".</li>
      </ul>
    </section>

    <section>
      <h3>Links:</h3>
      <ul>
        <li><a href="#">F1Ray's statement</a></li>
      </ul>
    </section>
  </main>

  <!-- DC LIST PAGE -->
  <main id="dc_list_4" class="page">
    <section>
      <h2>★★ Đ© Member List #4 (11/02/2017) ★★</h2>
      <p>This is the 4th (and last) Đ© Official List of all members that was uploaded in Miiverse on 11 February 2017. It was made by Đ©¹Mario and included 160 members. Next to each member is their ID inside { }.</p>

      <h3>Clan Leadership:</h3>
      <ul>
        <li>001. Đ©¹Mario {MARIO_BY_GREECE}</li>
        <li>002. Đ©²Nemesis {treewii}</li>
        <li>003. Đ©³Joris {Joris100}</li>
        <li>004. Đ©½Noob {csp56_57}</li>
        <li>005. Đ©¼Valco {valcoclive}</li>
        <li>006. Đ©¾Ozee {leedsrule99}</li>
      </ul>

      <h3>Creator of the Clan:</h3>
      <ul>
        <li>008. Đ©_Seba_Ω {sebasb}</li>
      </ul>

      <h3>Older Co-Leaders:</h3>
      <ul>
        <li>007. Đ©Lewis {Lew2205}</li>
        <li>009. Đ©Brand {1965bv}</li>
        <li>010. Đ©Aggelos {AGGELOS1313}</li>
        <li>011. Đ©Bison {SubWarsBison2}</li>
      </ul>

      <h3>All Members:</h3>
      <ul>
        <li>012. Đ©nickolas {nickska1}</li>
        <li>013. Đ©Zeak {swwwweeerr}</li>
        <li>014. Đ©Dino {RGdude}</li>
      </ul>
    </section>
  </main>

  <footer>
    <p>© Dark Captains™</p>
    <p>Đ© now exists in Facebook and in Amino.</p>
  </footer>

  <script>
    (function() {
      // Update CSS var with header height — used by scroll-margin-top
      function updateHeaderHeight(){
        var header = document.querySelector('header');
        if (!header) return;
        var h = header.offsetHeight;
        document.documentElement.style.setProperty('--header-h', h + 'px');
      }
      updateHeaderHeight();
      window.addEventListener('resize', updateHeaderHeight);

      // Page navigation
      const links = document.querySelectorAll('a[data-page]');
      const pages = document.querySelectorAll('.page');

      function showPage(pageId) {
        pages.forEach(p => p.classList.remove('active'));
        const target = document.getElementById(pageId);
        if (target) target.classList.add('active');
        window.scrollTo(0, 0);
      }

      links.forEach(link => {
        link.addEventListener('click', function(e) {
          e.preventDefault();
          const pageId = this.getAttribute('data-page');
          if (pageId) showPage(pageId);
        });
      });

      // Show first page on load
      showPage('home_page');
    })();
  </script>
</body>
</html>
