<template lang="">
  <h3 class="project">Project</h3>
  <div class="project-info">
    <p>
      <a
        href="https://github.com/judeokeleke"
        rel="noopener noreferrer"
        target="_blank"
        >Github</a
      >
    </p>
    <p>
      <a
        href="counter-8bbf7.firebaseapp.com"
        target="_blank"
        rel="noopener noreferrer"
        >404 Page Error.</a
      >
    </p>
    <p>
      <RouterLink class="link" to="/counter">Counter App</RouterLink>
    </p>
  </div>
</template>
<script setup></script>
<style>
.project-info {
  padding-left: 10px;
  color: #32355c;
}
.project {
  color: #32355c;
}
a {
  text-decoration: none;
  color: #32355c;
  cursor: pointer;
}
</style>
