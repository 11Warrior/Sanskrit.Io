<script>
  let chapters = Array.from({ length: 18 }, (_, i) => i + 1);

  let isMenuOpen = false;
  function toggleHamMenu() {
    isMenuOpen = !isMenuOpen;
  }
  function openChapter(num) {
    console.log("Open chapter", num);
    // Later you will navigate to verse page & call API
  }
</script>

<!-- NAVBAR -->
<nav class="navbar">
  <div class="nav-left">
    <img src="https://sanskrit.ie/images/logo.png" alt="logo" />
  </div>

  <div class="hamburger" on:click={() => toggleHamMenu()}>&#9776;</div>

  <div class="nav-right">

    <div class="search">
      <a href="#" class="search-link"><i class="fa fa-search" /></a>
      <div class="line"></div>
    </div>
    <div class="link">
      <a href="#"
        >ĀYURVEDA
        <svg
          class="caret-icon"
          width="10"
          height="10"
          viewBox="0 0 24 24"
          fill="none"
          stroke="currentColor"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <polyline points="6 9 12 15 18 9"></polyline>
        </svg>
      </a>
      <ul class="drop-menu">
        <li>Introduction</li>
        <li>Timing</li>
        <li>Food</li>
      </ul>
      <div class="line"></div>
    </div>

    <div class="link">
      <a href="#"
        >YOGASŪTRAS
        <svg
          class="caret-icon"
          width="10"
          height="10"
          viewBox="0 0 24 24"
          fill="none"
          stroke="currentColor"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <polyline points="6 9 12 15 18 9"></polyline>
        </svg>
      </a>
      <ul class="drop-menu">
        <li>Introduction</li>
        <li>Obstacles</li>
        <li>Practices</li>
        <li>Yogāsana</li>
        <li>Glossary</li>
      </ul>
      <div class="line"></div>
    </div>

    <div class="link">
      <a href="#">BHAGAVAD GĪTĀ</a>

      <div class="line"></div>
    </div>
    <div class="link">
      <a href="#"
        >UPANIṢADS
        <svg
          class="caret-icon"
          width="10"
          height="10"
          viewBox="0 0 24 24"
          fill="none"
          stroke="currentColor"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <polyline points="6 9 12 15 18 9"></polyline>
        </svg>
      </a>
      <ul class="drop-menu">
        <li>ĪŚOPANIṢAD</li>
        <li>TAITTIRĪYOPANIṢAD</li>
        <li>MĀṆḌŪKYOPANIṢAD</li>
        <li>KENOPANIṢAD</li>
        <li>KAṬHOPANIṢAD</li>
        <li>AITAREYOPANIṢAD</li>
        <li>MUṆḌAKOPANIṢAD</li>
        <li>PRAŚNOPANIṢAD</li>
      </ul>
      <div class="line"></div>
    </div>

    <div class="link">
      <a href="#"
        >SANSKRIT
        <svg
          class="caret-icon"
          width="10"
          height="10"
          viewBox="0 0 24 24"
          fill="none"
          stroke="currentColor"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <polyline points="6 9 12 15 18 9"></polyline>
        </svg>
      </a>
      <ul class="drop-menu">
        <li>Devotional Songs</li>
        <li>Grammar Songs</li>
        <li>Fun Songs</li>
        <li>Script Songs</li>
      </ul>
      <div class="line"></div>
    </div>

    <div class="link">
      <a href="#">CONTACT US</a>
      <div class="line"></div>
    </div>
  </div>

</nav>

