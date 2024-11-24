<!--
(c) Janusz Stal
Krakow University of Economics
Department of Informatics
stalj@uek.krakow.pl
-->

# TEXT DOCUMENT FORMATS

## 1. Text File (TXT)

1. A text file is a kind of computer file that is structured as a sequence of lines of electronic text. A text file exists stored as data within a computer file system.

    * On most operating systems, the name text file refers to a file format that allows only plain text content with very little formatting
    
    * Text files can be viewed and edited in simple text editors e..g Windows Notepad

    * Usually a file is regarded as a text file if the suffix of the name of the file (the "filename extension") is .txt, e.g. ideas.txt 

    Now, run Windows Notepad (or other basic text editor for the operating system you are using) and create a text file named WorkHealthily.txt containing the content below. To create a file, do not use Visual Studio Code.

    ```
    To work healthily at the computer, it's essential to follow some basic ergonomic principles and maintain good habits to prevent strain and injury. Here are three important rules:
    
    Maintain Proper Posture
    Sit with your back straight and shoulders relaxed. Your feet should be flat on the floor or on a footrest, and your knees should be at a 90-degree angle.
    Keep the monitor at eye level, about an arm's length away, to avoid straining your neck and eyes.
    Use a chair with good lumbar support to maintain the natural curve of your spine, and position your elbows at a 90-degree angle when typing or using a mouse.

    Take Regular Breaks
    Follow the 20-20-20 rule: Every 20 minutes, look at something 20 feet away for at least 20 seconds to reduce eye strain.
    Stand up, stretch, or walk around for a few minutes every hour to improve circulation and relieve muscle tension.
    Incorporate micro-breaks (30 seconds to 1 minute) to shake out your hands, roll your shoulders, or stretch your neck and wrists.

    Optimize Your Workspace
    Ensure your workspace is well-lit, with light coming from the side or behind the screen to reduce glare.
    Adjust your screen's brightness and contrast to a comfortable level and consider using blue light filters or glasses to reduce eye strain.
    Keep frequently used items, like a mouse and keyboard, within easy reach to prevent overreaching or straining your arms and shoulders.

    By following these rules, you can minimize the risk of repetitive strain injuries, eye strain, and other health issues associated with prolonged computer use.
    ```

1. Hiding file name extensions is an operating system feature that prevents the user from seeing file extensions (such as .txt, .jpg, .exe) in file names in the file explorer window. This feature is enabled by default in many systems, like Windows, to simplify the appearance of file names for less advanced users. However, disabling this feature can be helpful for better identifying file types.

    Check in Windows Explorer how the name of the file "WorkHealthily.txt" you created earlier is displayed. If only the file name is displayed, i.e. "WorkHealthily", change the operating system settings to display the file name and its extension, i.e. "WorkHealthily.txt". Search the Internet for information on how to make this change. 

1. International character encoding in text files is the process of representing text in a way that allows it to be displayed and handled correctly on different computer systems and platforms, regardless of language or alphabet. This is crucial for maintaining compatibility between different systems and applications, especially in the context of handling multilingual documents.

    Complete the following tasks

    1. In Windows Notepad, create a text file with the following content. Save the file as budget.txt and set the encoding to UTF-8.

    1. Check in your web browser whether the budget.txt file content is displayed correctly. To open the budget.txt file in your web browser, use the shortcut Ctrl+O.

    ```
    Here is a list of the five largest Polish cities by population and their indicative budgets for 2024:

    Warszawa - ok. 1,8 mln mieszkańców. Budżet Warszawy na 2024 rok wynosi około 22,3 miliarda PLN.
    Kraków - ok. 800 tys. mieszkańców. Roczny budżet to około 7,3 miliarda PLN.
    Łódź - ok. 670 tys. mieszkańców. Budżet na 2024 rok wynosi około 5 miliardów PLN.
    Wrocław - ok. 640 tys. mieszkańców. Budżet wynosi około 6 miliardów PLN.
    Poznań - ok. 530 tys. mieszkańców. Budżet na 2024 rok to około 4,8 miliarda PLN.
    ```

## 2. Comma-Separated Values (CSV)

1. CSV is a common data exchange format that is widely supported by consumer, business, and scientific applications. CSV is a text file format that uses commas to separate values, and newlines to separate records.

    * A CSV file stores data (numbers and text) in plain text, where each line of the file typically represents one data record.
    
    * Each record consists of the same number of fields, and these are separated by commas in the CSV file.
    
    * If the field delimiter itself may appear within a field, fields can be surrounded with quotation marks.

    The following CSV file consists of a header row containing column titles and ten data records. Notice that all data in the rows is separated by a comma. Save the data to a file named employees.csv.


    ```csv
    Name,Age,City,Email
    John Doe,28,New York,johndoe@example.com
    Jane Smith,34,Los Angeles,janesmith@example.com
    Michael Johnson,45,Chicago,michaelj@example.com
    Emily Davis,30,Houston,emilydavis@example.com
    David Wilson,25,Miami,davidwilson@example.com
    Sarah Miller,29,Seattle,sarahmiller@example.com
    James Brown,38,Boston,jamesbrown@example.com
    Jessica Garcia,31,San Francisco,jessicagarcia@example.com
    Daniel Martinez,42,Denver,danielmartinez@example.com
    Laura Hernandez,27,Atlanta,laurah@example.com
    ```

