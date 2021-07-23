# Hello, nerds 👋

I'm Thibaud, fullstack developer in Paris 🥐.

Passion for entrepreneurship, fond of the emotion caused by the search for ideas and innovation, I co-founded an interior design consulting studio to sublimate places with culture and creativity.

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
