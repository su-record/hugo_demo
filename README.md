# hugo_demo
showing short code &lt;script> issue

when using  

```<script>some javascript code </script>```

in a shortcode, if the shortcode is shown in the summary, anything 
between the <script/> tags is shown verbatim. In the summary then 
you will see the code. 

There is a shortcode, `button.html` in the layouts/shortcode directory

## to run

```
cd quickstart
hugo serve -D
```

You will see the script inner html in the summary view.
Clicking "read more" button will take you to the post view and show the button. 
Clicking the button when developer tools is open, you can see the "SHOW CLICK" messages.
