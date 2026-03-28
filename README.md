<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&amp;color=gradient&amp;customColorList=12,20,24&amp;height=220&amp;section=header&amp;text=Patlegu&amp;fontSize=52&amp;fontColor=ffffff&amp;fontFamily=Fira+Code&amp;animation=twinkling&amp;fontAlignY=38&amp;desc=Network%20Architect%20%C2%B7%20Security%20%C2%B7%20Local%20AI&amp;descAlignY=58&amp;descSize=18&amp;descColor=aaaaaa" width="100%" />

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;size=16&amp;duration=3000&amp;pause=800&amp;color=00D9FF&amp;center=true&amp;vCenter=true&amp;width=560&amp;lines=Multi-agent+AI+for+network+security;LoRA+fine-tuning+on+local+GPU+(RTX+4070+Ti);OPNsense+%7C+WireGuard+%7C+CrowdSec+automation;AnonyNER+RoBERTa+%E2%80%94+30+labels+%7C+F1+96%25;From+raw+logs+to+anonymized+%26+actionable+data" /></a>

</div>

Je construis des agents IA spécialisés pour l'automatisation réseau/sécurité, un modèle NER pour l'anonymisation de logs, et des outils de préparation de datasets pour le fine-tuning local de LLMs.

---

## Ce sur quoi je travaille

**[cyber-agent-engine](https://huggingface.co/patlegu)** — Système multi-agents IA pour l'automatisation réseau.
Coordinateur LLM (Qwen2.5-3B) + agents-outils spécialisés (OPNsense, WireGuard, CrowdSec) entraînés par LoRA sur GPU local. Architecture CAP v1, structured output via vLLM/Outlines, dashboard Svelte temps réel. Modèles publiés sur HuggingFace.

**[Victor](https://github.com/patlegu/victor)** — Modèle NER spécialisé pour l'anonymisation de logs de sécurité.
Architecture RoBERTa (spaCy Transformers), 30+ labels cybersécurité (IP, hostname, CVE, KEY_FINGERPRINT, SCHEDULED_TASK…), corpus 25k enregistrements multi-sources, F1 global **96%**. Cycles d'amélioration documentés : diagnostic FN par label → correction ciblée corpus → données synthétiques.

**[anonyfiles](https://github.com/patlegu/anonyfiles)** — Moteur d'anonymisation de logs et documents.
Pipeline batch cohérent, réversibilité session, règles custom, intégration du modèle NER Victor.

**[mlops](https://huggingface.co/patlegu)** — Usine à LoRAs pour la cybersécurité.
Pipeline automatisé : génération de datasets SFT → fine-tuning LoRA sur GPU local → vérification fonctionnelle → publication HuggingFace. Produit les modèles listés sur [huggingface.co](https://huggingface.co/patlegu).

---

## Autres projets

| Projet | Description |
|---|---|
| [dataset_forge](https://github.com/patlegu/dataset_forge) | GUI locale tout-en-un pour la préparation de datasets IA (Florence-2, captioning, filtrage) |
| [DatasetClassifier](https://github.com/patlegu/DatasetClassifier) | Curation manuelle de datasets — approche revisitée |
| [imageset-editor](https://github.com/patlegu/imageset-editor) | Éditeur de jeux d'images pour l'entraînement |
| [guitarfretboard](https://github.com/patlegu/guitarfretboard) | Outil de visionnage de gammes/accords sur guitare |

---

## Stack

<div align="center">

**IA / ML**

<a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=python,pytorch,fastapi&amp;theme=dark" /></a>
&nbsp;
<a href="https://huggingface.co/patlegu"><img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&amp;logo=huggingface&amp;logoColor=black" /></a>
<a href="https://spacy.io"><img src="https://img.shields.io/badge/spaCy-09A3D5?style=for-the-badge&amp;logoColor=white" /></a>
<a href="https://vllm.ai"><img src="https://img.shields.io/badge/vLLM-6E4AFF?style=for-the-badge&amp;logoColor=white" /></a>

**Frontend / Backend / Infra**

<a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=svelte,ts,docker,linux,nginx,ansible,git,gitlab&amp;theme=dark" /></a>

</div>

---

## GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=patlegu&amp;show_icons=true&amp;theme=tokyonight&amp;hide_border=true&amp;count_private=true&amp;include_all_commits=true" />
&nbsp;&nbsp;
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=patlegu&amp;theme=tokyonight&amp;hide_border=true&amp;layout=compact&amp;langs_count=6" />

</div>

---

<div align="center">

**[nope.breizhland.eu](https://nope.breizhland.eu)** — Articles techniques sur les agents IA, l'anonymisation NER et le fine-tuning LoRA local.

<img src="https://capsule-render.vercel.app/api?type=waving&amp;color=gradient&amp;customColorList=12,20,24&amp;height=120&amp;section=footer" width="100%" />

</div>
