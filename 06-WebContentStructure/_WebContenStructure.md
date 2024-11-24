<!--
(c) Janusz Stal
Krakow University of Economics
Department of Informatics
stalj@uek.krakow.pl
-->

# WEB CONTENT STRUCTURE

## 1. Introduction to HTML

1. HTML (HyperText Markup Language) is the standard markup language used to create web pages. It is used to structure and format the content on a page so that web browsers can display it correctly. HTML is not a programming language, but a markup language, meaning that it defines the elements of a page (e.g., headings, paragraphs, images, links) using tags.

    Pay attention to the structure of the followind HTML document. Looks familiar? The description of data in HTML is very similar to XML.
    
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Hello World</title>
    </head>
    <body>
        <h1>Hello World!</h1>
        <p>This is my first HTML document.</p>
    </body>
    </html>
    ```
    
    In simple terms, an HTML document contains an \<html\> element, which in turn contains two elements \<head\> and \<body\>:

    ```html
    <html>
        <head>
            <!-- head definitions go here -->
        </head>
        <body>
            <!-- the content goes here -->
        </body>
    </html>
    ```
    
1. Learn the details of HTML document structure in the tutorial available at:

    <https://www.w3schools.com/html/html_intro.asp>

    According to the tutorial:

    * \<!DOCTYPE html\> declaration defines that this document is an HTML5 document  
    * \<html\> element is the root element of an HTML page
    * The \<head\> element contains meta information about the HTML page  
    * \<meta charset ...\> element definines the way of writing/encoding international characters
    * \<metda name="viewport" ...\> element is used to correctly display a website on various devices, such as laptops, tablets, or smartphones
    * \<title\> element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)  
    * \<body\> element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.  
    * \<h1\> element defines a large heading  
    * \<p\> element defines a paragraph  
    * \<!-- --\> element contains user's comment which is not displayed in a web browser

1. In VSCode, open the hello.html document. Add the following paragraph to the end of the \<body\> element:

    ```
    I already know the basic structure of an HTML document.
    ```

1. It is very important to format the HTML document correctly, which is supported by VSCode. To format the document, right-click on the document content and select Format Document from the menu. 

1. Open the hello.html document in your web browser.

## 2. Complete HTML Document Content

1. The space.html document contains information about space exploration. Dosplay the document in your web browser. As you can see, it is divided into three sections.

1. The HTML document is incomplete. Complete the document so that it consists of the following five sections:

    ```
    Why Do We Explore Space?
    Milestones in Space Travel
    The Role of Private Companies
    Human Missions to Mars
    The Future of Space Exploration
    ```

    And here are the two missing sections:

    ```
    Milestones in Space Travel

    The history of space travel is filled with remarkable milestones
    that have shaped our understanding of the cosmos. The first artificial
    satellite, Sputnik 1, was launched by the Soviet Union in 1957,
    marking the beginning of the space age. This event triggered
    the space race between the United States and the Soviet Union,
    which culminated in the Apollo 11 mission in 1969. During this mission,
    Neil Armstrong became the first human to set foot on the Moon,
    a moment that remains iconic to this day.
    
    As space exploration progressed, so did our technological capabilities.
    The development of reusable rockets by companies like SpaceX has
    revolutionized the space industry, making missions more cost-effective
    and sustainable. This breakthrough has opened up new possibilities
    for future exploration, including manned missions to Mars and beyond.
    It is an exciting time for space travel, as advancements in technology
    continue to push the boundaries of what is possible.

    Another significant milestone was the construction of the International
    Space Station (ISS), which has been continuously inhabited by astronauts
    from various countries since the year 2000. The ISS serves as a research
    laboratory in space, where experiments are conducted in microgravity
    to advance our knowledge in fields like biology, physics, and medicine.
    The collaboration between countries on this project demonstrates
    how space exploration can unite people across borders.

    The Future of Space Exploration

    The future of space exploration is filled with possibilities.
    With the rapid advancement of technology, missions to the Moon, Mars,
    and beyond are becoming more feasible. International cooperation
    will play a crucial role in achieving these ambitious goals. Space
    agencies and private companies from around the world are working together
    to push the boundaries of human knowledge and capability.

    Advances in robotics, artificial intelligence, and propulsion systems
    will be critical in overcoming the challenges of long-duration space
    travel. New propulsion technologies, such as ion engines or nuclear
    propulsion, could drastically reduce travel time to distant planets.
    Additionally, the use of AI in space exploration could help us explore
    areas that are too dangerous or remote for humans to reach, such as
    the icy moons of Jupiter or Saturn.

    Ultimately, the future of space exploration will shape humanity's destiny.
    By continuing to explore space, we will not only learn more about
    the universe but also develop new technologies that could transform life
    on Earth. The dream of exploring the stars is one of humanity's oldest
    aspirations, and with the right dedication and collaboration, it is
    a dream that may soon come true.
    ```

1. Display the completed HTML document in your web browser.

## 3. Create HTML Document from Scratch

1. In VSCode, create an AI.html file.

1. In the html file add the structure of the HTML document. You can copy it from the hello.html file for example. However, VSCode supports creating HTML documents. In the document, enter ! (exclamation mark) and then the Tab key. The structure of the HTML document will be added to your file.

1. Add the following information regarding artificial intelligence to your document. Apply the following elements: \<title\>, \<h1\>, \<h2\>, \<p\>.

    ```
    ARTIFICIAL INTELLIGENCE

    AI Definition

    Artificial Intelligence (AI) refers to the development
    of computer systems that can perform tasks typically
    requiring human intelligence. These tasks include
    problem-solving, understanding natural language,
    recognizing patterns, and making decisions.
    
    AI is a broad field that encompasses various subfields
    and techniques, such as machine learning, natural
    language processing, robotics, and computer vision.

    Examples of AI in Daily Life

    AI is used as voice assistants. Siri, Google Assistant,
    and Alexa use AI to understand and respond to voice
    commands. Platforms like Netflix and Amazon use AI to
    recommend products or shows based on your previous
    interactions. AI enables self-driving cars to navigate
    roads and make driving decisions.

    The Future of AI

    AI continues to grow and impact various fields such as
    healthcare, education, finance, and manufacturing.
    However, ethical considerations, such as job
    displacement, privacy concerns, and AI safety, are also
    key topics of discussion. The development of AI is
    likely to reshape many industries and aspects of daily
    life in the years to come.

    ```

1. Format the HTML document.

1. Display AI.html in a web browser.

## 4. Insert Resource Link

1. The presentation of content on the Internet is done using the idea of ​​hypertext. It is a method of organizing and presenting information that allows different elements of text to be connected by means of links, allowing the user to navigate between related content in a flexible way. It is the basic technology used on the World Wide Web, where users can click on links in a web browser to go to other pages or resources.

    Read the tutorial on how to insert a link to another document or resource in an HTML document.

    <https://www.w3schools.com/html/html_links.asp>

1. In the document AI.html, add links in the text below. Links should point to Wikipedia entries.

    * Artificial Intelligence (AI)
    * natural language processing
    * Siri

1. Format the HTML document.

1. Display AI.html in a web browser. Check that links are working properly.

## 5. Group Items into Lists

1. To improve the readability of your document, you can use numbered and unnumbered lists to group a set of related items.

    Read the tutorial on how to use numbered and unnumbered lists.

    <https://www.w3schools.com/html/html_lists.asp>

    <https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol>

    <https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul>

1. In the AI.html document, add the following section. Place it before the Examples of AI in Daily Life section. Number the five key koncepts.

    ```
    Key Concepts in AI

    In relation to artificial intelligence,
    the following key concepts can be distinguished:

    Machine Learning (ML): A subset of AI
    that allows systems to learn from data and improve
    over time without being explicitly programmed.
    Examples include recommendation systems (like
    Netflix or YouTube) and fraud detection.

    Natural Language Processing (NLP): A branch of AI
    focused on enabling machines to understand, interpret,
    and generate human language. Applications include voice
    assistants like Siri or Alexa, chatbots, and language
    translation systems.

    Computer Vision: Enables machines to interpret
    and make decisions based on visual data from the world,
    such as images and videos. It's widely used in facial
    recognition, self-driving cars, and medical imaging.

    Robotics: AI powers robots, giving them the ability
    to perform tasks autonomously, often in environments
    that are too dangerous or complex for humans.

    Expert Systems: AI-based systems designed to mimic
    human expertise in specific domains, such as medical
    diagnosis or financial decision-making.
    ```

1. Format the HTML document.

1. Display AI.html in a web browser.

## 6. Add Images

1. Multimedia elements (images, photos, video, audio) can improve the design and the appearance of a web page and definitely make the communication of information more attractive.

    Read the tutorial on how to insert an image to an HTML document. Please note that you can add an image whose file you have in your resources or you can add an image that is located on the Internet on any server/website.

    <https://www.w3schools.com/html/html_images.asp>

1. On the Internet, find an image (jpg, png, svg, gif, ...) of an AI. Download the image and save it in the folder where the AI.html file is located. Then, place the image in the HTML document, between the first and second paragraph of the AI ​​Definition section.

1. On the Internet, find an image of the Amazon Alexa voice assistant. Place an image below the paragraph that mentions Alexa. Insert the image to the HTML document directly from the Internet, do not download it to your computer.

1. Format the HTML document.

1. Display AI.html in a web browser.

## 7. Create Table

1. Use the tutorial below to learn how to arrange data into rows and columns.

    <https://www.w3schools.com/html/html_tables.asp>

    In summary, to create a table you need to use the \<table\> tag. Each row of the table is described using the \<tr\> (table row) tag. Data in the table cells is contained in the \<td\> (table data) tag. An example structure of tables consisting of two rows and three columns looks like this:

    ```html
    <table>
        <tr>
            <td></td><td></td><td></td>
        </tr>
        <tr>
            <td></td><td></td><td></td>
        </tr>
    </table>
    ```

1. Display the countries.html in a web brower. The HTML document contains data in a table. First, complete the data in the document by adding information about two more countries. Then, display the document in a web browser again.

1. Complete the AI.html document. Add the following paragraph at the end of the section Examples of AI in Daily Life. After the paragraph, add a table. The data for the table is given below, in CSV format.

    ```
    The data in the table shows four main areas of AI application:
    natural language processing, computer vision, machine learning,
    and reinforcement learning. Each area is related to a specific application,
    such as chatbots, medical image analysis systems, or autonomous vehicles.
    These applications have a significant impact on various sectors,
    improving the efficiency of customer service, medical diagnostics,
    protection against financial fraud, and the development of modern
    technologies such as self-driving cars.

    Field,Application,Example,Impact
    Natural Language Processing,Chatbots,ChatGPT,Improves customer service efficiency
    Computer Vision,Healthcare,Medical Imaging,Enhances diagnostic accuracy
    Machine Learning,Finance,Fraud Detection,Reduces financial losses
    Reinforcement Learning,Robotics,Autonomous Vehicles,Enables self-driving technology
    ```

## 8. Design a Form

1. Forms are used for user input. Learn how to create forms using the tutorial:

    <https://www.w3schools.com/html/html_forms.asp>

    Basically, form elements (fields) are placed in the <form> element. HTML provides different types of elements that can be used, depending on the type of data being entered (text, numbers, list, date, ...). It is also possible to use buttons, e.g. to quickly confirm entered data.

    ```html
    <form>
        <input type="text">
        <input type="number">
        ...
        ...
        <button type="button">Ok</button>
    </form>
    ```    

1. The file patient.html contains the patient data form. Display the HTML document in your web browser.

1. Modify the patient data form patient.html by completing it with the data below. Then, display the modified form.

    * Date of birth (use date field)
    * Place of birth (use text field)
    * Ilnesses (use four checkboxes)
    * Notes (use textarea)

1. At the end of the AI.html document, add a new section:

    ```
    Survey

    Here is a survey about your knowledge
    of issues related to artificial
    intelligence. The survey is anonymous.
    Please fill out the survey. The survey
    results will be helpful in examining
    the degree of use of artificial
    intelligence in different age groups.
    ```

1. Create a file survey.html with the form for entering data. The form should contain the following fields:

    * Age (use number field)
    * Gender (use radio buttons)
    * How often do you use ChatGPT (use select element with answers: never, rarely, occasionally, often, constantly)
    * Describe shortly your benefits from using AI (use textarea)

1. In the Survey section, in the "fill out the survey" text, add a link to the survey.html document.

1. Display AI.html in a web browser. Then, click on the link to fill out the form.

## 9. Fix HTML Document

1. The document oceans.html contains many errors. Despite this, try to display the document in a web browser. Note that a web browser always tries to display the document, even if it contains errors. This is different from using XML documents, which cannot be processed if they contain errors.

1. Fix the HTML document:

    * remove all errors in the HTML syntax
    * complete the image oceans.jpg (download it from the Internet)
    * replace the link with a correct one, pointing to information on the Internet about plastic in oceans

1. Format the corrected HTML document.

1. Display the oceans.html document in your web browser.

## 10. Design and Share a Website

1. Design a website that provides information about healthy lifestyle. To do the website, create a new git repository named 'healthy-lifestyle' in which create index.html for your website. The website should include:

    * Headings that define health categories, such as nutrition, exercise, or sleep.
    * Paragraphs containing short descriptions about healthy habits.
    * Three images illustrating healthy habits (download from the Internet and save two of these images to your repository, then place them on the website you are creating; place the third image on the website you are creating directly from the Internet)
    * Links to articles about health, diet, and exercise.
    * Text in the form of a list with advice on diet and exercise.
    * Table with training plan or daily calorie intake.
    * Form to sign up for the health tips newsletter.

1. Upload your local 'healthy-lifestyle' repository content to a remote repository on GitHub.

1. Share the website you created using GitHub Pages.

    GitHub Pages is a free service offered by GitHub that allows users to create and host websites directly from their GitHub repositories. It's especially useful for hosting project websites, blogs, technical documentation, or even personal websites.

    To configure GitHub Pages, go to the repository’s settings, find the "Pages" section, select the branch (main or master), and save the settings.

    > Hint: more information on how to create personal or project website you can find at:
    
    * <https://youtu.be/OltY8JIaP-4?si=lXUIeiN-d6JO6jmJ>

    * <https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site>

1. Display the web page in your web browser.

    Your website will be available at:
    
    * **username.github.io/repository-name** (for a project website)
    * **username.github.io** (for your personal website)

    Share the link among you colleagues to access your website.

    > Note: It can take up to 10 minutes for changes to your site to publish after you push the changes to GitHub.