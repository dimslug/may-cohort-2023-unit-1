# Terminal Notes
- `pwd` print working directory
- `ls` list the files in the currect directory
- `mkdir` make a new directory
- `cd` & `cd..` change directory
- `rm -r` removes directory (recursive)
- `touch` create file within a directory
- `help` provides list of commands
- `cp` copy file
- `clear` clears terminal
- `mv` move a file

# How the Web Works

- Browsers
    - Chrome, Firefox, Edge, Safari, Brave etc
    - Client (client-side)
- `HTTP Request` : Hyper Text Transfer Protocol
    - Locating a file on the web
    - GET request
- `URL`
    -Uniform Resource Locator
![](assets/url.png)
    - Scheme
        - `HTTP` - basic
        - `HTTPS` - secure
    -Domain
        - Which server to point towards
    - Port
        - Any gates that may need to be accessed
        - typically part of the stardard HTTP protocol
    - Path to File
        - Locating the exact HTML Document
    - Any parameter that may seem necessary
    - and sometimes targeting specific points of the site


# Intro To HTML
- HTML : Hyper Text Markdown Language
    - Framework of our web page
    - Uses elements or tags to this

 **Elements**
 - `structural tags` : define the layout
 - `style tags` : define how it appears

 # Casing
  - **Camel Case** hereIsAnExample
  - **Pascal Case** hereIsAnExample
  - **Kebob Case** here-is-an-exmaple 
  - **Sake Case**here_is_an_example

  # Intro to CSS
  **Cascading Style Sheets**

  ## Box Model
- Content
    - Our information such as text or images / etc.
- Padding
    - Space around our content **withing** the border
- Border
    - Frame
- Margin
    - Space outside of the margin

` content + padding + border + margin = total element size `

content 100px x 100px
padding 10px all around
border 5px thick all around
margin of 10px all around

## Elements
```css
/* 
    Building Blocks

    selector {
        [ DECLARATION BLOCK]
        property: value;
    }
*/

nav {
    background-color: #d2d2d2;
    overflow: hidden;
};
```
## Order of Specificity
1. `!Important`
2. `Inline CSS`
3. `ID Selectors`
4. `Class Selectors`
5. `Element Selectors`

## Operators
**Compound Operators**
 - `>` refers to direct children of an element
 - `,` matching selector
 - `+` immediate sibling of an element
 - `~` subsequesnt sibling of an element

 ## Psuedo-Class Selector
 ```css
  /*
  selector:actopm {
    property: value
  }
  */
  a:hover {
    color: lightblue;
}
```
# VS Code Trick
- `CTRL + D`
    - select mutliple lines that are similar
- `CTRL+/`
    - Comments
- `SHIFT+ALT+DOWN`
    - copy line below current line
- `CTRL+ ~` opens terminal in vs code

# CSS Layout
## Inline
    - on the same line as other elements
    - width of its content

# Block
- set to a new line
- complete width of that line

## Position
- Relative
    - "relative" to the overall HTML document
- Absolute
- Fixed
- Static
