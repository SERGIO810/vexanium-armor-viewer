# 🛡️ Vexanium Armor Viewer

> **Visualizador 3D interativo de texturas de armadura para Minecraft Java Edition 1.21.1**
>
> Renderize, visualize e compartilhe suas criações de armadura em tempo real com Three.js e skinview3d.

---

## 🎮 O que é Vexanium?

Vexanium é um mod NeoForge revolucionário que introduz a **armadura Parasita Alienígena**, uma fusão de tecnologia mecha com matéria orgânica extraterrestre. A armadura oferece habilidades especiais e uma estética visual única no universo Minecraft.

Este visualizador permite que você:
- ✅ Visualize texturas de armadura em 360°
- ✅ Teste diferentes designs antes de implementar
- ✅ Compartilhe suas criações com a comunidade
- ✅ Faça upload de texturas customizadas em tempo real

---

## 🚀 Quick Start

### Usar Online (Recomendado)
Acesse diretamente: **https://sergio810.github.io/vexanium-armor-viewer/**

### Usar Localmente
1. Clone este repositório:
```bash
git clone https://github.com/SEU_USUARIO/vexanium-armor-viewer.git
cd vexanium-armor-viewer
```

2. Abra `index.html` em seu navegador:
```bash
# Windows
start index.html

# Mac
open index.html

# Linux
xdg-open index.html
```

---

## 📖 Como Usar o Visualizador

### 1. Upload de Texturas

1. **Camada 1 (Capacete, Armadura, Botas):**
   - Clique em "Upload Layer 1"
   - Selecione um arquivo PNG (1024x512 pixels)
   - A textura aparecerá no modelo em tempo real

2. **Camada 2 (Calças):**
   - Clique em "Upload Layer 2"
   - Selecione um arquivo PNG (1024x512 pixels)
   - A textura será aplicada automaticamente

### 2. Controlar o Modelo

| Ação | Controle |
|------|----------|
| **Rotação Automática** | Clique em "Auto Rotate" |
| **Rotação Manual** | Arraste com mouse |
| **Zoom** | Scroll do mouse |
| **Ângulos Rápidos** | Botões (Frente, Lado, Costas) |
| **Reset** | Clique em "Reset Camera" |

### 3. Exportar

- Clique em "Screenshot" para capturar a tela
- Use Print Screen para salvar a imagem completa

---

## 📐 Especificações de Textura

### Formato Obrigatório
- **Resolução:** 1024x512 pixels (proporção 2:1)
- **Formato:** PNG
- **Compressão:** Sem transparência (fundo sólido)

### Layer 1 (Capacete, Armadura, Botas)
```
┌─────────────────────────────────────────┐
│  Capacete  │  Armadura  │  Braços  │    │
├─────────────────────────────────────────┤
│  Botas     │  Botas     │  Botas   │    │
└─────────────────────────────────────────┘
```

### Layer 2 (Calças - Caixa Desmontada)
```
┌─────────────────────────────────────────┐
│  Frente    │  Costas    │  Lado    │    │
├─────────────────────────────────────────┤
│  Esquerda  │  Direita   │  Topo    │    │
└─────────────────────────────────────────┘
```

---

## 🎨 Exemplos de Uso

### Criar uma Armadura Customizada

1. **Design no Photoshop/GIMP:**
   - Crie uma imagem 1024x512
   - Siga o layout acima
   - Exporte como PNG

2. **Testar no Visualizador:**
   - Faça upload no site
   - Visualize em 360°
   - Ajuste cores e detalhes

3. **Implementar no Mod:**
   - Copie a textura para `src/main/resources/assets/vexanium/textures/armor/`
   - Compile o mod
   - Teste no Minecraft

---

## 🛠️ Desenvolvimento

### Estrutura do Projeto

