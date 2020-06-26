# ApiTestingSoapUI
Run Soap UI (free version) tests through MAVEN and generate HTML report
==================================================================================

# SOAP UI - MAVEN integration

  1. Create a project in Soap UI (free version)
  
  2. Generate a pom.xml file (please refer pom.xml file)
      - For more granularity in tests and other configurations refer https://www.soapui.org/test-automation/maven/maven-2-x/
      
==================================================================================

# Steps to run tests through Command Prompt

  1. Launch Command Prompt
  2. Go to the path of your project where pom.xml file is present
  3. run 'mvn clean surefire-report:report' command to generate surefire-report.html report in outputFolder (can be configured in pom.xml)
  
===================================================================================

# Steps to run tests through Jenkins

  1. Please follow above steps (Steps to run tests through Command Prompt) and create a .bat file
  2. Then build your project in Jenkins using "Execute Windows Batch Command"
  3. Give the path of .bat file in Command textbox of "Execute Windows Batch Command" section.
  

 
