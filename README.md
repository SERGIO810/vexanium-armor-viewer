# ⟁ Vexanium Viewer - Laboratório J.A.V.I.S.

O Visualizador 3D definitivo para texturas e entidades do mod Vexanium. Renderize, inspecione e valide suas criações de armadura e modelos 3D em tempo real, direto do seu navegador, impulsionado por **Three.js** e **skinview3d**.

---

## 🌐 Acesse o Laboratório Online

**https://sergio810.github.io/vexanium-armor-viewer/**

---

## 🌑 O que é o Vexanium?

**Vexanium** é um mod NeoForge revolucionário que introduz a **Armadura Parasita Alienígena** e a inteligência de silício **J.A.V.I.S.** — uma fusão letal de tecnologia militar avançada com matéria orgânica extraterrestre do Deep Dark.

Este laboratório web foi construído para a comunidade e desenvolvedores testarem rapidamente recursos visuais antes de implementá-los no motor do Minecraft.

---

## ✨ Recursos Exclusivos do Laboratório

Para garantir a melhor experiência de design, o nosso terminal foi equipado com tecnologia de ponta:

### 👁‍🗨 Renderização 360° em Tempo Real
Inspecione cada pixel da sua armadura ou entidade com controles de órbita fluidos e zoom de precisão.

### 🛡️ Modo Armadura (PNG)
Suporte completo para moldes padrão e HD (High Definition) de armaduras do Minecraft. Teste a **Camada 1** (Capacete, Peito, Botas) e a **Camada 2** (Calças) simultaneamente.

### 👾 Modo Entidade e Armas (GLTF/GLB)
Trouxemos a bancada do Blockbench para a web! Faça upload de modelos 3D de novas armas ou monstros e o sistema ajustará a escala e iluminação automaticamente.

### 💡 Iluminação Deep Dark Adaptativa
O modelo 3D é banhado por luzes "Osso de Warden" e recortes "Aqua Bioluminescente", simulando a atmosfera real das Ancient Cities.

### 🚀 Zero Instalação
Roda 100% no seu navegador (PC ou Mobile) sem precisar baixar nenhum software pesado.

---

## 📖 Como Usar o Visualizador

A interface foi desenhada para ser intuitiva. Escolha a sua aba de testes:

### 1️⃣ Testando Armaduras

1. Acesse a aba **"Armaduras"**
2. Clique em **Selecionar Arquivo PNG** na Camada 1 (Capacete/Peito/Botas)
3. *(Opcional)* Faça o upload da Camada 2 para as Calças
4. A armadura será vestida instantaneamente no manequim de testes

### 2️⃣ Testando Entidades ou Armas

1. Acesse a aba **"Entidades"**
2. Faça o upload do seu modelo exportado do Blockbench no formato `.gltf` ou `.glb`
3. O núcleo J.A.V.I.S. calculará o tamanho do modelo e o centralizará na câmera automaticamente

### 3️⃣ Controles

| Ação | Descrição |
|------|-----------|
| **Mouse Esquerdo** | Clique e arraste para rotacionar o modelo livremente |
| **Zoom** | Use o slider de Foco Analítico para aproximar detalhes |
| **Rotação Automática** | Ligue a chave para uma apresentação de 360 graus suave |
| **Ângulos Rápidos** | Botões predefinidos para Frente, Lado, Costas |

---

## 📐 Especificações de Textura (Armaduras)

Para que a armadura se encaixe perfeitamente no jogador, o arquivo deve seguir as regras de mapeamento UV do Minecraft:

| Especificação | Valor |
|---|---|
| **Formato** | `.PNG` (fundo transparente) |
| **Proporção** | Estritamente **2:1** (A largura deve ser o dobro da altura) |
| **Resoluções Padrão** | `64x32` pixels |
| **Resoluções HD** | `128x64`, `256x128`, `512x256`, `1024x512` |

### Estrutura de Camadas

- **Camada 1**: Capacete, Peitoral, Botas
- **Camada 2**: Calças (Leggings)

---

## 🌐 Comunidade e Conexões

Junte-se à iniciativa Vexanium. Compartilhe os seus designs de armadura, sugira ideias para o mod e interaja com os desenvolvedores:

| Plataforma | Link |
|---|---|
| 🎮 **CurseForge** | [LINK_CURSEFORGE_AQUI] |
| 💬 **Discord Oficial** | [LINK_DISCORD_AQUI] |
| 📺 **YouTube** | [LINK_YOUTUBE_AQUI] |
| 🐦 **Twitter/X** | [LINK_TWITTER_AQUI] |
| 💜 **Apoie o Projeto (Patreon)** | [LINK_PATREON_AQUI] |
| 🔗 **Site do Mod** | [LINK_WEBSITE_AQUI] |

---

## 🙏 Tecnologias e Créditos

O Laboratório J.A.V.I.S. foi construído com amor e arquitetura de código aberto:

- **Three.js** — O poderoso motor WebGL que dá vida aos modelos 3D
- **skinview3d** — Renderizador perfeito da anatomia do Minecraft
- **Vexanium Team** — Pelos conceitos e design de interface

> *"A carne alienígena é forte, mas o silício é perfeito."* — Dr. Aldrich

---

## 📝 Licença

Este projeto está sob licença **MIT**. Desenvolvido para a comunidade Minecraft.

**Atualizado em Abril de 2026**

---

## 🚀 Desenvolvimento Local

Para testar o visualizador localmente:

```bash
# 1. Clone o repositório
git clone https://github.com/seu-usuario/vexanium-armor-viewer.git
cd vexanium-armor-viewer

# 2. Abra o arquivo index.html em um navegador
# Opção A: Duplo clique no arquivo
# Opção B: Use um servidor local (recomendado)
python -m http.server 8000
# Acesse: http://localhost:8000
```

---

## 🐛 Problemas Conhecidos

- Modelos GLTF muito grandes podem causar lag em navegadores antigos
- Suporte limitado para animações em modelos 3D (versão 1.0)
- Mobile: Zoom com dois dedos pode ter latência em dispositivos de baixo desempenho

---

## 🔮 Roadmap Futuro

- [ ] Suporte para animações de modelos 3D
- [ ] Editor de cores em tempo real
- [ ] Exportação de renders como PNG/JPG
- [ ] Integração com CurseForge API
- [ ] Modo colaborativo (compartilhar designs)
- [ ] Suporte para shaders customizados

---

**Desenvolvido com ⚔️ para a comunidade Vexanium**
