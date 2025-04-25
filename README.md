### **:woman_technologist: A bit about me**

```typescript

// To run this TypeScript file:
// 1. Save it as noelle.ts
// 2. Run `tsc noelle.ts` to compile it to JavaScript
// 3. Run `node noelle.js` to see the output in the terminal

type TechStack = "JavaScript" | "React" | "TypeScript" | "NextJS" | "Node.js";

interface Developer {
  name: string;
  pronouns: [string, string];
  jobTitle: string;
  location: string;
  tech: TechStack[];
  interests: string[];
  currentFocus: string;
  introduce: () => void;
}

const noelle: Developer = {
  name: "Noelle",
  pronouns: ["She", "Her"],
  jobTitle: "Software Developer",
  location: "London",
  tech: ["JavaScript", "React", "TypeScript", "NextJS", "Node.js"],
  interests: ["Archery", "Volunteering", "Photography", "Baking"],
  currentFocus: "currently upskilling in the latest technologies",

  introduce() {
    console.log(`👋 Hi there! I'm ${this.name}, a ${this.jobTitle} based in ${this.location}.`);
    console.log(`💻 I mostly work with ${this.tech.join(", ")}, and I’m aiming to go Fullstack.`);
    console.log(`📚 Right now, I'm ${this.currentFocus}.`);
    console.log(`🍰 When I’m not coding, I love ${this.interests.join(", ")}.`);
    console.log(`Thanks for stopping by! ✨`);
  }
};

noelle.introduce();

// Task: Run the above and get to know Noelle 🌸

```

### :hammer_and_pick: Project Directory
- [View my projects here](https://github.com/noelledons/project-directory)

### :female_detective: Where to find me

<p>
    </a> <a href="https://noelledons.medium.com/" target="_blank"><img alt="Medium" src="https://img.shields.io/badge/medium-%2312100E.svg?&style=for-the-badge&logo=medium&logoColor=white" /></a>
</p>

**Interesting in collaborating together?** Drop me an [email](noelle321@hotmail.co.uk) :envelope_with_arrow:

