<template>
    <ul>
        <li><a href="https://github.com/DavidZalewski"><img src=".\icons\github-icon.png"/></a></li>
        <li><a href="https://www.linkedin.com/in/dawid-zalewski-633012292/"><img src=".\icons\linkedin-icon.png"/></a></li>
        <li><a href="mailto:david.zalewski@protonmail.com"><img src=".\icons\protonmail-icon.png"/></a></li>
        <li><a href="https://docs.google.com/document/d/1LDdZ_Oos0NvWGxdjvaWBQmMTfNpvFaqbS_WXydAYa-Y/edit?usp=sharing"><img src=".\icons\resume-icon.png"/></a></li>       
    </ul>
</template>

<style scoped>
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #fdfdfd;
}

li {
  float: right;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 16px;
  text-decoration: none;
}

li a:hover {
  background-color: #111111;
}

li img {
  width: 37px;
  height: 37px;
}
</style>