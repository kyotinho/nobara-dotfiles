<div align="center">
  <h1>Nobara Linux KDE Dotfiles 🐧</h1>
  <p>Minhas configurações pessoais e arquivos de ambiente para o Nobara Linux com KDE Plasma.</p>
  
  ![Nobara Linux](https://img.shields.io/badge/OS-Nobara%2044-blue?style=for-the-badge&logo=linux)
  ![KDE Plasma](https://img.shields.io/badge/DE-KDE%20Plasma-blue?style=for-the-badge&logo=kde)
  ![Kitty](https://img.shields.io/badge/Terminal-Kitty-green?style=for-the-badge&logo=gnometerminal)
</div>

<br>

<div align="center">
  <img src="https://github.com/user-attachments/assets/16beee8f-4ec8-4f56-a09a-62c46bb8e722" alt="Screenshot 3" width="800px" style="border-radius: 10px;">
</div>

<br>

## Visão Geral

Este repositório contém os meus *dotfiles*, organizados para facilitar a replicação do meu ambiente de desenvolvimento e uso diário. A filosofia aqui é manter um sistema bonito, rápido e focado em produtividade usando as tecnologias nativas do KDE.

## Especificações

| Componente | Ferramenta | Detalhes |
| :--- | :--- | :--- |
| **OS** | Nobara Linux 44 | Focado em performance e jogos |
| **Ambiente (DE)** | KDE Plasma | Moderno e altamente customizável |
| **Gerenciador de Janelas** | KWin | Comportamento padrão e atalhos globais |
| **Terminal** | Kitty | Acelerado por GPU e extremamente rápido |
| **Shell** | Bash | + Starship Prompt para um visual limpo |
| **Tema do Sistema** | Orchis | Tema GTK/Qt elegante e arredondado |
| **Informações (Fetch)** | Fastfetch | Arte customizada (Reze - Chainsaw Man) |
| **Extras** | Pokeget, CMatrix, Btop, Cava | Ferramentas visuais e de monitoramento |

  <img src="https://github.com/user-attachments/assets/f3336085-4d10-4ca5-9048-1f12bc5cff4b" alt="Screenshot 1" width="800px" style="border-radius: 10px; margin-bottom: 15px;">
  <br>
    <img src="https://github.com/user-attachments/assets/7fd7838c-8d09-474d-8a04-4b26fb73d54d" alt="Screenshot 2" width="800px" style="border-radius: 10px; margin-bottom: 15px;">
  <br>
  
## Como Instalar

Se você quiser usar essas configurações como base para o seu próprio sistema, siga os passos abaixo.

### 1. Clone o repositório:
```bash
git clone [https://github.com/SEU_USUARIO/nobara-dotfiles.git](https://github.com/SEU_USUARIO/nobara-dotfiles.git) ~/dotfiles
cd ~/dotfiles
```

### 2. Crie os links simbólicos (Exemplo para o Kitty e Starship):
**Faça backup dos seus arquivos originais primeiro**
```bash
ln -s ~/dotfiles/config/kitty/kitty.conf ~/.config/kitty/kitty.conf
ln -s ~/dotfiles/starship.toml ~/.config/starship.toml
```

## 📁 Estrutura de Diretórios
```
📦 ~/dotfiles
 ┣ 📂 config/
 ┃ ┣ 📂 btop/         # Monitor do sistema
 ┃ ┣ 📂 cava/         # Visualizador de áudio
 ┃ ┣ 📂 kitty/        # Emulador de terminal
 ┃ ┗ 📂 kde/          # kdeglobals, kwinrc, atalhos do Plasma
 ┣ 📜 starship.toml   # Configuração do prompt do terminal
 ┣ 📜 logo.txt        # Arte em ASCII customizada (Reze)
 ┗ 📜 README.md       # Este arquivo
