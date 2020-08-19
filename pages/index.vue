<template>
  <div class="container">
    <Header />
    <Main />
    <Source />
    <Discover />
    <Registration />
    <Time />
    <WebinarInfo />
    <AboutSpeaker />
    <Expectation />
    <Whom />
    <Mail />
    <Footer />
    <Video class="video" />
    <Video768 class="video768" />
    <Video460 class="video460" />
    <Nuxt />
  </div>
</template>

<script>
import Header from "@/components/Header";
import Main from "@/components/Main";
import Source from "@/components/Source";
import Discover from "@/components/Discover";
import Registration from "@/components/Registration";
import Time from "@/components/Time";
import WebinarInfo from "@/components/WebinarInfo";
import AboutSpeaker from "@/components/AboutSpeaker";
import Expectation from "@/components/Expectation";
import Whom from "@/components/Whom";
import Mail from "@/components/Mail";
import Footer from "@/components/Footer";
import Video from "@/components/Video";
import Video460 from "@/components/Video460";
import Video768 from "@/components/Video768";

export default {
  components: {
    Header,
    Main,
    Source,
    Discover,
    Registration,
    Time,
    WebinarInfo,
    AboutSpeaker,
    Expectation,
    Whom,
    Mail,
    Footer,
    Video,
    Video768,
    Video460
  }
};
</script>

<style lang="scss">
.container {
  overflow: hidden;
}
.video {
  display: flex;
  right: 0px;
  position: absolute;
  top: 2030px;
  z-index: 9;
}
.video768 {
  display: none;
}
.video460 {
  display: none;
}
@media (max-width: 768px) {
  .video {
    display: none;
  }
  .video768 {
    display: flex;
    right: 0px;
    position: absolute;
    top: 1850px;
    z-index: 9;
  }
  .video460 {
    display: none;
  }
}
@media (max-width: 460px) {
  .video460 {
    display: flex;
    left: 0px;
    position: absolute;
    top: 2090px;
    z-index: 9;
  }
  .video {
    display: none;
  }
  .video768 {
    display: none;
  }
}
</style>
