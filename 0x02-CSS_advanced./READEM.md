# 0x00-html_advanced

## Description
What you should learn from this project:

* Selectors, properties, and values
* The difference between block and inline styling
* How to ensure consistency across all browers (CSS reset)
* How to setup CSS variables
* The differences between inline, embeded and external CSS
* How grid systems work (with floats)
* The difference between icons webfonts and SVG icons
* The difference between pseudo-classes and pseudo-elements
* How to make background gradients
* How to animate elements in CSS
* How to transform (2d, 3d) elements
* What vendor prefixes are

---

### [0.Let's get some images!](./images)
* Images for the project

### [1.Effortless transitions when scrolling](./styles./1-style.css)
* When scrolling is triggered on the html element itself, we’d like the behavior of the scroll to be as fluid as possible.

### [2. Do you know your color values?](./styles./2-style.css)
* Based on styles/1-style.css, create the following declarations:

    For the body, set the foreground color value to #161616
    For all anchor elements, set the foreground color value to #161616
    All elements with the class visually-hidden should have their display to none
    All elements with the class card-category, should have their foreground color set to #D73953
    All elements with the class section-tagline should have their foreground color set to #D73953


### [3. Reuse and repeat. A programmer's life should be simple with variables](./3-style.css)
* Copy the content of 2-index.html into 3-index.html

Header:

    create the header of your page between the open and close body tag
    put the text Header inside the header

Main:

    create the main tag after the header tag
        put the text Main content inside your main tags

Footer:

    create the footer tag after the main tag
        put the text Footer inside the footer tags

### [4. Aside](./article.html)
* Copy the contents of 3-index.html into article.html

    change the <title> to put: Article - Techium
    inside the main tags
        after the text, create the aside tags with text Aside



### [5. Section](./5-index.html)
* Copy the content of 3-index.html into 5-index.html

    inside your <main> section
        remove the text in main, create these sections:
            create first section and put the text Hero section inside
            create second section and put the text Services section inside
            create third section and put the text Works section inside
            create fourth section and put the text About section inside
            create fifth section and put the text Latest news section inside
            create sixth section and put the text Testimonials section inside
            create seventh section and put the text Contact section inside



### [6. Work, News, Testimonial articles](./6-index.html)
* Copy the content of 5-index.html into 6-index.html

Work articles:

    inside the section Works section
        add 3 article tags
            inside each article write Work # where the hashtag will be the ordered number (1, 2, or 3)

News articles:

    inside the section Latest news section
        add 3 article tags
            inside each article write Article # where the hashtag will be the ordered number (1, 2, or 3)

Testimonial articles:

    inside the section Testimonials section
        add 3 article tags
            inside each article write Testimonial # where the hashtag will be the ordered number (1, 2, or 3)



### [7. Navigation](./7-index.html)
* Copy the content of 6-index.html into 7-index.html

    remove the Header text inside the <header>
    create the nav tag inside the header tag
        it should remain empty for now



### [8. Level 1 headings](./8-index.html)
* Copy the content of 7-index.html into 8-index.html

    create the level 1 heading inside your main before your sections
        put text Homepage in your heading tag



### [9. Level 2 headings](./9-index.html)
* Copy the content of 8-index.html into 9-index.html

    in the section tag with the the text Hero section, remove the text and create a level 2 heading with text We help you build your brand!
    in the section tag with the the text Services section, remove the text and create a level 2 heading with text Services
    in the section tag with the the text Works section, remove the text and create a level 2 heading with text Works
    in the section tag with the the text About section, remove the text and create a level 2 heading with text About Us
    in the section tag with the the text Latest news section, remove the text and create a level 2 heading with text Latest news
    in the section tag with the the text Testimonials section, remove the text and create a level 2 heading with text Testimonials
    in the section tag with the the text Contact section, remove the text and create a level 2 heading with text Contact



### [10. Level 3 headings](./10-index.html)
* Copy the content of 9-index.html into 10-index.html

Services headings:

    Inside the section containing the h2 heading Services, add these elements right after the h2:
        create a level 3 heading with text Design & Concept
        create a level 3 heading with text Digital Strategy
        create a level 3 heading with text Content Strategy
        create a level 3 heading with text UX Design
        create a level 3 heading with text Web Development
        create a level 3 heading with text Social Media

Works headings:

    Inside the section containing the h2 heading Works:
        in the first article, replace the text with a level 3 heading with text Interior Design
        in the second article, replace the text with a level 3 heading with text Web Development
        in the third article, replace the text with a level 3 heading with text Personal Brand

