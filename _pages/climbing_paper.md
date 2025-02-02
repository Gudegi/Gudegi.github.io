---
permalink: /publications/Learning_Climbing_Controllers
---

<html>
<head>
  <meta charset="utf-8">
  <meta name="description"
        content="Learning Climbing Controllers for Physics-Based Characters">
  <meta name="keywords" content="climbing, motion synthesis, physics-based character control">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Learning Climbing Controllers for Physics-Based Characters</title>

  <!-- Global site tag (gtag.js) - Google Analytics -->
  <script async src="https://www.googletagmanager.com/gtag/js?id=G-PYVRSFMDRL"></script>
  <script>
    window.dataLayer = window.dataLayer || [];

    function gtag() {
      dataLayer.push(arguments);
    }

    gtag('js', new Date());

    gtag('config', 'G-PYVRSFMDRL');
  </script>

  <link href="https://fonts.googleapis.com/css?family=Google+Sans|Noto+Sans|Castoro"
        rel="stylesheet">

  <link rel="stylesheet" href="../assets/nerfies_share_template/css/bulma.min.css">
  <link rel="stylesheet" href="../assets/nerfies_share_template/css/bulma-carousel.min.css">
  <link rel="stylesheet" href="../assets/nerfies_share_template/css/bulma-slider.min.css">
  <link rel="stylesheet" href="../assets/nerfies_share_template/css/fontawesome.all.min.css">
  <link rel="stylesheet"
        href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">
  <link rel="stylesheet" href="../assets/nerfies_share_template/css/index.css">
  <link rel="icon" href="../assets/nerfies_share_template/images/favicon.svg"> <!-- use differnt favicon if want -->

  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script defer src="../assets/nerfies_share_template/js/fontawesome.all.min.js"></script>
  <script src="../assets/nerfies_share_template/js/bulma-carousel.min.js"></script>
  <script src="../assets/nerfies_share_template/js/bulma-slider.min.js"></script>
  <script src="../assets/nerfies_share_template/js/index.js"></script>
</head>
<body>

<section class="hero">
  <div class="hero-body">
    <div class="container is-max-desktop">
      <div class="columns is-centered">
        <div class="column has-text-centered">
          <h1 class="title is-1 publication-title">Learning Climbing Controllers for Physics-Based Characters</h1>
          <h4 class="title is-4 journal-title" style="color: green;">Computer Graphics Forum, 2025</h4>
          <div class="is-size-5 publication-authors">
            <span class="author-block">
              <a href="https://gudegi.github.io/">Kyungwon Kang</a><sup>1</sup>,</span>
            <span class="author-block">
              <a >Taehong Gu</a><sup>1</sup>,</span>
            <span class="author-block">
              <a href="http://calab.hanyang.ac.kr/?node=Home">Taesoo Kwon</a><sup>1</sup>,
            </span>
          </div>
          <div class="is-size-5 publication-authors">
            <span class="author-block"><sup>1</sup>Hanyang University</span>
          </div>
          <div class="column has-text-centered">
            <div class="publication-links">
              <!-- PDF Link. -->
              <span class="link-block">
                <a href="https://onlinelibrary.wiley.com/share/author/NMWWIRIQDCF4FG6VK9GX?target=10.1111/cgf.15284"
                   class="external-link button is-normal is-rounded is-dark">
                  <span class="icon">
                      <i class="fas fa-file-pdf"></i>
                  </span>
                  <span>Paper(publisher)</span>
                </a>
              </span>
              <!-- Video Link. -->
              <span class="link-block">
                <a href="https://youtu.be/HL283g6n8Vc"
                   class="external-link button is-normal is-rounded is-dark">
                  <span class="icon">
                      <i class="fab fa-youtube"></i>
                  </span>
                  <span>Video</span>
                </a>
              </span>
              <!-- Code Link. -->
              <span class="link-block">
                <a href=""
                   class="external-link button is-normal is-rounded is-dark">
                  <span class="icon">
                      <i class="fab fa-github"></i>
                  </span>
                  <span>Code(coming soon)</span>
                  </a>
              </span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="hero teaser">
  <div class="container is-max-desktop">
    <div class="hero-body">
      <video id="teaser" autoplay muted loop playsinline height="100%">
        <source src="../assets/video/climb_teaser.mp4"
                type="video/mp4">
      </video>
      <h2 class="subtitle has-text-centered">
        Our controller perceives the environment with depth data and enables climbing to the target.
      </h2>
    </div>
  </div>
</section>

<section class="section">
  <div class="container is-max-desktop">
    <!-- Abstract. -->
    <div class="columns is-centered has-text-centered">
      <div class="column is-four-fifths">
        <h2 class="title is-3">Abstract</h2>
        <div class="content has-text-justified">
          <p>
            Despite the growing demand for capturing diverse motions, collecting climbing motion data remains challenging due to difficulties in tracking obscured markers and scanning climbing structures. Additionally, preparing varied routes further adds to the complexities of the data collection process. 
          </p>
          <p> 
            To address these challenges, this paper introduces a physics-based climbing controller for synthesizing climbing motions. The proposed method consists of two learning stages. In the first stage, a hanging policy is trained to naturally grasp holds. This policy is then used to generate a dataset containing hold positions, postures, and grip states, forming favorable initial poses. In the second stage, a climbing policy is trained using this dataset to perform actual climbing movements. The episode begins in a state close to the reference climbing motion, enabling the exploration of more natural climbing style states. This policy enables the character to reach the target position while utilizing its limbs more evenly.
          </p>
          <p>   
            The experiments demonstrate that the proposed method effectively identifies good climbing postures and enhances limb coordination across environments with varying slopes and hold patterns.
          </p>
        </div>
      </div>
    </div>
    <!--/ Abstract. -->
    <!-- Paper video. -->
    <div class="columns is-centered has-text-centered">
      <div class="column is-four-fifths">
        <h2 class="title is-3">Video</h2>
        <div class="publication-video">
          <iframe src="https://www.youtube.com/embed/HL283g6n8Vc"
                  frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
        </div>
      </div>
    </div>
    <!--/ Paper video. -->
  </div>
</section>

<section class="section" id="BibTeX">
  <div class="container is-max-desktop content">
    <h2 class="title">BibTeX</h2>
    <pre><code>@article{kang2025climbing,
    title = {Learning Climbing Controllers for Physics-Based Characters},
    author = {Kang, Kyungwon and Gu, Taehong and Kwon, Taesoo},
    journal = {Computer Graphics Forum},
    volume = {n/a},
    number = {n/a},
    pages = {e15284},
    year = {2025},
    doi = {https://doi.org/10.1111/cgf.15284},
    publisher = {Wiley Online Library},
}</code></pre>
  </div>
</section>


<footer class="footer">
  <div class="container">
    <div class="columns is-centered">
      <div class="column is-8">
        <div class="content">
          <p>
            This website is licensed under a <a rel="license"
                                                href="http://creativecommons.org/licenses/by-sa/4.0/">Creative
            Commons Attribution-ShareAlike 4.0 International License</a>.
          </p>
          <p>
            Its template is from <a
              href="https://github.com/nerfies/nerfies.github.io">Nerfies</a>.
          </p>
        </div>
      </div>
    </div>
  </div>
</footer>

</body>
</html>
