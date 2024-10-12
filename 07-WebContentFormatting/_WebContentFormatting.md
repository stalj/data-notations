<!--
(c) Janusz Stal
Krakow University of Economics
Department of Informatics
stalj@uek.krakow.pl
-->

# WEB CONTENT FORMATTING

## 1. CSS Basics

1. CSS (Cascading Style Sheets) is used to style and design websites, controlling the layout, colors, fonts, and overall appearance of HTML elements. With CSS you define rules that specify how HTML elements should be displayed. Each rule consists of:

    * Selector: indicate HTML element or elements you want to style.
    * Declaration: specifies what style should be applied to the indicated elements. It consists of a property and a value. Declarations are placed inside the curly braces {}.

    Open the facts.html document. Take a look at the content of the \<body\> element, which is displayed in a web browser window and can be formatted. As you can see, it contains \<h1\>, \<h2\>, and \<p\> elements.
 
    And here is the cascading style sheet that specifies how to display text contained in \<h1\> and \<p\> elements:

    ```css
    h1 {
        color: blue;
        font-size: 28px;
    }

    p {
        color: gray;
    }
    ```

    Familiarize yourself with more detailed information on CSS syntax, available in the tutorial:

    <https://www.w3schools.com/Css/css_syntax.asp>

1. To format the content of an HTML document, you need to add a cascading style sheet to the HTML document. There are three methods available:

    * External
    * Internal
    * Inline

    Check out the tutorial on how to use these methods:

    <https://www.w3schools.com/Css/css_howto.asp>

    Then, create three copies of the document facts.html named:

    * facts-external.html
    * facts-internal.html
    * facts-inline.html

    Apply the cascading style sheet from the previous task to each of them. Finally, display all three HTML documents in a web browser.

1. The HTML document transport.html discusses key innovations in future transportation, such as autonomous vehicles, electric aircraft, hyperloop systems, and smart infrastructure. The document content is formatted using internal CSS. Change the CSS formatting to external. Make sure the HTML document is displayed and formatted correctly.

## 2. CSS Box Model

