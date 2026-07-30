# multica-ai/andrej-karpathy-skills

https://github.com/multica-ai/andrej-karpathy-skills  
New project:
```
curl -o CLAUDE.md 
https://raw.githubusercontent.com/forrestchang/andrej-karpathy-skills/main/CLAUDE.md
```
From Andrej:  
>"LLMs are exceptionally good at looping until they meet specific goals... Don't tell it what to do, give it success criteria and watch it go."
The "Goal-Driven Execution" principle captures this: transform imperative instructions into declarative goals with verification loops.


# mattpocock/skills

[![skills.sh](https://skills.sh/b/mattpocock/skills)](https://skills.sh/mattpocock/skills)  

https://github.com/mattpocock/skills  
Developing real applications is hard. Approaches like GSD, BMAD, and Spec-Kit try to help by owning the process. But while doing so, they take away your control and make bugs in the process hard to resolve.

These skills are designed to be small, easy to adapt, and composable. They work with any model. They're based on decades of engineering experience. Hack around with them. Make them your own. Enjoy.


## Quickstart (30-second setup)

1. Run the skills.sh installer:

```bash
npx skills@latest add mattpocock/skills
```

2. Pick the skills you want, and which coding agents you want to install them on. **Make sure you select `/setup-matt-pocock-skills`**.

3. Run `/setup-matt-pocock-skills` in your agent. It will:
   - Ask you which issue tracker you want to use (GitHub, Linear, or local files)
   - Ask you what labels you apply to tickets when you triage them (`/triage` uses labels)
   - Ask you where you want to save any docs we create

4. Bam - you're ready to go.

---


## thai-claude

```
## Language Rules

- Communicate with the user in Thai by default.
- Always use English for code, comments, identifiers, filenames, logs, and developer-facing content.
- Use Thai only for user-facing UI content, messages, localization resources, and authoritative Thai text.
- Prefer localization files over hardcoded Thai text in application logic.
- Keep references in their original language, preferring English for technical sources.
```



















