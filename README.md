# jqueryNumberValidator
You might have witness, at some places where numbers are allowed, paste feature doesn’t work either in IE or in Chrome/Firefox AND in some particular scenarios, paste feature worked fine in IE/Chrome but not in Firefox AND paste alphabets along numbers too in numbers only text field . After coding/debugging/testing, finally come up with below written code that totally runs smoothly even on IE > 6.0 

During development I always encountered by scenario where we have to allow number only as input in text fields[sounds child play!! right ], since validation plugin is provide by jQuery , you can always include such plugins in your page in order to achieve validation feature for input fields, So coming back to point, always remember KISS principle [Keep It Simple Stupid – Google it!!!], it states that system runs smoothly when they are less complex, since we can achieve validation feature from native JavaScript/jQuery then there seems no reason to include extra validation plugin in your page for couple of fields and increase page load time [unless you tweak plugin library a lot – which totally depends upon time]

So this function will check the input value on keypress or when you move focus to other field or when you press ctrl + v in target input area,  just need to place the code in:  
jQuery - $(document).ready(), in case of JavaScript -  window.onload 
