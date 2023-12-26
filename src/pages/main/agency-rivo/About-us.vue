<template>
  <article class="background">
    <span class="about-us">WHO WE ARE</span>
    <div class="about-wrapper">
      <div>
        <img src="/images/about-us_video.png">
      </div>
      <div class="section-wrapper">
        <div v-for="(text, index) in data" :key="index">
          <div class="style">{{ text.title }}</div>
          <div class="small-text" v-html="text.text"></div>
        </div>
      </div>
    </div>
  </article>
</template>

<script>
export default {
  name: "about-us",
  data() {
    return {
      data: [
        {
          title: "Hi! We are a team of professionals",
          text: "With proven expertise in delivering effective, secured and high-quality digital solutions for various industries and digital marketing.",
        },
        {
          title: "Our company",
          text: "Offers development of different products starting from simple promo websites for individuals or companies, and finishing with complicated solutions for multiple purposes, e.g. <br><br>CRM and ERP systems, scalable web platforms, mobile applications, Internet-of-Things, etc. We apply our expertise and knowledge to take your product from concept to prototype and to production.",
        }
      ]
    };
  }
};
</script>

<style scoped>
.background {
	background: #EEEEF0;
}
.about-wrapper {
	display: flex;
	flex: 1;
	gap: 28px;
}
.about-us {
	display: flex;
	justify-content: left;
	line-height: normal;
	white-space: nowrap;
	font-size: 52px;
	font-weight: 700;
	font-style: normal;
}
.style {
	text-transform: uppercase;
	line-height: 100%;
	font-size: 24px;
	font-weight: 700;
	font-style: normal;
}
.small-text {
	margin: 24px 0px;
	line-height: 150%;
	color: #818181;
	font-family: Gilroy;
	font-size: 17px;
	font-weight: 500;
	font-style: normal;
}
</style>
