<h1 align="center">Auto Theme Changer - Plus UI Addon</h1>

![autoThemeChanger](https://raw.githubusercontent.com/theamanstark/autoThemeChanger/v1.0/.gitassets/demo.png)
</br>
<h3 align="center">
  Demo :- <a href="https://imstark.link/autoThemeChanger">Click Here</a>
</h3>
</br>
</br>

# # Working

1. Auto Theme Changer will change the theme on site load, like opening posts, pages, searches, labels, categories, and reloading the site.
2. Auto Themer will change the site theme every 5 seconds, giving it a disco-like look. Use this as an Easter egg on your site.

</br>
</br>

# # Documentation

1. Just add the CSS using any one of the following methods above the `</head>` in your theme.

   (i) Using inline CSS Style 👇

   ```html
   <style>
   .head1,.para1,.para2{margin-left:6px}.head1{font-size:14px;font-family:"Google Sans Text";color:#343435;margin-bottom:-7px;font-weight:unset}.para1{margin-bottom:-11px}.brr{content:"";display:block;border-bottom:1px solid var(--contentL);margin:12px 5px}.cusP{margin-bottom:-20px}@media screen and (min-width:750px){.switch{left:205px;transform:rotate(90deg);top:-48px}}@media screen and (max-width:361px) and (min-width:322px){.switch{left:220px!important;top:-45px!important}}@media screen and (max-width:321px){.switch{left:202px!important;top:-46px!important;transform:rotate(90deg)!important}}@media screen and (max-width:376px) and (min-width:362px){.switch{left:240px!important;top:-45px!important}}@media screen and (max-width:415px) and (min-width:395px){.switch{left:280px!important;top:-45px!important}}@media screen and (max-width:394px) and (min-width:377px){.switch{left:255px!important;top:-45px!important}}@media screen and (max-width:749px) and (min-width:416px){.switch{left:286px;top:-45px}}.switch{position:relative;display:inline-block;width:55px;height:30px;margin-bottom:-2000px}.switch input{opacity:0;width:0;height:0}.slider{position:absolute;cursor:pointer;top:0;left:0;right:0;bottom:0;background-color:#ccc;-webkit-transition:.4s;transition:.4s}.slider:before{position:absolute;content:"";height:22px;width:22px;left:3.5px;bottom:4px;background-color:#fff;-webkit-transition:.4s;transition:.4s}input:checked+.slider{background-color:var(--linkC)}.drK input:checked+.slider{background-color:var(--darkU)}input:focus+.slider{box-shadow:0 0 1px #2196f3}input:checked+.slider:before{-webkit-transform:translateX(26px);-ms-transform:translateX(26px);transform:translateX(26px)}.slider.round{border-radius:34px}.slider.round:before{border-radius:50%}
   </style>
   ```

   **Note**: We suggest adding CSS using the second method, which is to use an external CSS style cdn link. This way, if any changes are made to the code, you will see the updates on your site right away, but if you intend to customize the widget, use the first method.

   (ii) Using an external CSS style cdn link 👇

   #### 

   ✨ If you want to get the latest updates as soon as possible, then use the below CDN link.
   
   ```html
    <link rel="stylesheet" href="https://theamanstark.com/cdn/blogger/plus-ui/autoThemeChanger/latest/autoTheme.min.css" />
    ```

   ### 

   ✨ If you want to use version 1.0 of autoThemeChanger, then use the below cdn link.

   ```html
    <link rel="stylesheet" href="https://theamanstark.com/cdn/blogger/plus-ui/autoThemeChanger/v1.0/autoTheme.min.css" />
    ```

   ##

2. Now, put the following javascript above: `</body>` in your theme, using any one of the cdn links.

   ####

   🎫 If you want to get the latest updates as soon as possible, then use the below CDN link.

   ```html
   <script src='https://theamanstark.com/cdn/blogger/plus-ui/autoThemeChanger/latest/autoTheme.min.js'></script>
   ```

   ###

   🎫 If you want to use version 1.0 of autoThemeChanger, then use the below cdn link.

   ```html
   <script src='https://theamanstark.com/cdn/blogger/plus-ui/autoThemeChanger/v1.0/autoTheme.min.js'></script>
   ```

   ##

3. Finally, add the following HTML in the `<div class='cusP'>`; check the image below to know the place of addition.

   ![ThemeChangerHTML](https://raw.githubusercontent.com/theamanstark/autoThemeChanger/v1.0/.gitassets/html-help.png)

   ```html
   <div class="brr"/><h6 class="head1">Auto Theme Changer</h6><p class="para1">When turned on automatically changes</p><p class="para2">the theme color on reload.</p><label class="switch"><input id="theme-toggle" type="checkbox"/><span class="slider round"/></label><div class="brr" style="margin-top:-6px;"/><h6 class="head1">Auto Themer</h6><p class="para1">When turned on automatically changes</p><p class="para2">the theme color every 5 sec.</p><label class="switch"><input id="auto-theme" type="checkbox"/><span class="slider round"/></label>
   ```

   ##

#### #Note: If you experience any problems with the code, raise the issue on the repo's <a href="https://github.com/theamanstark/autoThemeChanger/issues">Issues</a> tab. Also, you cannot presently adjust the time-frame of Auto Themer from 5 seconds to a custom number; this will be included in a future version of the code.

##

**Credits**: Auto Theme Changer created by [Aman Singh](https://www.amanstark.com).
