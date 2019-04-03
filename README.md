# Logo TEDAM
Logo TEDAM is an open source test management and automation software. TEDAM can be used to create test cases, test sets and store test data. Test sets can be assigned to clients running TEDAM Agent software. Test execution results are stored on the TEDAM Server. 

![tedamschemaeng](https://user-images.githubusercontent.com/44693634/48532853-1db52180-e8b3-11e8-8f12-45e7e858379c.png)

## Demo Video
[![Watch the demo](https://img.youtube.com/vi/eczwqyTae0A/maxresdefault.jpg)](https://youtu.be/eczwqyTae0A)

## Try It
On a Linux box with docker and docker-compose execute the following:<br>

 wget https://github.com/logobs/tedam-docker/blob/master/docker-compose.yml<br>
 mkdir tedamdata <br>
 docker-compose up -d <br>

tedamdata folder will hold the mysql data files.<br>

Browse http://yourserver.name.here:8888/TEDAMFaceV2<br>

Use the following credentials:<br>
User Name: admin<br>
Password: 2018tedaM<br>

![image](https://user-images.githubusercontent.com/11722394/55487415-b8ca5000-5636-11e9-99c3-5d394d2a490f.png)

## Technology
The following technologies are used in the project:

- Java 
- SpringBoot
- Hibernate
- Vaadin
- Websockets
- Chrome Extension
- Beanshell scripts (http://www.beanshell.org/)
- Selenium (https://www.seleniumhq.org/)

## What is so special about TEDAM?
TEDAM brings a new perspective to test automation:
- It organizes all UI interactions under action items and couples them with test data
- Its flexible architecture can be extended to support new action items
- It can support many scripting languages and frameworks
- It uses test steps and data as metadata/pseudo code to generate actual test script at runtime

## Who can use TEDAM?
TEDAM is used by Logo Business Solutions for test automation of its own software products. Originally it was created for test automation of [J-Platform](http://www.logo.com.tr/en/solutions/erp-solutions/j-platform) which is a full-fledged ERP solution using Java Web Start technology. Later it evolved to support HTML based web applications too. TEDAM currently supports only automated test execution. 

## User Guides
- [Installation](https://github.com/logobs/tedam/wiki/Installation)
- [How to use Tedam Face?](https://github.com/logobs/tedam-face)

# Project Guidelines
Read the related wiki pages to learn about:
- [Project Governance Model](https://github.com/logobs/tedam/wiki/Project-Governance-Model)
- [How to Become a Contributor](https://github.com/logobs/tedam/wiki/How-to-Become-a-Contributor)

