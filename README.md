# wordpress-100 
An ongoing project toward a WordPress build that achieves default Google Lighthouse scores of 100/100


## The Premise 
In 2021 i learned that Google Lighthouse throws the user a fireworks party when the Chrome Lighthouse browser extension detects four (4) perfect 100/100 scores for Performance, Accessibility, Best Practices, and SEO:  

<video width="600" height="375" controls>
  <source src="https://darkblack-papa.s3.us-east-1.amazonaws.com/210603-ericadreisbach-desktop-100-lighthouse.mp4" type="video/mp4">
</video>

<video width="600" height="342" controls>
  <source src="https://darkblack-papa.s3.us-east-1.amazonaws.com/210605-erica-dreisbach-mobile-lighthouse.mp4" type="video/mp4">
</video>

Scores above were achieved on my lightweight PHP portfolio; **could they be achieved on a default WordPress build?**


## The Plan

1. Identify a suitable tech stack to: 
    - optimize images
    - secure the build
    - deliver assets
2. Identify a suitably fancy visual design  
    - Establish that bells and whistles need not be compromised for performant WordPres
3. Adapt the WordPress default <a href="https://wordpress.org/themes/twentytwentyfive/" targe="_blank" rel="nofollow noopener">Twenty Twenty-Five theme</a>
    - Learn <a href="https://developer.wordpress.org/themes/templates/template-parts/" target="_blank" rel="nofollow noopener">Template Part syntax</a>
    - `<!-- wp:template-part {"slug":"your-template-part-slug"} /-->`