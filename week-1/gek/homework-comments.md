### Homework Completion

- [x] Link both pages together using `a` tag
- [x] Use a unique `title` and a single unique `h1` tag
- [x] Show images using `img` tags including unique `alt` attributes
- [x] Use an external CSS stylesheet to style your pages  
- [x] Select at least 5 elements on the page and apply at least 5 different css properties (`font-size`, `color`, `font-family`, `background`, `text-decoration`) to these elements
- [x] Use at least 6 different HTML tags (`h1`, `h2`, `h3`, `h4`, `h5`, `h6`, `p`, `ul`, `ol`, `a`, `img`) on your pages
- [x] Follow naming conventions, maintain consistency across your .html and .css files
- [x] Indent nested elements to increase your code's readability

### Homework Comments
Interesting layout for your **About Me** page. I like the *large typography* introduction, it's actually quite a trendy style in web design!

Here are some areas that you can modify to improve on your website.
- You might want to rename your **Resume page.html** to **resume-page.html**, as the blank space in-between words will appear as `Resume%20page.html` in the URL and this will cause your link to fail. So use small caps and no spaces when naming html files.

- For the list items in Resume page, you can nest all your items and reduce the markup. Below is an example:

```html
<ul>
  <li>
    <h4>Web Developer, Relaxr 2015 - present</h4>

    <p>Developed a multi-column layout blog, landing page, and contact forms that render on mobile devices.</p>

    <img src="images/relaxr_deliverable.png" alt="text">
  </li>
  <li>
    <h4>Web Developer, Startup Matchmaker 2015 - present</h4>

    <p>Used a design team's wireframes to develop this company's responsive homepage.</p>

    <img src="images/startup_matchmaker_deliverable.png" alt="text">
  </li>
  <!-- add more <li> below -->
</ul>
```

You can also try to experiment using the `<div>` tag to separate sections of your content in future. Good work Gek!
