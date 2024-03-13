Files : images/pic-about-01.jpg, images/pic-work-01.jpg, images/pic-work-02.jpg, images/pic-work-03.jpg, images/pic-article-01.jpg, images/pic-article-02.jpg, images/pic-article-03.jpg, images/pic-person-01.jpg, images/pic-person-02.jpg, images/pic-person-03.jpg
- The description of the project contains some inspiration for the final look of the project but we’ll have to download some images.
- Head to unsplash and download 10 high resolution images that look as close to the final product that you’re going to make. You will be using these same high res images for a project on Responsive Design in the future. Remember to also include the 3 images (the 2 logos and the favicon) linked in the description of the project.
- The images should all be representative of category they belong to. Images in the work category should be closely related to work.

styles/1-style.css - When scrolling is triggered on the html element itself, we’d like the behavior of the scroll to be as fluid as possible.

styles/3-style.css - Based on styles/2-style.css:
    • Target the root element and define the following custom properties:
        -color-primary set to #d73953
        -color-black set to #090909
        -color-white set to #ffffff
        -color-light-grey set to #f3f3f3
        -color-dark-grey set to #353535
        -text-color set to color-black
    • Revisit the section-tagline and card-category declarations and reset their color to color-primary
    • Revisit the body and anchor declarations and reset their color to text-color
Does not have to pass w3c

styles/4-style.css - Based on styles/3-style.css:
    • Targeting the root element, create 2 custom font-family properties font-family-base and font-family-title with the same list of fonts:
        -set the first choice font as Helvetica Neue
        -set the second choice font as Helvetica
        -set the third choice font as Arial
        -set the last choice font as sans-serif
    • Set body‘s font-family to font-family-base
    • Create a new declaration targeting all 6 levels of heading tags
        -set its font-family to font-family-title
Does not need to pass W3C

styles/5-style.css - Based on styles/4-style.css:
    • Targeting the root selector, create the following custom properties:
        -font-size-small set to 1.2rem
        -font-size-medium set to 1.6rem
        -font-size-large set to 1.8rem
        -font-size-x-large set to 2.3rem
        -font-size-xx-large set to 4.8rem
    • All fonts in the html element should be at 62.5% of their normal size
    • Any fonts in the body should have their sizes set to font-size-medium
Does not need to pass W3C

styles/6-style.css - Based on styles/5-style.css
    • Targeting the root element, create the following custom properties:
        -font-weight-regular set to 400
        -font-weight-bold set to 700
    • Set the boldness of fonts in the body to font-weight-regular
    • Set the boldness of fonts in the headings to font-weight-bold
Does not need to pass W3C

styles/7-style.css - Based on styles/6-style.css:
    • Add Open Sans as the first choice font for font-family-base, with the previous fonts shifted down accordingly
    • Add Raleway as the first choice font for font-family-title, with the previous fonts shifted down accordingly
Does not need to pass w3c