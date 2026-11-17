# Lui

**Lui is a personal assistant for your PC and your phone that runs AI coding agents on your own
projects, with you in control.** You tell Lui what you want; it starts agents (your own Claude Code
or Codex) in your project folders, asks before anything risky and keeps every change it made
undoable. From the phone you follow your tasks, answer approvals, see and control the PC's screen,
and stop everything with one tap.

> Lui is in a private test. Accounts are by invitation only.

[Português](#português)

## What it does

- **Tasks with agents.** Each project has its own tasks. Lui runs your own Claude Code or Codex,
  signed in with your own accounts, in the project's folder, with your MCP servers, connectors,
  plugins and skills as they are. Each task has a model level, a task goes on with another account
  when one reaches its limit, and a local AI (Ollama, LM Studio) can do the work too. A project can
  also get a Windows user of its own, with few rights, so its agents reach nothing else.
- **Agents with a name and a role.** A project has its own agents: a programmer, a tester, a
  designer. Call one with "@" in a message or let Lui pick the one that fits, chain them
  ("@programmer do it, then @tester test it"), and let them ask each other for help. Each one can
  have a spending limit.
- **Plans and subtasks.** A big request becomes a plan you start: its parts run together as tasks
  of their own and wait for each other when they must. An agent that finds its task is several
  pieces of work can propose the split itself, and comes back at the end to gather the results. The
  Agents view (a graph and a tree, with Stop for each agent) and the Wall show who is working on
  what.
- **Approvals and Stop all.** Every tool call an agent makes is checked first. Risky ones wait for
  your yes, on the PC or on the phone, and Stop all pauses every agent at once. With your
  permission, an agent can also use an app on the PC through its screen.
- **Review and undo.** Lui keeps a copy of each project outside its folder, so you can review what
  a task changed and undo it, file by file. The project's checks run before the review, and a
  council of reviewers can look at design work.
- **Replies you can use.** Agents answer with tables, buttons, fields and small pages that work on
  the PC and on the phone, and ask you with a card of options.
- **Board, Docs and Canvas.** Items, milestones and ideas linked to the tasks; pages with their
  versions, links between them, images and a graph of it all; and a free-form canvas with shapes,
  arrows, text, drawing and images, which agents can read and draw on too. The Docs import from
  Notion and Obsidian and export to Markdown files.
- **Your phone and your other computers.** The Android app and other PCs join your account with a
  QR code or your recovery words. Each task runs on its own computer, can be followed from the
  others and can continue on another one. From the phone you also see the PC's screen and control
  it, at home or on mobile data: it is off until you turn it on, and control starts after a
  countdown or your OK at the PC.
- **It starts from what you have.** Lui imports a project's AI setup from its folder (Claude Code,
  Codex, Cursor and Antigravity: instructions, memory, skills and MCP servers), reviewed item by
  item, and a project's way of working can be saved as a template for the next one.
- **Encrypted end to end.** Your devices sync through a server that only keeps and passes on
  encrypted data. The keys stay on your devices, and backups are encrypted with a password of
  yours.
- **And more:** a terminal panel, routines, a memory that learns from your corrections, the usage
  of your plans by account and by agent, an optional git worktree for each task, and tasks that
  resume by themselves after an update or a restart.

## Download

Get the files from the [latest release](https://github.com/tanlugi/Lui-AI/releases/latest).

| | File | What it needs |
|---|---|---|
| Windows | `Lui-Setup-<version>.exe` | Windows 11 (64-bit). To run agents, [Claude Code](https://docs.claude.com/en/docs/claude-code) or [Codex](https://github.com/openai/codex) installed and signed in: either one, neither is required by itself. Without Claude Code, Lui reads your messages with a local AI (its own engine in Settings › Connections, Ollama or LM Studio) |
| Android | `Lui-<version>.apk` | Android 7.0 or newer, on a 64-bit ARM phone |

### On Windows

1. Run `Lui-Setup-<version>.exe`. Windows may say it protected your PC, because the installer is
   not code-signed yet: choose **More info › Run anyway**.
2. Sign in with Google or with a code sent to your email (only invited emails get in).
3. Write down the 24 recovery words when Lui shows them. They are the only way back into your data
   on a new device, and nobody else has them.

### On Android

1. Download `Lui-<version>.apk` on the phone and open it. Allow installing apps from your browser
   or file manager when Android asks.
2. Sign in with the same account, then join with the QR code from the PC (**Settings › Devices › Pair a phone**)
   or with your recovery words.

## Updates

Lui looks for new versions by itself, on the PC and on the phone. Every version is signed with
Lui's release key, and the app checks the signature and the file's hash before installing it.
Nothing is installed in the middle of a task without asking you, and tasks resume by themselves
after an update.

What changed in each version is on the [releases page](https://github.com/tanlugi/Lui-AI/releases).

## About this repository

This repository only publishes Lui's releases. The source code is private.

---

## Português

**O Lui é um assistente pessoal para o seu PC e o seu celular que roda agentes de IA de
programação nos seus próprios projetos, com você no controle.** Você diz ao Lui o que quer; ele
inicia agentes (o seu Claude Code ou o seu Codex) nas pastas dos seus projetos, pergunta antes de
qualquer coisa arriscada e deixa tudo o que mudou pronto para desfazer. Pelo celular, você
acompanha as tarefas, responde as aprovações, vê e controla a tela do PC e para tudo com um toque.

> O Lui está em teste fechado. As contas são só por convite.

### O que ele faz

- **Tarefas com agentes.** Cada projeto tem as próprias tarefas. O Lui roda o seu Claude Code ou o
  seu Codex, com o login das suas próprias contas, na pasta do projeto, com os seus servidores MCP,
  conectores, plugins e skills como estão. Cada tarefa tem um nível de modelo, uma tarefa segue em
  outra conta quando uma chega ao limite, e uma IA local (Ollama, LM Studio) também pode fazer o
  trabalho. Um projeto também pode ganhar um usuário do Windows só dele, com poucos privilégios,
  para os agentes não alcançarem mais nada.
- **Agentes com nome e papel.** Um projeto tem os próprios agentes: um programador, um testador, um
  designer. Chame um com "@" na mensagem ou deixe o Lui escolher o que serve, encadeie
  ("@programmer faça isso e depois @tester teste") e deixe que peçam ajuda uns aos outros. Cada um
  pode ter um limite de gasto.
- **Planos e subtarefas.** Um pedido grande vira um plano que você inicia: as partes rodam juntas,
  cada uma como uma tarefa, e esperam umas pelas outras quando precisam. Um agente que descobre que
  a tarefa dele são vários trabalhos pode propor a divisão, e volta no fim para juntar os
  resultados. A vista dos agentes (um grafo e uma árvore, com Parar para cada agente) e o Wall
  mostram quem está trabalhando em quê.
- **Aprovações e Parar tudo.** Cada ferramenta que um agente usa é conferida antes. As
  arriscadas esperam o seu sim, no PC ou no celular, e o Parar tudo pausa todos os agentes de uma
  vez. Com a sua permissão, um agente também pode usar um app do PC pela tela.
- **Revisar e desfazer.** O Lui guarda uma cópia de cada projeto fora da pasta dele, para você ver
  o que uma tarefa mudou e desfazer, arquivo por arquivo. As verificações do projeto rodam antes da
  revisão, e um conselho de revisores pode olhar os trabalhos de design.
- **Respostas que você usa.** Os agentes respondem com tabelas, botões, campos e páginas pequenas
  que funcionam no PC e no celular, e perguntam com um cartão de opções.
- **Board, Docs e Quadro.** Itens, marcos e ideias ligados às tarefas; páginas com as versões
  delas, links entre elas, imagens e um grafo de tudo; e um quadro livre com formas, setas, texto,
  desenho e imagens, que os agentes também leem e desenham. As Docs importam do Notion e do
  Obsidian e exportam para arquivos Markdown.
- **Seu celular e seus outros computadores.** O app Android e outros PCs entram na sua conta por
  um QR code ou pelas suas palavras de recuperação. Cada tarefa roda no próprio computador, pode
  ser acompanhada dos outros e pode continuar em outro. Pelo celular você também vê a tela do PC e
  a controla, em casa ou nos dados móveis: vem desligado até você ligar, e o controle começa depois
  de uma contagem ou do seu OK no PC.
- **Começa do que você já tem.** O Lui importa a configuração de IA de um projeto pela pasta
  (Claude Code, Codex, Cursor e Antigravity: instruções, memória, skills e servidores MCP),
  revisada item a item, e o jeito de trabalhar de um projeto pode ser salvo como modelo para o
  próximo.
- **Cifrado de ponta a ponta.** Os aparelhos sincronizam por um servidor que só guarda e repassa
  dados cifrados. As chaves ficam nos seus aparelhos, e os backups são cifrados com uma senha sua.
- **E mais:** painel de terminal, rotinas, uma memória que aprende com as suas correções, o uso dos
  seus planos por conta e por agente, uma worktree opcional do git para cada tarefa e tarefas que
  voltam sozinhas depois de uma atualização ou de o PC reiniciar.

### Download

Baixe os arquivos da [release mais recente](https://github.com/tanlugi/Lui-AI/releases/latest).

| | Arquivo | O que precisa |
|---|---|---|
| Windows | `Lui-Setup-<versão>.exe` | Windows 11 (64 bits). Para rodar agentes, o [Claude Code](https://docs.claude.com/en/docs/claude-code) ou o [Codex](https://github.com/openai/codex) instalado e com login: qualquer um dos dois, nenhum é obrigatório sozinho. Sem o Claude Code, o Lui entende as suas mensagens com uma IA local (o motor próprio em Configurações › Conexões, o Ollama ou o LM Studio) |
| Android | `Lui-<versão>.apk` | Android 7.0 ou mais novo, em celular ARM de 64 bits |

#### No Windows

1. Rode o `Lui-Setup-<versão>.exe`. O Windows pode dizer que protegeu o PC, porque o instalador
   ainda não tem assinatura de código: escolha **Mais informações › Executar assim mesmo**.
2. Entre com o Google ou com um código enviado ao seu email (só emails convidados entram).
3. Anote as 24 palavras de recuperação quando o Lui mostrar. Elas são o único jeito de voltar aos
   seus dados num aparelho novo, e mais ninguém as tem.

#### No Android

1. Baixe o `Lui-<versão>.apk` no celular e abra. Permita instalar apps pelo navegador ou pelo
   gerenciador de arquivos quando o Android pedir.
2. Entre com a mesma conta e ligue o celular pelo QR code do PC (**Configurações › Dispositivos › Parear um celular**)
   ou pelas suas palavras de recuperação.

### Atualizações

O Lui procura versões novas sozinho, no PC e no celular. Cada versão é assinada com a chave de
release do Lui, e o app confere a assinatura e o hash do arquivo antes de instalar. Nada é
instalado no meio de uma tarefa sem perguntar a você, e as tarefas voltam sozinhas depois de uma
atualização.

O que mudou em cada versão está na [página de releases](https://github.com/tanlugi/Lui-AI/releases).

### Sobre este repositório

Este repositório só publica as releases do Lui. O código-fonte é privado.
