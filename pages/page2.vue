<template>
  <div class="container">
    <div>
      <h1 class="title">
        Question 9
      </h1>
      <div class="subtitle">
          Steps:
      </div>
      <div class="text">
        <ol>
            <li>I created a nuxt app with the command "npx create-nuxt-app question9".</li>
            <li>Created a basic logo in Illustrator, saved as .svg so i could play around with some animation in CSS to give the app a bit more personallity.</li>
            <li>Edited the index.vue file to serve my needs.</li>
            <li>Added a new page "page2.vue".</li>
            <li>Created a new Git repo and pushed my content before making any new changes to the app.</li>
            <li>Deployed my Git repo to netlify.</li>
            <li>Added final preperations to the app.</li>
        </ol>
      </div>
      <div class="links">
            <NuxtLink to="/"
                class="button--green"
            >
                Back
            </NuxtLink>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.text {
    width: 80%;
    text-align: left;
    margin: 0 auto;
}

li {
    margin-bottom: 15px;
}
</style>
