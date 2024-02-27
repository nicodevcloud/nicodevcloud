### Hi there 👋

```javascript
class WhoAmI {
    constructor() {
        this.user = "Nicolas Ventosilla";
        this.education = "Cloud Computing";
        this.languages = ["Python", "HTML", "CSS", "JavaScript"];
        this.skills = ["AWS Services", "Node.js", "React"];
        this.interests = ["Cloud Architecture", "Serverless Computing", "Web Development"];
    }

    introduce() {
        console.log(`¡Hola! Soy ${this.user}, estudiante de ${this.education}.`);
        console.log("Aquí tienes un poco más sobre mí:");
        console.log("- Lenguajes: " + this.languages.join(", "));
        console.log("- Habilidades: " + this.skills.join(", "));
        console.log("- Intereses: " + this.interests.join(", "));
    }
}

const nicolas = new WhoAmI();
nicolas.introduce();
```

<!--

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
