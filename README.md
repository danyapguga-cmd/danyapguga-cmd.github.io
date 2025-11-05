# danyapguga-cmd.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Should Video Games Be Considered a Sport? | ENG-1A Blog</title>
  <meta name="description" content="An ENG-1A blog essay presented in a New York Times–style article layout about whether esports should be considered sports." />
  <!-- NYT-ish typography via Google Fonts (free & permissible) -->
  <link href="https://fonts.googleapis.com/css2?family=Crimson+Text:ital,wght@0,400;0,600;0,700;1,400;1,600&family=Libre+Franklin:wght@300;400;500;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --ink: #111;
      --muted: #666;
      --rule: #e5e5e5;
      --accent: #0a0a0a;
      --maxw: 760px; /* NYT article column width ~700–800px */
    }

    * { box-sizing: border-box; }
    html, body { height: 100%; }
    body {
      margin: 0;
      color: var(--ink);
      background: #fff;
      font-family: 'Crimson Text', Georgia, 'Times New Roman', Times, serif;
      line-height: 1.65;
      -webkit-font-smoothing: antialiased;
      text-rendering: optimizeLegibility;
    }

    /* Masthead */
    .masthead {
      font-family: 'Libre Franklin', system-ui, -apple-system, Segoe UI, Roboto, 'Helvetica Neue', Arial, sans-serif;
      letter-spacing: .08em;
      text-transform: uppercase;
      font-weight: 700;
      font-size: 14px;
      padding: 18px 0 8px;
      text-align: center;
      border-bottom: 1px solid var(--rule);
    }

    .wrapper { max-width: var(--maxw); margin: 0 auto; padding: 0 18px; }

    header.article-head { text-align: left; padding: 24px 0 8px; }
    .kicker {
      font-family: 'Libre Franklin', system-ui, -apple-system, Segoe UI, Roboto, 'Helvetica Neue', Arial, sans-serif;
      text-transform: uppercase;
      letter-spacing: .09em;
      color: var(--muted);
      font-size: 12px;
      margin-bottom: 8px;
    }
    h1.headline {
      font-weight: 700;
      font-size: clamp(30px, 5vw, 48px);
      line-height: 1.1;
      margin: 0 0 10px;
    }
    .deck {
      font-size: clamp(18px, 2.4vw, 22px);
      color: #222;
      font-style: italic;
      margin: 6px 0 14px;
    }
    .byline {
      font-family: 'Libre Franklin', system-ui, -apple-system, Segoe UI, Roboto, 'Helvetica Neue', Arial, sans-serif;
      font-size: 13px;
      color: var(--muted);
      margin-bottom: 18px;
    }
    .byline strong { color: var(--ink); font-weight: 700; }
    .rule { height: 1px; background: var(--rule); margin: 18px 0 24px; }

    article.story p { font-size: 20px; margin: 0 0 18px; }
    article.story p + p { margin-top: 0; }

    /* Drop cap for the very first paragraph of the article body */
    .article-body p:first-of-type::first-letter {
      float: left;
      font-size: 74px;
      line-height: .85;
      padding-right: 8px;
      padding-top: 6px;
      font-weight: 700;
    }

    /* Section heads */
    h2.section-hed {
      font-family: 'Libre Franklin', system-ui, -apple-system, Segoe UI, Roboto, 'Helvetica Neue', Arial, sans-serif;
      font-weight: 700;
      text-transform: none;
      font-size: clamp(18px, 2.2vw, 22px);
      letter-spacing: .01em;
      margin: 28px 0 10px;
      border-top: 1px solid var(--rule);
      padding-top: 18px;
    }

    /* Figures with NYT-ish captions */
    figure { margin: 22px 0; }
    figure img, figure .ph {
      display: block;
      width: 100%;
      height: auto;
      border: 1px solid var(--rule);
      background: #f9f9f9;
    }
    /* Added for split-screen figure */
    .photo img { width: 100%; height: auto; display: block; }
    .photo.two-up { display: flex; gap: 1rem; }
    .photo.two-up img { width: 50%; }

    .ph { aspect-ratio: 16/9; display: grid; place-items: center; color: var(--muted); font-family: 'Libre Franklin', system-ui, -apple-system, Segoe UI, Roboto, 'Helvetica Neue', Arial, sans-serif; font-size: 13px; }
    figcaption {
      font-family: 'Libre Franklin', system-ui, -apple-system, Segoe UI, Roboto, 'Helvetica Neue', Arial, sans-serif;
      font-size: 12px;
      color: var(--muted);
      line-height: 1.4;
      margin-top: 6px;
    }

    /* Pullquote option (not used by default, but available) */
    .pullquote {
      font-size: clamp(20px, 2.4vw, 24px);
      line-height: 1.4;
      font-style: italic;
      border-left: 3px solid var(--rule);
      padding-left: 14px;
      margin: 24px 0;
      color: #222;
    }

    /* Links */
    a { color: inherit; text-decoration-thickness: 1px; text-underline-offset: 3px; }
    a:hover { text-decoration-thickness: 2px; }

    /* Works Cited — hanging indents like an academic bib */
    #works-cited ol { list-style: decimal; padding-left: 24px; }
    #works-cited li { margin: 0 0 10px; }
    #works-cited li > span { display: block; padding-left: 14px; text-indent: -14px; }

    /* Footer */
    footer { color: var(--muted); font-family: 'Libre Franklin', system-ui, -apple-system, Segoe UI, Roboto, 'Helvetica Neue', Arial, sans-serif; font-size: 12px; text-align: center; padding: 28px 0 60px; border-top: 1px solid var(--rule); margin-top: 36px; }

    /* Print tweaks */
    @media print {
      .masthead { border-bottom: none; }
      .rule { display: none; }
      a[href^="http"]::after { content: " (" attr(href) ")"; font-size: 10px; color: #999; }
      body { color: #000; }
    }
  </style>
</head>
<body>
  <div class="masthead">ENG-1A • Blog</div>

  <div class="wrapper">
    <header class="article-head" role="banner">
      <div class="kicker">Opinion • Sports & Culture</div>
      <h1 class="headline">Should Video Games Be Considered a Sport?</h1>
      <p class="deck">Esports demand skill, training, and organized competition—and they draw audiences rivaling traditional games. So why isn’t everyone calling them sports?</p>
      <div class="byline">By <strong>Danya</strong> · <time datetime="2025-11-05">November 5, 2025</time></div>
      <div class="rule" aria-hidden="true"></div>
    </header>

    <article class="story" role="article">
      <!-- Meme / lead image (open-license substitute for Pepe) -->
      <figure class="photo">
        <img src="https://upload.wikimedia.org/wikipedia/commons/d/d4/Twemoji_1f620.svg"
             alt="Angry face emoji reacting to the phrase ‘Esports isn’t a real sport.’" loading="lazy">
        <figcaption>
          The debate over whether esports count as sports sparks strong reactions.
          <br><small>Image: Twemoji “Angry Face” by Twitter, licensed
          <a href="https://creativecommons.org/licenses/by/4.0/" target="_blank" rel="noopener">CC BY 4.0</a>.
          Source: <a href="https://commons.wikimedia.org/wiki/File:Twemoji_1f620.svg" target="_blank" rel="noopener">Wikimedia Commons</a>.</small>
        </figcaption>
      </figure>

      <section class="article-body" id="intro">
        <h2 class="section-hed">Section 1: Introduction</h2>
        <p>Video games have grown from hobbies into a massive global industry. Millions of people play for fun, but millions more watch professional players compete. In 2023, the League of Legends World Championship drew over six million peak viewers online, more than the NBA Finals that same year, according to Esports Insider.</p>
        <p>Traditionally, sports are defined by skill, competition, and physical movement. Basketball, soccer, and football are easy to recognize because they involve running, jumping, and teamwork. Esports are different: athletes use their hands, eyes, and minds more than their whole bodies. This difference has sparked debate about whether video games should be considered sports.</p>
        <p>This blog argues that esports deserve recognition as sports because they require skill and training, involve organized competition, and attract huge audiences. Critics say esports lack physical exertion, but looking at both sides shows how they fit into the modern idea of sport.</p>
      </section>

      <section id="skills-competition">
        <h2 class="section-hed">Section 2: Skills and Competition</h2>

        <figure class="photo">
          <img src="https://upload.wikimedia.org/wikipedia/commons/7/7c/Yongsan_esports_stadium.jpg"
               alt="Pro players practicing on stage at Yongsan Esports Stadium" loading="lazy">
          <figcaption>
            Pro players train up to 10 hours a day, just like traditional athletes.
            <br><small>Photo:
            <a href="https://commons.wikimedia.org/wiki/File:Yongsan_esports_stadium.jpg" target="_blank" rel="noopener">Yongsan Esports Stadium</a>
            by Altostratus, licensed
            <a href="https://creativecommons.org/licenses/by-sa/3.0/" target="_blank" rel="noopener">CC BY-SA 3.0</a>.</small>
          </figcaption>
        </figure>

        <p>Esports demand serious skill and discipline. Professional players train eight to twelve hours daily, working on reflexes, communication, and strategies, according to The Washington Post. Reaction times are measured at 150 to 200 milliseconds, as fast as baseball players hitting a pitch. Many teams also hire coaches, nutritionists, and psychologists to keep players healthy and focused. Teamwork is essential, with players needing to trust and coordinate under pressure, just like in basketball or soccer.</p>

        <figure class="photo">
          <img src="https://upload.wikimedia.org/wikipedia/commons/f/f4/League_of_Legends_World_Championship_2017_Finals.jpg"
               alt="League of Legends World Championship 2017 Finals in Beijing National Stadium" loading="lazy">
          <figcaption>
            Esports tournaments now fill stadiums worldwide.
            <br><small>Photo:
            <a href="https://commons.wikimedia.org/wiki/File:League_of_Legends_World_Championship_2017_Finals.jpg" target="_blank" rel="noopener">Richard Ye</a>,
            licensed <a href="https://creativecommons.org/licenses/by-sa/2.0/" target="_blank" rel="noopener">CC BY-SA 2.0</a>.</small>
          </figcaption>
        </figure>

        <p>Esports competitions are highly organized. Major tournaments like The International for Dota 2 or the Overwatch League offer prize pools of over thirty million dollars. Teams sign contracts, train together, and travel internationally, much like NBA or FIFA teams. Colleges now offer scholarships for esports athletes, showing that esports are taken seriously both professionally and academically.</p>
        <p>This structure proves esports are not casual games but professional competitions with strict rules, high stakes, and global recognition.</p>
      </section>

      <section id="spectatorship-conclusion">
        <h2 class="section-hed">Section 3: Spectatorship, Counterargument, and Conclusion</h2>

        <figure class="photo">
          <img src="https://upload.wikimedia.org/wikipedia/commons/b/b9/IEM_Katowice_Major_2019.jpg"
               alt="Fans cheering at IEM Katowice Major 2019" loading="lazy">
          <figcaption>
            Esports fans show the same passion as traditional sports audiences.
            <br><small>Photo:
            <a href="https://commons.wikimedia.org/wiki/File:IEM_Katowice_Major_2019.jpg" target="_blank" rel="noopener">Esports Kingdom</a>,
            licensed <a href="https://creativecommons.org/licenses/by/2.0/" target="_blank" rel="noopener">CC BY 2.0</a>.</small>
          </figcaption>
        </figure>

        <p>Esports attract massive audiences. Millions watch live streams on Twitch and YouTube, and stadiums sell out for finals. Sponsors like Coca-Cola, Intel, and Nike invest heavily, proving esports’ cultural impact. Fans wear jerseys, follow teams, and debate strategies, just like traditional sports fans. Esports also create careers for commentators, organizers, and streamers, building an ecosystem similar to traditional sports.</p>
        <p>Critics argue esports are not sports because they lack physical exertion. The International Olympic Committee defines sports as involving physical effort and skill. Esports rely more on mental agility and hand-eye coordination. One article from TheBoBs calls video games “a pleasurable pastime, a hobby, but not a sport.” While this reflects traditional views, it ignores that chess, archery, and shooting are recognized sports despite focusing more on precision than physical strength. Esports fit into this category, testing reflexes and coordination.</p>

        <!-- Split screen — football vs. esports -->
        <figure class="photo two-up">
          <img src="https://upload.wikimedia.org/wikipedia/commons/e/ee/Levisstadium.jpg"
               alt="American football at Levi’s Stadium, Santa Clara" loading="lazy">
          <img src="https://upload.wikimedia.org/wikipedia/commons/f/f4/League_of_Legends_World_Championship_2017_Finals.jpg"
               alt="Esports arena during the 2017 League of Legends World Championship" loading="lazy">
          <figcaption>
            The definition of sport is evolving in the digital age.
            <br><small>Left:
            <a href="https://commons.wikimedia.org/wiki/File:Levisstadium.jpg" target="_blank" rel="noopener">Levi’s Stadium</a>
            by Travis Wise, <a href="https://creativecommons.org/licenses/by/2.0/" target="_blank" rel="noopener">CC BY 2.0</a>.
            Right:
            <a href="https://commons.wikimedia.org/wiki/File:League_of_Legends_World_Championship_2017_Finals.jpg" target="_blank" rel="noopener">Worlds 2017 Finals</a>
            by Richard Ye, <a href="https://creativecommons.org/licenses/by-sa/2.0/" target="_blank" rel="noopener">CC BY-SA 2.0</a>.</small>
          </figcaption>
        </figure>

        <h3 class="section-hed" style="border-top: none; padding-top: 0;">Conclusion</h3>
        <p>Esports require skill, training, organization, and attract huge audiences, all of which align them with traditional sports. While critics focus on physical exertion, esports highlight mental and reflex-based competition. Video games should be considered sports because they embody dedication, teamwork, and cultural impact. As technology reshapes culture, the definition of sport must evolve to include esports.</p>
      </section>

      <section id="works-cited">
        <h2 class="section-hed">Works Cited</h2>
        <ol>
          <li><span>TheBoBs. “Why Should Video Games Not Be Considered a Sport.” <em>TheBoBs</em>, 2023. <a href="https://thebobs.com/why-should-video-games-not-be-considered-a-sport" target="_blank" rel="noopener">thebobs.com/why-should-video-games-not-be-considered-a-sport</a>.</span></li>
          <li><span>Wingfield, Nick. “In E-Sports, Video Gamers Draw Real Crowds and Big Money.” <em>The New York Times</em>, 30 Aug. 2014. <a href="https://www.nytimes.com/2014/08/31/technology/esports-explosion-brings-opportunity-riches-for-video-gamers.html" target="_blank" rel="noopener">nytimes.com/2014/08/31/technology/…</a>.</span></li>
          <li><span>Baxter, Daryl. “What Is Esports? A Beginner’s Guide to Competitive Gaming.” <em>Esports Insider</em>, 6 June 2025. <a href="https://esportsinsider.com/explainers/what-is-esports" target="_blank" rel="noopener">esportsinsider.com/explainers/what-is-esports</a>.</span></li>
          <li><span>Escharts. “League of Legends World Championship Viewership.” <em>Esports Charts</em>, 2023. <a href="https://escharts.com" target="_blank" rel="noopener">escharts.com</a>.</span></li>
        </ol>
      </section>
    </article>

    <footer>
      <div>© <span id="year">2025</span> ENG-1A • Layout inspired by classic newspaper design for educational use.</div>
    </footer>
  </div>

  <script>
    // Update year automatically
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>

