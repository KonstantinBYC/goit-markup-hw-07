# goit-markup-hw-07

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/modern-normalize/1.0.0/modern-normalize.min.css">

  <!-- fonts! -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link
    href="https://fonts.googleapis.com/css2?family=Raleway:wght@800&family=Roboto:wght@100;400;500;700;900&display=swap"
    rel="stylesheet">
  <link rel="stylesheet" href="./css/tablet.css">
  <link rel="stylesheet" href="./css/styles.css">
  <link rel="stylesheet" href="./css/mobile.css">

</head>

<body>
  <header class="header">

    <div class="container header-container">
      <a href="./index.html" class="header-logo">Web<span>Studio</span></a>

      <button type="button" class="menu-toggle js-open-menu" aria-expanded="false" aria-controls="mobile-menu">

        <svg width="32" height="22" viewBox="0 0 32 22" xmlns="http://www.w3.org/2000/svg">
          <path id="menu-icon" d="M1.34814 20.0431H30.8866M1.34814 10.7354H30.8866M1.34814 1.42773H30.8866"
            stroke="#2E2F42" stroke-width="3" stroke-linecap="round" stroke-linejoin="round" />
        </svg>
      </button>


      <div class="mobile-cont js-menu-container" id="mobile-menu">

        <nav class="header-nav">

          <button type="button" class="x-button close-toggle js-close-menu">
            <svg class="x-icon" width="8" height="8">
              <use href="./images/x-sign.svg#vector"></use>
            </svg>
          </button>

          <ul class="header-ul">
            <li class="header-item"><a class="header-link active link" href="./index.html">Studio</a></li>
            <li class="header-item"><a class="header-link link " href="./portfolio.html">Portfolio</a></li>
            <li class="header-item"><a class="header-link link " href="">Contacts</a></li>
          </ul>
        </nav>

        <div class="address-cont">

          <address class="address">
            <ul class="address-list address-desktop">
              <li class="address-item"><a class="address-mail" href="mailto:info@devstudio.com">info@devstudio.com</a>
              </li>
              <li class="address-item"><a class="address-tel" href="tel:+110001111111">+11 (000) 111-11-11</a></li>
            </ul>
          </address>

          <div class="social-media-header">
            <ul class="header-social-list">
              <li class="header-social-item">
                <a class="header-social-link" href="">
                  <svg class="header-social-icon" width="24" height="24">
                    <use href="./images/symbol-defs.svg#icon-instagram">
                    </use>
                  </svg>
                </a>
              </li>

              <li class="header-social-item">
                <a class="header-social-link" href="">
                  <svg class="header-social-icon" width="24" height="24">
                    <use href="./images/symbol-defs.svg#icon-twitter"></use>
                  </svg>
                </a>
              </li>

              <li class="header-social-item">
                <a class="header-social-link" href="">
                  <svg class="header-social-icon" width="24" height="24">
                    <use href="./images/symbol-defs.svg#icon-facebook"></use>
                  </svg>
                </a>
              </li>

              <li class="header-social-item">
                <a class="header-social-link" href="">
                  <svg class="header-social-icon" width="24" height="24">
                    <use href="./images/symbol-defs.svg#icon-linkedin"></use>
                  </svg>
                </a>
              </li>

            </ul>
          </div>
        </div>

      </div>
      <div class="address-tablet">
        <address class="address">
          <ul class="address-list">

            <li class="address-item"><a class="address-mail" href="mailto:info@devstudio.com">info@devstudio.com</a>
            </li>
            <li class="address-item"><a class="address-tel" href="tel:+110001111111">+11 (000) 111-11-11</a></li>

          </ul>
        </address>
      </div>

    </div>

  </header>
  <!--                     - Hero-                 -->
  <main>
    <!-- Section 1-->
    <section class="hero">
      <div class="container hero-container">
        <h1 class="hero-title">Effective Solutions for Your Business</h1>
        <button type="button" data-modal-open class="hero-button">Order Service</button>
      </div>

    </section>

    <!-- Section 2                           ADVANTAGES                -->
    <section class="advantages">
      <div class="container">
        <h2 class="adv-title visually-hidden">Advantages</h2>
        <ul class="advan-list">
          <li class="advlist-item">

            <div class="adv-icon">
              <svg class="adv-icon-space" width="64" height="64">
                <use href="./images/symbol-defs.svg#icon-antenna"></use>
              </svg>
            </div>
            <h3 class="advantages-item">Strategy</h3>
            <p class="advantages-desc">
              Our goal is to identify the business problem to walk away with the
              perfect and creative solution.
            </p>

          </li>
          <li class="advlist-item">
            <div class="adv-icon">
              <svg class="adv-icon-space" width="64" height="64">
                <use href="./images/symbol-defs.svg#icon-clock"></use>
              </svg>
            </div>
            <h3 class="advantages-item">Punctuality</h3>
            <p class="advantages-desc">
              Bring the key message to the brand's audience for the best price
              within the shortest possible time.
            </p>
          </li>
          <li class="advlist-item">
            <div class="adv-icon">
              <svg class="adv-icon-space" width="64" height="64">
                <use href="./images/symbol-defs.svg#icon-notebook"></use>
              </svg>
            </div>
            <h3 class="advantages-item">Diligence</h3>
            <p class="advantages-desc">
              Research and confirm brands that present the strongest digital
              growth opportunities and minimize risk.
            </p>
          </li>
          <li class="advlist-item">
            <div class="adv-icon">
              <svg class="adv-icon-space" width="64" height="64">
                <use href="./images/symbol-defs.svg#icon-astronaut"></use>
              </svg>
            </div>
            <h3 class="advantages-item">Technologies</h3>
            <p class="advantages-desc">
              Design practice focused on digital experiences. We bring forth a
              deep passion for problem-solving.
            </p>
          </li>
        </ul>

      </div>
    </section>

    <!--                                 Section 3-->
    <section class="product-container">
      <div class="container">
        <h2 class="product">What are we doing</h2>
        <ul class="product-list">
          <li class="product-item"><img srcset="../images/pr-1.jpg 1x, ../images/pr-1@2x.jpg 2x"
              src="../images/pr-1.jpg" alt="Monitor" width="360"></li>
          <li class="product-item"><img srcset="../images/pr-2.jpg 1x, ../images/pr-2@2x.jpg 2x" src="./images/pr-2.jpg"
              alt="Smartphone layers" width="360"></li>
          <li class="product-item"><img srcset="../images/pr-3.jpg 1x, ../images/pr-3@2x.jpg 2x" src="./images/pr-3.jpg"
              alt="Smartphone" width="360"></li>
        </ul>
      </div>
    </section>

    <!--                                  Section 4                   -->
    <section class="ourteam">


      <div class="team-container container">
        <h2 class="team">Our Team</h2>
        <ul class="team-list">

          <li class="team-list-member">
            <img srcset="./images/tm1.jpg 1x, ./images/tm1@2x.jpg 2x" src="./images/tm1.jpg" alt="Mark Guerrero"
              width="264">
            <div class="team-item-text">
              <h3 class="team-member">Mark Guerrero</h3>
              <p class="team-position">Product Designer</p>
              <ul class="team-social-list">
                <li class="team-social-item">
                  <a class="team-social-link" href="">
                    <svg class="team-social-icon" width="16" height="16">
                      <use href="./images/symbol-defs.svg#icon-instagram"></use>
                    </svg>
                  </a>
                </li>
                <li class="team-social-item">
                  <a class="team-social-link" href="">
                    <svg class="team-social-icon" width="16" height="16">
                      <use href="./images/symbol-defs.svg#icon-twitter"></use>
                    </svg>
                  </a>
                </li>
                <li class="team-social-item">
                  <a class="team-social-link" href="">
                    <svg class="team-social-icon" width="16" height="16">
                      <use href="./images/symbol-defs.svg#icon-facebook"></use>
                    </svg>
                  </a>
                </li>
                <li class="team-social-item">
                  <a class="team-social-link" href="">
                    <svg class="team-social-icon" width="16" height="16">
                      <use href="./images/symbol-defs.svg#icon-linkedin"></use>
                    </svg>
                  </a>
                </li>
              </ul>
            </div>

          </li>
          <li class="team-list-member">
            <img srcset="./images/tm2.jpg 1x, ./images/tm2@2x.jpg 2x" src="./images/tm2.jpg" alt="Tom Ford" width="264">
            <div class="team-item-text">
              <h3 class="team-member">Tom Ford</h3>
              <p class="team-position">Frontend Developer</p>

              <ul class="team-social-list">
                <li class="team-social-item">
                  <a class="team-social-link" href="">
                    <svg class="team-social-icon" width="16" height="16">
                      <use href="./images/symbol-defs.svg#icon-instagram"></use>
                    </svg>
                  </a>
                </li>
                <li class="team-social-item">
                  <a class="team-social-link" href="">
                    <svg class="team-social-icon" width="16" height="16">
                      <use href="./images/symbol-defs.svg#icon-twitter"></use>
                    </svg>
                  </a>
                </li>
                <li class="team-social-item">
                  <a class="team-social-link" href="">
                    <svg class="team-social-icon" width="16" height="16">
                      <use href="./images/symbol-defs.svg#icon-facebook"></use>
                    </svg>
                  </a>
                </li>
                <li class="team-social-item">
                  <a class="team-social-link" href="">
                    <svg class="team-social-icon" width="16" height="16">
                      <use href="./images/symbol-defs.svg#icon-linkedin"></use>
                    </svg>
                  </a>
                </li>
              </ul>
            </div>
          </li>
          <li class="team-list-member">
            <img srcset="./images/tm3.jpg 1x, ./images/tm3@2x.jpg 2x" src="./images/tm3.jpg" alt="Camila Garcia"
              width="264">
            <div class="team-item-text">
              <h3 class="team-member">Camila Garcia</h3>
              <p class="team-position">Marketing</p>
              <ul class="team-social-list">
                <li class="team-social-item">
                  <a class="team-social-link" href="">
                    <svg class="team-social-icon" width="16" height="16">
                      <use href="./images/symbol-defs.svg#icon-instagram"></use>
                    </svg>
                  </a>
                </li>
                <li class="team-social-item">
                  <a class="team-social-link" href="">
                    <svg class="team-social-icon" width="16" height="16">
                      <use href="./images/symbol-defs.svg#icon-twitter"></use>
                    </svg>
                  </a>
                </li>
                <li class="team-social-item">
                  <a class="team-social-link" href="">
                    <svg class="team-social-icon" width="16" height="16">
                      <use href="./images/symbol-defs.svg#icon-facebook"></use>
                    </svg>
                  </a>
                </li>
                <li class="team-social-item">
                  <a class="team-social-link" href="">
                    <svg class="team-social-icon" width="16" height="16">
                      <use href="./images/symbol-defs.svg#icon-linkedin"></use>
                    </svg>
                  </a>
                </li>
              </ul>
            </div>
          </li>
          <li class="team-list-member">
            <img srcset="./images/tm4.jpg 1x, ./images/tm4@2x.jpg 2x" src="./images/tm4.jpg" alt="Daniel Wilson"
              width="264">
            <div class="team-item-text">
              <h3 class="team-member">Daniel Wilson</h3>
              <p class="team-position">UI Designer</p>
              <ul class="team-social-list">
                <li class="team-social-item">
                  <a class="team-social-link" href="">
                    <svg class="team-social-icon" width="16" height="16">
                      <use href="./images/symbol-defs.svg#icon-instagram"></use>
                    </svg>
                  </a>
                </li>
                <li class="team-social-item">
                  <a class="team-social-link" href="">
                    <svg class="team-social-icon" width="16" height="16">
                      <use href="./images/symbol-defs.svg#icon-twitter"></use>
                    </svg>
                  </a>
                </li>
                <li class="team-social-item">
                  <a class="team-social-link" href="">
                    <svg class="team-social-icon" width="16" height="16">
                      <use href="./images/symbol-defs.svg#icon-facebook"></use>
                    </svg>
                  </a>
                </li>
                <li class="team-social-item">
                  <a class="team-social-link" href="">
                    <svg class="team-social-icon" width="16" height="16">
                      <use href="./images/symbol-defs.svg#icon-linkedin"></use>
                    </svg>
                  </a>
                </li>
              </ul>
            </div>
          </li>
        </ul>
      </div>
    </section>
    <!--                          CUSTOMERS                    -->
    <section class="customers-section ">
      <h2 class="customers">Customers</h2>
      <div class="customers-container container">


        <ul class="customers-list">
          <li class="customers-item">
            <a class="customers-anc" href="#">
              <svg class="customers-icon">
                <use href="./images/symbol-defs.svg#icon-logo-1"></use>
              </svg>
            </a>

          </li>
          <li class="customers-item">
            <a class="customers-anc" href="#">
              <svg class="customers-icon">
                <use href="./images/symbol-defs.svg#icon-logo-2"></use>
              </svg>
            </a>
          </li>
          <li class="customers-item">
            <a class="customers-anc" href="#">
              <svg class="customers-icon">
                <use href="./images/symbol-defs.svg#icon-logo-3"></use>
              </svg>
            </a>
          </li>
          <li class="customers-item">
            <a class="customers-anc" href="#">
              <svg class="customers-icon">
                <use href="./images/symbol-defs.svg#icon-logo-4"></use>
              </svg>
            </a>
          </li>
          <li class="customers-item">
            <a class="customers-anc" href="#">
              <svg class="customers-icon">
                <use href="./images/symbol-defs.svg#icon-logo-5"></use>
              </svg>
            </a>
          </li>
          <li class="customers-item">
            <a class="customers-anc" href="">
              <svg class="customers-icon">
                <use href="./images/symbol-defs.svg#icon-logo-6"></use>
              </svg>
            </a>
          </li>
        </ul>
      </div>
    </section>

  </main>

  <footer class="footer">
    <div class="footer-container container">
      <div class="footer-container-logo">
        <a href="./index.html" class="footer-logo">Web<span>Studio</span></a>
        <p class="footer-desc">Increase the flow of customers and sales for your business with
          digital marketing &
          growth solutions.</p>
      </div>

      <div class="social-media">
        <p class="footer-social-title">Social media</p>
        <ul class="social-list">
          <li class="social-item">
            <a class="social-link" href="">
              <svg class="social-icon" width="24" height="24">
                <use href="./images/symbol-defs.svg#icon-instagram">
                </use>
              </svg>
            </a>
          </li>
          <li class="social-item">
            <a class="social-link" href="">
              <svg class="social-icon" width="24" height="24">
                <use href="./images/symbol-defs.svg#icon-twitter"></use>
              </svg>
            </a>
          </li>
          <li class="social-item">
            <a class="social-link" href="">
              <svg class="social-icon" width="24" height="24">
                <use href="./images/symbol-defs.svg#icon-facebook"></use>
              </svg>
            </a>
          </li>
          <li class="social-item">
            <a class="social-link" href="">
              <svg class="social-icon" width="24" height="24">
                <use href="./images/symbol-defs.svg#icon-linkedin"></use>
              </svg>
            </a>
          </li>

        </ul>
      </div>
      <!--                      footer form                        -->
      <div class="form-box">
        <p class="subs-title">Subscribe</p>


        <form class="form-fields form-footer">


          <input type="email" class="email-foot" aria-label="email" name="username" id="email-foot"
            placeholder="E-mail" />



          <button type="submit" class="subscribe-but">Subscribe<svg class="icon-send" width="24" height="20">
              <use href="./images/icons.svg#icon-send"></use>
            </svg>
          </button>

        </form>

      </div>
    </div>

  </footer>

  <div class="backdrop is-hidden" data-modal>
    <div class="modal">
      <button class="x-button" data-modal-close type="button">
        <svg class="x-icon" width="8" height="8">
          <use href="./images/x-sign.svg#vector"></use>
        </svg>
      </button>

      <p class="form-title">Leave your contacts and we will call you back</p>

      <form action="#" class="modal-form form">
        <div class="form-input">
          <label class="form-label">
            Name
            <span class="form-span">
              <input type="text" name="user" required class="form-item" />
              <svg class="icon-form" width="18px" height="18px">
                <use href="./images/icons.svg#icon-user"></use>
              </svg>
            </span>
          </label>
        </div>
        <div class="form-input">
          <label class="form-label">
            Phone
            <span class="form-span">
              <input type="tel" name="phone" required class="form-item" />
              <svg class="icon-form" width="18" height="24">
                <use href="./images/icons.svg#icon-phone"></use>
              </svg>
            </span>
          </label>
        </div>

        <div class="form-input">
          <label class="form-label">
            Email
            <span class="form-span">
              <input name="email" required class="form-item" />
              <svg class="icon-form" width="18" height="24">
                <use href="./images/icons.svg#icon-email"></use>
              </svg>
            </span>
          </label>
        </div>

        <div class="form-input-cb">
          <label class="form-label">
            Comment
            <textarea name="comment" class="form-item-area" placeholder="Text input"></textarea>

          </label>
        </div>

        <div class="form-input">

          <input type="checkbox" class="form-privacy visually-hidden" name="privacy" id="privacy" />
          <label class="form-checkbox" for="privacy">
            <span>
              <svg class="icon-check" width="12" height="10">
                <use href="./images/icons.svg#icon-check"></use>
              </svg></span>
            <span> I accept the terms and conditions of the&nbsp;<a class="privacy" href="#">Privacy
                Policy</a></span></label>
        </div>

        <button type="submit" class="send-button">Send</button>



      </form>
    </div>

  </div>

  <script defer src="https://cdnjs.cloudflare.com/ajax/libs/body-scroll-lock/3.1.5/bodyScrollLock.min.js"
    integrity="sha512-HowizSDbQl7UPEAsPnvJHlQsnBmU2YMrv7KkTBulTLEGz9chfBoWYyZJL+MUO6p/yBuuMO/8jI7O29YRZ2uBlA=="
    crossorigin="anonymous"></script>
  <script defer src="js/mobile-menu.js"></script>
  <script src="./js/modal.js"></script>
</body>

</html>
