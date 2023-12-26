<template>
      <div class="header">
      <div class="wrap-logo">
        <img class="img-logo" src="@/assets/Logo.svg">
      </div>
      <nav class="navigation"> 
        <a href="/projects">Projects<sup>16</sup></a>
        <a href="/services">Services</a>
        <a href="/expertise">Expertise</a>
        <a href="/contacts">Contacts</a>
        <a href="/careers">Careers<sup style="background: #FDDD0A; font-size: 10px;">HOT</sup></a>
      </nav>
    </div>
 </template>
 
 <script>
 export default {
   name: "app-header",
 };
 </script>
 
 <style lang="scss" scoped>
.header {
	box-sizing: border-box;
	display: flex;
	align-items: center;
	justify-content: space-between;
	gap: 5px;
}
.wrap-logo {
	flex: 1;
  & .img-logo {
	width: 36px;
	height: auto;
 }
}
.navigation {
	display: flex;
	flex: 1;
	align-items: center;
	justify-content: flex-end;
	gap: 8px;
	& a {
		text-align: center;
		text-decoration: none;
		color: #000000;
		font-size: clamp(12px, 2vw, 18px);
		font-weight: 700;
	}
}
 </style>