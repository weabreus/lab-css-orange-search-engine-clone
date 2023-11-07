![enter image description here](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# LAB | HTML & CSS - Orange Search Engine Clone

In the starter code we have included an index.html file (the website copy has been provided, but not organized into HTML elements), an empty style.css file inside a folder called styles, and an images folder with image assets necessary to complete this lab.

In this lab we will be working from a [Figma file](https://www.figma.com/file/XOlmIULD1NbdfqVgavBIcB/Orange-Search-Engine?node-id=2%3A374).

![enter image description here](https://education-team-2020.s3.eu-west-1.amazonaws.com/uxui/orange-search-engine-1.png)




## Iteration 1: Plan the HTML

It may useful to do some kind of wire-framing, or loose sketch, to help plan the elements  in your html.

Here is an example:

![enter image description here](https://education-team-2020.s3.eu-west-1.amazonaws.com/uxui/whiteboarding-exercise-html-sections.png)
 *(this is just an example, for illustration purposes, and is not necessarily how your html will look)

Here is an example of how to break-down how all of the elements might be contained in the desktop view:

![enter image description here](https://res.cloudinary.com/dt8b5pu9l/image/upload/v1699374430/OrangeSearchContainers_g6ffpn.png)

Think about what HTML elements could be used to contain or represent what is presented in the design.

The HTML elements will be the same for each screen-size, but you can use media-queries to alter the way the elements behave based on screen-size.  (more on that in Iteration 3).

For each screen size (Mobile, Tablet, and Desktop):

1.  Divide the webpage into 3 big blocks: body, header, and footer.
2.  Inside the body, create the different sections: start with the main sections, then move to the smaller parts of the content.
3.  For each section or component, try to find the appropriate HTML tag that is both aligned with your Style Guide and semantical.
4.  If you cannot find a semantical HTML tag for certain UI elements, you can always wrap them into containers with the  `div`  tag.

  

#### Recommended HTML tags

  

Here are some HTML tags that you may want to include in your webpage:

-   **Body:**  the  `<body>`  tag contains all the contents of an HTML document. There can only be one  `<body>`  element in an HTML document.
-   **Navigation:**  the  `<nav>`  tag. This will wrap the logo and the navigation part.
-   **Main Section:**  The  `<main>`  tag specifies the main content of a document.
-   **Main Title:**  one  `<h1>`  tag. This is the main heading of the website. Remember, there should only be one  `<h1>`  in a webpage.
-   **Paragraph:**  You can use  `<p>`  tag for the description of the product.
-   **Lists:**  choose between  `<ol>`  or  `<ul>`  which is the most appropriated to create the navigation menu and to list the features of the product.
-   **Images:**  use a few  `<img>`  tags for logo, icons, photography, and illustration.
-   **Buttons:**  use a combination of <button> and the  `<a>`  tag to create the different call-to-actions.
-   **Footer:**  use the tag to semantically separate the footer content from the rest of the content


## Iteration 2: Define the HTML

Now that you have an idea of how which elements to use, write them into your HTML document.

Using the structure you defined in the first iteration of the project, write the HTML and place the content to structure your webpage.

## Iteration 3: Mobile-First CSS

### 1. Create  `.class`es and  `#ID`s

1.  Assign classes or IDs to the right HTML tags.
2.  Think of how you’re going to assign properties to those elements when you style them with CSS.

### 2. Link the stylesheet

The HTML structure is ready, let’s move on to the CSS.

You should connect your CSS file to your HTML using the `<link>` tag in the `<head>` of your `index.html` document.

### 3. Define the CSS for the Mobile View

Open the  `style.css`  file.  Start placing CSS properties for every class and ID you’ve defined, or other selectors you've chosen. Remember you shouldn’t overwrite properties and all classes and IDs should be useful for your design!

**Remember, we are coding mobile-first.**  All modern browsers have a feature that can render the view of a mobile device.  You can use the mobile toggle in the Dev Tools in your browser to size your internal browser window for a mobile view.  This will allow you to visualize the result of your work for the mobile view.

**CASCADING STYLES**

Remember CSS will read your styles from top to bottom of the file. That means the browser will apply the last style written in the stylesheet for every component/element.


## Iteration 4: Flexbox and Responsive Design

You have learned both media queries and Flexbox. You should try to use and combine them. We advise using Flexbox to create a flexible layout that can adapt to different viewport sizes and media queries when the layout breaks after a certain viewport size.

![enter image description here](https://education-team-2020.s3.eu-west-1.amazonaws.com/uxui/orange-search-engine-4.png)

### Steps

  

-   Use Flexbox to add flexibility to your design
-   Create media queries to add breakpoints for tablet and desktop.

  

#### Bonus

  

-   Plan for the tablet landscape version. It is probably a mix of your mobile and desktop designs! But don’t just jump in the code yet, go back to your Figma file first. In it, you’ll find a frame entitled ‘Tablet Portrait'.  Organize your components, then code this new design in your CSS file.

# Congratulations!

You've now built a responsive, mobile-first, website using media-queries and flexbox!

