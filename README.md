# PokeHub — instaladores oficiais para Windows

Este repositório **público** é dedicado à distribuição dos instaladores do **PokeHub**, um gerenciador de múltiplas contas para Windows. O **código-fonte, o histórico de desenvolvimento e a documentação técnica permanecem em um repositório privado**.

## Download

**Última versão documentada: v0.5.7 (02/11/2026).**

[**Baixar a versão mais recente do PokeHub**](https://github.com/lucasgrayeb1/PokeHub-Releases/releases/latest)

Em cada lançamento, verifique:

- `PokeHub-Setup-vX.Y.Z.exe`: instalador para Windows x64;
- `SHA256SUMS.txt`: hash SHA-256 do instalador para conferir integridade.

O PokeHub utiliza **.NET 8 / WPF / Microsoft Edge WebView2**. É destinado a **Windows**; não há distribuição nativa para Android, iOS, macOS ou Linux.

## Instalação e atualização

1. Baixe e execute o instalador oficial a partir da página de Releases.
2. Instale normalmente no Windows. Quando uma versão nova for publicada, use o botão **Atualizações** no próprio PokeHub.
3. O aplicativo consulta versões públicas, verifica o tamanho e o SHA-256 do instalador e solicita confirmação antes de iniciá-lo.
4. **Não desinstale a versão anterior para atualizar**: a instalação por cima preserva a pasta local de sessões, desde que você não a apague.

## Privacidade e segurança

- Este repositório **não armazena** senhas de usuários, cookies, perfis, dados de sessão ou tokens do aplicativo.
- As contas e seus dados ficam no computador do usuário, em `%LOCALAPPDATA%\PokeHubWebView2Lab`, separados da pasta de instalação.
- Quando usadas, as credenciais cadastradas individualmente na versão 0.5.7 ficam protegidas pela criptografia DPAPI do usuário atual do Windows; não são sincronizadas com este repositório.
- O SHA-256 verifica integridade, mas **não equivale a uma assinatura digital**. Instaladores não assinados podem apresentar avisos do Windows SmartScreen.
- Como todo software distribuído como binário, os instaladores podem ser inspecionados por ferramentas de análise. O repositório de distribuição não publica código-fonte.

## Aviso

PokeHub é um projeto independente, **sem afiliação** com PokeIdle.io ou Poke Idle World.
