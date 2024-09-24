# odin-recipes
In this project, I am going to build a basic recipe website, and it will consist of a main index page that will have links to a few recipes.

## On the **index page**, it contains:

1. ### Usual HTML boilerplate 

    - #### The DOCTYPE: 
        
        `<!DOCTYPE html>`
        
        > Let the browser know what version of HTML it should use to render the document. (this version is HTML5)
         

    - #### HTML element: 
        
        `<html lang="en"></html>`
        
        > Root element, the ancestor of all element in this document.

        - ##### lang attribute:        
            
            > Specifies the language of the text content in that element.

    - #### Head element: 
        
        `<head></head>`
        
        > Where we put important meta-information about webpages, always under `<html>` tag.

        - ##### Meta element: 
            
            `<meta charset="UTF-8">`

            > We should always include in the `<head>` element.

            - ###### charset attribute:
                
                > Setting the encoding ensures that the webpage will display special symbol and characters from different language correctly in the browser.

        - ##### Title element:
            
            `<title>` Title `</title>` 
            
            > Give webpages a human-readable title, display in the browser's tab, we should always include in the <head> element, otherwise it would show the file name.

    - #### Body element:
        
        `<body>` contents `</body>`

        > Include all the content that will be shown on the webpage.

2. ### Heading element: 
    
    `<h1>` to `<h6>`
    
    > Displayed larger and bolder than other text to signify that they are headings.

3. ### Unordered lists: 

    `<ul></ul>` includes multiple `<li>` item name `</li>`
    
    > Use it when the order of lists doesn't matter.

4. ### Anchor elements: 

    `<a href="destination">` click on this text to link to `</a>`
    
    > By default, without the href attribute, it just looks like plain text, so we need to tell the anchor tag where we want to link to.

    - #### href(hypertext reference) attribute


## On the **recipe pages**, it contains other elements:

1. ### Paragraph element: 
    
    `<p>` text content `</p>`
    
    > Use it when you need several paragraphs; otherwise, it will compress them into a single space.

2. ### Image element: 
    
    `<img src="destination" width="number" height="number">`
    
    - #### src(source) attribute:
        
        > Tell the browser where the image file is located, like the href attribute for anchor tags.
    
    - #### alt(alternative text) attribute:
        
        > Used to describe an image; if the image cannot be loaded, it will be displayed. Also used by screen readers to describe what is visible to visually impaired users.

    - #### Image size attributes: width and height
        
        > It's not strictly necessary, but it's a good habit to include these attributes on every image.

3. ### Ordered lists:
    
    `<ol></ol>` includes multiple `<li>` item name `</li>`
    
    > Use this when the order of the lists is important.