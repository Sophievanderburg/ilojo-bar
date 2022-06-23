# :church: Ilojo Bar
<img width="200" alt="Screenshot 2022-06-23 at 13 43 24" src="https://user-images.githubusercontent.com/70900763/175290940-e4c28ef1-fd7b-4638-b2da-e1a6bd833ad3.png"> <img width="200" alt="Screenshot 2022-06-23 at 13 53 03" src="https://user-images.githubusercontent.com/70900763/175292442-ab9354b8-695c-40f6-a2bd-4270daaafd4b.png"> <img width="190" alt="Screenshot 2022-06-23 at 13 52 16" src="https://user-images.githubusercontent.com/70900763/175292344-a49df2b2-8b16-4ff5-8a69-0d35dc1bcba5.png">


<img width="2000" alt="Screenshot 2022-06-23 at 13 50 30" src="https://user-images.githubusercontent.com/70900763/175292064-d842399c-8445-47cf-9c97-8c453645908d.png">

## :black_nib: About the project
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


## :iphone: Prototype
### Interaction
**Home**

On the homepage you can see the 3d model of the Ilojo bar! It spins around so you can see everything of the Ilojo bar. When you click on the button "go down in history", you can learn more about the Ilojo bar and all the stories behind it. 

**View the paintings**

When you clicked on the button "go down in history" you will end up in the museum where the history about the Ilojo bar is laid out for you. You can view the paintings and when you want to know what's the story behind the painting, you can click on "read the story". At the end of the gallery you will see a bookstand with "write your own story" and a arrow pointing to the bookstand. When you click on the bookstand, you will end up in the book. You can write your own story about the Ilojo bar here!

**Read the stories**

This is the page where you can read the whole story behind the painting you clicked on. You can scroll down and read the story and take a look at all the photos in between the paragraphs.

**Send a story**

At this page you can send your own story about the Ilojo bar! You can write your story and add some photo's. This will be send to the email from Legacy so they can be check them out. When the story is approved, they can add them to the timeline. 


## :page_facing_up: Practical information
### Prismic
We use Prismic as a headless CMS. A headless CMS is a content management system (CMS), only used for back-end purposes, built from the ground up to make content accessible and maintainable. Prismic is supported for lots of frameworks as Next.js & Vue.js, but is also be used with an express server or even just vanilla javascript. In our case, we use it in combination with an express server.

We use Prismic to retrieve the stories and images from. The images are linked to the stories. This is the structure of all the stories:<br>
<img width="25%" alt="Schermafbeelding 2022-06-21 om 10 22 38" src="https://user-images.githubusercontent.com/70577898/174752624-5f87c7b2-fe26-4337-a1e7-78454f60feec.png">


For more information how to use Prismic click [here](https://prismic.io/docs/technologies/express-overview_)

### Activity diagram

<img width="870" alt="Screenshot 2022-06-23 at 14 36 21" src="https://user-images.githubusercontent.com/70900763/175299907-c2e60419-7442-44c0-b0a1-ce5c66d7947b.png">

### Service worker
The service worker checks whether the user has an internet connection. When a request is made, the service worker stores the 'CORE_ASSETS' in the browser's cache memory 'v3'. The CORE_ASSETS contains the offline page and the styling file. This allows the service worker to still show the offline page with associated styling when there is no internet connection. 

If there is internet connection, the service worker caches the rendered content in 'html cache'. If the user later returns to de SPA without internet, he can see still the pages he has already visited.

<img width="783" alt="Screenshot 2022-06-23 at 14 31 03" src="https://user-images.githubusercontent.com/70900763/175299015-e70a6101-c603-426c-80e5-f23536a9cc8e.png">


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

## :computer: How to install/use the code
Install and use this repo in a view simple steps:
1. Clone this repo with git clone ``https://github.com/Sophievanderburg/ilojo-bar.git``
2. Install all the used packages with ``npm install``
3. Start the server with ``npm run dev``
4. Open http://localhost:2020/ in your favourite browser
Good luck! 🍀



