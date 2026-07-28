<div align="center">
  <h1>Nobara Linux KDE Dotfiles 🐧</h1>
  <p>Minhas configurações pessoais e arquivos de ambiente para o Nobara Linux com KDE Plasma.</p>
  
  ![Nobara Linux](https://img.shields.io/badge/OS-Nobara%2044-blue?style=for-the-badge&logo=linux)
  ![KDE Plasma](https://img.shields.io/badge/DE-KDE%20Plasma-blue?style=for-the-badge&logo=kde)
  ![Kitty](https://img.shields.io/badge/Terminal-Kitty-green?style=for-the-badge&logo=gnometerminal)
</div>

<br>

<div align="center">
  <img width="1920" height="1080" alt="Captura_de_tela_20260613_090110" src="https://github.com/user-attachments/assets/c86977ae-0725-4f06-b8b0-2b45af3b891c" />
</div>

<br>

## Visão Geral

Este repositório contém os meus *dotfiles*, organizados para facilitar a replicação do meu ambiente de desenvolvimento e uso diário. A filosofia aqui é manter um sistema bonito, rápido e focado em produtividade usando as tecnologias nativas do KDE.

## Especificações

| Componente | Ferramenta | Detalhes |
| :--- | :--- | :--- |
| **OS** | Nobara Linux 44 | Focado em performance e jogos |
| **Ambiente (DE)** | KDE Plasma | Moderno e altamente customizável |
| **Gerenciador de Janelas** | [KWin](https://github.com/KDE/kwin) | Comportamento padrão e atalhos globais |
| **Terminal** | [Kitty](https://github.com/kovidgoyal/kitty) | Acelerado por GPU e extremamente rápido |
| **Shell** | Bash | + [Starship Prompt](https://github.com/starship/starship) para um visual limpo |
| **Tema do Sistema** | [Orchis](https://github.com/vinceliuice/Orchis-theme) | Tema GTK/Qt elegante e arredondado |
| **Informações (Fetch)** | [Fastfetch](https://github.com/fastfetch-cli/fastfetch) | Arte customizada (Reze - Chainsaw Man) |
| **Extras** | [Pokeget](https://github.com/talwat/pokeget-rs), [CMatrix](https://github.com/abishekvashok/cmatrix), [Btop](https://github.com/aristocratos/btop), [Cava](https://github.com/karlstav/cava) | Ferramentas visuais e de monitoramento |

  <img width="1920" height="1080" alt="Captura_de_tela_20260728_170843" src="https://github.com/user-attachments/assets/15dd805f-4b3d-4263-8dfc-63536dad316f" />
  
  ```
  pokeget
  ```

  <img width="1920" height="1080" alt="Captura_de_tela_20260613_081828" src="https://github.com/user-attachments/assets/c6287a65-d7c0-48a3-821a-eed1a9aca2c7"/>
  
```
cmatrix
aphex (customizado por mim)
cava
btop
fastfetch
```
  

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
 ┣ 🖼️ wallpaper.png   # Wallpaper do Showcase
 ┗ 📜 README.md       # Este arquivo
```
--- 
#### Agradecimentos Especiais:

[Akiakane (秋赤音)](https://x.com/_akiakane) pelo wallpaper, baixado via [Gruvbox-Wallpapers](https://gruvbox-wallpapers.pages.dev/), confira também o [projeto de esquemas de cores para Vim](https://github.com/morhetz/gruvbox) deles 😸
