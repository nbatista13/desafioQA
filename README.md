2. 1. # Automated Tests - Serasa :man_technologist:
   
      This automation project was created using Selenium WebDriver with Java and Junit, and it’s important to mention that its entire structure follows the Page Object pattern.
   
      The test suite includes three validations:
   
      - ***Validate registration attempt with invalid data***
      - ***Validate login on the Serasa page***
      - ***Validate access to the Score History in the Financial Health tab***
   
      #### **Project Presentation Materials:**
   
      1. ***Video 1 - Explanation of the testing strategy and presentation of the written tests***
   
         https://youtu.be/-CUJeqW2gcQ
   
      2. ***Video 2 - Presentation of the created Automation and explanation of its construction***
   
         https://youtu.be/XrzzRSoPlvQ
   
      3. ***Spreadsheet with the written tests:***
   
         https://drive.google.com/file/d/1OsRbwcb_WYcWEhIViziYQTJx4kP9NTEL/view?usp=sharing
   
      #### **Below is what you need to run the project:**
   
      1. IDE: Eclipse
         1. https://www.eclipse.org/downloads/
      2. Selenium WebDriver
      3. JAVA and its system variable declarations
         1. https://openjdk.java.net/projects/jdk/15/
         2. https://www.java.com/en/download/help/path.html
   
      #### **Directory adjustments in some project pages and the CSV**
   
      Below I will list some necessary adjustments regarding directories and the CSV file.
   
      **Pages - Changes**
   
      1. ***Web Page*** - In the ***createChrome*** method, change the browser driver directory to where your browser driver is located.
      2. ***InformacoesUsuarioTest Page*** - In the ***directory*** variable, change it to the directory where you want the evidence to be saved.
   
      **CSV - InformacoesUsuarioTest.csv - Changes**
   
      1. **testValidaLogin**
   
          \- in INSERT CPF, INSERT PASSWORD, INSERT FULL NAME OF THE USER
   
         1. INSERT CPF - Enter a valid CPF with an active registration to log in.
         2. INSERT PASSWORD - Enter a valid password to log in.
         3. INSERT FULL NAME OF THE USER - Enter the full name displayed after clicking on the user’s initials when logged in.
   
      2. **testHistorico**
   
          \- in INSERT CPF, INSERT PASSWORD
   
         1. INSERT CPF - Enter a valid CPF with an active registration to log in.
         2. INSERT PASSWORD - Enter a valid password to log in.

