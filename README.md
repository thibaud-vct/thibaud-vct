# Hello, nerds 👋

I'm Thibaud, fullstack developer in Paris 🥐.

I spend hours learning things online, I love it. I listen to a lot of music or podcacts. Traveling and discovering the planet amazes me. I am in love with the great American spaces 🏜.

I have always been immersed in IT, from my studies in electronics to my passion for electronic music to web development. 
Since the beginning of 2021, I have enriched my skills by following the [Le Reacteur](https://www.lereacteur.io) 🚀 bootcamp in order to professionalize my knowledge. 
Passion also for entrepreneurship, fond of the emotion caused by the search for ideas and innovation, I co-founded an interior design consulting studio to sublimate places with culture and creativity.

I am open to all reflections 🤔 or partnerships 🤝, see opportunity 🚀 : [Mail me Here](thibaudfaurevincent@gmail.com)


## my knowledge in code :
```javascript
  export default function Thibaud({ learning, knowledge }) {
      const {code, technologies} = knowledge
      const [TypeScript, ThreeJS, GraphQL] = learning
      
      code = ["Javascript", "HTML", "CSS", "Sass", TypeScript],
      technologies = {
        frontEnd: {
            React: ["Hooks", "Axios", "Stripe", "Redux", GraphQL, ThreeJS],
            Framework: ["Next", "Gatsby", "CRA"]
        },
        backEnd: {
            Nodejs: ["Express", "Cloudinary", "Mongoose", "Jest"]
        },
        dataBase: "MongoDB",
        mobile: {
            ReactNative: "Expo"
        }
      }
      
      const software = [VSCode, Compass, Postman]
      const host = [GitHub, Heroku, Netlify, MongodbAtlas]
      
      const internet = useInternet()
      
    return (
      <Office>
        <Human className="Thibaud">{knowledge}</Human>
        <Computer className="MacBookPro">{software}</Computer>
        {internet && host.map(service => <Working connectTo={service} />)}
      </Office>
    );
  };
```
