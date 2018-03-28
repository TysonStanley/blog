---
layout: post
title: "Using to Jamovi: Correlation and Regression"
categories: jekyll update
author: Tyson S. Barrett
comments: true
---

[Jamovi](https://www.jamovi.org) is a new piece of software that makes running most basic analyses quicker, easier, and better. Shockingly, this is a *free* program based on the R programming language. It has the goal of "free and open software to bridge the gap between researcher and statistician." Needless to say, it is worth taking a look if you are doing some basic analyses and don't want to pay for SPSS or SAS, or learn how to use `R`. It provides informative tables and neat visuals. 

This post is part of a series--demonstrating the use of Jamovi--mainly because some of my students asked for it. Notably, this is using version 0.8.6.0.

## Correlation

Getting data into Jamovi is fairly straightforward if your data are in CSV, Excel, SPSS, Stata, and others. To import existing data, click on the upper left corner of Jamovi on the three horizontal lines. This opens up what is shown in the following screen shot. From here, you find the data file on your computer, select it, and select "open".

![]( {{ site.baseurl }}/assets/Jamovi/DataTypes.png)

From here, we can change the variable types by double clicking on the variable name. The bubbles or ruler tell us what kind of variable it is.

![]( {{ site.baseurl }}/assets/Jamovi/VarTypes.png)

Now that these are prepped, much of the data cleaning is much like you do in Microsoft Excel (although I recommend cleaning in a program other than Jamovi since at this point you can only do basic adjustments in Jamovi).

At the top of Jamovi's GUI, there are a number of tabs that are different analyses that you can do, including `Exploration`, `T-Tests`, etc. For this demonstration, we are going to show the `Exploration` tab.

## Regression








{% if page.comments %} 
<div id="disqus_thread"></div>
<script>
    /**
     *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
     *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables
     */
    /*
    var disqus_config = function () {
        this.page.url = page.url;  // Replace PAGE_URL with your page's canonical URL variable
        this.page.identifier = page.identifer; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
    };
    */
    (function() {  // DON'T EDIT BELOW THIS LINE
        var d = document, s = d.createElement('script');
        
        s.src = '//tysonstanley.disqus.com/embed.js';
        
        s.setAttribute('data-timestamp', +new Date());
        (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript" rel="nofollow">comments powered by Disqus.</a></noscript>
{% endif %}