About Us headings:

    Inside the section containing the h2 heading About Us, after the h2 heading, create these elements in this order:
        a level 3 heading with text Who are we
        a level 3 heading with text Our culture
        a level 3 heading with text How we work

Latest news headings:

    Inside the section containing the h2 heading Latest news:
        in the first article replace the text with a level 3 heading with text Hoc loco tenere se Triarius non potuit.
        in the second article replace the text with a level 3 heading with text Ut alios omittam, hunc appello, quem ille unum secutus est.
        in the third article replace the text with a level 3 heading with text Bestiarum vero nullum iudicium puto.

### [11. styleguide](./11-styleguide.html)
* Copy the content of 3-index.html into 11-styleguide.html

    change the title to Styleguide - Techium
    remove the text from header, main, and footer
    create a new <section> inside your main tag
        create a header in this section
            in the header add a level 2 heading with text Headings
        after the header:
            add a level 1 heading with text Heading level 1
            add a level 2 heading with text Heading level 2
            add a level 3 heading with text Heading level 3
            add a level 4 heading with text Heading level 4
            add a level 5 heading with text Heading level 5
            add a level 6 heading with text Heading level 6

### [12. Paragraphs](./12-index.html)
* Copy the content of 10-index.html into 12-index.html

About Us paragraphs:

    in the About Us section
        after the first h3 (who are we) create a paragraph with the text: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum, omnis expedita! Eum, praesentium cumque accusantium rem, sit quaerat est nisi ratione, deserunt ducimus quidem iste dicta quibusdam atque maxime cum!
        after the second h3 create a paragraph with the text: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum, omnis expedita! Eum, praesentium cumque accusantium rem, sit quaerat est nisi ratione, deserunt ducimus quidem iste dicta quibusdam atque maxime cum!
        after the third h3 create a paragraph with the text: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum, omnis expedita! Eum, praesentium cumque accusantium rem, sit quaerat est nisi ratione, deserunt ducimus quidem iste dicta quibusdam atque maxime cum!

Latest news paragraphs:

    in the Latest news section
        in the first article
            create a paragraph with text Career before the heading
            create a paragraph with text Lorem ipsum dolor sit amet, consectetur adipiscing elit. Id Sextilius factum negabat. Quo tandem modo? At eum nihili facit; Quae contraria sunt his, malane? after the heading
        in the second article
            create a paragraph with text Digital Life before the heading
            create a paragraph with text Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tum mihi Piso: Quid ergo? Tum ille: Ain tandem? Non autem hoc: igitur ne illud quidem. Sed quod proximum fuit non vidit. Nos commodius agimus. An nisi populari fama? after the heading
        in the third article
            create a paragraph with text Social before the heading
            create a paragraph with text Lorem ipsum dolor sit amet, consectetur adipiscing elit. Non igitur bene. Quid enim est a Chrysippo praetermissum in Stoicis? Pugnant Stoici cum Peripateticis. Prioris generis est docilitas, memoria; Apparet statim, quae sint officia, quae actiones. after the heading

Contact paragraph:

    in the Contact section after the heading
        create a paragraph with the text: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Id Sextilius factum negabat. Quo tandem modo? At eum nihili facit; Quae contraria sunt his, malane?

Additional paragraphs:

    below the level 2 Services heading add a paragraph with text We work with you
    below the level 2 Works heading add a paragraph with text Take a look in our portfolio
    below the level 2 About Us heading add a paragraph with text Everything about us
    below the level 2 Testimonials heading add a paragraph with text We are more than a digital company
    below the level 2 Contact heading add a paragraph with text We like to know new people



### [13. styleguide paragraphs](./13-styleguide.html)
* Copy the contents of 11-styleguide.html into 13-styleguide.html

    After the existing section containing Headings, create a new section in main
        in this section create a header
            Inside the header, create a level 2 heading with text Paragraph
        after the header add a level 2 heading with text Heading with a subtitle
        after the level 2 heading, add a paragraph with text This is my subtitle
        after the last paragraph, add another paragraph with text: Nunc lacinia ante nunc ac lobortis. Interdum adipiscing gravida odio porttitor sem non mi integer non faucibus ornare mi ut ante amet placerat aliquet. Volutpat eu sed ante lacinia sapien lorem accumsan varius montes viverra nibh in adipiscing blandit tempus accumsan.

### [14. Span](./14-index.html)
* Copy the contents of 12-index.html into 14-index.html

In the very first <header>,

    before the nav, create a span with the text Techium

### [15. Div](./15-index.html)
* Copy the contents of 14-index.html into 15-index.html

    Wrap the contents of the header element with a div
    Wrap the contents of all section elements with a div
    Finally, wrap the contents of the <footer> tag with a div


