# Welcome to my profile! 👋
## Currently looking for a job

## Living in Toronto 🇨🇦

```javascript


function MyProfile() {
const alejandro =
{
name: "Alejandro SIlva Juarez",
job: "Web developer",
school: "Seneca College",
languages: [
{
language: "Spanish",
level: "Native",
},
{
language: "English",
level: "Fluenty",
},
{
language: "Korean",
level: "intermediate",
},
],
}

return(
<>
<div className="container">
  <h1>Hi 👋, I'm {alejandro.name}</h1>
  <h2>Self-taught {alejandro.job} since 2019</h2>
  <p>currently studying in {alejandro.school}</p>

  <h1>Languages</h1>
  {
  alejandro.languages.map((lan, i) => (
  <div key={i}>
  <p>{lan.name}: <span>{lan.level}</span></p>
  </div>
  ));
  }
</div>
</>
)

} 


```
- 🔭 I’m currently working on      :  enchancing my knowledge
- 🌱 I’m currently learning        : React.js, Python, Node.js, C, C++ and so on!
- 👯 I’m looking to collaborate on : Projects that help me on my personal objectives
- 🤔 I’m looking for help with     : OOP languages
- 💬 Ask me about                  : What are my plans in my future

<h2 align="center">You can reach me at ⭐</h2>

<p align="center">
  <a href="https://www.linkedin.com/in/alejandro-canada-4a955127b/">
    <img src="https://www.vectorlogo.zone/logos/linkedin/linkedin-icon.svg" alt="Alejandro Silva Juarez Linkedin" height="30" width="30">
  </a>
</p>



