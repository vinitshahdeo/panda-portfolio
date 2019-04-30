![Panda-portfolio Logo](https://raw.githubusercontent.com/YashMeh/portfolio-panda/master/logoPanda.png)<br>
[![npm](https://img.shields.io/badge/npm-6.8.0-brightgreen.svg)](https://www.npmjs.com/package/panda-portfolio) ![node](https://img.shields.io/badge/node-11.8.0-brightgreen.svg) ![npm](https://img.shields.io/npm/dw/panda-portfolio.svg)
## panda-portfolio
No more worries while making single page github portfolio websites.
### Installation
```javascript
sudo npm install -g panda-portfolio
```
### Running
```javascript
panda <filename>.json
```
### How to do it
- Create a JSON file with whatever name you want for example 'data.json'.
- Copy and paste the following 
```javascript
{
    "theme":"(dark or light)",  
    "name":"YOUR-NAME",
    "profilePhoto":"PICTURE-LINK",
    "resumeLink":"RESUME-LINK",
    "about":[
        "Paragraph1",
        "Paragraph2",
        "Paragraph3",
        "So on.."
    ],
    "links":{
        "github":"YOUR-GITHUB-PROFILE",
        "linkedin":"YOUR-LINKEDIN-PROFILE",
        "medium":"YOUR-MEDIUM-PROFILE",
        "facebook":"YOUR-FACEBOOK-PROFILE",
        "instagram":"YOUR-INSTAGRAM-PROFILE"
    }
}
```
- Run the below command
```javascript
panda data.json
```
- Get your single page portfolio as index.html.
- Publish on github.

### Demo
[![asciicast](https://asciinema.org/a/DqlkYR2ofzrpN5gesljAHjcjq.svg)](https://asciinema.org/a/DqlkYR2ofzrpN5gesljAHjcjq)

### Example
| Theme        | Picture           |
| ------------- |:-------------:|
| light      |   ![light](https://raw.githubusercontent.com/YashMeh/portfolio-panda/master/light.png)
| dark      | ![dark](https://raw.githubusercontent.com/YashMeh/portfolio-panda/master/dark.png)      |
