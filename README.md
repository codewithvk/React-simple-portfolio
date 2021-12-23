
# React Simple Portfolio

![Intro GIF](https://github.com/codewithvk/React-simple-portfolio/blob/master/assets/Intro.gif)

## Getting started

1. Clone the repo 
    `git clone https://github.com/codewithvk/React-simple-portfolio.git`
    or use the template by clicking on "Use this template"
    
![Intro GIF](https://github.com/codewithvk/React-simple-portfolio/blob/master/assets/template.png)

2. Go into the project directory and install the node modules by running
	 `npm install`

3. After successfully installing all the node modules run
  `npm start`
  
 You should be able to see the website running in a new tab on http://localhost:3000/

## Customisation

For user simplicity I created a central file where you can add your info which will be reflected on local/prod.

### Experience
  - In the Experience section you can add your work history. For that, you should go to `/src/ExData.js`, where you can modify the JSON according to you.
  ```
  const workHistory = [
    {
      companyName : '..',
      role: '..',
      duration: "...",
      workDes: [
          '....',
          '...',
          '..'
        ],
      exposer: [..] ,
      link: '..',
   },
  ]
  ```

### Projects
  - In the Projects section you can add your Project. For that, you should go to `/src/projectData.js`, where you can modify the JSON according to you.
  ```
  const projects = [
     {
         title: '...',
         image: '..',
         description: "...",
         tools: ["..",".."],
         github: '...',
         link: '..',
      },
  ]
  ```
  
The same customisations can be implemented in the skills and main sections. For that you can refer to the file `src/root.link.js` and  `src/SkillData.js`.
 
If you would like to add any skill which is not mentioned, then you will need to download a svg for  the skill logo, for that you can refer [here](https://github.com/codewithvk/React-simple-portfolio/blob/master/src/SkillData.js#L77).


