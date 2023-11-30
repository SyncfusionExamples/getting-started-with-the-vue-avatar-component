<script>

</script>

<template>
<div>
  <!-- <div class="e-avatar image e-avatar-small"></div>
  <div class="e-avatar image"></div> -->
 
  <div class="container-div">
    <div class="e-card e-custom-card">
        <div class="e-card-header">   
           <div class="e-avatar image e-avatar-xlarge e-avatar-circle"></div>  
        </div>
        <div class="e-card-header">
            <div class="e-card-header-caption center">
                <div class="e-card-header-title name">Laura Callahan</div>
                <div class="e-card-sub-title">Sales Coordinator</div>
            </div>
        </div>
        <div class="e-card-content">
            <p class="avatar-content">
                Laura received a BA in psychology from the University of Washington. She has also completed a course
                in business French. She reads and writes French.
            </p>
        </div>
    </div>
  </div>
</div>
</template>

<style>
@import "../node_modules/@syncfusion/ej2-base/styles/material.css";
@import "../node_modules/@syncfusion/ej2-layouts/styles/material.css";

.e-avatar.image{
  background-image: url(https://ej2.syncfusion.com/vue/demos/img/pic02.cbd95002.png);
  margin: 2px;
}
.container-div .name {
  margin-top: 10px;
}

.container-div {
  max-width: 300px;
  margin: auto;
  min-height: 400px;
}

.e-custom-card {
  overflow: visible;
  margin-top: 80px;
  border-width: 1px;
  padding: 1px;
}

.e-custom-card .e-card-header {
  text-align: center;
  padding: 0px;
}

.e-custom-card .e-avatar {
  font-size: 25px;
  position: absolute;
  bottom: 160px;
  left: auto;
  box-shadow: 0 16px 28px -8px rgba(0, 0, 0, .36), 0 4px 15px 0 rgba(0, 0, 0, .12), 0 8px 10px -5px rgba(0, 0, 0, .2);
}

.e-card.e-custom-card :nth-child(3) {
  padding: 10px 0px 10px 0px;
}

.e-custom-card.e-card .e-card-content {
  overflow: visible;
}

.avatar-content {
  text-align: center;
  color: rgb(94, 94, 94);
}

</style>
