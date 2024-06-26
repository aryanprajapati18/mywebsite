# Understanding how to create a Website using HTML and CSS

# Let’s understand about the History of html and CSS

## The History of HTML

- **HTML was created by Tim Berners-Lee in 1990s while working at CERN (European Organization for Nuclear Research).**
- **In 1991 First HTML version was released, which contained 18 elements, including 
basic tags like `<a>`, `<p>`, `<h1>`, and `<img>`.**
- **In 1997 HTML 3.2 and HTML 4.0 was released. HTML 3.2 and HTML 4.01 brought improvements, including support for tables, scripts, and styles. HTML 4.01, in particular, laid a strong foundation for modern web development.**
- **In 2014 HTML 5 was released it was the most significant update, became a standard. In this update semantic elements e.g., ‘<article>’,’<section>’ and multimedia support e.g., ‘<audio>’, ‘<video>’ and APIs, pushing the web into the realm of complex applications were introduced**

## The History of CSS

- **CSS (Cascading Style Sheets) was proposed by Håkon Wium Lie while working with Tim Berners-Lee at CERN in 1994.**
- **Its first version CSS1 was released by W3C (World Wide Web Consortium) that allowed developers  to separate content from presentation. This was a game-changer, enabling consistent styling across web pages. Later on its new version got developed and released with improvements and new features in every successive version.**
- **The latest version is W3.CSS 4.15 which was released in December 2020.**

# What is HTML?

- HTML stands for[Hypertext Markup Language] which is used to create webpages. It provides the structure of a website by using elements and tags.
- HTML 5 is the current version of the html.
- Websites like Facebook, Twitter, YouTube, Instagram, Amazon, Google, Wikipedia, and almost every other website you visit on the web are built using HTML.
- HTML is not a programming language it is a markup language i.e. it will tell a web browser how to display content (structure a web page) not how to perform a specific task.

## What is CSS?

- CSS stands for[Cascading style sheets] which is used to control presentation, formatting, and layout of webpages

**Types of CSS**

- Inline:-An inline CSS is used to apply a unique style to a single HTML element.
- Internal:-An internal CSS is used to define a style for a single HTML page.
- External:-An external style sheet is used to define the style for many HTML pages. It is written in separate file saved with '.css'extension.And further linked with the html file. To link two files "<link rel="stylesheet" href="header.css"> element is used.

## What is JavaScript?

- **JavaScript** is a scripting language. It handles all the logical (moving) parts of a web page.

## The major languages for creating a website