{#if isMenuOpen}
  <div class="ham-menu">
    <div class="search">
      <a href="#" class="search-link"><i class="fa fa-search" /></a>
      <div class="line"></div>
    </div>

    <div class="link">
      <a href="#"
        >ĀYURVEDA
        <svg
          class="caret-icon"
          width="10"
          height="10"
          viewBox="0 0 24 24"
          fill="none"
          stroke="currentColor"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <polyline points="6 9 12 15 18 9"></polyline>
        </svg>
      </a>
      <ul class="drop-menu">
        <li>Introduction</li>
        <li>Timing</li>
        <li>Food</li>
      </ul>
      <div class="line"></div>
    </div>

    <div class="link">
      <a href="#"
        >YOGASŪTRAS
        <svg
          class="caret-icon"
          width="10"
          height="10"
          viewBox="0 0 24 24"
          fill="none"
          stroke="currentColor"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <polyline points="6 9 12 15 18 9"></polyline>
        </svg>
      </a>
      <ul class="drop-menu">
        <li>Introduction</li>
        <li>Obstacles</li>
        <li>Practices</li>
        <li>Yogāsana</li>
        <li>Glossary</li>
      </ul>
      <div class="line"></div>
    </div>

    <div class="link">
      <a href="#">BHAGAVAD GĪTĀ</a>

      <div class="line"></div>
    </div>

    <div class="link">
      <a href="#"
        >UPANIṢADS
        <svg
          class="caret-icon"
          width="10"
          height="10"
          viewBox="0 0 24 24"
          fill="none"
          stroke="currentColor"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <polyline points="6 9 12 15 18 9"></polyline>
        </svg>
      </a>
      <ul class="drop-menu">
        <li>ĪŚOPANIṢAD</li>
        <li>TAITTIRĪYOPANIṢAD</li>
        <li>MĀṆḌŪKYOPANIṢAD</li>
        <li>KENOPANIṢAD</li>
        <li>KAṬHOPANIṢAD</li>
        <li>AITAREYOPANIṢAD</li>
        <li>MUṆḌAKOPANIṢAD</li>
        <li>PRAŚNOPANIṢAD</li>
      </ul>
      <div class="line"></div>
    </div>

    <div class="link">
      <a href="#"
        >SANSKRIT
        <svg
          class="caret-icon"
          width="10"
          height="10"
          viewBox="0 0 24 24"
          fill="none"
          stroke="currentColor"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <polyline points="6 9 12 15 18 9"></polyline>
        </svg>
      </a>
      <ul class="drop-menu">
        <li>Devotional Songs</li>
        <li>Grammar Songs</li>
        <li>Fun Songs</li>
        <li>Script Songs</li>
      </ul>
      <div class="line"></div>
    </div>

    <div class="link">
      <a href="#">CONTACT US</a>
      <div class="line"></div>
    </div>
  </div>
{/if}

<div id="app">
  <!-- HERO IMAGE -->
  <div class="hero">
    <div class="hero-image">
      <h1>BHAGAVAD GEETA</h1>
      <div class="book">
        <img src="/images/book.png" alt="" />
      </div>
      <!-- <img src="/images/gita_banner.png" alt="" /> -->
    </div>
  </div>

  <!-- CHAPTER GRID -->
  <section class="chapters">
    <div class="section-title">GITA CHAPTERS</div>
    <div class="chapter-grid">
      {#each chapters as num}
        <div class="chapter-card" on:click={() => openChapter(num)}>
          <div class="chapter-image">
            <img src="/images/gita_book.jpg" alt="" />
          </div>
          <div class="chapter-number"><div class="number">{num}</div></div>
        </div>
      {/each}
    </div>
  </section>

  <footer>
    <div class="footer-contents">
      <div class="socials">
        <ul>
          <li>
            <h3>Connect</h3>
          </li>

          <li>
            <a href="">
              <i class="fa fa-facebook" aria-hidden="true"></i>
            </a>
          </li>

          <li>
            <a href="">
              <i class="fa fa-twitter" aria-hidden="true"></i>
            </a>
          </li>

          <li>
            <a href="">
              <i class="fa fa-youtube" aria-hidden="true"></i>
            </a>
          </li>

          <li>
            <a href="">
              <i class="fa fa-safari" aria-hidden="true"></i>
            </a>
          </li>
        </ul>
      </div>

      <div class="footer-logo">
        <img src="/images/footer-logo.png" alt="" />
      </div>

      <div class="footer-heading">
        <h1>WELLBEING~SVASTI</h1>
      </div>

      <div class="rights">
        <p>
          © 2025 Rutger Kortenhorst. All Rights Reserved | Design and Developed
          by
          <br /> <span> Burning Desire Inclusive</span>
        </p>
      </div>
    </div>
  </footer>
</div>
