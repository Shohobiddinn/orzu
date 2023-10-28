<template>
  <div>
    <div class="tekshiruv">
      <div class="container">
    
      </div>
    </div>
    <!-- <div class="hero">
      <div class="container">
        <Swiper
          class="hero_swiper"
          :modules="[SwiperAutoplay, SwiperEffectCreative, SwiperNavigation]"
          :slides-per-view="4"
          :space-between="78"
          :pagination="{
      clickable: true,
    }"
          :breakpoints="{
            '200': {
              slidesPerView: 1,
            },
            '600': {
              slidesPerView: 1,
              spaceBetween: 30,
            },
            '800': {
              slidesPerView: 1,
            },
            '1020': {
              spaceBetween: 30,
              slidesPerView: 1,
            },
            '1370': {
              spaceBetween: 110,
              slidesPerView: 1,
            },
          }"
          :navigation="{
            prevEl: '.hero_prev',
            nextEl: '.hero_next',
          }"
        >
          <SwiperSlide class="hero_slider" v-for="t in 5" :key="t.id">
            <div class="item">
              <div class="item_content">
                <div class="item_content_title">
                  Lorem ipsum, dolor sit amet
                </div>
                <div class="item_content_text">
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex
                  praesentium, quasi velit excepturi corporis corrupti natus
                  atque aliquid dolorem nihil quia nostrum perferendis
                  temporibus molestiae earum vero sapiente rerum nemo eum!
                  Doloribus fugiat repellat quod?
                </div>
                <NuxtLink to="/" class="item_content_link btn">
                  Подробнее
                </NuxtLink>
              </div>

              <div class="item_image">
                <img src="../assets/image/slide 1.png" alt="photo" />
              </div>
            </div>
          </SwiperSlide>
          <div class="swiper-pagination"></div>
        </Swiper>
      </div>
    </div> <div class="banner">
      <div class="container">
        <div class="banner_top">
          <div class="banner_title">ПРОДУКЦИЯ</div>
        </div>
        <div class="banner_bottom">
          <div class="item" v-for="item in 6" :key="item">
            <div class="item_image">
              <img src="../assets/image/itemimage.png" alt="photo" />
            </div>
            <div class="item_title">Эндоваскулярная хирургия</div>
            <NuxtLink to="/" class="item_link btn">Посмотреть все</NuxtLink>
          </div>
        </div>
        <div class="banner_footer">
          <NuxtLink to="/" class="banner_footer_link">
            <div class="banner_footer_link_title">
              Перейти в каталог нашей продукции
            </div>
            <div class="banner_link_icon">
              <svg
                width="30"
                height="30"
                viewBox="0 0 30 30"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <g clip-path="url(#clip0_502_67)">
                  <path
                    d="M30 15C30 6.7285 23.2715 -2.94112e-07 15 -6.55671e-07C6.7285 -1.01723e-06 -2.94112e-07 6.72849 -6.55671e-07 15C-1.01723e-06 23.2715 6.72967 30 15 30C23.2703 30 30 23.2715 30 15ZM2.32377 15C2.32377 8.01123 8.01006 2.32377 15 2.32377C21.9899 2.32377 27.6762 8.01123 27.6762 15C27.6762 21.9899 21.9899 27.6762 15 27.6762C8.01006 27.6762 2.32377 21.9888 2.32377 15Z"
                    fill="#0D4C93"
                  />
                  <path
                    d="M13.3966 21.6344L19.2061 15.825C19.6569 15.3718 19.6569 14.6399 19.2061 14.1867L13.3966 8.37725C12.9621 8.0043 12.3196 8.0043 11.885 8.37725C11.3982 8.79438 11.3413 9.52867 11.7584 10.0155L16.7429 15L11.7583 19.9962C11.3075 20.4493 11.3075 21.1813 11.7583 21.6344C12.2115 22.0853 12.9435 22.0853 13.3966 21.6344Z"
                    fill="#0D4C93"
                  />
                </g>
                <defs>
                  <clipPath id="clip0_502_67">
                    <rect
                      width="30"
                      height="30"
                      fill="white"
                      transform="translate(30) rotate(90)"
                    />
                  </clipPath>
                </defs>
              </svg>
            </div>
          </NuxtLink>
          <div class="banner_footer_title">УСЛУГИ</div>
        </div>
      </div>
    </div>  <div class="section">
      <div class="container">
        <div class="item" v-for="item in 3" :key="item">
          <div class="item_image">
            <img src="../assets/image/itaemimage1.png" alt="photo" />
          </div>
          <div class="item_title">СЕРВИС ОБОРУДОВАНИЯ</div>
          <div class="item_text">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Explicabo
            delectus officiis illum debitis dolor iusto accusamus quibusdam.
            Doloribus, maiores porro!
          </div>
          <NuxtLink to="/" class="item_link btn"> Подробнее </NuxtLink>
        </div>
      </div>
    </div> <div class="about">
      <div class="container">
        <div class="about_image">
          <div class="circle">
            <div class="circle_1">
              <div class="circle_2">
                <img src="../assets/image/logo 1.png" alt="photo" />
              </div>
            </div>
          </div>
        </div>
        <div class="about_content">
          <div class="about_content_title">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Et vel,
            natus ad quaerat similique velit eum veritatis quos non commodi
            consequuntur doloribus perferendis, harum incidunt dolorum beatae,
            maiores quo iusto. Fugit, vero. Labore dolore, et molestiae rem sit
            libero, aperiam blanditiis voluptas ipsa tempora voluptate!
            Consequatur neque, consectetur voluptate ex at aut enim sunt natus
            eveniet soluta animi quasi voluptas numquam non impedit, asperiores
            quis labore sapiente, distinctio recusandae vero? Labore,
            necessitatibus repellendus temporibus, amet nulla facilis
            perspiciatis quis blanditiis id voluptatibus voluptates vel porro
            similique ullam asperiores! Officia velit explicabo tempore
            laudantium? Voluptatibus, hic veritatis. Quo recusandae quibusdam
            iure!
          </div>
          <NuxtLink to="/" class="about_content_link btn">
            Узнать больше
          </NuxtLink>
        </div>
      </div>
    </div>
    <div class="swiper_page">
      <div class="container">
        <div class="swiper_page_top">
          <div class="swiper_page_top_title">НОВОСТИ</div>
        </div>
        <Swiper
          class="swiper_page_swiper"
          :modules="[SwiperAutoplay, SwiperEffectCreative, SwiperNavigation]"
          :slides-per-view="4"
          :space-between="78"
          :breakpoints="{
            '200': {
              slidesPerView: 1,
            },
            '600': {
              slidesPerView: 2,
              spaceBetween: 30,
            },
            '800': {
              slidesPerView: 2,
            },
            '1020': {
              spaceBetween: 30,
              slidesPerView: 3,
            },
            '1370': {
              spaceBetween: 110,
              slidesPerView: 3,
            },
          }"
          :navigation="{
            prevEl: '.swiper_page_prev',
            nextEl: '.swiper_page_next',
          }"
        >
          <SwiperSlide class="swiper_page_slider" v-for="t in 5" :key="t.id">
            <div class="item">
              <div class="item_image">
                <img src="../assets/image/itaemimage1.png" alt="photo" />
              </div>
              <div class="item_title">
                Lorem ipsum, dolor sit amet consectetur adipisicing.
              </div>
              <div class="item_day">27.10.2023</div>
              <div class="item_text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex
                praesentium, quasi velit excepturi corporis corrupti natus atque
                aliquid dolorem nihil quia nostrum perferendis temporibus
                molestiae earum vero sapiente rerum nemo eum! Doloribus fugiat
                repellat quod?
              </div>
              <NuxtLink to="/" class="item_link btn"> Подробнее </NuxtLink>
            </div>
          </SwiperSlide>
        </Swiper>
        <div class="swiper_page_pagination">
          <div class="swiper_page_prev icon">
            <svg
              width="50"
              height="50"
              viewBox="0 0 50 50"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <rect
                width="50"
                height="50"
                rx="25"
                fill="url(#paint0_linear_502_209)"
              />
              <g clip-path="url(#clip0_502_209)">
                <path
                  d="M18.0848 24.4999C18.0848 24.1594 18.2148 23.819 18.4743 23.5593L26.644 15.3898C27.1637 14.8701 28.0063 14.8701 28.5257 15.3898C29.0452 15.9092 29.0452 16.7517 28.5257 17.2714L21.2968 24.4999L28.5255 31.7285C29.045 32.2482 29.045 33.0906 28.5255 33.61C28.006 34.1299 27.1634 34.1299 26.6437 33.61L18.4741 25.4406C18.2145 25.1808 18.0848 24.8403 18.0848 24.4999Z"
                  fill="white"
                />
              </g>
              <defs>
                <linearGradient
                  id="paint0_linear_502_209"
                  x1="25"
                  y1="0"
                  x2="25"
                  y2="50"
                  gradientUnits="userSpaceOnUse"
                >
                  <stop stop-color="#0D4C93" />
                  <stop offset="1" stop-color="#00C9C9" />
                </linearGradient>
                <clipPath id="clip0_502_209">
                  <rect
                    width="19"
                    height="19"
                    fill="white"
                    transform="translate(33 15) rotate(90)"
                  />
                </clipPath>
              </defs>
            </svg>
          </div>
          <div class="swiper_page_next icon">
            <svg
              width="50"
              height="50"
              viewBox="0 0 50 50"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <rect
                width="50"
                height="50"
                rx="25"
                fill="url(#paint0_linear_502_214)"
              />
              <g clip-path="url(#clip0_502_214)">
                <path
                  d="M30.9151 24.4999C30.9151 24.1594 30.7851 23.819 30.5256 23.5593L22.356 15.3898C21.8363 14.8701 20.9937 14.8701 20.4742 15.3898C19.9547 15.9092 19.9547 16.7517 20.4742 17.2714L27.7032 24.4999L20.4745 31.7285C19.955 32.2482 19.955 33.0906 20.4745 33.61C20.9939 34.1299 21.8365 34.1299 22.3562 33.61L30.5259 25.4406C30.7854 25.1808 30.9151 24.8403 30.9151 24.4999Z"
                  fill="white"
                />
              </g>
              <defs>
                <linearGradient
                  id="paint0_linear_502_214"
                  x1="25"
                  y1="0"
                  x2="25"
                  y2="50"
                  gradientUnits="userSpaceOnUse"
                >
                  <stop stop-color="#0D4C93" />
                  <stop offset="1" stop-color="#00C9C9" />
                </linearGradient>
                <clipPath id="clip0_502_214">
                  <rect
                    width="19"
                    height="19"
                    fill="white"
                    transform="matrix(4.37114e-08 1 1 -4.37114e-08 16 15)"
                  />
                </clipPath>
              </defs>
            </svg>
          </div>
        </div>
      </div>
    </div> 
     <footer>
      <div class="container">
        <div class="footer_left">
          <div class="left_top">
            <div class="item">
              <div class="item_title bold">Контакты</div>
            </div>
            <div class="item">
              <div class="item_content">
                <div class="item_content_icon">
                  <svg
                    width="25"
                    height="25"
                    viewBox="0 0 25 25"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M12.5 0C7.50757 0 3.44595 4.06162 3.44595 9.054C3.44595 15.2497 11.5484 24.3454 11.8934 24.7295C12.2174 25.0904 12.7832 25.0898 13.1066 24.7295C13.4516 24.3454 21.554 15.2497 21.554 9.054C21.554 4.06162 17.4924 0 12.5 0ZM12.5 13.6093C9.98818 13.6093 7.94472 11.5658 7.94472 9.054C7.94472 6.54219 9.98823 4.49873 12.5 4.49873C15.0118 4.49873 17.0552 6.54224 17.0552 9.05405C17.0552 11.5659 15.0118 13.6093 12.5 13.6093Z"
                      fill="#0D4C93"
                    />
                  </svg>
                </div>
                <div class="item_content_title">
                  г.Ташкент, Чиланзар <br />
                  10 квартал, дом 3/1
                </div>
              </div>
              <div class="item_content">
                <div class="item_content_icon">
                  <svg
                    width="23"
                    height="23"
                    viewBox="0 0 23 23"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <g clip-path="url(#clip0_502_285)">
                      <path
                        d="M20.9785 2.74023H2.02149C1.71031 2.74023 1.41899 2.81674 1.15544 2.94283L11.4551 13.2425L13.7636 11.0239C13.7636 11.0239 13.7637 11.0237 13.7638 11.0236C13.7638 11.0235 13.764 11.0234 13.764 11.0234L21.8449 2.94301C21.5813 2.81683 21.2898 2.74023 20.9785 2.74023Z"
                        fill="#0D4C93"
                      />
                      <path
                        d="M22.7977 3.896L15.1932 11.5001L22.7974 19.1043C22.9235 18.8408 23 18.5495 23 18.2383V4.76173C23 4.45074 22.9237 4.15946 22.7977 3.896Z"
                        fill="#0D4C93"
                      />
                      <path
                        d="M0.202598 3.89551C0.076502 4.15906 0 4.45038 0 4.76156V18.2381C0 18.5491 0.0764121 18.8405 0.202418 19.1039L7.80693 11.4998L0.202598 3.89551Z"
                        fill="#0D4C93"
                      />
                      <path
                        d="M14.2403 12.4532L11.9315 14.672C11.7999 14.8037 11.6275 14.8695 11.4551 14.8695C11.2828 14.8695 11.1103 14.8037 10.9787 14.672L8.75977 12.4531L1.15512 20.0573C1.41873 20.1835 1.71022 20.2601 2.02149 20.2601H20.9785C21.2897 20.2601 21.581 20.1836 21.8446 20.0575L14.2403 12.4532Z"
                        fill="#0D4C93"
                      />
                    </g>
                    <defs>
                      <clipPath id="clip0_502_285">
                        <rect width="23" height="23" fill="white" />
                      </clipPath>
                    </defs>
                  </svg>
                </div>
                <div class="item_content_title">info@medol.uz</div>
              </div>
            </div>
            <div class="item">
              <div class="item_content">
                <div class="item_content_icon">
                  <svg
                    width="22"
                    height="22"
                    viewBox="0 0 22 22"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <g clip-path="url(#clip0_502_301)">
                      <path
                        d="M9.1099 12.89C7.01004 10.7902 6.5359 8.69031 6.42894 7.849C6.39905 7.61637 6.4791 7.38309 6.64552 7.21782L8.34483 5.51927C8.5948 5.26946 8.63916 4.88013 8.4518 4.58048L5.74618 0.379239C5.53889 0.0474371 5.11327 -0.0723136 4.76338 0.102722L0.419903 2.14834C0.136959 2.28767 -0.0294639 2.58829 0.00266119 2.90203C0.230247 5.0641 1.17283 10.379 6.39594 15.6025C11.619 20.826 16.9332 21.7682 19.0964 21.9958C19.4101 22.0279 19.7107 21.8615 19.8501 21.5785L21.8957 17.235C22.0701 16.8859 21.9511 16.4614 21.6207 16.2538L17.4195 13.5489C17.12 13.3613 16.7307 13.4054 16.4807 13.6551L14.7821 15.3544C14.6168 15.5208 14.3836 15.6009 14.1509 15.571C13.3096 15.464 11.2098 14.9899 9.1099 12.89Z"
                        fill="#0D4C93"
                      />
                      <path
                        d="M17.4483 11.7585C17.0293 11.7585 16.6897 11.4188 16.6897 10.9999C16.6861 7.85903 14.1409 5.31376 11 5.31021C10.581 5.31021 10.2414 4.97056 10.2414 4.55159C10.2414 4.13261 10.581 3.79297 11 3.79297C14.9785 3.79736 18.2025 7.02142 18.2069 10.9999C18.2069 11.4188 17.8673 11.7585 17.4483 11.7585Z"
                        fill="#0D4C93"
                      />
                      <path
                        d="M21.2414 11.7586C20.8224 11.7586 20.4828 11.419 20.4828 11C20.4769 5.76524 16.2348 1.52309 11 1.51724C10.581 1.51724 10.2414 1.1776 10.2414 0.758621C10.2414 0.339646 10.581 0 11 0C17.0724 0.00668947 21.9933 4.92764 22 11C22 11.2012 21.9201 11.3942 21.7778 11.5364C21.6356 11.6787 21.4426 11.7586 21.2414 11.7586Z"
                        fill="#0D4C93"
                      />
                    </g>
                    <defs>
                      <clipPath id="clip0_502_301">
                        <rect width="22" height="22" fill="white" />
                      </clipPath>
                    </defs>
                  </svg>
                </div>
                <div class="item_content_title">
                  +998 71 276-62-53 <br />+998 71 276-62-54
                </div>
              </div>
              <div class="item_content">
                <NuxtLink to="/" class="item_content_link btn">
                  Оставить заявку
                </NuxtLink>
              </div>
            </div>
          </div>
          <div class="left_bottom">
            <div class="left_bottom_image">
              <img src="../assets/image/logo 1.png" alt="photo" />
            </div>
            <div class="left_bottom_title">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae
              numquam velit temporibus quidem tempore consectetur magnam esse
              minima nulla quos ea perferendis, nostrum neque itaque debitis,
              dolorem sequi alias? Eius ipsa veniam officiis sint quaerat libero
            </div>
          </div>
        </div>
        <div class="footer_right">
          <div class="item">
            <div class="item_text">lorem</div>
            <NuxtLink to="/" class="item_link"> lorem ipsum. </NuxtLink>
            <NuxtLink to="/" class="item_link"> lorem ipsum. </NuxtLink>
            <NuxtLink to="/" class="item_link"> lorem ipsum. </NuxtLink>
          </div>
          <div class="item">
            <div class="item_text">lorem</div>
            <NuxtLink to="/" class="item_link"> lorem ipsum. </NuxtLink>
            <NuxtLink to="/" class="item_link"> lorem ipsum. </NuxtLink>
            <NuxtLink to="/" class="item_link"> lorem ipsum. </NuxtLink>
            <NuxtLink to="/" class="item_link"> lorem ipsum. </NuxtLink>
            <NuxtLink to="/" class="item_link"> lorem ipsum. </NuxtLink>
            <NuxtLink to="/" class="item_link"> lorem ipsum. </NuxtLink>
            <NuxtLink to="/" class="item_link"> lorem ipsum. </NuxtLink>
          </div>
          <div class="item">
            <div class="item_text">lorem</div>
            <NuxtLink to="/" class="item_link"> lorem ipsum. </NuxtLink>
            <NuxtLink to="/" class="item_link"> lorem ipsum. </NuxtLink>
            <NuxtLink to="/" class="item_link"> lorem ipsum. </NuxtLink>
          </div>
        </div>
      </div>
    </footer>  -->
  </div>
</template>

<script setup>
</script>

<style lang="scss" scoped>
</style>