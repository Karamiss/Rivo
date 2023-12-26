<template>
  <h1>WE ARE RIVO AGENCY</h1>
 
 <section class="preview">
  <div class="Kfau">
    <div class="we-help">
      <img src="/images/preview_icon-1.png">
      <span>WE HELP</span>
    </div>
    <div class="ideas">
      <span>IDEAS</span>
      <img class="icon-click" src="/images/preview_icon-click.png">
    </div>
    <div>
      <img src="/images/preview_icon-2.png">
      <span>CHANGE</span>
    </div>
    <div>

      <span>THE WORLD</span>
    </div>
  </div>
</section>

</template>

<script>
export default {
  name: "main-preview",
};

</script>


<style lang="scss" scoped>
.icon-click {
  // width: clamp(160px, 5vw, 373px);
  width: clamp(160px, 15vw, 373px);
  padding: 0 0px 0 20px;
}
img {
  width: clamp(74px, 10vw, 168px);
  padding: 0 20px 0 0;
}
span {
  font-size: clamp(60px, 15vw, 139px);
  
  // font-size: 139px;

}

.Kfau {
  border: 1px dashed #e96004;
  // max-width: 100%;
  // max-width: 75%;
  white-space: nowrap;
  box-sizing: border-box;
  // margin: 0px 15px;


}
.preview {
  width: 100%;
  display: flex;
  justify-content: center;
  
}

h1{
  max-width: 100%;
  font-size: 20px;
  color: #818181;
  text-align: center;
  display: flex;
    justify-content: center;
}
span {
  color: #1A1A1A;
  // font-size: 139px;
  // line-height: 100%;
}


</style>