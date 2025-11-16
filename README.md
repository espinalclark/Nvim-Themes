## ＮＶＩＭ  ＴＨＥＭＥＳ 

Entorno de Neovim, limpio, modular y potenciado con *Lazy.nvim*, Treesitter, LSP y todas las comodidades modernas. Este README te guía para instalarlo y entender su estructura.

---

## Instalación

Sigue estos pasos para usar esta configuración en tu sistema:

### **1️⃣ Clona el repositorio**

```bash
git clone https://github.com/espinalclark/Nvim-Themes.git ~/.config/nvim
```


### **2️⃣ Instala Neovim **

Arch Linux:

```bash
sudo pacman -S neovim
```

Debian/Ubuntu:

```bash
sudo apt install neovim
```

### **3️⃣ Instala Nerd Fonts **

```bash
sudo pacman -S nerd-fonts
```

### **4️⃣ Abre Neovim para instalar plugins automáticamente**

```bash
nvim
```

Lazy.nvim detectará los plugins y realizará la instalación.

---

## Estructura del repositorio

```
.
├── README.md
├── init.lua
├── lazy-lock.json
└── lua
    ├── config
    │   └── lazy.lua
    └── plugins
        ├── cfhelper.lua
        ├── completions.lua
        ├── gitsigns.lua
        ├── lsp-config.lua
        ├── lualine.lua
        ├── neotree.lua
        ├── none-ls.lua
        ├── telescope.lua
        ├── tokyonight.lua
        └── treesitter.lua
```

### **Explicación breve**

* **init.lua** → Punto de entrada; carga configuraciones y plugins.
* **lazy-lock.json** → Archivo generado por Lazy.nvim para versiones fijas.
* **lua/config/** → Configuración base del gestor de plugins.
* **lua/plugins/** → Módulos individuales de cada plugin (modular y limpio).

---

## Plugins destacados

* **Treesitter** → Syntax highlighting avanzado.
* **LSP + none-ls** → Autocompletado, diagnósticos y formateo.
* **Telescope** → Fuzzy finder para todo.
* **Gitsigns** → Integración con Git.
* **Neo-tree** → Explorador de archivos moderno.
* **Tokyonight** → Tema elegante y oscuro.
* **Lualine** → Barra de estado minimalista.

---

## Probando la configuración

Dentro de Neovim:

* Explorar archivos → `:Neotree`
* Buscar archivos → `<leader>ff`
* Ver diagnósticos → `:Trouble`
* Ver Git diff → signos en el gutter

---


