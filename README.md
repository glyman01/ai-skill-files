# AI Skill Files

Geoff Lyman's library of Claude skills. Each skill lives in its own folder with a `SKILL.md` file, plus any reference files it needs.

## Skills

| Skill | What it does |
|---|---|
| [landing-page-design](landing-page-design/SKILL.md) | Design, build, audit, and optimize landing pages for lead generation and conversion |
| [subcontractor](subcontractor/SKILL.md) | Act as a general contractor that picks the right Claude model for each piece of work, saving credits and time without sacrificing quality |

## Using a skill

To upload a skill to Claude as a zip, download its folder and zip it so the folder itself sits at the top of the archive:

```
subcontractor.zip
└── subcontractor/
    └── SKILL.md
```

## Adding a new skill

1. Create a folder named after the skill (lowercase, hyphens).
2. Add a `SKILL.md` with `name` and `description` frontmatter.
3. Put supporting files in a `references/` subfolder.
4. Add a row to the table above.
