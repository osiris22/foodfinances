<template>
  <div class="desktop">
    <div class="div-3">
      <Overlap />
      <Slide />
      <OverlapWrapper />
      <SlideWrapper />
      <DivWrapper />
      <Div />
      <SectionComponentNode />
      <OverlapGroup />
      <img
        class="illustration-3"
        alt="Illustration"
        src="https://c.animaapp.com/exWe3emh/img/illustration02@2x.png"
      />
    </div>
  </div>
</template>

<script>
import Overlap from "./Desktop/sections/Overlap.vue";
import Slide from "./Desktop/sections/Slide.vue";
import OverlapWrapper from "./Desktop/sections/OverlapWrapper.vue";
import SlideWrapper from "./Desktop/sections/SlideWrapper.vue";
import DivWrapper from "./Desktop/sections/DivWrapper.vue";
import Div from "./Desktop/sections/Div.vue";
import SectionComponentNode from "./Desktop/sections/SectionComponentNode.vue";
import OverlapGroup from "./Desktop/sections/OverlapGroup.vue";

export default {
  name: "Desktop",
  components: {
    Overlap,
    Slide,
    OverlapWrapper,
    SlideWrapper,
    DivWrapper,
    Div,
    SectionComponentNode,
    OverlapGroup,
  },
};
</script>

<style>
.desktop {
  background-color: #ffffff;
  display: flex;
  flex-direction: row;
  justify-content: center;
  width: 100%;
}

.desktop .div-3 {
  background-color: #ffffff;
  height: 7582px;
  overflow: hidden;
  position: relative;
  width: 1920px;
}

.desktop .illustration-3 {
  height: 177px;
  left: 1746px;
  position: absolute;
  top: 2637px;
  width: 174px;
}
</style>