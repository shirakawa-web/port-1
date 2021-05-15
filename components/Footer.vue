<template>
  <div class="test">a</div>
</template>

<script>
import { gsap /*Bounce*/ } from "gsap";
import { ScrollTrigger } from "gsap/ScrollTrigger";

export default {
  data() {
    return {};
  },
  mounted() {
    var tl = gsap.timeline();
    tl.set(".test", { alpha: 0 });
    tl.to(".test", 9, {
      alpha: 1,
      scrollTrigger: {
        trigger: ".test",
        start: "center 70%",
        end: "center 30%",
        markers:true,
      },
    });
  },
};
</script>
