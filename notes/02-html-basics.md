## Div
So what is div , and how can we use div in the HTML? We can also use it in a very basic form without styling, to hold other elements together. So for example, we can create a div and put a heading in it, and put a paragraph in it, and now these two elements will be grouped together:
```html
<div>
  <h1>Heading</h1>
  <p>Paragraph</p>
</div>
```
**Remember:** Section has sematic meaning but div doesn't have. Div has their own personality with no defined meaning. 

## IDS and Classes
I will explain this with the help of simple difference just to let you classify it easily. 
1. ID should contain unique attribute value while class doesn't i.e you can add multiple class attribute value to an element.
2. ID shouldn't contain any space between them , as mentioned above. ( Just to point out )
3. Class attribute value can be accessed in CSS to apply it's own styling with the help of . and for ID, we use #. (Which we will discuss in CSS)
   
   ```html
   <h1 id="heading-style">HEY LAZY POTATO</h1>
   <h1 class="heading-style additional-style">HEY LAZY TOMATO</h1>
   ```
**If you use the same id more than once in your HTML - It can lead to unwanted results and issues when trying to apply styles or targetting and elements in JAVASCRIPT**

## Script Element:
What does JavaScript do Yugal? 
-> It adds interactivity to the webpage. 

Before diving into the concept of scripting, Script is an element used to embed executable code. We use it to add java script code in the html. 

```html
<script> alert("Hey Lazy Banana"); </script>
```

This display an alert message. 

But, Imagine writing 1000 lines of code into the same file, it's messy , hectic and not so beautiful. So What do we do? We separate them into distinct separate files. 
Separation of concerns is a design principle where you separate your programs into distinct sections and have each sections addres a sep<arate concern. This principle is useful because you can organize the executable code in different file and think independently.
```html
<script src="your-js-code.js"></script>
```

## Meta Description and SEO:

**SEO**: Don't you want your hardworked website to be ranked higher when a user searches something related to it. SEO (Search Enginer Optimization) is a practice that optimizes web pages so they become more visible and rank higher on search engines. 
A quick assisgnment - search anything in the website, do you see a little description below the web page? Let's know how it is created?

```html
<meta name="description" content="This is the content that is being displayed below the webpage in the search result page."/>
```
*Remember the above content or meta description will not be displayed inside the webpage. Keep your descriptions short , sweet and concise so that it results into user clicking it easily and previewing the general outlook of the website.*

## Open Graph tag and SEO:
Open Graph (OG) tags are snippets of code that publishers can add to their websites to control how content appears when shared on social media platforms. While not a direct ranking factor for search engines, they play a crucial role in SEO by influencing user engagement and click-through rates from social media, indirectly impacting a site's overall visibility

<img width="686" height="386" alt="image" src="https://github.com/user-attachments/assets/0c948d74-a11f-4a1c-ba5a-299c8c9c8143" />

Above picture explain the general outlook of the concept we are going to learn. 
1. title:
   ```html
     <meta content="yugal-music" property="og:title" />
   ```
   The content attribute is where you will write the title you want displayed for social media sites.
2. type:
   ```html
     <meta property="og:type" content="website" />
   ```
   The type property is used to represent the type of content being shared on social media. Examples of this content include articles, websites, videos, or music.
3. image:
   ```html
   <meta content="photo.png" property="og:image"/>
   ```
4. url:
   ```html
   <meta property="og:url" content="https://www.google.com" />
   ```
*well-crafted OG properties can enhance the appearance for your content in users' feeds*




   
