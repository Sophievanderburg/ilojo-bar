# Ilojo Bar
<img width="200" alt="Screenshot 2022-06-23 at 13 43 24" src="https://user-images.githubusercontent.com/70900763/175290940-e4c28ef1-fd7b-4638-b2da-e1a6bd833ad3.png"> <img width="200" alt="Screenshot 2022-06-23 at 13 53 03" src="https://user-images.githubusercontent.com/70900763/175292442-ab9354b8-695c-40f6-a2bd-4270daaafd4b.png"> <img width="200" alt="Screenshot 2022-06-23 at 13 53 14" src="https://user-images.githubusercontent.com/70900763/175292468-020e6d07-eac2-4d3d-8f31-df6c16864acc.png"> <img width="190" alt="Screenshot 2022-06-23 at 13 52 16" src="https://user-images.githubusercontent.com/70900763/175292344-a49df2b2-8b16-4ff5-8a69-0d35dc1bcba5.png">


<img width="2000" alt="Screenshot 2022-06-23 at 13 50 30" src="https://user-images.githubusercontent.com/70900763/175292064-d842399c-8445-47cf-9c97-8c453645908d.png">

## About the project
### The problem
Ilojo Bar or Casa do Fernandez was an iconic national monument in Lagos, Nigeria, which was illegally demolished in 2016. Ilojo Bar was designed and built by Africans returning from slavery in Brazil in the 1800s. Legacy would like an English-language website that becomes a virtual monument of this special building and the many stories surrounding it.

> User stories
> 1. Read, listen and watch stories about Ilojo Bar
> As a resident of Lagos, Nigerian, member of the Nigerian diaspora or interested world citizen, I want to be able to read, listen and see stories about  Ilojo Bar online so that I can learn more about the significance of the building for the metropolis of Lagos and of the cosmopolitan history of it, leading > from Spain to Brazil to Nigeria.
>
> 2. Add stories about Ilojo Bar
> As an artist/visitor I want to be able to add a story about Ilojo Bar to the website, so that I can convey and complement the meaning of the building.
> 
> 3. Experience Ilojo Bar
> As a resident of Lagos, Nigerian, member of the diaspora or interested citizen of the world, I want to be able to get a virtual impression of the building so that I can see what it once was like. 


## Prototype
### Interaction
**Home**
❗
**View the paintings**
❗
**Read the stories**
❗
**Send a story**
❗


## Practical information
### Prismic
We use Prismic as a headless CMS. A headless CMS is a content management system (CMS), only used for back-end purposes, built from the ground up to make content accessible and maintainable. Prismic is supported for lots of frameworks as Next.js & Vue.js, but is also be used with an express server or even just vanilla javascript. In our case, we use it in combination with an express server.

We use Prismic to retrieve the stories and images from. The images are linked to the stories. This is the structure of all the stories:<br>
<img width="25%" alt="Schermafbeelding 2022-06-21 om 10 22 38" src="https://user-images.githubusercontent.com/70577898/174752624-5f87c7b2-fe26-4337-a1e7-78454f60feec.png">


For more information how to use Prismic click [here](https://prismic.io/docs/technologies/express-overview_)

### Activity diagram
❗
### Used packages
- [EJS](https://www.npmjs.com/package/ejs)
- [express](https://www.npmjs.com/package/express)
- [dotenv](https://www.npmjs.com/package/dotenv)
- [body-parser](https://www.npmjs.com/package/body-parser)
- [nodemailer](https://www.npmjs.com/package/nodemailer)
- [@prismicio/client](npmjs.com/package/@prismicio/client)
- [@prismicio/helpers](https://www.npmjs.com/package/@prismicio/helpers)
- [node-dev](https://www.npmjs.com/package/node-dev)
- [multer](https://www.npmjs.com/package/multer)

## How to install/use the code
Install and use this repo in a view simple steps:
1. Clone this repo with git clone ``https://github.com/Sophievanderburg/ilojo-bar.git``
2. Install all the used packages with ``npm install``
3. Start the server with ``npm run dev``
4. Open http://localhost:2020/ in your favourite browser
Good luck! 🍀



