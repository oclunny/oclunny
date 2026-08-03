<div align="center">

<img src="./banner.png" width="100%">

```ts
const miguel = {
    alias: "oclunny",
    class: "GameDeveloper",
    level: 21,
    location: "Portugal",
    currently: "Building games & weird projects",
    status: "ONLINE"
};
```

</div>

---

# boot.ts

```bash
$ npm run profile

✔ Loading Unity...
✔ Loading Roblox Studio...
✔ Loading Electron...
✔ Loading Web Development...
✔ Loading Coffee...

Ready.
```

---

## profile.ts

```ts
export class Miguel {

    constructor() {
        this.name = "Miguel Costa";
        this.role = "Game Developer";
    }

    skills() {
        return [
            "JavaScript",
            "C#",
            "Lua",
            "Unity",
            "Node.js",
            "Docker"
        ];
    }

    interests() {
        return [
            "Game Systems",
            "Backend",
            "AI",
            "Open Source"
        ];
    }

}
```

---

## projects.ts

```ts
interface Project {
    name: string;
    engine: string;
    status: string;
}

const projects: Project[] = [

    {
        name: "Heartcastle",
        engine: "RPG Maker MZ",
        status: "Active Development"
    },

    {
        name: "Farm Simulator",
        engine: "Roblox Studio",
        status: "Building"
    },

    {
        name: "Sentinel",
        engine: "Electron",
        status: "Released"
    }

];
```

---

## skills.json

```json
{
    "languages": [
        "JavaScript",
        "TypeScript",
        "C#",
        "Lua",
        "C",
        "HTML",
        "CSS"
    ],

    "frameworks": [
        "Node.js",
        "Electron"
    ],

    "engines": [
        "Unity",
        "Roblox Studio",
        "RPG Maker"
    ],

    "tools": [
        "Docker",
        "Git",
        "GitHub Actions",
        "VS Code"
    ]
}
```

---

## currentFocus.py

```python
current_focus = [

    "Heartcastle",

    "Unity",

    "Advanced C#",

    "Backend Development",

    "Game Architecture",

    "AI Experiments"

]
```

---

## achievements.sql

```sql
SELECT project_name
FROM portfolio
WHERE status = "Completed";
```

```
Heartcastle
Sentinel
Portfolio Website
```

---

## future.rs

```rust
fn main() {

    learn();

    build();

    ship();

    repeat();

}
```

---

## stats.yml

```yaml
github:
  commits: "∞"
  bugs: "Too many"
  coffee: "Required"
  motivation: "100%"
```

<div align="center">

<!-- GitHub Stats -->

</div>

---

## links.ts

```ts
const links = {
    website: "https://oclunny.github.io",
    heartcastle: "https://heartcastle.netlify.app",
    sentinel: "https://sentinel-inc.xyz",
    github: "https://github.com/oclunny"
};
```
