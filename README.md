# Hello, nerds 👋

I'm Thibaud, fullstack developer in Paris 🥐.

Passion for entrepreneurship, fond of the emotion caused by the search for ideas and innovation, I co-founded an interior design consulting studio to sublimate places with culture and creativity.

I am open to all reflections 🤔 or partnerships 🤝, see opportunity 🚀 : [Mail me Here](thibaudfaurevincent@gmail.com)


## my knowledge in code :
<svg role="img" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><title>Express</title><path d="M24 18.588a1.529 1.529 0 01-1.895-.72l-3.45-4.771-.5-.667-4.003 5.444a1.466 1.466 0 01-1.802.708l5.158-6.92-4.798-6.251a1.595 1.595 0 011.9.666l3.576 4.83 3.596-4.81a1.435 1.435 0 011.788-.668L21.708 7.9l-2.522 3.283a.666.666 0 000 .994l4.804 6.412zM.002 11.576l.42-2.075c1.154-4.103 5.858-5.81 9.094-3.27 1.895 1.489 2.368 3.597 2.275 5.973H1.116C.943 16.447 4.005 19.009 7.92 17.7a4.078 4.078 0 002.582-2.876c.207-.666.548-.78 1.174-.588a5.417 5.417 0 01-2.589 3.957 6.272 6.272 0 01-7.306-.933 6.575 6.575 0 01-1.64-3.858c0-.235-.08-.455-.134-.666A88.33 88.33 0 010 11.577zm1.127-.286h9.654c-.06-3.076-2.001-5.258-4.59-5.278-2.882-.04-4.944 2.094-5.071 5.264z"/></svg>

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
