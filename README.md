# Lui

**Lui is a personal assistant for your PC and your phone that runs AI coding agents on your own
projects, with you in control.** You tell Lui what you want; it starts Claude Code agents in your
project folders, asks before anything risky and keeps every change it made undoable. From the
phone you follow your tasks, answer approvals and stop everything with one tap.

> Lui is in a private test. Accounts are by invitation only.

[Português](#português)

## What it does

- **Tasks with agents.** Each project has its own tasks. Lui runs your own Claude Code, signed in
  with your own account, in the project's folder. A project can also get a Windows user of its own,
  with few rights, so its agents reach nothing else.
- **Approvals and Stop all.** Every tool call an agent makes is checked first. Risky ones wait for
  your yes, on the PC or on the phone, and Stop all pauses every agent at once.
- **Undo.** Lui keeps a copy of each project outside its folder, so you can review what a task
  changed and undo it, file by file.
- **Board, Docs and Canvas.** Items, milestones and ideas linked to the tasks; pages with their
  versions; and a free-form canvas with shapes, arrows, text, drawing and images, which agents can
  read and draw on too.
- **Your phone and your other computers.** The Android app and other PCs join your account with a
  QR code or your recovery words. Each task runs on its own computer and can be followed from the
  others.
- **Encrypted end to end.** Your devices sync through a server that only keeps and passes on
  encrypted data. The keys stay on your devices.
- **And more:** a terminal panel, routines, project memory and the usage of your plan.

## Download

Get the files from the [latest release](https://github.com/tanlugi/Lui-AI/releases/latest).

| | File | What it needs |
|---|---|---|
| Windows | `Lui-Setup-<version>.exe` | Windows 11 (64-bit) and [Claude Code](https://docs.claude.com/en/docs/claude-code) installed and signed in |
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
Nothing is installed in the middle of a task without asking you.

## About this repository

This repository only publishes Lui's releases. The source code is private.

---

## Português

**O Lui é um assistente pessoal para o seu PC e o seu celular que roda agentes de IA de
programação nos seus próprios projetos, com você no controle.** Você diz ao Lui o que quer; ele
inicia agentes do Claude Code nas pastas dos seus projetos, pergunta antes de qualquer coisa
arriscada e deixa tudo o que mudou pronto para desfazer. Pelo celular, você acompanha as tarefas,
responde as aprovações e para tudo com um toque.

> O Lui está em teste fechado. As contas são só por convite.

### O que ele faz

- **Tarefas com agentes.** Cada projeto tem as próprias tarefas. O Lui roda o seu Claude Code,
  com o login da sua própria conta, na pasta do projeto. Um projeto também pode ganhar um usuário
  do Windows só dele, com poucos privilégios, para os agentes não alcançarem mais nada.
- **Aprovações e Parar tudo.** Cada ferramenta que um agente usa é conferida antes. As
  arriscadas esperam o seu sim, no PC ou no celular, e o Parar tudo pausa todos os agentes de uma
  vez.
- **Desfazer.** O Lui guarda uma cópia de cada projeto fora da pasta dele, para você ver o que uma
  tarefa mudou e desfazer, arquivo por arquivo.
- **Board, Docs e Quadro.** Itens, marcos e ideias ligados às tarefas; páginas com as versões
  delas; e um quadro livre com formas, setas, texto, desenho e imagens, que os agentes também leem
  e desenham.
- **Seu celular e seus outros computadores.** O app Android e outros PCs entram na sua conta por
  um QR code ou pelas suas palavras de recuperação. Cada tarefa roda no próprio computador e pode
  ser acompanhada dos outros.
- **Cifrado de ponta a ponta.** Os aparelhos sincronizam por um servidor que só guarda e repassa
  dados cifrados. As chaves ficam nos seus aparelhos.
- **E mais:** painel de terminal, rotinas, memória do projeto e o uso do seu plano.

### Download

Baixe os arquivos da [release mais recente](https://github.com/tanlugi/Lui-AI/releases/latest).

| | Arquivo | O que precisa |
|---|---|---|
| Windows | `Lui-Setup-<versão>.exe` | Windows 11 (64 bits) e o [Claude Code](https://docs.claude.com/en/docs/claude-code) instalado e com login |
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
instalado no meio de uma tarefa sem perguntar a você.

### Sobre este repositório

Este repositório só publica as releases do Lui. O código-fonte é privado.
