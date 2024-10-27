<template>
  <header
    :style="{ backgroundImage: `url(${bg})` }"
    >
    <div class="top-left corner" :style="{ backgroundImage: `url(${topLeft})` }"></div>
    <div class="top-center corner" :style="{ backgroundImage: `url(${topCenter})` }"></div>
    <div class="top-right corner" :style="{ backgroundImage: `url(${topRight})` }"></div>
    <div class="bottom-left corner" :style="{ backgroundImage: `url(${bottomLeft})` }"></div>
    <div class="bottom-right corner" :style="{ backgroundImage: `url(${bottomRight})` }"></div>
    <div class="naturemort corner" :style="{ backgroundImage: `url(${naturemort})` }"></div>
    <div class="basket corner" :style="{ backgroundImage: `url('./components/lib/basket.svg')` }">
      <svg width="58" height="58" viewBox="0 0 58 58" fill="none" xmlns="http://www.w3.org/2000/svg">
        <rect x="1" y="11" width="46" height="46" fill="white"/>
        <rect x="1" y="11" width="46" height="46" stroke="white" stroke-width="2" stroke-dasharray="5 5"/>
        <path d="M20.0055 44C19.455 44 18.9838 43.8042 18.5917 43.4125C18.1997 43.0208 18.0037 42.55 18.0037 42C18.0037 41.45 18.1997 40.9792 18.5917 40.5875C18.9838 40.1958 19.455 40 20.0055 40C20.5561 40 21.0273 40.1958 21.4194 40.5875C21.8114 40.9792 22.0074 41.45 22.0074 42C22.0074 42.55 21.8114 43.0208 21.4194 43.4125C21.0273 43.8042 20.5561 44 20.0055 44ZM30.0148 44C29.4643 44 28.993 43.8042 28.601 43.4125C28.209 43.0208 28.0129 42.55 28.0129 42C28.0129 41.45 28.209 40.9792 28.601 40.5875C28.993 40.1958 29.4643 40 30.0148 40C30.5653 40 31.0366 40.1958 31.4286 40.5875C31.8206 40.9792 32.0166 41.45 32.0166 42C32.0166 42.55 31.8206 43.0208 31.4286 43.4125C31.0366 43.8042 30.5653 44 30.0148 44ZM19.1548 28L21.557 33H28.5635L31.316 28H19.1548ZM18.2039 26H32.9675C33.3512 26 33.6431 26.1708 33.8433 26.5125C34.0435 26.8542 34.0519 27.2 33.8684 27.55L30.3151 33.95C30.1316 34.2833 29.8855 34.5417 29.5769 34.725C29.2683 34.9083 28.9305 35 28.5635 35H21.1066L20.0055 37H31.0157C31.2993 37 31.537 37.0958 31.7289 37.2875C31.9207 37.4792 32.0166 37.7167 32.0166 38C32.0166 38.2833 31.9207 38.5208 31.7289 38.7125C31.537 38.9042 31.2993 39 31.0157 39H20.0055C19.2549 39 18.6877 38.6708 18.304 38.0125C17.9203 37.3542 17.9036 36.7 18.2539 36.05L19.6052 33.6L16.0018 26H15.0009C14.7173 26 14.4796 25.9042 14.2878 25.7125C14.0959 25.5208 14 25.2833 14 25C14 24.7167 14.0959 24.4792 14.2878 24.2875C14.4796 24.0958 14.7173 24 15.0009 24H16.6274C16.8109 24 16.9861 24.05 17.1529 24.15C17.3197 24.25 17.4448 24.3917 17.5283 24.575L18.2039 26Z" fill="#231F20"/>
        <g clip-path="url(#clip0_0_139)">
        <rect x="34" width="24" height="24" rx="12" fill="#231F20"/>
        <path d="M42.3219 14.312C42.3219 13.5973 42.5725 12.9893 43.0739 12.488C43.4685 12.1147 43.9485 11.736 44.5139 11.352C43.9485 10.9573 43.5379 10.6267 43.2819 10.36C42.7912 9.85867 42.5459 9.32533 42.5459 8.76C42.5459 7.90667 42.8659 7.21867 43.5059 6.696C44.1565 6.17333 45.0045 5.912 46.0499 5.912C47.0952 5.912 47.8952 6.14133 48.4499 6.6C49.0152 7.048 49.2979 7.608 49.2979 8.28C49.2979 9.28267 48.6365 10.2533 47.3139 11.192C48.4979 11.864 49.2339 12.536 49.5219 13.208C49.6605 13.5387 49.7299 13.9013 49.7299 14.296C49.7299 15.1707 49.3885 15.8747 48.7059 16.408C48.0232 16.9307 47.1379 17.192 46.0499 17.192C44.9725 17.192 44.0819 16.952 43.3779 16.472C42.6739 15.992 42.3219 15.272 42.3219 14.312ZM46.0499 16.104C46.5832 16.104 47.0045 15.9493 47.3139 15.64C47.6339 15.3307 47.7939 14.9307 47.7939 14.44C47.7939 13.9493 47.5699 13.496 47.1219 13.08C46.6739 12.6533 46.0445 12.2213 45.2339 11.784C44.9672 12.0613 44.7379 12.4187 44.5459 12.856C44.3539 13.2933 44.2579 13.7627 44.2579 14.264C44.2579 14.7653 44.4232 15.1973 44.7539 15.56C45.0952 15.9227 45.5272 16.104 46.0499 16.104ZM44.4819 8.408C44.4819 9.32533 45.1805 10.1253 46.5779 10.808C46.8125 10.5093 46.9992 10.1467 47.1379 9.72C47.2872 9.28267 47.3619 8.856 47.3619 8.44C47.3619 8.024 47.2285 7.672 46.9619 7.384C46.6952 7.08533 46.3379 6.936 45.8899 6.936C45.4419 6.936 45.0952 7.09067 44.8499 7.4C44.6045 7.70933 44.4819 8.04533 44.4819 8.408Z" fill="white"/>
        </g>
        <defs>
        <clipPath id="clip0_0_139">
        <rect x="34" width="24" height="24" rx="12" fill="white"/>
        </clipPath>
        </defs>
        </svg>
    </div>
    <ul class="nav corner">
      <li v-for="item in nav">
        {{ item }}
      </li>
    </ul>
    <div class="content">
      <h6 class="decor">
        &#9472 bonjour &#9472
      </h6>
      &nbsp;
      <h1>Serving Baked <br />Goods <span>Every Day</span></h1>
      <p class="comment">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
      </p>
      <button class="button">
        Shop Now
        <svg width="27" height="14" viewBox="0 0 27 14" fill="none" xmlns="http://www.w3.org/2000/svg">
            <g clip-path="url(#clip0_2350_5)">
            <path d="M0 7L24 7" stroke="#CF8C0B" stroke-width="2" stroke-miterlimit="10"/>
            <path d="M18 15C18 15 20.9388 7.00003 27 7.00003C20.9388 7.00003 18 -1 18 -1" stroke="#CF8C0B" stroke-width="2" stroke-miterlimit="10"/>
          </g>
          <defs>
            <clipPath id="clip0_2350_5">
            <rect width="27" height="14" fill="white"/>
          </clipPath>
          </defs>
        </svg>
      </button>
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>