### [16. Structure your sections](./16-index.html)
* Copy the contents of 15-index.html into 16-index.html

    in the div in the Services section
        create a header tag that wraps the h2 and the p
        create a div sibling to the header that wraps the rest of the content
    in the div in the Works section
        create a header tag that wraps the h2 and the p
        create a div sibling to the header that wraps the rest of the content
    in the div in the About Us section
        create a header tag that wraps the h2 and the p
        create a div sibling to the header that wraps the rest of the content
    in the div in the Latest news section
        create a header tag that wraps the h2
        create a div sibling to the header that wraps the rest of the content
    in the div in the Testimonials section
        create a header tag that wraps the h2 and the p
        create a div sibling to the header that wraps the rest of the content
    in the div in the Contact section
        create a header tag that wraps the h2 and the first p
        create a div sibling to the header that wraps the rest of the content

### [17. Comments](./17-index.html)
* Copy the content of 16-index.html into 17-index.html

    before the header add a line break and a comment saying Header to help with scanning your code
    before the main add a line break and a comment saying Main to help with scanning your code
    before the footer add a line break and a comment saying Footer to help with scanning your code
    before the Hero section add a line break and a comment saying Hero section
    before the Services section add a line break and a comment saying Services section
    before the Works section add a line break and a comment saying Works section
    before the About Us section add a line break and a comment saying About Us section
    before the Latest news section add a line break and a comment saying Latest news section
    before the Testimonials section add a line break and a comment saying Testimonials section
    before the Contact section add a line break and a comment saying Contact section



### [18. link your logo](./18-index.html)
* Copy the content of 17-index.html into 18-index.html

    in the header, wrap the span with a link that redirects to the page at the root of your folder (/)
    wrap the link with a div


### [19. Create new pages](./about.html)(./latest_news.html)(./contact.html)
* Copy the content of 18-index.html into about.html, latest_news.html and contact.html

    change the title of about.html to replace Homepage with About
    change the title of latest_news.html to replace Homepage with Latest news
    change the title of contact.html to replace Homepage with Contact

### [20. Add links](./20-index.html)
* Copy the content of 18-index.html into 20-index.html

    in your nav tags
        create a link to / with the text Home
        create an anchor to services with the text Services
        create an anchor to works with the text Works
        create an anchor to about with the text About
        create an anchor to latest_news with the text Latest news
        create an anchor to testimonials with the text Testimonials
        create an anchor to contact with the text Contact

For now, the anchor links will not work. We will make them work in the CSS project.
### [21. Add social media links](./21-index.html)
* Copy the content of 20-index.html into 21-index.html

    in the div in the footer
        remove any text you have
        create a link to https://www.facebook.com/HolbertonSchool/ with the text Facebook
        create a link to https://twitter.com/holbertonschool with the text Twitter
        create a link to https://www.instagram.com/holbertonschool/ with the text Instagram


### [22. "Button" links](./22-index.html)
* Copy the content of 21-index.html into 22-index.html

    in the Hero section, after the heading
        create a link to # with the text Get started
    in the About Us section, after the div containing the level 3 headings and paragraphs
        create a link to about.html with the text Learn more about us
    in the Contact section, after the div containing the paragraph
        create a link to contact.html with text Get in touch


### [23. Services, Works, Latest news links](./23-index.html)
* Copy the content of 22-index.html into 23-index.html

    in the Services section
        in each level 3 heading, create a link to # around the text already in the heading
    in the Works section
        in each level 3 heading, create a link to # around the text already in the heading
    in the Latest news section
        in each level 3 heading, create a link to # around the text already in the heading


### [24. List the links](./24-index.html)
* Copy the content of 23-index.html into 24-index.html

    in the nav
        create an unordered list, put each anchor tag (Home, Services, Works, …) as an individual list item
    in the div in the footer
        create an unordered list and put each anchor tag (Facebook, Twitter, …) as an individual list item


### [25. Secondary navigation menu](./25-index.html)
* Copy the content of 24-index.html into 25-index.html

    inside the footer, after the div
        create a new div
        in the new div create an unordered list with the following links:
            link to # with text Terms of Use
            link to # with text Privacy Policy
            link to # with text Cookie Policy


### [26. Examples of lists for the styleguide ](./26-styleguide.html)
* Copy the content of 13-styleguide.html into 26-styleguide.html

Example of unordered list:

    inside main after Paragraph section, add :
        a new line and a comment with text Lists
        after, create a new section with inside:
            create a header with inside a level 2 heading with the text Lists
            after the new header, create a div with inside:
                a level 3 heading with text Unordered
                    under it, add an unordered list with these items: Dolor pulvinar etiam magna etiam., Sagittis adipiscing lorem eleifend., Felis enim feugiat dolore viverra.