1. The CSS Box Model describes how elements are structured and displayed on a web page. Every HTML element is seen as a box, and the box model consists of several layers that define the space an element takes up. These layers are arranged in the following order from the inside to the outside:

    ![CSS Box Model](https://alvaromontoro.com/images/blog/the-css-box-model-0.png)


    * Content: The actual content of the element, such as text, images, or other elements.
    * Padding: The space between the content and the border. Padding is transparent and adds space inside the element.
    * Border: A line around the element that separates the padding from the margin. It can have various styles, colors, and widths.
    * Margin: The space outside the border that separates the element from other elements. The margin is also transparent.

    Open the document boxmodel.html. Notice how the \<h1\> and \<p\> elements are styled. Then open the HTML document in a web browser.

1. See the tutorial for details on manipulating the Box Model:

    <https://www.w3schools.com/Css/css_boxmodel.asp#:~:text=In%20CSS%2C%20the%20term%20%22box%20model%22%20is%20used,It%20consists%20of%3A%20content%2C%20padding%2C%20borders%20and%20margins.>

1. Complete the landmarks.html document. Add styling to h2 elements and unordered list. Use at least three CSS declarations for each element (e.g. color, margin, border).

## 3. Styling links

1. Links contained in an HTML document can be styled in a simple way, just like other text in the document. In addition, links can be styled differently depending on their state (univisited and visited link, when the mouse is over a link or link is in the moment of clicking).

    See a brief explanation, with examples, on how to style links:

    <https://www.w3schools.com/csS/css_link.asp>

1. The HTML document components.html concerns the key components of a computer and contains brief descriptions of each component along with links to the corresponding Wikipedia articles. Make the following changes to the document:

    * add styling to links depending on their state; apply different font and background colors
    * change document styling from internal to external

## 4. Styling Tables

1. The courses.html file represents a list of courses for students studying computer science. Open the file and familiarize yourself with the table structure. How many rows and columns does the table have? Then analyze how the table elements (rows, columns, column headers, and the entire table) are styled using CSS.

1. Familiarize yourself with the basic table styling options available in the tutorial:

    <https://www.w3schools.com/csS/css_table.asp>

1. The krakow.html document contain a table on the topic of historical landmarks in Krakow. The table is not yet styled. Style the table as follows. Save styling to a CSS file.

    * Change the background color of the table header: Use the background-color property to set a background color for the table header (<th> cells), for example, dark green to give the table a more distinguished look.

    * Add padding to table cells: Use the padding property to add internal margins inside the cells (both <td> and <th>) to make the content more readable and properly spaced.

    * Add a border to the table: Use the border and border-collapse properties to set a uniform border around table cells. You can specify the border thickness and style, such as solid or dashed.

    * Set the width of table columns: Use the width property to control the width of each column in the table. For example, set the "Landmark" column to 25% and the "Significance" column to 40%.

    * Change text color and add hover effect: Use the color property to change the text color and the :hover pseudo-class to add a hover effect that changes the background color when a user hovers over a table row.

## 5. Styling Forms

1. The spacetravel.html file contains a space travel booking form. First, open the form in your web browser. As you can see, the form is not styled. Notice the types of form fields that have been used. Next, open the HTML document in an editor and see how the form has been made. Next, remove the highlighted comment lines to add styling and display the form in your web browser.

1. Learn the basics of form styling, available in the tutorial:

    <https://www.w3schools.com/csS/css_form.asp>

1. The family.html document contains a form for entering family information. The form is not styled, and it includes six different types of input fields. Add styling for this form in an external CSS file as follows:

    * Add space between form fields: Use the margin-bottom property to add space between each form element. This will make the form look more organized and easier to read.

    * Change the font: Use the font-family property to change the font used in the form to a more modern or readable font, such as Arial or Verdana.

    * Style the submit button: Use the background-color and color properties to change the background color of the submit button and the text color. Make it stand out by giving it a different style.

    * Add a border to input fields: Use the border property to give the text fields (input, select, textarea) a simple border, making them more defined.

    * Change the width of the form fields: Use the width property to make the form fields wider (e.g., width: 100%), so that they stretch across the available space and are easier to fill out.

## 6. Responsive Web Design

1. Responsive Web Design (RWD) is an approach to web design that allows the appearance of a page to be automatically adjusted to the screen size of the device on which it is displayed. This makes the page look good and easy to use on both large computer monitors and small smartphone or tablet screens.

    There are many methods and tools available for designing responsive websites. One of them is Flexbox (Flexible Box Layout), a  powerful tool in CSS, that allows you to create flexible and responsive web layouts. With flexbox, you can easily manage the arrangement of elements inside a container.

    Open the sample HTML document flexbox.html, which uses flexbox styling. Notice the "row" class, which acts as a flex container for the box elements. The @media causes the elements in the container to be arranged vertically for screens with a width smaller than the specified value.

1. Learn the basics of using flexbox in the tutorial:

    <https://www.w3schools.com/csS/css3_flexbox.asp>

    Pay attention to how the container is created, what the properties of the container elements are, and how flexbox allows you to create responsive content.

1. Utwórz stronę internetową
    responsywną
    zastosuj flexbox
    css zewnętrzny

## 7. Styling complex HTML document

1. The wonders.html document content refers to topic of "The Wonders of the Natural World." It contains three sections, each with two paragraphs, three Wikipedia links, two tables, and one form. The document is not styled yet.

    Add styling to this document in an external CSS file as follows:

    * Set the font and text alignment for the document: Use font-family to set a consistent font across the entire document and text-align to center the main heading.

    * Add background colors to the section titles: Use background-color to add a soft background color to the \<h2\> elements, making them stand out.

    * Style the tables: Add padding and borders to the table cells (\<td\> and \<th\>) using padding and border properties to make the table content more readable and visually appealing.

    * Change the width of the form inputs: Use the width property to make the form input fields (\<input\>, \<textarea\>, and \<select\>) take up more horizontal space.

    * Add padding and margin to form elements: Apply padding to the input fields and margin-bottom to add space between the form sections.

    * Style the submit button: Change the background-color, color, and border-radius of the submit button to make it look more attractive. Add a hover effect with the :hover pseudo-class.

    * Style the links: Use the color and text-decoration properties to change the appearance of the links. For example, remove underlining and change the color to blue or green.

    * Add borders to images or sections: If you include images, use border or box-shadow to give them more definition. Otherwise, add borders around sections like the tables to separate them visually.

    * Add spacing between the sections: Use margin-top or margin-bottom to create visual space between different sections of the text.

    * Change the text color for different sections: Use color to set different text colors for each section of the document, such as dark green for the Grand Canyon, blue for the Great Barrier Reef, and gray for Mount Everest.

