<template>
  <div id="app">
    <header class="mod_header">
      <div class="row">
        <div class="header_logo">
          <a href="/" class="header_logo_link">
            <img class="header_logo_image" alt="Victorinox" src="./assets/logo.svg" />
          </a>
        </div>
      </div>
    </header>
    <main class="mod_content">
      <div class="row">
        <router-view />
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
  /*! normalize.css v3.0.1 | MIT License | git.io/normalize */
  html{font-family:sans-serif;-ms-text-size-adjust:100%;-webkit-text-size-adjust:100%;font-size:62.5%}body{margin:0;font-family:Helvetica,Arial,sans-serif;font-weight:300;line-height:1.5;font-size:16px;font-size:1.6rem;color:#000}article,aside,details,figcaption,figure,footer,header,hgroup,main,nav,section,summary{display:block}audio,canvas,progress,video{display:inline-block;vertical-align:baseline}audio:not([controls]){display:none;height:0}[hidden],template{display:none}a{background:0 0}a:active,a:hover{outline:0}abbr[title]{border-bottom:1px dotted}b,strong{font-weight:700}dfn{font-style:italic}h1{margin:.67em 0;font-size:40px;font-weight:300}mark{background:#ff0;color:#000}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sup{top:-.5em}sub{bottom:-.25em}img{border:0;max-width:100%;height:auto}svg:not(:root){overflow:hidden}figure{margin:1em 40px}hr{-moz-box-sizing:content-box;box-sizing:content-box;height:0}pre{overflow:auto}code,kbd,pre,samp{font-family:monospace,monospace;font-size:1em}button,input,optgroup,select,textarea{color:inherit;font:inherit;margin:0}button{overflow:visible}button,select{text-transform:none}button,html input[type=button],input[type=reset],input[type=submit]{-webkit-appearance:button;cursor:pointer}button[disabled],html input[disabled]{cursor:default}button::-moz-focus-inner,input::-moz-focus-inner{border:0;padding:0}input{line-height:normal}input[type=checkbox],input[type=radio]{box-sizing:border-box;padding:0}input[type=number]::-webkit-inner-spin-button,input[type=number]::-webkit-outer-spin-button{height:auto}input[type=search]{-webkit-appearance:textfield;-moz-box-sizing:content-box;-webkit-box-sizing:content-box;box-sizing:content-box}input[type=search]::-webkit-search-cancel-button,input[type=search]::-webkit-search-decoration{-webkit-appearance:none}fieldset{border:1px solid silver;margin:0 2px;padding:.35em .625em .75em}legend{border:0}textarea{overflow:auto}optgroup{font-weight:700}table{border-collapse:collapse;border-spacing:0}legend,td,th{padding:0}p{font-size:20px}.row{box-sizing:content-box;max-width:640px;margin-right:auto;margin-left:auto;display:-webkit-box;display:-webkit-flex;display:-ms-flexbox;display:flex;-webkit-box-orient:horizontal;-webkit-box-direction:normal;-webkit-flex-flow:row wrap;-ms-flex-flow:row wrap;flex-flow:row wrap}.svginject{display:none}.svg-wrap{position:relative;height:0;width:100%}.svg-wrap svg.svginject{position:absolute;top:0;left:0;width:100%;height:100%;max-width:100%;display:block}.mod_header{border-bottom:1px solid #d0d0ce;padding:20px 0}.header_logo{width:137px;width:13.7rem;padding-left:50px;padding-left:5rem}.mod_content{padding:40px}.mod_content>.row{border-bottom:1px solid #d0d0ce}.content_element{width:100%;margin-bottom:50px}.content_element.var_centered,.mod_button{text-align:center}.mod_button{font-size:20px;background:#b11e37;color:#fff;max-width:240px;padding:5px 0;margin:0 auto;cursor:pointer}.mod_button:hover{background:#a01d34}.mod_table{display:flex;flex-flow:column nowrap;flex:1 1 auto}.table_column,.table_row{display:flex;flex-flow:row nowrap}.table_column{flex-grow:1;flex-basis:0}.mod_alert{font-size:20px;background:#f2f2f2;color:#b11e37;text-align:center;padding:40px;margin-bottom:10px}
</style>
