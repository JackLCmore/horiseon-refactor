# My First Coding Project

## Table of Contents
* [Who Am I?](#who-am-i)
* [Why Refactor This Website?](#why-refactor-this-website)
* [What Changed?](#what-changed)
* [Impact](#impact)
* [Resources Used](#resources-used)
* [Credits](#credits)
* [Contact Info](#contact-info)

## Who Am I?

[Visit the Deployed Site](https://jacklcmore.github.io/horiseon-refactor/)

The first thing to address in my first README.md is who I am. Hello! My name is Jack Lunchick-Seymour, I am a novice coder and current coding student with the UC Berkeley Extension, I am 24 years old and I enjoy spending time with my friends, playing video games and Magic The Gathering! 

Whilst my coding knowledge is limited, it is also the reason I am writing this README and editing this code!

## Why Refactor This Website?

To know an answer you must first know the question, and its not as easy as 42. 

**Why edit the code of a perfectly working website?**

There are many reasons to edit code and whether it be for the sake of knowledge, experimentation or obligation they are all valid reasons, as well as all reasons I took on this project.

Another and very important reason to edit code (and especially in this case) is to achieve better legibility or organization. While the code might be able to be read by your device that doesnt mean it can be read on all devices; or even by your friendly neighborhood coding student (spoiler)

## What Changed?

Now that we properly defined who I am, why I decided to edit this code and the reasons I did so, you might be wondering what I did to these poor html and css files. 

That's Easy! Not much at all has changed in all honesty, but that's the beauty (and bane) of coding (as far as my limited knowledge goes).

To summerize what I have done to these files is simple: I took the snippet of code I wanted to edit, explored it from the top down and modified redundant or non-accesible* elements

Examples of my changes:

```html
 <header class="header">
        <h1 title="Horiseon">Hori<span class="seo">seo</span>n</h1>
        <section class="header-list">
            <ul>
                <li><a href="#search-engine-optimization" alt="Search Engine Optimization">Search Engine Optimization</a></li>
                <li><a href="#online-reputation-management" alt="Online Reputation Marketing">Online Reputation Management</a></li>
                <li><a href="#social-media-marketing" alt="Social Media Marketing">Social Media Marketing</a></li>
            </ul>
        </section>
    </header>
```
Here I added title and alt attributes to their respective sections as to increase the sites accessibility.

```html
<section class="benefits">
        <article class="benefit-lead">
            <h3 class="h3">Lead Generation</h3>
            <img class="benefits-img-dimensions" src="./assets/images/lead-generation.png" alt="Work Funneling into Money">
            <p>Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.</p>
        </article>
        <article class="benefit-brand">
            <h3 class="h3">Brand Awareness</h3>
            <img class="benefits-img-dimensions" src="./assets/images/brand-awareness.png" alt="Lightbulb Sending Signal">
            <p>Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.</p>
        </article>
        <article class="benefit-cost">
            <h3 class="h3">Cost Management</h3>
            <img class="benefits-img-dimensions" src="./assets/images/cost-management.png" alt="Gearcog and Coins">
            <p>As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.</p>
        </article>
    </section>
```
Here I added semantic elements to replace previous div elements as to increase the sites accessibility as well as added class elements to further consolidate and organize code structure.

```css
.benefit-lead, .benefit-brand, .benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}
```
Here I consolidated the dimension information for three seperate classes into one snippet of code.

## Impact

What is the impact of this project? 
Why spend hours to fix a website with few flaws from the users point of view?

To put it bluntly: greed and selfish gain >:)

Seriously, fixing things such as organization or content accesibility is extremely important to keep websites running smoothly and appeal to the diverse range of users the site might invite!

Finally, my portfolio must start somewhere, and this is a comfortable start to my future coding career!

## Resources Used
* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [Git](https://git-scm.com/)

## Credits
* You! Thanks for reading!
* Jerome Chenette! Thank you for teaching good and stuff!
* Me! I'm the greatest!

## Contact Info

**Contact me here**
* [Email] (jack.lcmore@gmail.com)
* [Phone#] ((808)640-4366)
* [GitHub] (https://github.com/JackLCmore)