0-index.html - Create your first HTML file 0-index.html with:
    • Add the doctype on the first line (without any comment)
    • After the doctype, open and close a html tag
    • Add the language tag, specify English for ISO language code and add the direction tag (ltr or rtl) on the html tag.
    • Open your file in your browser (the page should be blank)

1-index.html - Copy the content of 0-index.html into 1-index.html
Create the head and body sections
    • inside the html tag, create the head and body tags (empty) in this order
    (W3C won’t pass - you can ignore it)

2-index.html - Copy the content of 1-index.html into 2-index.html
Meta charset:
    • add a meta tag inside the head:
        - add the charset attribute with the value utf-8
Viewport:
    • add a meta tag inside the head:
        - add an attribute name on the tag and specify that it is the meta viewport
        - add the key width with the value device-width
        - add the key initial-scale with the value 1.0
        - add the key viewport-fit with the value cover
Title:
    • add the title tag just after the meta viewport with value: Homepage - Techium
Description:
    • add a meta tag inside the head section
        - add an attribute name on the tag and specify that is the meta description
        - add another attribute called content
        - add the following description: Techium is a digital agency
Favicons:
    • download the image above to use as a favicon
    • Use the tool at https://realfavicongenerator.net/ to generate all the favicon formats
    • take the favicon.ico and favicon.png and place these at the root of your project directory, so that it is siblings with your [0-9]+-index.html files.
    • inside the head, create 2 link tags with these 3 attributes: rel, type, and href.
        - the first link tag:
            - rel: icon
            - type: image/x-icon
            - href: ./favicon.ico
        -the second link tag:
            - rel: icon
            - type: image/png
            - href: ./favicon.png

3-index.html - Copy the content of 2-index.html into 3-index.html
Header:
    • create the header of your page between the open and close body tag
    • put the text Header inside the header
Main:
    • create the main tag after the header tag
        - put the text Main content inside your main tags
Footer:
    • create the footer tag after the main tag
        - put the text Footer inside the footer tags

5-index.html - Copy the content of 3-index.html into 5-index.html
    • inside your <main> section
        - remove the text in main, create these sections:
            1.create first section and put the text Hero section inside
            2.create second section and put the text Services section inside
            3.create third section and put the text Works section inside
            4.create fourth section and put the text About section inside
            5.create fifth section and put the text Latest news section inside
            6.create sixth section and put the text Testimonials section inside
            7.create seventh section and put the text Contact section inside
Does not need to pass W3C