```
vexanium-armor-viewer/
├── index.html          # Visualizador principal
├── README.md           # Este arquivo
├── .gitignore          # Configuração Git
└── assets/             # Texturas de exemplo (opcional)
    ├── layer1.png
    └── layer2.png
```

### Tecnologias Usadas

- **Three.js** - Motor 3D em WebGL
- **skinview3d** - Renderizador de skins Minecraft
- **HTML5 Canvas** - Renderização gráfica
- **Vanilla JavaScript** - Sem dependências externas

### Modificar o Visualizador

1. Clone o repositório
2. Edite `index.html`
3. Teste localmente
4. Faça commit e push

```bash
git add .
git commit -m "Descrição da mudança"
git push origin main
```

---

## 🌐 Comunidade & Links

### Conecte-se Conosco

| Plataforma | Link |
|-----------|------|
| 🎮 **CurseForge** | [LINK_CURSEFORGE_AQUI] |
| 💜 **Patreon** | [LINK_PATREON_AQUI] |
| 💬 **Discord** | [LINK_DISCORD_AQUI] |
| 🐦 **Twitter/X** | [LINK_TWITTER_AQUI] |
| 📺 **YouTube** | [LINK_YOUTUBE_AQUI] |
| 🔗 **Website** | [LINK_WEBSITE_AQUI] |

### Contribuir

Quer contribuir com novos designs ou melhorias?

1. Faça um fork deste repositório
2. Crie uma branch: `git checkout -b feature/novo-design`
3. Faça suas alterações
4. Faça commit: `git commit -m "Add novo design"`
5. Faça push: `git push origin feature/novo-design`
6. Abra um Pull Request

---

## 📊 Estatísticas

| Métrica | Valor |
|---------|-------|
| **Resolução Máxima** | 1024x512 |
| **Tempo de Carregamento** | < 1 segundo |
| **Compatibilidade** | Todos os navegadores modernos |
| **Dependências Externas** | 0 (apenas CDN) |
| **Tamanho do Arquivo** | ~50 KB |

---

## 🐛 Problemas Conhecidos

- [ ] Texturas com transparência podem não renderizar corretamente
- [ ] Alguns navegadores antigos (IE11) não suportam WebGL
- [ ] Zoom extremo pode causar clipping do modelo

**Soluções:**
- Use PNG sem transparência
- Use navegadores modernos (Chrome, Firefox, Safari, Edge)
- Use zoom moderado (1x a 3x)

---

## 📝 Licença

Este projeto está sob a licença **MIT**. Veja o arquivo `LICENSE` para detalhes.

---

## 🙏 Créditos

- **Three.js** - Comunidade de código aberto
- **skinview3d** - Renderizador Minecraft
- **Vexanium** - Seu mod incrível

---

## 📞 Suporte

Tem dúvidas ou encontrou um bug?

1. **Verifique a seção de Troubleshooting** acima
2. **Abra uma Issue** no GitHub
3. **Entre em contato** via Discord: [LINK_DISCORD_AQUI]

---

## 🎯 Roadmap

- [ ] Adicionar editor de cores integrado
- [ ] Suporte para múltiplas camadas de textura
- [ ] Comparador de designs lado-a-lado
- [ ] Exportar para formato glTF
- [ ] Integração com CurseForge API
- [ ] Modo escuro/claro

---

## 📈 Estatísticas do Projeto

![GitHub Stars](https://img.shields.io/github/stars/SEU_USUARIO/vexanium-armor-viewer?style=flat-square)
![GitHub Forks](https://img.shields.io/github/forks/SEU_USUARIO/vexanium-armor-viewer?style=flat-square)
![GitHub Issues](https://img.shields.io/github/issues/SEU_USUARIO/vexanium-armor-viewer?style=flat-square)

---

## 🎉 Agradecimentos Especiais

Obrigado a todos que testaram e contribuíram com feedback para melhorar o visualizador!

---

**Desenvolvido com ❤️ para a comunidade Minecraft**

*Última atualização: Abril 2026*
