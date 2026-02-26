# Veille
19/10/2025 :
- Entendu dans le podcast "Artisan développeur" : https://open.spotify.com/episode/7xdqFbKKlvH6YECXJTcWye?si=68da5a82fffe4244 : <br/>
    Kafka n'est pas fait pour faire du job management, C'est un système de messaging "partition-tolérant" (peut traverser des espaces réseaux différrents)
- Vraiment très intéressants ces podcasts : en voici un sur "le facteur de performance" : https://open.spotify.com/episode/2LUnEL2DiEjFcaiRRMw9I3?si=81a6703021c949d7 :
    il parle d'une étude google qui infdique que la caractéristique la plus présente dans les équipes perfrmates est la "sécurité psychologique" : le droit de dire "je ne sais pas faire", "j'ai besoin de ton aide", etc... <br/>
    L'étude  Google en question : https://www.michigan.gov/-/media/Project/Websites/mdhhs/Folder4/Folder10/Folder3/Folder110/Folder2/Folder210/Folder1/Folder310/Google-and-Psychological-Safety.pdf?rev=7786b2b9ade041e78828f839eccc8b75 et https://rework.withgoogle.com/intl/en/guides/understanding-team-effectiveness
- "l'uniformisation est un appauvrissement"


___
26/02/2026
#### 	<ins>Les Skills sont un concept unifié</ins> 

  Tu avais raison de me challenger. C'est **un seul et même concept** — un standard ouvert publié sur [agentskills.io](https://agentskills.io), annoncé le 16 octobre 2025.                     
   
  #### Architecture commune                                                                                                                                                                       
                  
  L'architecture est la même partout :
  - Un dossier avec un fichier `SKILL.md` (frontmatter YAML)
  - Des scripts/templates optionnels
  - Un mécanisme de **progressive disclosure** (chargé uniquement quand pertinent)

  #### Ce qui change entre plateformes

  | | **claude.ai** | **Claude Code** | **API** |
  |---|---|---|---|
  | Skills pré-construits (Excel, PPT...) | Oui | Non | Oui |
  | Skills custom | Oui (upload zip) | Oui (filesystem) | Oui (endpoint API) |
  | Slash commands (`/skill-name`) | Non | Oui | Non |
  | Subagent (`context: fork`) | Non | Oui | Non |
  | Sync entre surfaces | Non | Non | Non |

  #### Conclusion

  Quand j'ai fait ma distinction "Skills claude.ai vs Skills Claude Code" comme si c'étaient deux choses différentes, **j'avais tort**. C'est le même système, décliné avec des capacités
  différentes selon la surface.

  #### Sources officielles

  - [What are Skills? — Claude Help Center](https://support.claude.com/en/articles/12512176-what-are-skills)
  - [Introducing Agent Skills — Blog Anthropic](https://claude.com/blog/skills)
  - [Agent Skills Overview — Claude API Docs](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/overview)
  - [Extend Claude with Skills — Claude Code Docs](https://code.claude.com/docs/en/skills)
  - [Equipping agents for the real world — Anthropic Engineering](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills)

