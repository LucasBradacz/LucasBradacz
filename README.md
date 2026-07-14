```js
import Desenvolvedor from "LucasBradacz";

class LucasBradacz extends Desenvolvedor {
  constructor() {
    super();

    this.nome = "Lucas Miron Bradacz";
    this.cargo = "Desenvolvedor Full Stack";
    this.local = "Brasil 🇧🇷";

    this.contato = {
      email: "lucas1bradacz@gmail.com",
      linkedin: "linkedin.com/in/lucas-miron-bradacz-19403024b",
      github: "github.com/LucasBradacz"
    };

    this.skills = {
      linguagens: [
        "Java",
        "JavaScript",
        "C#",
        "Python",
        "PHP",
        "Ruby"
      ],

      frontend: [
        "HTML5",
        "CSS3",
        "React",
        "Bootstrap"
      ],

      backend: [
        "Spring Boot",
        ".NET",
        "ASP.NET"
      ],

      bancoDeDados: [
        "PostgreSQL",
        "MySQL"
      ],

      ferramentas: [
        "Git",
        "GitHub",
        "Docker",
        "Rider",
        "RubyMine",
        "WebStorm",
        "VS Code"
      ]
    };

    this.estudando = [
      "Spring Security",
      "Docker",
      "Clean Architecture",
      "Microsserviços"
    ];

    this.interesses = [
      "Back-end",
      "APIs REST",
      "Arquitetura de Software"
    ];

    this.hobbies = [
      "🎲 RPG",
      "☕ Café"
    ];
  }

  dizerOi() {
    return "Obrigado por visitar meu perfil! 😄";
  }
}

export default new LucasBradacz();
```
