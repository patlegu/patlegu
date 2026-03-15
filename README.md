# Patrice Leguyader

Architecte réseau & sécurité de jour, bidouilleur IA de nuit — quelque part en Bretagne.

Je construis des agents IA spécialisés pour l'automatisation réseau/sécurité, et des outils de préparation de datasets pour le fine-tuning local de LLMs.

---

## Ce sur quoi je travaille

**[cyber-agent-engine](https://huggingface.co/patlegu)** — Système multi-agents IA pour l'automatisation réseau.
Coordinateur LLM (Qwen2.5-3B) + agents-outils spécialisés (OPNsense, WireGuard, CrowdSec) entraînés par LoRA sur GPU local. Architecture CAP v1, structured output via vLLM/Outlines, dashboard Svelte temps réel. Modèles publiés sur HuggingFace.

**[anonyfiles](https://github.com/patlegu/anonyfiles)** — Anonymisation automatisée de logs et documents.
NER spaCy custom (labels cybersécurité : IP, hostname, CVE, VPN_USER…), réversibilité session, pipeline batch cohérent.

**mlops** *(projet interne)* — Usine à LoRAs pour la cybersécurité.
Pipeline automatisé : génération de datasets SFT → fine-tuning LoRA sur GPU local → vérification fonctionnelle → publication HuggingFace. Produit les modèles listés sur [huggingface.co/patlegu](https://huggingface.co/patlegu).

---

## Autres projets

| Projet | Description |
|---|---|
| [dataset_forge](https://github.com/patlegu/dataset_forge) | GUI locale tout-en-un pour la préparation de datasets IA (Florence-2, captioning, filtrage) |
| [DatasetClassifier](https://github.com/patlegu/DatasetClassifier) | Curation manuelle de datasets — approche revisitée |
| [imageset-editor](https://github.com/patlegu/imageset-editor) | Éditeur de jeux d'images pour l'entraînement |
| [joschekscaptioner](https://github.com/patlegu/joschekscaptioner) | Outil de captioning multi-backend pour datasets image |
| [network_automation](https://github.com/patlegu/network_automation) | Toolbox d'automatisation réseau (Netmiko, Ansible) |
| [docker-wireguard-debian11](https://github.com/patlegu/docker-wireguard-debian11) | WireGuard containerisé sur Debian 11 |

---

## Stack

**IA / ML**

[![Python](https://skillicons.dev/icons?i=python)](https://python.org)
[![PyTorch](https://skillicons.dev/icons?i=pytorch)](https://pytorch.org)
[![FastAPI](https://skillicons.dev/icons?i=fastapi)](https://fastapi.tiangolo.com)
[![HuggingFace](https://img.shields.io/badge/🤗%20HuggingFace-FFD21E?style=for-the-badge)](https://huggingface.co/patlegu)
[![vLLM](https://img.shields.io/badge/vLLM-6E4AFF?style=for-the-badge&logo=data:image/svg+xml;base64,)](https://vllm.ai)
[![spaCy](https://img.shields.io/badge/spaCy-09A3D5?style=for-the-badge)](https://spacy.io)

**Frontend / Backend**

[![Svelte](https://skillicons.dev/icons?i=svelte)](https://svelte.dev)
[![TypeScript](https://skillicons.dev/icons?i=ts)](https://typescriptlang.org)
[![Docker](https://skillicons.dev/icons?i=docker)](https://docker.com)
[![Linux](https://skillicons.dev/icons?i=linux)](https://kernel.org)
[![Nginx](https://skillicons.dev/icons?i=nginx)](https://nginx.org)

**Réseau / Sécurité**

[![Ansible](https://skillicons.dev/icons?i=ansible)](https://ansible.com)
[![Git](https://skillicons.dev/icons?i=git)](https://git-scm.com)
[![GitLab](https://skillicons.dev/icons?i=gitlab)](https://gitlab.com)

---

## Blog

[nope.breizhland.eu](https://nope.breizhland.eu) — Articles techniques sur les agents IA, l'anonymisation NER et le fine-tuning LoRA local.
