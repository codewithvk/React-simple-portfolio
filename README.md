## React Simple Portfolio

![Intro GIF](https://github.com/codewithvk/React-simple-portfolio/blob/master/assets/Intro.gif)

### Set Up

- Clone repo
  <br />
  ```
  git clone https://github.com/codewithvk/React-simple-portfolio.git
  ```
  <!--   <br /> -->
  or you can diretly use as template
  <br />
  ![Intro GIF](https://github.com/codewithvk/React-simple-portfolio/blob/master/assets/template.png)
- Go to Project Directory and install node modules
  ```
  npm install
  ```
- After installing node module ,
  ```
  npm start
  ```
  - You can see website popup on http://localhost:3000/

## Customisation

For user simplicity i had create all centeral file where you can add your info and it will reflect on local/prod.

- ### Experiance
  - In Experiance section you can add your work history, For that you should go `/src/ExData.js`, Where you can modified JSON according to you.
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
- ### Projects
  - In Projects section you can add your Project, For that you should go `/src/projectData.js`, Where you can modified JSON according to you.
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
  - Same thing you can do with skill and main info, For that you can refer file `src/root.link.js ` & `src/SkillData.js`.
  - If you want to add any skill which is not mentioned , then you need to download svg for skill logo, for that you can refer [here](https://github.com/codewithvk/React-simple-portfolio/blob/master/src/SkillData.js#L77)

## Contributor & Credit

- I had use basic template from [Deelip's repo](https://github.com/Deelip7/react-portfolio) , Coustomised it and make thing centralized! <br />
  ```
  Do not Repet your self!
  ```
- Wanna Contribute or doubt , Fill free to drop mail work.vivekjaviya@gmail.com