![image1](https://github.com/aryanprajapati18/mywebsite/assets/172613612/e0a0a08a-6a5b-4619-9cb6-932cb0a88e6c)

# Understanding with example about HTML and CSS

![image2](https://github.com/aryanprajapati18/mywebsite/assets/172613612/fffa0666-8e58-42d5-ad79-55c95b7c2c17)




## Common elements that are used for creating a website

- Heading
- Paragraph
- Document Section
- Block, inline and
- Page Layout
- Image
- List
- Links
- Body
- Sections

# Structure of a HTML page

```html
<!DOCTYPE html>
<html>
<head>
<title>Welcome</title>
</head>
<body>
<h1>Get startedx</h1>
</body>
</html>
```

### Explanation of above syntax

 **`<html>`** element is the root element of an HTML page. You will declare an HTML document using this tag.

**`<head>`** contains meta-information about the HTML page.

**`<title>`** whatever you will write inside this element will be treated as the title of your HTML page. And will be displayed as the title on the tab of a web browser.

**`<body>`** whatever you will do inside this element will be rendered by the browser and will be visible to the user. You will write most of your HTML code inside this element.

## What is tag?

A tag is a special type of text that is used to create elements and structure a web page. Tags are the fundamental building blocks of HTML. Each tag generally consists of an opening tag and a closing tag, with content in between.

![image3](https://github.com/aryanprajapati18/mywebsite/assets/172613612/270c359a-e544-4fd1-9980-bc43d2502745)


Example:-

```html
<h6>
Hey this is an example of a tag
</h6>
```

# Backbone elements that are needed to create a webpage

- `<html>`: The root element that wraps all other elements.
- `<head>`: Contains meta-information about the document, such as its title and links to CSS files.
- `<body>`: Holds the content of the document, including text, images, links, and other media.
- `<h1>` to `<h6>`: Header tags, used to define headings.
- `<p>`: Paragraph tag, used to define blocks of text.
- `<a>`: Anchor tag, used to create hyperlinks.
- `<img>`: Image tag, used to embed images.
- `<div>`: Division tag, used to group content and apply CSS styles.

# The software tools to build a website are:

1. Code Editor (i.e. Notepad++, eclipse, atom, etc.)
2. Understanding of Basic HTML
3. Understanding of Basic CSS

# Case sensitivity

### HTML is not a case-sensitive language we can write it as per our wish.  We can use either **lowercase** or **uppercase** or even **mix case.**

## How to save an html document?

- You can save the HTML document by ‘.html’ extension.

# **We can link any CSS file with html file using link element**

 ** `<link rel="stylesheet" href="path to your file">`**

# **Anatomy of Styling Rules (Syntax)**

### While styling any content Classes will always begin with `.`, and Ids will always begin with `#`. Elements will begin with neither and just have the element name. After the name of the selector, we will use braces (“{}”) to hold our rules to that one selector.

# What is id and class?

**`*Id`s:** are titles that can only appear on a single element. For example your driver’s license number. ONLY you have that one number.*

**`*Class`es:** on the other hand can apply to multiple elements. For example a classroom. Usually, you aren’t the only person in a class, although you might be. The class is big enough for lots of people.*

# CSS box model

![image4](https://github.com/aryanprajapati18/mywebsite/assets/172613612/19f64e0d-7e36-4416-b3a8-5150dc3ee659)


- **Content box:** It is the space where the content of the HTML element appears, such as images, text, and more.
- **Padding:** It is the transparent area around the content of the element.
    
    ![Capture7](https://github.com/aryanprajapati18/mywebsite/assets/172613612/276d6802-be4f-4757-820e-fdcdfad61f74)

    
- **Border:** It is the box surrounding the padding box. By default, the value of the border for every HTML element is zero; however, increasing the border value increases the space between the padding and the margin box. Border will set a border around your element. You can determine the size, color, and style of the border. It will be set up in this order: width, style, color
    
    ![Capture8](https://github.com/aryanprajapati18/mywebsite/assets/172613612/187366d9-27f7-4aad-b608-f498b244129b)

    
- **Margin:** It is the transparent area outside the border box.
    
    ![Capture9](https://github.com/aryanprajapati18/mywebsite/assets/172613612/cafb8852-b6dc-47cd-9637-67f3111b43f7)

    
    # Creating a about us page for a website
    
   ![image5](https://github.com/aryanprajapati18/mywebsite/assets/172613612/d67e6480-52f9-4303-b34b-5decc72ce892)

    
    ### Steps to create following about us page:
    
    1. Create a division with class as about us i.e.
    
    ```html
     <div class="about-us">
    ```
    
    1. Create another division for writing text with class name as text and write the contents 
    
    ```html
     <div class="text">
                <h1><strong>Few Words About US</strong></h1><br> 
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Hic corporis optio modi, nulla, ullam quia numquam enim, est iusto nam vel a veritatis sapiente assumenda commodi iste. Incidunt, sunt inventore.</p>
            </div>
    ```
    
    1. Create another division for storing image  
    
    ```html
     <div class="image">
                <img src="https://img.freepik.com/free-vector/teamwork-concept-landing-page_52683-20165.jpg?size=626&ext=jpg&ga=GA1.1.1558447040.1717062635&semt=ais_user" height="400px" width="100px" alt="Please wait for a while">
            </div>
    ```
    
    ### Now let’s design with CSS
    
    ```css
    .about-us{
        width: 100%;
        float: left;
        background-color: floralwhite;
    }
    .text{
        margin-top: 20px;
        width: 50%;
        float: left;
    }
    .image{
        margin-top: 25px;
        width: 50%;
        float: left;
    }
    ```
    
    # Embedding a map in website
    
    ### To embed a map in our website <iframe> tag is used
    
    ```html
     <div class="map">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3673.4399857067633!2d72.61209187436594!3d22.97084271825851!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x395e8f54c957c849%3A0x78ef1181c6762ceb!2sDipika%20Mobile%20Service!5e0!3m2!1sen!2sin!4v1717063477892!5m2!1sen!2sin" width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        </div>
    ```
    
    # Facts section of a website
    
  ![image6](https://github.com/aryanprajapati18/mywebsite/assets/172613612/5dd70896-02f0-4aa9-bb38-0bac5cebcee6)

    
    ## Let’s understand with html code how this facts section is created
    
    ```html
    <section class="facts-section">
            <h2 class="facts-title">FACTS</h2>
            <p class="facts-description">Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque.</p>
            <div class="facts-container">
              <div class="fact">
                <span class="fact-number">0</span>
                <span class="fact-label">Clients</span>
              </div>
             
    ```
    
    ## CSS code for designing facts section
    
    ```css
    .facts-section {
        text-align: center;
        padding: 50px 20px;
        background-color: #f9f9f9;
    }
      
    .facts-title {
        font-size: 36px;
        font-weight: bold;
        margin-bottom: 10px;
      }
     .facts-description {
        font-size: 16px;
        color: #777;
        margin-bottom: 40px;
      }
    ```
