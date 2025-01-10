<template>
  <main>
    <!-- HSiF hero section -->
    <section class="pt-0 pb-0 relative">
      <div class="relative">
        <Herobackground class="w-full"/>
        <div class="absolute left-1/2 bottom-1/2 transform -translate-x-1/2 translate-y-3/7 md:w-hsiflogo md:h-hsiflogo w-hsiflogomobile h-hsiflogomobile bg-realwhite rounded-full">
          <Hsif class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 md:w-auto w-3/4"/>
        </div>
      </div>
    </section>

    <!-- Description section -->
    <section class="px-2 md:px-9">
      <div class="md:flex md:flex-row md:gap-4">
        <div class="relative text-realwhite w-min h-min md:self-start mx-auto">
          <ContentVector class="w-18 h-18 md:w-auto md:h-auto"/>
          <div class="absolute left-1/2 top-1/2 transform -translate-x-1/2 -translate-y-1/2">
            <ul class="list-inside text-xl md:text-4xl font-bold w-max" :style="{ listStyleImage: `url(${listStyleImage})`}">
              <li>
                UX/UI
              </li>
              <li>
                Web Design
              </li>
              <li>
                Research
              </li>
              <li>
                8 weeks
              </li>
            </ul>
          </div>
        </div>
        <div class="flex flex-col justify-around md:mt-0 mt-2 md:gap-0 gap-2">
          <div>
            <h5 class="text-2xl">
              Background
            </h5>
            <span>
              It is a startup company working to help students and young people in the field. They presented us with a project aimed at creating their own website to introduce their customers to them.
            </span>
          </div>
          <div>
            <h5 class="text-2xl">
              Goal
            </h5>
            <span>
              We did an in-depth study of all users and then we created prototypes and tested them. Based on the results, we created the final design and tested it again. It took us around 8 weeks to finish this project, and we are glad to share the steps with you!
            </span>
          </div>
        </div>
      </div>
      <!-- Gallery -->
      <div class="flex justify-center pt-4">
        <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="383" height="383" viewBox="0 0 383 383" fill="none" class="h-1/2 md:h-auto md:w-full">
          <defs>
            <pattern id="pattern_image_1" patternUnits="userSpaceOnUse" width="383" height="383">
              <image xlink:href="~/assets/images/hsif/image1.jpg" x="0" y="0" width="383" height="383" preserveAspectRatio="xMinYMin"/>
            </pattern>
          </defs>
          <path d="M383 25L0 0L25 382.5L357.5 358.5L383 25Z" fill="url(#pattern_image_1)"/>
        </svg>
        <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="383" height="383" viewBox="0 0 383 383" fill="none" class="h-1/2 md:h-auto md:w-full">
          <defs>
            <pattern id="pattern_image_2" patternUnits="userSpaceOnUse" width="383" height="383">
              <image xlink:href="~/assets/images/hsif/image2.jpg" x="0" y="0" width="383" height="383" preserveAspectRatio="xMinYMin"/>
            </pattern>
          </defs>
          <path d="M0 357.5L383 382.5L358 0L25.5 24L0 357.5Z" fill="url(#pattern_image_2)"/>
        </svg>
        <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="383" height="383" viewBox="0 0 383 383" fill="none" class="h-1/2 md:h-auto md:w-full">
          <defs>
            <pattern id="pattern_image_3" patternUnits="userSpaceOnUse" width="383" height="383">
              <image xlink:href="~/assets/images/hsif/image3.jpg" x="0" y="0" width="383" height="383" preserveAspectRatio="xMinYMin"/>
            </pattern>
          </defs>
          <path d="M383 25L0 0L25 382.5L357.5 358.5L383 25Z" fill="url(#pattern_image_3)"/>
        </svg>
      </div>
      <!-- End of gallery -->
      <span class="flex font-bold text-2xl justify-center pt-3">
        Visit website &#8594;
      </span>
    </section>

    <!-- Request a project section -->
    <section class="px-2 md:px-9 relative">
      <div>
        <h5 class="text-5xl pb-1">Speed up your digital growth together?</h5>
        <span class="text-2xl">
        You can leave your project information, we will review it, and we will contact you! <br/>
        After that we will have a free discussion of your project.
      </span>
      </div>
      <div class="pt-2 md:pt-0 flex justify-end">
        <button class="btn">
          Request project
        </button>
      </div>
      <!-- Decorations -->
      <div class="absolute bottom-0 left-0">
        <svg xmlns="http://www.w3.org/2000/svg" width="116" height="177" viewBox="0 0 116 177" fill="none">
          <path d="M15.7306 372.322L113.952 113.94L-195.625 2.00124L-249.09 325.175L15.7306 372.322Z" stroke="#FFBA00" stroke-width="2"/>
        </svg>
      </div>
      <div class="absolute -top-4 md:top-4 right-2">
        <svg width="89" height="104" viewBox="0 0 89 104" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M81.4579 62.9448L39.9657 100.407L0.000660453 56.6362L56.2302 21.6024L81.4579 62.9448Z" fill="#4E5B73"/>
          <path d="M20.8986 58.636L69.6044 60.0234L70.3104 2.00001L13.4099 11.8165L20.8986 58.636Z" stroke="#FFBA00" stroke-width="2"/>
        </svg>
      </div>
      <!-- End of decorations -->
    </section>
  </main>
</template>

<script>
import Vue from 'vue'
import VueMarqueeSlider from 'vue-marquee-slider';
import Herobackground from '~/assets/images/hsif/herobackground.svg';
import Hsif from '~/assets/images/hsif/HSiF.svg';
import ContentVector from '~/assets/images/hsif/contentvector.svg';
Vue.use(VueMarqueeSlider)


export default {
  components: {
    Herobackground,
    Hsif,
    ContentVector
  },
  head() {
    return {
      script: [
        { src: "https://identity.netlify.com/v1/netlify-identity-widget.js" }
      ]
    };
  },
  data() {
    return {
      listStyleImage: require('~/assets/css/components/ulfinger.png'),
    };
  },
  mounted() {
    console.log(this.listStyleImage);
  }
};
</script>
