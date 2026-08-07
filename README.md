# janhetzler/skills

Universal Agent Skills — portable, project-independent skill definitions.

## Was sind Agent Skills?

Ein Skill ist ein Ordner mit einer `SKILL.md` — Anweisungen die ein Agent
lädt wenn eine Aufgabe zum Skill passt. Kein projektspezifisches Wissen,
keine Konfiguration — nur universell anwendbare Expertise.

Format: [agentskills.io](https://agentskills.io) Standard.

## Verfügbare Skills

| Skill | Zweck |
|-------|-------|
| [doc/](doc/SKILL.md) | Dokumentation erstellen, OKF anwenden, Qualität sichern |

## Einbinden in ein Projekt

```bash
# Als Git Submodule (empfohlen)
git submodule add https://github.com/janhetzler/skills skills

# Oder manuell kopieren
git clone https://github.com/janhetzler/skills /tmp/skills
cp -r /tmp/skills/doc /pfad/zum/projekt/skills/
```

## Lizenz

MIT
