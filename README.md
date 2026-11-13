# 🎬 AI Video Architect & Producer

<p align="center">
  <img src="https://img.shields.io/badge/Agent_Skill-Claude_Code%20%7C%20Codex%20%7C%20Antigravity-blue?style=for-the-badge&logo=openai" alt="Supported Agents"/>
  <img src="https://img.shields.io/badge/Stack-Remotion%20%7C%20Three.js%20%7C%20Blender-orange?style=for-the-badge" alt="Tech Stack"/>
  <img src="https://img.shields.io/badge/Author-KleidsonDev-brightgreen?style=for-the-badge&logo=github" alt="Author"/>
</p>

O **AI Video Architect** é um mega-prompt (Skill) desenvolvido para transformar agentes autônomos de código (como Claude Code, Codex e Antigravity) em Diretores de Arte e Arquitetos de Produção Audiovisual. 

Ele substitui a edição manual em timeline por **edição programática**, instruindo a IA a escrever código (React, Python, Three.js) e controlar softwares em background (Blender, ComfyUI) para gerar vídeos, animações 2D/3D e motion graphics de altíssimo nível.

---

## ✨ Principais Funcionalidades

- 🧠 **Engenharia Reversa de Virais:** Analisa a frequência de cortes e gatilhos de vídeos de referência e cria estruturas originais baseadas na mesma retenção.
- 🗣️ **Roteiro "Humanizer" & Sincronia Estrita:** Remove o "sotaque de IA" (vícios de linguagem) dos roteiros e utiliza *Forced Alignment* para sincronizar eventos da tela exatamente com o milissegundo de cada palavra narrada.
- 🛠️ **Integração de Ferramentas Locais:** Orienta o agente a rodar **Blender** em modo *headless* ou acionar o **ComfyUI** (via MCP) para renderizar imagens base e gerar máscaras/assets localmente a custo zero.
- 🎶 **Engenharia de Áudio (Ducking & Beats):** Automação de *ducking* (-10dB) da trilha durante falas e uso da biblioteca `Librosa` para sincronizar as animações com as batidas da música.
- 🤖 **Loop de Self-QA (Auto-Auditoria):** O agente captura frames da própria renderização para inspecionar erros visuais (textos cortados, iluminação dura, bugs de física) antes de entregar o `.mp4` final.

---

## 🚀 Como Instalar

Existem duas formas de utilizar este projeto, dependendo do seu ambiente de IA:

### Método 1: Como Skill Nativa (Claude Code, Antigravity, Codex)
Se você utiliza agentes de terminal/CLI que suportam o carregamento de skills locais:
1. Copie o arquivo `ai-video-architect.md` deste repositório.
2. Cole na pasta de configurações de skills do seu agente.
3. O agente passará a reconhecer a arquitetura automaticamente pelo campo `description`.

### Método 2: Como Mega-Prompt (ChatGPT, Claude Web, Gemini)
Se você estiver utilizando interfaces de chat web:
1. Abra o arquivo `ai-video-architect.md`.
2. Copie todo o conteúdo de texto do arquivo.
3. Cole no seu chat como a primeira mensagem para inicializar a persona do Arquiteto.

---

## 🎮 Como Usar

Com a skill instalada ou o prompt iniciado, basta acionar o agente com um comando simples:

> *"Inicie o protocolo do AI Video Architect"* ou *"Quero criar um vídeo estilo documentário de mistério usando a skill ai-video-architect."*

O agente iniciará o **MÓDULO 1**, fazendo 4 perguntas estratégicas (Grill Me) para mapear suas ferramentas disponíveis, referências visuais e método de TTS (Kokoro, Voice Studio, ElevenLabs). Responda às perguntas e o agente começará a gerar o código do seu vídeo.

---

## 🏗️ Stack Tecnológico Suportado

O prompt instrui a IA a priorizar as seguintes bibliotecas e ferramentas de ponta:

- **Física e 3D:** `Three.js`, `React Rapier`, `Blender` (headless/MCP).
- **Montagem e Composição:** `Remotion`, `HyperFrames`, `transitions.dev`.
- **Efeitos e Correção:** `Postprocessing`, `Pixel FX`, `Lemo Opus`.
- **Áudio:** `Librosa` (detecção de beat), `Kokoro` / `Voice Studio` (TTS local).
- **Geração de Assets:** `ComfyUI` (Crea 2, remoção de fundos em nós).

---

## 🤝 Uso da Comunidade e Autoria

Criado e mantido exclusivamente por **[Kleidson Soares (@KleidsonDev)](https://github.com/KleidsonDev)**.

Este repositório é disponibilizado publicamente para que a comunidade possa baixar, instalar e utilizar a arquitetura em seus próprios projetos. No entanto, este é um projeto de contribuição fechada (Closed Contributions). **Não são aceitos Pull Requests, forks modificados ou alterações no código-fonte original.** 

Aproveitem a ferramenta! 🚀
