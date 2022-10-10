<template>
  <div>
    <img src="../assets/logo.png" />
    <p class="gVaTvc">404</p>
    <p class="jwJDVb">Oops, page not found.</p>
    <button>Back Home</button>
  </div>
</template>

<script>
export default {
  name: "NotFound",
  components: {},
};
</script>

<style scoped>
div {
  align-items: center;
  display: flex;
  flex-direction: column;
  height: calc(100vh - 64px);
  justify-content: center;
}

img {
  width: 64px;
}

button {
  position: relative;
  -webkit-box-align: center;
  align-items: center;
  border: 0px;
  border-radius: 16px;
  box-shadow: rgb(14 14 44 / 40%) 0px -1px 0px 0px inset;
  cursor: pointer;
  display: inline-flex;
  font-family: inherit;
  font-size: 16px;
  font-weight: 600;
  -webkit-box-pack: center;
  justify-content: center;
  letter-spacing: 0.03em;
  line-height: 1;
  opacity: 1;
  outline: 0px;
  transition: background-color 0.2s ease 0s, opacity 0.2s ease 0s;
  height: 32px;
  padding: 0px 16px;
  background-color: #1fc7d4;
  color: white;
}

.jwJDVb {
  color: #280d5f;
  font-weight: 400;
  margin-bottom: 16px;
  font-size: 16px;
}

.gVaTvc {
  font-size: 64px;
  color: #280d5f;
  font-weight: 600;
  vertical-align: baseline;
  margin-block-start: 0em;
  margin-block-end: 0em;
}
</style>
