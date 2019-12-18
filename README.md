# Boilerplate code for HTML, CSS, JS

* This is a custom made boilerplate HTML template code I use for projects for static webpages. Includes normalize.css file which targets common elements accross browsers to render all elements more consistently more in line with modern standards. Includes grid.css file which is a custom modified file from Responsive Grid System (http://www.responsivegridsystem.com/) that provides a responsive grid.

## Notes

* Also resets all default CSS behaviors using the following CSS rule and sets all CSS elements to use box-sizing: border-box. 
` 
    \* {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    } 
`

* Also uses CSS rule below to create a generic 'row' container
` 
    .row {
        width: 1140px;
        margin: 0 auto;
    }
`

## Folder Structure

The file structure looks like this:
```
    public/
        css/styles.css -> custom CSS
        js/
        vendors/css/normalize.css -> third party CSS/Icons
        index.html
    firebase/
```