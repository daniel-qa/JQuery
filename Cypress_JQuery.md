* 設定 Cookies
https://www.runoob.com/jquery/jquery-cookie-plugin.html

* 說明
```
 * Create a cookie with the given key and value and other optional parameters.
 *
 * @example $.cookie('the_cookie', 'the_value');
 * @desc Set the value of a cookie.
 
 * @example $.cookie('the_cookie', 'the_value', { expires: 7, path: '/', domain: 'jquery.com', secure: true });
 * @desc Create a cookie with all available options.

 * @example $.cookie('the_cookie', 'the_value');
 * @desc Create a session cookie.

 * @example $.cookie('the_cookie', null);
 * @desc Delete a cookie by passing null as value. Keep in mind that you have to use the same path and domain
 *       used when the cookie was set.

```


* Ex
```
$(document).ready(function(){
  $.cookie('name', 'runoob');  // 创建 cookie
  name = $.cookie('name');     // 读取 cookie
  $("#test").text(name);
  $.cookie('name2', 'runoob2', { expires: 7, path: '/' });
  name2 = $.cookie('name2');
  $("#test2").text(name2);
});

```




```

$(this).hide()- 隱藏當前元素。

$("p").hide()- 隱藏所有 <p> 元素。

$(".test").hide()- 隱藏所有帶有 class="test" 的元素。

$("#test").hide()- 隱藏 id="test" 的元素。

您可以<p>像這樣選擇頁面上的所有元素：

$("p")

```



```
Cypress.$('p')

Cypress.$(".w-e-up-img-container div").show;


```
