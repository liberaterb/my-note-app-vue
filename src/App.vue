<template>
  <div id="main">
    <div id="head">
      <menu-icon id="guide-icon" icon="yt-icons:menu" className="style-scope ytd-masthead" style="margin: 12px">
        <svg viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet" focusable="false" className="style-scope yt-icon"
             style="pointer-events: none; display: block; width: 100%; height: 100%;">
          <g className="style-scope yt-icon">
            <path d="M21,6H3V5h18V6z M21,11H3v1h18V11z M21,17H3v1h18V17z" className="style-scope yt-icon"></path>
          </g>
        </svg><!--css-build:shady-->
      </menu-icon>
    </div>
    <div id="body">
    </div>
  </div>

</template>

<script>
export default {
  name: 'top-head',
  props: {}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


#main {
  height: 100vh;
  overflow: auto;
  display: flex;
  flex-direction: column;
}

#head {
  background-color: white;
  height: 56px;
  display: flex;
}

#body {
  background-color: #f9f9f9;
  flex: 1;
}
</style>