<script setup>
import TheWelcome from './components/TheWelcome.vue'
import { src } from './components/lib/header_bg.json'
import { top_left } from './components/lib/top_left.json'
import { top_center } from './components/lib/top_center.json'
import { top_right } from './components/lib/top_right.json'
import { bottom_left } from './components/lib/bottom_left.json'
import { bottom_right } from './components/lib/bottom_right.json'
import { naturemort } from './components/lib/naturemort.json'

const bg = src
const topLeft = top_left
const topCenter = top_center
const topRight = top_right
const bottomLeft = bottom_left
const bottomRight = bottom_right

const nav = [
  "Store",
  "About",
  "Shipping",
  "Recieps",
  "Blog"
]
</script>

<style lang="scss">
header {
  line-height: 1.5;
  width: 100%;
  height: 1000px;
  background-size: cover;
  background-position: center;
  position: relative;
  text-align: center;

  .corner {
    position: absolute;
    background-size: cover;
    background-position: center;

    &.top-left {
      width: 436px;
      height: 409px;
      top: 0;
      left: 0;
    }

    &.top-right {
      width: 588px;
      height: 539px;
      top: 0;
      right: 0;
    }

    &.top-center {
      width: 529px;
      height: 229px;
      top: 0;
      left: 695px;
    }

    &.bottom-left {
      width: 546px;
      height: 553px;
      bottom: 0;
      left: 0;
    }

    &.bottom-right {
      width: 488px;
      height: 457px;
      bottom: 0;
      right: 0;
    }

    &.naturemort {
      width: 128px;
      height: 128px;
      top: 4px;
      left: 64px;
    }

    &.basket {
      width: 58px;
      height: 58px;
      top: 4px;
      right: 84px;
    }

    &.nav {
      width: 456px;
      height: 28px;
      top: 24px;
      left: 272px;
      display: flex;
      justify-content: space-between;
      font-family: "Comorand Garamond";
      font-weight: 400;
      font-size: 20px;

      li {
        list-style: none;
        display: inline-block;
      }
    }
  }
}
.content {
  width: 716px;
  display: inline-block;
  margin-top: 285px;
  text-align: center;

  h1 {
    display: inline-block;
    font-family: "Cormorant Garamond";
    font-size: 96px;
    font-weight: 400;
    line-height: 96px;
    letter-spacing: -0.035em;

    & span {
      font-weight: 700;
    }
  }

  .decor {
    display: inline-block;
    font-family: Cormorant Garamond;
    font-size: 20px;
    font-weight: 600;
    line-height: 24px;
    color: #CF8C0B;
  }

  .comment {
    display: inline-block;
    margin-top: 32px;
    font-family: "Jost";
    font-size: 20px;
    font-weight: 400;
    line-height: 28px;
    text-align: center;
  }

  .button {
    margin-top: 32px;
    width: Hug (196px)px;
    height: Hug (60px)px;
    padding: 16px 32px 16px 32px;
    gap: 12px;
    border: 1px 0px 0px 0px;
    opacity: 0px;
    font-family: Jost;
    font-size: 20px;
    font-weight: 500;
    line-height: 28px;
    text-align: left;
    border: 1px solid #CF8C0B;
  }
}
</style>
