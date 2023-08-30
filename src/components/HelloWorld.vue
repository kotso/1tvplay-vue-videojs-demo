<template>
  <div class="hello">
    **<video
      id="vid1"
      width="500"
      height="300"
      class="video-js"
      preload="auto"
      poster="//vjs.zencdn.net/v/oceans.png"
      controls
      data-setup="{}"
    >
      <source
        src="http://tv.cdn.xsg.ge/ge/1tv/index.m3u8"
        type="application/x-mpegURL"
      />
      <p class="vjs-no-js">
        To view this video please enable JavaScript, and consider upgrading to a
        web browser that
        <a href="http://videojs.com/html5-video-support/" target="_blank">
          supports HTML5 video
        </a>
      </p>
    </video>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
