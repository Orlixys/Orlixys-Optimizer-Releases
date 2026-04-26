<div align="center">

<img src="https://raw.githubusercontent.com/Orlixys/Orlixys-Optimizer-Source/main/OrlixysOptimizer/Assets/icon.png" width="120" alt="Orlixys Optimizer" />

# Orlixys Optimizer

**Otimização e manutenção do Windows, em um só lugar.**

[![Latest Release](https://img.shields.io/github/v/release/Orlixys/Orlixys-Optimizer-Releases?label=vers%C3%A3o&style=for-the-badge)](https://github.com/Orlixys/Orlixys-Optimizer-Releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Orlixys/Orlixys-Optimizer-Releases/total?label=downloads&style=for-the-badge)](https://github.com/Orlixys/Orlixys-Optimizer-Releases/releases)
[![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#requisitos)
[![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)](https://github.com/Orlixys/Orlixys-Optimizer-Source/blob/main/LICENSE)

### [⬇️ Baixar para Windows](https://github.com/Orlixys/Orlixys-Optimizer-Releases/releases/latest/download/OrlixysOptimizer-win-Setup.exe)

</div>

---

## ✨ O que é?

Um aplicativo nativo (.NET 9 + WPF + WebView2) para limpar, otimizar e manter o Windows funcionando como deveria. Foco em **performance, segurança e clareza** — sem instalar dezenas de processos pesados, sem telemetria, sem propagandas.

## 🚀 Recursos principais

- **Dashboard em tempo real** com CPU, GPU, memória, rede e armazenamento
- **Otimização rápida** com um clique e ponto de restauração automático
- **Limpeza inteligente** de cache, temporários, log files e standby memory
- **Modo Foco** — silencia notificações e processos de fundo enquanto você trabalha ou joga
- **Gerenciamento de inicialização** com detalhes que o `msconfig` esconde
- **Hardening de segurança** — desativa telemetria, ativa proteções nativas
- **Cores GPU live** (saturação, brilho, contraste) sem reiniciar o driver
- **Limpeza de pastas dev** (`node_modules`, `__pycache__`, `bin/`, `obj/`...)
- **Automação** com tarefas agendadas que rodam em background
- **Atualização automática** via [Velopack](https://velopack.io) — silenciosa e segura

## 📦 Instalação

### Instalador (recomendado)

Baixe o **[OrlixysOptimizer-win-Setup.exe](https://github.com/Orlixys/Orlixys-Optimizer-Releases/releases/latest/download/OrlixysOptimizer-win-Setup.exe)** e execute. O app instala em segundos e abre automaticamente. Atualizações futuras chegam sozinhas.

### Versão portátil

Se você prefere não instalar, baixe `OrlixysOptimizer-win-Portable.zip` da [última release](https://github.com/Orlixys/Orlixys-Optimizer-Releases/releases/latest), extraia em qualquer pasta e execute o `.exe`. Atualização automática **não funciona** nessa modalidade.

## 🔧 Requisitos

| | |
|---|---|
| **Sistema** | Windows 10 (build 1809+) ou Windows 11, 64-bit |
| **WebView2 Runtime** | Já vem com Windows 11. Em Windows 10, [baixe o Evergreen](https://developer.microsoft.com/microsoft-edge/webview2/) (gratuito, ~120 KB de bootstrap) |
| **Permissões** | Algumas funções (serviços, hardening, ponto de restauração) pedem privilégios de administrador via UAC quando necessário |

## ❓ Perguntas frequentes

<details>
<summary><b>O Windows Defender / SmartScreen bloqueou o instalador. É vírus?</b></summary>

Não. O aviso aparece porque o instalador ainda não tem assinatura digital com certificado EV (que custa cerca de US$ 300/ano). É comum em projetos open source pequenos. Você pode:

1. Clicar em **Mais informações** no aviso do SmartScreen
2. Clicar em **Executar mesmo assim**

Conforme mais usuários instalam, o Windows aprende que o binário é seguro e o aviso some sozinho. O código-fonte está totalmente disponível para auditoria no [repositório privado](https://github.com/Orlixys/Orlixys-Optimizer-Source) (acesso sob solicitação).
</details>

<details>
<summary><b>Onde o app é instalado?</b></summary>

`%LocalAppData%\OrlixysOptimizer\current\` — não pede admin para instalar (cada usuário tem sua cópia).
</details>

<details>
<summary><b>Como desinstalar?</b></summary>

**Configurações → Aplicativos → Aplicativos instalados → Orlixys Optimizer → Desinstalar.** Tudo é removido, incluindo configurações em `%LocalAppData%`.
</details>

<details>
<summary><b>O app coleta dados meus?</b></summary>

Não. Sem telemetria, sem analytics, sem chamada para servidores que não sejam o GitHub Releases (apenas para verificar atualizações). Toda configuração fica em `%LocalAppData%\OrlixysOptimizer\` na sua máquina.
</details>

<details>
<summary><b>Algumas opções pedem reinicialização?</b></summary>

Sim — alterações de hardening do sistema, agendamentos do Windows e ajustes de boot só têm efeito completo após reiniciar. O app sempre avisa quando isso acontece.
</details>

<details>
<summary><b>Por que o monitoramento detalhado de sensores fica desativado por padrão?</b></summary>

Porque ele depende do driver `WinRing0`, que tem uma CVE conhecida ([CVE-2020-14979](https://nvd.nist.gov/vuln/detail/CVE-2020-14979)). O Defender bloqueia esse driver no histórico de proteção. Se você precisa ver temperatura de CPU e clocks de GPU, pode ativar em **Configurações → Avançado** — mas é uma decisão informada.
</details>

## 🐛 Reportar problema

[Abrir uma issue](https://github.com/Orlixys/Orlixys-Optimizer-Releases/issues/new) com:

- Versão do Orlixys Optimizer (visível em **Configurações → Sobre**)
- Versão do Windows (`winver`)
- Descrição do problema e passos para reproduzir
- Screenshot, se for visual

## 📜 Licença

[MIT](https://github.com/Orlixys/Orlixys-Optimizer-Source/blob/main/LICENSE) — uso comercial permitido, atribuição apreciada.

---

<div align="center">

Feito com ❤️ por **[Orlixys](https://github.com/Orlixys)**

</div>
