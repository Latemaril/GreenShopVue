<template>
  <div class="wrapper">
    <!-- MOBILE-NAVIGATION -->
    <nav class="navigation">
      <div class="navigation__menu">
        <div class="navigation__div_img">
          <img :src="'src/assets/img/Navigation.svg'" alt="" class="navigation__img">
        </div>
        <div class="navigation__div_button">
          <button class="navigation__button"><img :src="'src/assets/img/Filter.svg'" class="search__img" alt=""></button>
        </div>
        <div class="navigation__imgContainer">
          <div class="navigation__list">
            <ul class="nav__mobile_container">
              <li class="nav__item">
                <a href="#" class="navigation__link">
                  <svg xmlns="http://www.w3.org/2000/svg" width="16" height="18" viewBox="0 0 16 18" fill="none">
                    <path d="M5.61199 16.3111V13.763C5.61199 13.1125 6.14315 12.5852 6.79837 12.5852H9.19352C9.50816
                       12.5852 9.80992 12.7093 10.0324 12.9302C10.2549 13.1511 10.3799 13.4506 10.3799 13.763V16.3111C10.3779
                       16.5815 10.4847 16.8416 10.6766 17.0335C10.8686 17.2254 11.1297 17.3333 11.4021 17.3333H13.0362C13.7994
                       17.3353 14.532 17.0357 15.0723 16.5007C15.6127 15.9656 15.9163 15.2391 15.9163 14.4815V7.22237C15.9163
                       6.61037 15.6431 6.02986 15.1702 5.63721L9.61136 1.22988C8.64439 0.457125 7.25893 0.482075 6.32083 1.28914L0.888851
                       5.63721C0.393625 6.01828 0.0976347 6.60052 0.0830078 7.22237V14.4741C0.0830078 16.0532 1.37249 17.3333 2.96315
                       17.3333H4.55992C5.1257 17.3333 5.58551 16.8802 5.58961 16.3185L5.61199 16.3111Z" fill="#46A358"
                    />
                  </svg>
                </a>
              </li>
              <li class="nav__item">
                <a href="#" class="navigation__link">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="18" viewBox="0 0 20 18" fill="none">
                    <path d="M18.4134 1.74133C17.3781 0.618439 15.9575 0 14.413 0C13.2585 0 12.2012 0.36499 11.2704 1.08475C10.8008 1.44806 10.3752 1.89255 10 2.41135C9.62494 1.8927 9.19922 1.44806 8.7294 1.08475C7.79877 0.36499 6.74149 0 5.58701 0C4.04251 0 2.62177 0.618439 1.58646 1.74133C0.563507 2.8511 0 4.36722 0 6.01059C0 7.70203 0.630341 9.25034 1.98364 10.8833C3.19427 12.3441 4.93423 13.8269 6.94916 15.544C7.63718 16.1304 8.41705 16.795 9.22684 17.5031C9.44077 17.6904 9.71527 17.7936 10 17.7936C10.2846 17.7936 10.5592 17.6904 10.7729 17.5034C11.5826 16.7952 12.363 16.1302 13.0513 15.5435C15.0659 13.8268 16.8059 12.3441 18.0165 10.8832C19.3698 9.25034 20 7.70203 20 6.01044C20 4.36722 19.4365 2.8511 18.4134 1.74133Z" fill="#D9D9D9"/>
                  </svg>
                </a>
              </li>
            </ul>
            <ul class="nav__mobile_container">
              <li class="nav__item">
                <a href="#" class="navigation__link">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20" fill="none">
                    <path d="M18.333 6.80134L17.3894 12.7778C17.2178 13.9562 16.2742 14.7138 15.0732 14.7138H6.83791C5.72271 14.7138 4.6933 13.872 4.52173 12.7778L3.49232 5.79124L3.23497 3.85521C3.14918 3.35016 2.72026 3.01346 2.11977 3.01346H1.51928C1.17615 3.01346 0.833008 2.67676 0.833008 2.34006C0.833008 2.00336 1.17615 1.66666 1.51928 1.66666H2.11977C3.32075 1.66666 4.35016 2.50841 4.43595 3.68686L4.60752 5.03366H16.7889C17.2178 5.03366 17.6467 5.20201 17.9041 5.53871C18.2472 5.87541 18.333 6.38046 18.333 6.80134Z" fill="#D9D9D9"/>
                    <path d="M15.2448 18.3333C15.7185 18.3333 16.1026 17.9565 16.1026 17.4916C16.1026 17.0267 15.7185 16.6498 15.2448 16.6498C14.771 16.6498 14.3869 17.0267 14.3869 17.4916C14.3869 17.9565 14.771 18.3333 15.2448 18.3333Z" fill="#D9D9D9"/>
                    <path d="M6.66634 18.3333C7.14012 18.3333 7.52418 17.9565 7.52418 17.4916C7.52418 17.0267 7.14012 16.6498 6.66634 16.6498C6.19257 16.6498 5.8085 17.0267 5.8085 17.4916C5.8085 17.9565 6.19257 18.3333 6.66634 18.3333Z" fill="#D9D9D9"/>
                  </svg>
                </a>
              </li>
              <li class="nav__item">
                <a href="#" class="navigation__link">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20" fill="none">
                    <path d="M9.99967 9.82998C12.2655 9.82998 14.1022 8.00257 14.1022 5.74835C14.1022 3.49413 12.2655 1.66672 9.99967 1.66672C7.73389 1.66672 5.89711 3.49413 5.89711 5.74835C5.89711 8.00257 7.73389 9.82998 9.99967 9.82998Z" fill="#D9D9D9"/>
                    <path d="M12.1364 11.5307H7.86292C5.38429 11.5307 3.33301 13.5716 3.33301 16.0375C3.33301 16.6328 3.58942 17.143 4.10224 17.3981C4.87147 17.8233 6.58087 18.3335 9.99967 18.3335C13.4185 18.3335 15.1279 17.8233 15.8971 17.3981C16.3245 17.143 16.6663 16.6328 16.6663 16.0375C16.6663 13.4865 14.6151 11.5307 12.1364 11.5307Z" fill="#D9D9D9"/>
                  </svg>
                </a>
              </li>
            </ul>
          </div>

        </div>
      </div>
    </nav>

    <!-- SEARCH -->
    <div class="search">
      <div class="search__container">

        <div class="text-field">
          <div class="text-field__icon">
            <svg class="text-field__icon_search" xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 22 22" fill="none">
              <path fill-rule="evenodd" clip-rule="evenodd" d="M10.5296 3.2436C6.50469 3.2436 3.24326 6.50244 3.24326 10.5207C3.24326 14.539 6.50469 17.7978 10.5296 17.7978C12.5376 17.7978 14.3546 16.9875 15.6732 15.675C16.9977 14.3566 17.8159 12.5347 17.8159 10.5207C17.8159 6.50244 14.5545 3.2436 10.5296 3.2436ZM1.83301 10.5207C1.83301 5.72204 5.72737 1.83334 10.5296 1.83334C15.3318 1.83334 19.2262 5.72204 19.2262 10.5207C19.2262 12.6706 18.4436 14.6389 17.149 16.1554L19.9595 18.9627C20.2351 19.2379 20.2353 19.6843 19.9601 19.9599C19.6849 20.2354 19.2384 20.2356 18.9629 19.9604L16.1497 17.1505C14.6343 18.4335 12.6719 19.2081 10.5296 19.2081C5.72737 19.2081 1.83301 15.3194 1.83301 10.5207Z" fill="#A5A5A5"/>
            </svg>
            <input class="text-field__input" type="" placeholder="Find you planets" value="">
          </div>
        </div>
        <!-- <div class="mheader__search"><img src="" alt="">Find your plants</div>
        <button class="mheader__filtre"><img src="" alt=""></button> -->
      </div>
    </div>

    <!-- HEADER -->
    <header class="header">
      <!-- HEADER -->
      <div class="container">
        <div class="header__top-row">
          <a href="index.html">
            <img :src="'src/assets/img/header/logo.png'" alt="Greenshop">
          </a>
          <div class="header__nav">
            <nav class="nav">
              <ul class="nav__list">
                <li class="nav__item nav__item_active"><a href="#">Home</a></li>
                <li class="nav__item"><a href="#">Shop</a></li>
                <li class="nav__item"><a href="#">Blogs</a></li>
              </ul>
            </nav>
          </div>
          <div class="header__right">
            <div class="header__cart">
              <a href="product_cart.html">
                <img class="header__cart" :src="'src/assets/img/header/cart.svg'" alt="Cart">
              </a>
            </div>
            <div class="header__login">
              <a href="login.html">
                <button class="header__button">
                  <svg class="header__logout" width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M18.1601 10.1006H8.12598" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M15.7212 7.67059L18.1612 10.1006L15.7212 12.5306" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M13.6342 6.35823C13.3592 3.3749 12.2425 2.29156 7.80082 2.29156C1.88332 2.29156 1.88332 4.21656 1.88332 9.9999C1.88332 15.7832 1.88332 17.7082 7.80082 17.7082C12.2425 17.7082 13.3592 16.6249 13.6342 13.6416" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                  </svg>
                  Login
                </button>
              </a>
            </div>
          </div>
        </div>
      </div>
    </header>

    <!-- SLIDER -->
    <div class="slider">
      <div class="slider-slides">
        <div class="slider-slide">
          <img class="slider__mobile" :src="'src/assets/img/Banner-test2.png'" alt="">
          <img class="slider__desc" :src="'src/assets/img/main_banner.png'" alt="">
          <div class="slider__img">

          </div>
        </div>
      </div>
    </div>
    <!-- Products -->
    <div class="products">
      <div class="products__container">
        <!-- Categories -->
        <div class="categories">
          <div class="categories__container">
            <div class="categories__block">
              <h1 class="categories__text">Categories</h1>
              <div class="categories__content">
                <div class="categories__leftColumn">
                  <ul>
                    <li><a href="#">House Plants </a></li>
                    <li><a href="#">Potter Plants </a></li>
                    <li><a href="#">Seeds  </a></li>
                    <li><a href="#">Small Plants</a></li>
                    <li><a href="#">Big Plants</a></li>
                    <li><a href="#">Succulents</a></li>
                    <li><a href="#">Trerrariums</a></li>
                    <li><a href="#">Gardening </a></li>
                    <li><a href="#">Accessories</a></li>
                  </ul>
                </div>
                <div class="categories__rightColumn">
                  <ul>
                    <li>(33)</li>
                    <li>(12)</li>
                    <li>(65)</li>
                    <li>(39)</li>
                    <li>(23)</li>
                    <li>(17)</li>
                    <li>(19)</li>
                    <li>(13)</li>
                    <li>(18)</li>
                  </ul>
                </div>
              </div>
            </div>
            <div class="categories__price">
              <h1 class="categories__range">Price Range</h1>
              <div class="categories__sildeContainer">
                <input type="range" min="39" max="2000" value="1" id="categories__range" class="categories__slider">
                <p class="categories__price-text">Price: <span id="value">39$ - 1230$</span></p>
              </div>
              <button class="categories__button">Filter</button>
            </div>
            <div class="categories__size">
              <h1 class="categories__text">Size</h1>
              <div class="categories__contentSize">
                <div class="categories__leftColumn">
                  <ul>
                    <li><a href="#">Small </a></li>
                    <li><a href="#">Medium </a></li>
                    <li><a href="#">Large  </a></li>
                  </ul>
                </div>
                <div class="categories__rightColumn">
                  <ul>
                    <li>(119)</li>
                    <li>(86)</li>
                    <li>(78)</li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="categories__banner">
            <img :src="'src/assets/img/sale.png'" alt="">
          </div>
        </div>
        <!-- Catalog -->

        <div class="catalog">
          <div class="catalog__container">
            <div class="catalog__sort">
              <p class="catalog__plants_active">All Plants</p>
              <p class="catalog__plants_arrivals">New Arrivals</p>
              <p class="catalog__plants_sale">Sale</p>
              <p class="catalog__sortBy">Sort by: <span id="catalog__parameter">Default sorting</span><img :src="'src/assets/img/arrowDown.png'" alt=""></p>
            </div>
            <div class="catalog__block">
              <a class="catalog__item" href="product_view.html">
                <!-- <div class="catalog__img_container"> -->

                <img :src="'src/assets/img/item1.png'" alt="" class="catalog__img">
                <!-- <div class="catalog__img_container-color"></div> -->
                <!-- </div> -->
                <h3 class="catalog__title">
                  Barberton Daisy
                </h3>
                <div class="catalog__footer">
                  <div class="catalog__price">
                    $119.00
                  </div>
                </div>
              </a>
              <a class="catalog__item catalog__item-bottom" href="product_view.html">
                <img :src="'src/assets/img/item2.png'" alt="" class="catalog__img">
                <h3 class="catalog__title">
                  Angel Wing Begonia
                </h3>
                <div class="catalog__footer">
                  <div class="catalog__price">
                    $169.00
                  </div>
                </div>
              </a>
              <a class="catalog__item" href="product_view.html">
                <img :src="'src/assets/img/item3.png'" alt="" class="catalog__img">
                <h3 class="catalog__title">
                  African Violet
                </h3>
                <div class="catalog__footer">
                  <div class="catalog__price">
                    $199.00
                  </div>
                </div>
              </a>
              <a class="catalog__item catalog__item-bottom" href="product_view.html">
                <img :src="'src/assets/img/item44.png'" alt="" class="catalog__img catalog_img4">
                <h3 class="catalog__title">
                  Beach Spider Lily
                </h3>
                <div class="catalog__footer">
                  <div class="catalog__price">
                    $129.00
                  </div>
                </div>
              </a>
              <a class="catalog__item" href="product_view.html">
                <img :src="'src/assets/img/item5.png'" alt="" class="catalog__img">
                <h3 class="catalog__title">
                  Blushing Bromeliad
                </h3>
                <div class="catalog__footer">
                  <div class="catalog__price">
                    $139.00
                  </div>
                </div>
              </a>
              <a class="catalog__item catalog__item-bottom" href="product_view.html">
                <img :src="'src/assets/img/item6.png'" alt="" class="catalog__img">
                <h3 class="catalog__title">
                  Aluminum Plant
                </h3>
                <div class="catalog__footer">
                  <div class="catalog__price">
                    $179.00
                  </div>
                </div>
              </a>
              <a class="catalog__item catalag__item_cut" href="product_view.html">
                <img :src="'src/assets/img/item7.png'" alt="" class="catalog__img">
                <h3 class="catalog__title">
                  Bird's Nest Fern
                </h3>
                <div class="catalog__footer">
                  <div class="catalog__price">
                    $99.00
                  </div>
                </div>
              </a>
              <a class="catalog__item catalag__item_cut" href="product_view.html">
                <img :src="'src/assets/img/item8.png'" alt="" class="catalog__img">
                <h3 class="catalog__title">
                  Broadleaf Lady Palm
                </h3>
                <div class="catalog__footer">
                  <div class="catalog__price">
                    $59.00
                  </div>
                </div>
              </a>
              <a class="catalog__item catalag__item_cut" href="product_view.html">
                <img :src="'src/assets/img/item9.png'" alt="" class="catalog__img">
                <h3 class="catalog__title">
                  Chinese Evergreen
                </h3>
                <div class="catalog__footer">
                  <div class="catalog__price">
                    $39.00
                  </div>
                </div>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- PAGES -->
    <div class="pages">
      <div class="pages__container">
        <div class="pages__item">
          <button class="pages__button pages__button_active">1</button>
        </div>
        <div class="pages__item">
          <button class="pages__button">2</button>
        </div>
        <div class="pages__item">
          <button class="pages__button">3</button>
        </div>
        <div class="pages__item">
          <button class="pages__button">4</button>
        </div>
        <div class="pages__item">
          <button class="pages__button"><img :src="'src/assets/img/arrowRight.svg'" alt=""></button>
        </div>
      </div>
    </div>

    <!-- BLOG -->
    <div class="blog">
      <div class="blog__container">
        <div class="blog__content">
          <div class="blog__sheet">
            <h1 class="blog__title">
              Our Blog Posts
            </h1>
            <div class="blog__subtitle">
              We are an online plant shop offering a wide range of cheap and trendy plants.
            </div>
          </div>
          <div class="blog__row">

            <div class="blog__column blog__columnLeft">
              <div class="item-blog">
                <div class="item-blog__icon">
                  <img :src="'src/assets/img/01.png'" alt="">
                </div>
                <div class="item-blog__date">September 12  I Read in 6 minutes</div>
                <div class="item-blog__title">Cactus & Succulent
                  Care Tips</div>
                <div class="item-blog__subtitle">Cacti are succulents are easy care plants for any home or patio. </div>
                <div class="item-blog__read"><a href="#">Read More<img class="item-blog__arrow" :src="'src/assets/img/arrow.svg'" alt=""></a></div>
              </div>
            </div>

            <div class="blog__column"><div class="item-blog">
              <div class="item-blog__icon">
                <img :src="'src/assets/img/02.png'" alt="">
              </div>
              <div class="item-blog__date">September 13  I Read in 2 minutes</div>
              <div class="item-blog__title">Top 10 Succulents for
                Your Home</div>
              <div class="item-blog__subtitle">Best in hanging baskets. Prefers medium to high light. </div>
              <div class="item-blog__read"><a href="#">Read More<img class="item-blog__arrow" :src="'src/assets/img/arrow.svg'" alt=""></a></div>
            </div>
            </div>

            <div class="blog__column blog__columnRight">
              <div class="item-blog">
                <div class="item-blog__icon">
                  <img :src="'src/assets/img/03.png'" alt="">
                </div>
                <div class="item-blog__date">September 15  I Read in 3 minutes</div>
                <div class="item-blog__title">Cacti & Succulent
                  Care Tips</div>
                <div class="item-blog__subtitle">Cacti and succulents thrive in containers and because most are.. </div>
                <div class="item-blog__read"><a href="#">Read More<img class="item-blog__arrow" :src="'src/assets/img/arrow.svg'" alt=""></a></div>
              </div>
            </div>

            <div class="blog__column blog__column-hide">
              <div class="item-blog">
                <div class="item-blog__icon">
                  <img :src="'src/assets/img/04.png'" alt="">
                </div>
                <div class="item-blog__date">September 15  I Read in 2 minutes</div>
                <div class="item-blog__title">Best Houseplants
                  Room by Room</div>
                <div class="item-blog__subtitle">The benefits of houseplants are endless. In addition to.. </div>
                <div class="item-blog__read"><a href="#">Read More<img class="item-blog__arrow" :src="'src/assets/img/arrow.svg'" alt=""></a></div>
              </div>
            </div>
          </div>

        </div>
      </div>
    </div>
    <!-- FOOTER -->
    <footer class="footer">
      <div class="footer__container">
        <div class="footer__top">
          <div class="footer__top-cut">
            <div class="footer__logo">
              <img :src="'src/assets/img/logo.svg'" alt="">
            </div>
            <div class="footer__address">
              <img :src="'src/assets/img/location.svg'" alt=""> <div class="footer__adress-text">70 West Buckingham Ave.
              Farmingdale, NY 11735</div>
            </div>
            <div class="footer__mail">
              <img :src="'src/assets/img/message.svg'" alt=""> contact@greenshop.com
            </div>
            <div class="footer__number">
              <img :src="'src/assets/img/phone.svg'" alt=""> +88 01911 717 490
            </div>
          </div>
        </div>
        <div class="footer__main">
          <div class="footer__content">
            <div class="footer__nav">

              <nav class="footer-nav">
                <ul class="footer-nav__list">
                  <li class="footer__title">My Account</li>
                  <li class="footer__text"><a href="#">My account</a></li>
                  <li class="footer__text"><a href="#">Our stores</a></li>
                  <li class="footer__text"><a href="#">Contact us</a></li>
                  <li class="footer__text"><a href="#">Career</a></li>
                  <li class="footer__text"><a href="#">Specials</a></li>
                </ul>
              </nav>

              <nav class="footer-nav">
                <ul class="footer-nav__list">
                  <li class="footer__title">Help & Guide</li>
                  <li class="footer__text"><a href="#">Help Center</a></li>
                  <li class="footer__text"> <a href="#">How to Buy</a></li>
                  <li class="footer__text"><a href="#">Shipping & Delivery</a></li>
                  <li class="footer__text"><a href="#">Product Policy</a></li>
                  <li class="footer__text"><a href="#">How to Return</a></li>
                </ul>
              </nav>

              <nav class="footer-nav">
                <ul class="footer-nav__list">
                  <li class="footer__title">Categories</li>
                  <li class="footer__text"><a href="#">House Plants</a></li>
                  <li class="footer__text"><a href="#">Potter Plants</a></li>
                  <li class="footer__text"><a href="#">Seeds</a></li>
                  <li class="footer__text"><a href="#">Seeds Small</a></li>
                  <li class="footer__text"><a href="#">Accessories</a></li>
                </ul>
              </nav>

            </div>
            <div class="footer__right">
              <div class="footer__media">
                <div class="footer__title">Social Media</div>
                <div class="footer__social">
                  <a href="#"><button class="footer__button"><img :src="'src/assets/img/Facebook.svg'" alt=""></button></a>
                  <a href="#"><button class="footer__button"><img :src="'src/assets/img/Instagram.svg'" alt=""></button></a>
                  <a href="#"><button class="footer__button"><img :src="'src/assets/img/Twitter.svg'" alt=""></button></a>
                  <a href="#"><button class="footer__button"><img :src="'src/assets/img/Linkedin.svg'" alt=""></button></a>
                  <a href="#"><button class="footer__button"><img :src="'src/assets/img/Union.svg'" alt=""></button></a>
                </div>
              </div>
              <div class="footer__payment">
                <div class="footer__title" id="footer__accept_text">We accept</div>
                <a href="#"><img :src="'src/assets/img/visa.png'" alt=""></a>
              </div>
            </div>
          </div>
        </div>
        <div class="footer__copyright">
          <span>© 2021 GreenShop. All Rights Reserved.</span>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App',

}

</script>

<style>

</style>
