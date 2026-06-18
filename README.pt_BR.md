<!-- l10n-sync: source-file="README.md" -->

<div align="center">

# 🎮 Mona Mayhem

### Construa uma Arena de Batalha de Contribuições GitHub com GitHub Copilot

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Astro](https://img.shields.io/badge/Astro-v5-BC52EE?logo=astro)](https://astro.build/)
[![Node.js](https://img.shields.io/badge/Node.js-22+-339933?logo=node.js)](https://nodejs.org/)
[![GitHub Copilot](https://img.shields.io/badge/GitHub%20Copilot-Powered-000000?logo=github)](https://github.com/features/copilot)

**Um workshop prático onde você usa GitHub Copilot para construir um app com tema de arcade retrô do zero — em ~1 hora.**

[🚀 Começar](#-início-rápido) · [📚 Guia do Workshop](workshop/pt_BR/00-overview.md) · [🎯 Escolha seu Track](#-escolha-seu-track)

</div>

---

## 🏆 O que Você Vai Construir

![Mona Mayhem Screenshot](https://github.com/user-attachments/assets/5eca79e2-cb9f-4e93-aa0d-23666ebde3b7)

Uma **arena de batalha arcade retrô** que coloca dois usuários do GitHub frente a frente comparando seus gráficos de contribuições. Digite qualquer par de nomes de usuário e assista ao drama pixelado se desenrolar.

**Você vai deste template → um app completamente funcional** usando GitHub Copilot para cuidar de arquitetura, implementação, estilização e polimento.

---

## 🎯 Escolha seu Track

Este workshop funciona em **dois tracks paralelos** — escolha o que melhor se adapta ao seu fluxo de trabalho:

| | Track VS Code | Track CLI |
|---|---|---|
| **Ideal para** | Desenvolvedores centrados no editor | Usuários avançados de terminal |
| **Ferramentas principais** | Chat, Plan Mode, Agent Mode, background agents | `copilot`, `/plan`, `/fleet`, `/delegate`, `/review` |
| **Ambiente** | VS Code v1.107+ | Qualquer terminal |

---

## 🧠 O que Você Vai Aprender

| Habilidade | Descrição |
|------------|-----------|
| **Engenharia de Contexto** | Ensine o Copilot sobre seu projeto com instruções e restrições precisas |
| **Desenvolvimento Plan-First** | Projete a arquitetura antes de escrever uma única linha de código |
| **Fluxos de Trabalho Agênticos** | Deixe o Copilot realizar trabalho multi-etapa em arquivos — com você no loop |
| **Iteração de Design** | Transforme um scaffold simples em uma experiência arcade retrô polida |
| **Fluxos Paralelos** | Divida o trabalho entre agentes e sessões para entregar mais rápido |

---

## 📚 Workshop

| Parte | Título | Recurso do Copilot |
|-------|--------|-------------------|
| [00](workshop/pt_BR/00-overview.md) | Visão Geral | O que você vai aprender |
| [01](workshop/pt_BR/01-setup.md) | Configuração & Engenharia de Contexto | Instruções de workspace, background agents |
| [02](workshop/pt_BR/02-plan-and-scaffold.md) | Planejar & Estruturar | Plan Mode |
| [03](workshop/pt_BR/03-agent-mode.md) | Agent Mode: Construir o Jogo | Agent Mode |
| [04](workshop/pt_BR/04-design-vibes.md) | Temas Design-First | Plan + Agent Mode |
| [05](workshop/pt_BR/05-polish.md) | Polimento & Multi-Agent | Background & cloud agents |
| [06](workshop/pt_BR/06-bonus.md) | Bônus & Extensões | Desafios abertos |

---

## 🚀 Início Rápido

1. **Crie sua própria cópia** — clique em **Use this template** (ou faça um fork)
2. **Escolha seu track:**
   - **VS Code** → clone seu repo e abra no VS Code
   - **CLI** → clone seu repo, instale o `copilot` e trabalhe no seu terminal
3. **Siga o [guia do workshop →](workshop/pt_BR/00-overview.md)**

> 💡 Use o **DevContainer** incluído para um ambiente totalmente pré-configurado sem nenhuma configuração adicional.

---

## ✅ Pré-requisitos

### Compartilhados
- GitHub Copilot (Pro, Business ou Enterprise)
- Git
- Node.js

### Track VS Code
- VS Code v1.107+
- Extensão GitHub Copilot conectada

### Track CLI
- GitHub Copilot CLI (`copilot`)
- Node.js 22+ (ou instale via Homebrew / WinGet)

---

## 🛠️ Stack Tecnológica

| Ferramenta | Propósito |
|------------|-----------|
| [Astro](https://astro.build/) v5 | Framework web |
| [@astrojs/node](https://docs.astro.build/en/guides/integrations-guide/node/) | Renderização no servidor |
| Press Start 2P | Fonte de jogos retrô |
| GitHub Contribution Graph API | Dados de usuários |

---

## Licença

MIT
