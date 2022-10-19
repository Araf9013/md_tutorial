# The Noble Quran


The official source code repository for Quran.com

![Join Quran.com community >>](www.google.com)

![VisitiQuran.com*](quran.com)![Report Bugs*](bugs.com)![Request Feature*](feeature.com)![Storybook](Storybook.com)

###How to contribute

We trust thast you will not copy this idea/project, this is at the end for the sake of Allah and we all have goof intentions while working with this project . But we must stress that copying the code/ project is unacceptable.

### Running the app locally

- Ensure you have the latest 'nodejs' and 'npm' installed. Prefer 10+. 
- Ensure you have 'yarn' installed. Simply 'npm i -g yarn'.
- Clone this repo.
- Run 'yarn' on the repo to install 'node_modules'.
- Run 'yarn dev' to start the app. If you wish to run on a different port, run 'yarn dev -p 8000
- open 'localhost;3000
The app runs on next.js and will automatically hot  reload when you make changes.

### Environment variables
If you have the access to Quran.com associated vercel account , run 'vercel env pull'. Otherwise, rename the 'env.example' filke 'env.local' and you should be good to go.

### DLS( design language system)
One mistake we made previously is treated each component as unique. This made our work not scalable . Secondly, when looking at large companies, they often devvelop a desiogn style language that can be used across the app without the nedd to create unique components and ensure better c onsistency across the product. We are trying to take the similar approach. If somnething can be used elewhere, please put it inside the 'dls/' directory and create stories for it.

### Storybook.js
Our components are build within Storybook.js . See files with the name 
