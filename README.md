# 🌑 Eclipse: Anime Clash

<p align="center">
  <strong>Where anime legends collide.</strong>
</p>

<p align="center">
  Um projeto de jogo de combate inspirado em anime para Roblox, desenvolvido com foco em precisão, estratégia, impacto visual e profundidade mecânica.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Em%20Desenvolvimento-orange?style=for-the-badge" alt="Status do projeto: em desenvolvimento">
  <img src="https://img.shields.io/badge/Platform-Roblox-red?style=for-the-badge&logo=roblox" alt="Plataforma Roblox">
  <img src="https://img.shields.io/badge/Language-Luau-blue?style=for-the-badge" alt="Linguagem Luau">
  <img src="https://img.shields.io/badge/Workflow-Rojo-purple?style=for-the-badge" alt="Workflow Rojo">
</p>

---

## 📖 Sobre o projeto

**Eclipse: Anime Clash** é um projeto de jogo de combate no Roblox inspirado na intensidade das batalhas de anime.

A proposta é desenvolver uma experiência em que cada confronto seja mais do que simplesmente utilizar habilidades: posicionamento, tempo de reação, leitura do adversário e domínio das mecânicas deverão fazer a diferença.

O projeto busca combinar **combate técnico e espetáculo cinematográfico**, criando lutas com impacto, ritmo e espaço para evolução da habilidade dos jogadores.

A visão é construir uma experiência competitiva, com identidade própria, sistemas bem estruturados e atenção especial à qualidade do combate.

> Nosso objetivo não é apenas criar mais um jogo de batalha inspirado em anime, mas desenvolver uma experiência em que cada luta seja memorável.

## 🎯 Pilares do projeto

### ⚔️ Combate técnico

Um sistema de combate responsivo, com combos, defesa, movimentação e gerenciamento de estados. As decisões dos jogadores devem ter consequências claras durante as lutas.

### 💥 Impacto cinematográfico

Animações, efeitos visuais, câmera e habilidades deverão transmitir a força e a identidade de cada confronto sem prejudicar a leitura do combate.

### ⚖️ Equilíbrio competitivo

Habilidades poderosas precisam ter contrajogadas e limitações compreensíveis. O objetivo é favorecer domínio mecânico, estratégia e decisões bem executadas.

### 🚀 Desenvolvimento consistente

Cada sistema será construído e testado gradualmente, priorizando uma base técnica confiável antes da expansão do conteúdo.

## 🥊 Sistemas planejados

Os sistemas abaixo representam a direção de desenvolvimento do projeto. Eles ainda não devem ser considerados funcionalidades concluídas.

| Sistema | Objetivo |
|---|---|
| Combate M1 | Criar a base dos combos e ataques básicos |
| Hitboxes e dano | Registrar acertos de maneira consistente |
| Stun e knockback | Definir reações aos golpes e controle de espaço |
| Defesa | Permitir respostas defensivas durante os confrontos |
| Dash | Adicionar mobilidade, esquivas e reposicionamento |
| Habilidades | Criar técnicas com funções e características próprias |
| Awakening | Explorar transformações ou estados especiais de combate |
| Arena de batalha | Fornecer um ambiente para confrontos e testes |
| Interface de combate | Comunicar vida, estados e informações importantes |

## 🛠️ Tecnologias e ferramentas

O projeto utiliza ou pretende utilizar as seguintes tecnologias:

- **Roblox Studio:** criação, execução e testes da experiência.
- **Luau:** linguagem de programação utilizada no desenvolvimento dos sistemas.
- **Claude Code:** assistente de programação para implementação, análise e manutenção do código.
- **Rojo:** sincronização entre os arquivos do projeto e a estrutura de instâncias do Roblox.
- **Git e GitHub:** controle de versão e hospedagem do código, planejados para uma etapa posterior.

## 🏗️ Arquitetura planejada

A organização do código busca separar responsabilidades entre servidor, cliente e módulos compartilhados.

```text
Eclipse-Anime-Clash/
├── default.project.json
├── README.md
└── src/
    ├── ReplicatedStorage/
    │   └── Shared/
    │       ├── Config/
    │       └── Modules/
    ├── ServerScriptService/
    │   └── Services/
    │       ├── CombatService
    │       ├── HitboxService
    │       ├── StateService
    │       └── AbilityService
    └── StarterPlayer/
        └── StarterPlayerScripts/
            └── Controllers/
```

*Estrutura conceitual: a organização definitiva dependerá da implementação e da configuração do Rojo.*

### 🔒 Segurança e autoridade do servidor

Um dos princípios técnicos do projeto é manter o servidor como autoridade sobre os resultados relevantes do combate.

Isso inclui a validação de ataques, alcance, cooldowns, estados e aplicação de dano. O cliente ficará responsável principalmente pela entrada do jogador e pela apresentação visual, sem poder determinar livremente os resultados das lutas.

A intenção é reduzir possibilidades de exploração e manter a consistência das partidas multiplayer.

## 🗺️ Roadmap

O desenvolvimento será dividido em etapas para facilitar testes, manutenção e evolução.

- [x] Definição inicial da visão do projeto.
- [x] Preparação inicial do ambiente de desenvolvimento.
- [ ] Validar a estrutura de arquivos e a configuração do Rojo.
- [ ] Conectar o Rojo ao Roblox Studio.
- [ ] Criar uma arena básica para testes.
- [ ] Implementar vida, dano e estados de combate.
- [ ] Desenvolver o combo M1.
- [ ] Implementar defesa e dash.
- [ ] Testar confrontos multiplayer com dois jogadores.
- [ ] Refinar responsividade, balanceamento e feedback visual.
- [ ] Desenvolver habilidades e sistemas especiais.
- [ ] Preparar uma versão de teste mais completa.

O roadmap poderá mudar conforme os testes revelarem prioridades técnicas e oportunidades de melhoria.

## 👥 Equipe

O projeto começa com uma equipe pequena, priorizando desenvolvimento iterativo e testes frequentes.

- **Desenvolvimento:** responsável principal pelo projeto.
- **Testes:** dois testers, incluindo o desenvolvedor.
- **Marketing e comunidade:** divulgação inicial conduzida pela própria equipe.

A estrutura poderá crescer conforme as necessidades do projeto.

## 📌 Estado atual

O Eclipse: Anime Clash está em sua fase inicial de desenvolvimento.

Neste momento, o foco é preparar a infraestrutura, validar a sincronização com o Roblox Studio e estabelecer uma base organizada para os futuros sistemas de combate.

Ainda não se trata de uma versão completa ou de um lançamento público.

## ⚖️ Propriedade intelectual

Eclipse: Anime Clash é um projeto em desenvolvimento e busca construir uma identidade própria.

Referências a outros jogos servem como inspiração para estudo de design e mecânicas. Personagens, marcas, músicas, animações e outros elementos pertencentes a terceiros exigem as permissões apropriadas para uso.

A presença de referências a obras de anime não implica afiliação, patrocínio ou autorização dos respectivos titulares.

## 📬 Contato e acompanhamento

O desenvolvimento poderá ser acompanhado por meio deste repositório.

Sugestões técnicas, relatos de problemas e ideias construtivas serão bem-vindos conforme o projeto evoluir.

---

<p align="center">
  <strong>ECLIPSE: ANIME CLASH</strong><br>
  <em>Where anime legends collide.</em>
</p>