Example of ordered list:

    after previous unordered list, in the same div
        add a level 3 heading with text Ordered
            add an ordered list with these items:
                Dolor pulvinar etiam magna etiam.
                Sagittis adipiscing lorem eleifend.
                Felis enim feugiat dolore viverra.

Example of definition list:

    after previous ordered list, in the same div
        add a heading level 3 with text Definition
        add a definition list with these items:
            Term: Definition List title, Definition: Definition text.
            Term: Startup, Definition: A startup company or startup is a company or temporary organization designed to search for a repeatable and scalable business model.
            Term: Water, Definition: A colorless, transparent, odorless liquid that forms the seas, lakes, rivers, and rain and is the basis of the fluids of living organisms.


### [27. Separate content](./27-index.html)
* Copy the content of 25-index.html into 27-index.html

    in the footer between the two divs:
        add a horizontal rule
        after the horizontal rule add a paragraph with text © 2020 Techium, made with ♥ by students at Holberton School.

### [28. Horizontal rule example](./28-styleguide.html)
* Copy the content of 26-styleguide.html into 28-styleguide.html

    in main after Lists section
        add a new line and a comment with the text Horizontal rule
        create a new section
            create a header and inside it add a level 2 heading with the text Horizontal rule
            after the header create a div and put a horizontal rule in it

### [29. Client quotes](./29-index.html)
* Copy the content of 27-index.html into 29-index.html

    in the Testimonials section
        in the first article
            replace the text with a blockquote with text I am completely blown away. Thanks to Techium, we've just launched our 5th website! and cite author Yuri Y.
        in the second article
            replace the text with a blockquote with text Thank you so much for your help. Techium company is awesome! and cite author Dorrie S.
        in the third article
            replace the text with a blockquote with text I love your system. Definitely worth the investment. I'd be lost without Techium company. and cite author Sven H.

### [30. Examples of quotes](./30-styleguide.html)
* Copy the content of 28-styleguide.html into 30-styleguide.html

Example of inline quote:

    inside main after Horizontal rule section
        add a new line and a comment with text Blockquotes
        create a new section
            in the section create a header, in the header create a level 2 heading with text Blockquotes
            after the header, create a div
                in the div add a level 3 heading with the text Inline quote
                add an inline quote with the text Stay hungry. Stay foolish.

Example of blockquote:

    after the inline quote div, create another div
        in the new div add a level 3 heading with the text Blockquote
        add a multiline quote with the text I will be the leader of a company that ends up being worth billions of dollars, because I got the answers. I understand culture. I am the nucleus. I think that’s a responsibility that I have, to push possibilities, to show people, this is the level that things could be at. and cite Kanye West, Musician

### [31. Address and latest news authors](./31-index.html)
* Copy the content of 29-index.html into 31-index.html

    in the footer
        right after open footer tag, put the following address: 234 Washington Street (line-break) Urbana, Illinois
    in the Latest news section
        in the first article, after the last paragraph, add the author name in small print: By Kelly D.
        in the second article, after the last paragraph, add the author name in small print: By William A.
        in the third article, after the last paragraph, add the author name in small print: By Frances J.

### [32. Typography section - using the correct tags](./32-styleguide.html)
* Copy the content of 30-styleguide.html into 32-styleguide.html

    inside main after the Blockquotes section
        add a new line and a comment with text Typography

        create a new section
            in the section create a header and inside it add a level 2 heading with the text Typography
            after the header create a div, inside the div add this text with the correct HTML tag: 320 Stewart Avenue, Unit 12 (line break) New York City NY 10001, the city, state, and postal code should be on a separate line
            create another div, in the new div nest this code block using the pre HTML tag:

         <code>
             <h2>My title</h2>
             <p>Proin lacus turpis, feugiat sit amet sollicitudin non, volutpat in libero. Aenean hendrerit ultrices nulla ac lobortis. Vestibulum consectetur nibh vel ante rhoncus faucibus.</p>
         </code>

            create another div, in the new div add this paragraph of text with the correct HTML tag: Curabitur sit amet turpis cursus massa mollis highlighted. Duis finibus leo massa, eget dapibus erat finibus sed. Aenean condimentum sapien magna, eleifend highlighted mi consequat ut. Cras nec quam sed sapien ultricies highlighted ut sed metus. Each occurrence of the word highlighted should be highlighted.

---

## Author
* **Mahdi Ben Zouitina** - [mahdibz97](https://github.com/mahdibz97)