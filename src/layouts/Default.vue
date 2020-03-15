<template>
  <main class="layout" role="main">
    <slot/>
    <div class="footer">
      <p>
        Built with
        <a target="_blank" class="link" href="//gridsome.org">Gridsome</a>
        & Made with ❤️ by
        <a target="_blank" class="link" href="//alex.design">Alex Brown</a>
      </p>
    </div>
  </main>
</template>

<style>
body {
  font-family: -apple-system,system-ui,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif;
  margin:0;
  padding:0;
  line-height: 1.5;
  font-size:1.1em;
}
.layout {
  max-width: 760px;
  margin: 0 auto;
  padding-left: 20px;
  padding-right: 20px;
}
.footer {
  margin-top:60px;
}
a {
  border-bottom: 1px solid currentColor;
  color: rgb(32, 201, 151);
  text-decoration: none;

}
a:hover {
  border-bottom-color: currentColor;
  color: #686868;
}
</style>