1. The coursesA.csv and coursesB.csv files contain information about the courses at the university. Create a courses.csv file that contains information about all the courses (combine the data from the coursesA.csv and coursesB.csv files).

1. Based on the data in the table, create a CSV file called cars.csv. 

    * Add an extra line to the file with information about your favorite car

    * Open the cars.csv file in Microsoft Excel


    | Make       | Model       | Year | Price (USD) |
    |------------|-------------|------|-------------|
    | Toyota     | Corolla     | 2021 | 20,000      |
    | Honda      | Civic       | 2020 | 22,500      |
    | Ford       | Focus       | 2019 | 18,000      |
    | Tesla      | Model 3     | 2022 | 35,000      |
    | Volkswagen | Golf        | 2021 | 25,000      |

1. The file students.csv contains student data. Unfortunately, the file is incorrect. Repair the file, fixing all errors. Then, find any service on the Internet that allows you to check if the CSV file is correct/valid. Check if the file students.csv is valid. Finally, open the CSV file in Microsoft Excel.

## 3. Extensible Markup Language (XML)

1. An XML file is a plain text file that uses a specific structure to store data in a format that is both human-readable and machine-readable. XML is a flexible, versatile markup language that allows users to define their own custom tags to describe data in a structured way. Instead of separating data with commas, the data is contained between tags. XML is commonly used to exchange data between different systems.

    * XML prolog (first line)
    * XML element
    * XML attribute

    Familiarize yourself with the basic syntax of an XML document. Notice how to create:
    
    * XML prolog
    * element
    * attribute
    * comment
    
    You can find more information at the following address, in the sections: XML Syntax, XML Elements and XML Attributes.

    <https://www.w3schools.com/xml/xml_syntax.asp>

1. The following XML document contains data about two geometric figures. Save the data to a file named figures.xml. Then, add to the file the data about the three-dimensional geometric figure of your choice. Remember to format your XML document correctly. Use line indents.

    ```xml
    <?xml version="1.0" encoding="UTF-8"?>
    <geometricFigures>
        <figure>
            <name>Circle</name>
            <type>2D</type>
            <properties>
                <property>Radius</property>
                <property>Diameter</property>
            </properties>
            <formulas>
                <area>π * radius^2</area>
                <perimeter>2 * π * radius</perimeter>
            </formulas>
        </figure>
        <figure>
            <name>Square</name>
            <type>2D</type>
            <properties>
                <property>Side Length</property>
            </properties>
            <formulas>
                <area>side^2</area>
                <perimeter>4 * side</perimeter>
            </formulas>
        </figure>
    </geometricFigures>
    ```

1. Each email contains at least information about the sender, recipient, subject and message body. Create an email.xml document that contains the data of one email. 

1. Some elements can contain additional information contained in attributes, which are placed in the opening tag of the element. Attributes are additional information describing the element, they are optional, they may or may not be present.

    ```xml
    <student id="343666" semester="2">Anna May</student>
    ```

    The smartphones.xml file contains data describing smartphones. As you probably noticed, some elements contain additional attributes. Add a description of your smartphone in the file, if you have one ;-) Use exactly the same data structure as for the smartphone that is already in the file. Use elements and attributes. Remember to format the XML file.


1. Create a transport.xml document containing information about the three means of transport you use. To describe a single means of transport, use at least 4 elements and two attributes.


1. The XML document can only be used if it is valid. To check if the XML document is valid, you can use e.g. a web browser. If the XML document is valid, the browser will display its content. If the document is invalid, the content will not be displayed, only error messages. To open an XML document in a web browser, use the Ctrl+O shortcut.

    Check if the documents you created earlier are valid. If any of the files are not valid, remove errors and reopen it in your web browser.

    * figures.xml
    * email.xml
    * smartphones.xml
    * transport.xml

1. The creatures.xml file contains data in XML format. Unfortunately, the file contains many errors. Remove all errors and display the file content in a web browser to ensure that the XML file is valid.

## 4. JavaScript Object Notation (JSON)

1. JSON is an open standard file format and data interchange format that uses human-readable text to store and transmit data consisting of key–value pairs. It is a commonly used data format with diverse uses in electronic data interchange, including that of web applications with servers. JSON is a language-independent data format. It was derived from JavaScript. JSON filenames use the extension .json.

    Note that unlike CSV or XML formats, the data contained in a JSON document can be of different types, e.g. string, number, or boolean.

    The following JSON document contains data about any laptop. Save the data to the laptop.json file. Then add three more key-value pairs describing the laptop. Use different data types.

    ```json
    {
    "brand": "Dell",
    "model": "Inspiron 15",
    "year": 2023,
    "isTouchscreen": false,
    "devices": ["touchpad","webcam"]
    }
    ```

1. The clothes.json file contains data about selected clothing companies. Complete the data with two more clothing companies. Find the information on the Internet. Remember to format the data.

1. Create a trainticket.json file containing train ticket data. Find any train ticket on the Internet and try to transfer the key data from the ticket to the json file. Use at least six key-value pairs to describe the ticket. Use various data types.

1. The planets.json file contains data in JSON format. Unfortunately, the file contains many errors. First, remove all errors. Then, check if the file is valid. Then, search the Internet for an online JSON validator and use it to check if the planets.json file is valid.

