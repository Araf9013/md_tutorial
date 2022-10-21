<h1 align="center">The Noble Quran</h1>

<p align="center">
    The official source code repository for Quran.com
    <br />

[Join Quran.com community »](www.google.com)

[VisitiQuran.com](quran.com)- 
  [Report Bugs*](bugs.com)- 
  [Request Feature*](feeature.com)- 
  [Storybook](Storybook.com)

### How to contribute

We trust thast you will not copy this idea/project, this is at the end for the sake of Allah and we all have goof intentions while working with this project . But we must stress that copying the code/ project is unacceptable.

### Running the app locally

- Ensure you have the latest `nodejs` and `npm` installed. Prefer 10+. 
- Ensure you have `yarn` installed. Simply `npm i -g yarn`.
- Clone this repo.
- Run `yarn` on the repo to install `node_modules`.
- Run `yarn dev` to start the app. If you wish to run on a different port, run `yarn dev -p 8000`
- open `localhost;3000`
The app runs on next.js and will automatically hot  reload when you make changes.

### Environment variables
If you have the access to Quran.com associated vercel account , run `vercel env pull`. Otherwise, rename the `env.example` filke `env.local` and you should be good to go.

### DLS( design language system)
One mistake we made previously is treated each component as unique. This made our work not scalable . Secondly, when looking at large companies, they often devvelop a desiogn style language that can be used across the app without the nedd to create unique components and ensure better c onsistency across the product. We are trying to take the similar approach. If somnething can be used elewhere, please put it inside the `dls/` directory and create stories for it.

### Storybook.js
Our components are build within Storybook.js . See files with the name `.stories.tsx` . This helps engineers view their work outside the product, making it super easy to test different cofigurations of the components.
[Wer also display the components here.](Google.com)

### Recommended Extensions
Check `.vscode/extensions.json` for the recommended VSCode Extensions.

### Typescript
We chose typescript to help out n, please look at issues on the Github repo. This a place to start.

### Filing Bugs
Thank you for taking time to file a bug! We'd appreciate your help on fixing it 🙏. Please [Open an Issue](Google.com).

### Community
[Join Quran.com Discord community »](Google.com)

### Credits
- Localization was made possible by the help of [Lokalise](Lokalise.com) which is computer-aided translation system that fopcuses on productivity and quality assurance nad provides a seamless localization workflow.

![Lokalise](https://user-images.githubusercontent.com/15169499/139687128-15ed6189-6be2-44bf-9173-75cce317d546.png)

- Deployment was made posiible by the help [Vercel](Vercel.com) whoch is deployment and collaboration platform for fronted developers whioch puts fronted develpoer first, giving them the3 comprehensive tools to build high-performance websites asnd application.

![Powered by Vercel](https://user-images.githubusercontent.com/15169499/147745340-b7e84819-d1b0-4399-87a0-d5276ba21bca.png)
