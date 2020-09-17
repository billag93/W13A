<template>
  <div class="page-body">
    <div id="about-us">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore, labore nobis neque nemo maxime repellat consequatur illum exercitationem laboriosam numquam non. Facere veniam architecto placeat sint nostrum veritatis harum at.
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore, labore nobis neque nemo maxime repellat consequatur illum exercitationem laboriosam numquam non. Facere veniam architecto placeat sint nostrum veritatis harum at.
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore, labore nobis neque nemo maxime repellat consequatur illum exercitationem laboriosam numquam non. Facere veniam architecto placeat sint nostrum veritatis harum at.
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore, labore nobis neque nemo maxime repellat consequatur illum exercitationem laboriosam numquam non. Facere veniam architecto placeat sint nostrum veritatis harum at.
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore, labore nobis neque nemo maxime repellat consequatur illum exercitationem laboriosam numquam non. Facere veniam architecto placeat sint nostrum veritatis harum at.
    </div>
    <div id="meet-crew">
      <div>
        <img
          src="https://vignette.wikia.nocookie.net/character-level/images/f/f1/Goku_universe_survival_by_koku78-dbg6nkx.png/revision/latest/scale-to-width-down/340?cb=20190817185125"
          alt="goku"/>
      </div>
      <div>
        <img
          src="https://i.pinimg.com/originals/9d/f7/12/9df71280ef9bcceb74f507a168ddecee.jpg"
          alt="Luffy"/>
      </div>
      <div>
        <img
          src="https://i.pinimg.com/originals/48/3c/80/483c809a649a28ac59f19f7f9ba9657a.png"
          alt="naruto"/>
      </div>
    </div>
    <div id="more-links">
      <a href="https://www.apple.com/">Apple</a>
      <a href="www.google.com">Google</a>
      <a href="youtube.com">Youtube</a>
      <a href="microsoft.com">Microsoft</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "page-body",
};
</script>

<style scoped>
.page-body {
  display: grid;
  justify-items: center;
  align-items: center;
}
#about-us {
  text-align: left;
}
img {
  width: 100%;
  height: 600px;
}
#meet-crew {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  column-gap: 2%;
  width: 100%;
  border: 3px solid black;
  box-shadow: 5px 10px lightskyblue;
}
#more-links {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  column-gap: 20%;
  text-decoration: none;
  font-family: Arial, Helvetica, sans-serif;
  text-shadow: 2px 3px lightskyblue;
  color: skyblue;
  justify-items: center;
  align-items: center;
  padding: 3% 3%;
  margin: 5% 5%;
}
</style>