##⟁ Vexanium Viewer - Laboratório J.A.V.I.S.

O Visualizador 3D definitivo para texturas e entidades do mod Vexanium. Renderize, inspecione e valide suas criações de armadura e modelos 3D em tempo real, direto do seu navegador, impulsionado por **Three.js** e **skinview3d**.


## 🌐 Acesse o Laboratório Online

**https://sergio810.github.io/vexanium-armor-viewer/**

---

## 🦠 O que é o Vexanium?
Vexanium é um mod NeoForge revolucionário que introduz a **Armadura Parasita Alienígena** e a inteligência de silício **J.A.V.I.S.** — uma fusão letal de tecnologia militar avançada com matéria orgânica extraterrestre do Deep Dark.

Este laboratório web foi construído para a comunidade e os desenvolvedores testarem rapidamente os recursos visuais antes de implementá-los no motor do Minecraft.

---

## 🗺️ Mapa do Laboratório (Interface Tática)

O terminal está dividido em sistemas modulares. Aqui está o que cada parte faz:

* **🖥️ Visor 3D Central:** O palco principal onde a sua `MekaSuit` (armadura) ou entidade `.gltf` é renderizada. Reage em tempo real às alterações.
* **📊 Painel de Diagnóstico (Canto Superior Direito):** Monitoriza o estado de compilação das suas texturas (Ausente, Bruta ou Compilada) e o sincronismo do Motor 3D.
* **⚙️ Barra de Controle (Inferior):**
    * `🛡️ ARMADURA` / `👾 ENTIDADE`: Alterna o motor gráfico entre visualizar uma *Skin* do Minecraft ou um modelo 3D próprio.
    * `⏸️` e `📸`: Pausa a rotação do boneco e tira um *Screenshot* limpo (com fundo transparente) do seu trabalho.
    * `📥 BASE L1` / `📥 BASE L2`: Importa texturas ou artes brutas do seu PC para o sistema.
    * `📡`, `✨`, `📊`: Ferramentas de conexão com a IA (Geração de Lore, Telemetria In-Game e Status Táticos).
    * `✂️ ESTÚDIO`: Abre o **Bloco Operatório** (Uma mesa de trabalho gigante) para recortar, escalar e montar as peças da armadura.
    * `💾 EXPORTAR`: Baixa o arquivo de textura final, perfeitamente recortado e dimensionado para o Minecraft (1024x512).

---

## 📖 Manual de Operação (Como Forjar sua Armadura)

Siga estes passos táticos para construir a sua primeira simbiose visual:

1.  **Iniciação:** Abra o Laboratório e clique em `📥 BASE L1 (C/P/B)` para enviar a sua arte base. Alternativamente, vá direto ao `✂️ ESTÚDIO` e use o botão `✨ 0. Gerar Arte Base (IA)` para que a Rede Neural crie uma textura do zero baseada no seu texto.
2.  **Limpeza:** Na mesa de trabalho do Estúdio, caso a sua imagem tenha um fundo sólido não desejado, clique em `✨ 2. Remover Fundo Inteligente`.
3.  **Fatiamento:** Use a `✂️ Varinha Mágica` ou a `📐 Seleção Manual` para isolar e extrair peças específicas da sua arte (como partes do Capacete, Peito, Botas).
4.  **Montagem UV:** Arraste e posicione as peças limpas rigorosamente para dentro da **Zona Laranja de Exportação (1024x512)**, alinhando com as guias verdes. Mantenha o `🧲 Snap Magnético` ativado para um encaixe perfeito nos pixels.
5.  **Simbiose:** Clique no botão verde `✅ Fundir Textura Final ao 3D`. A janela fechará e o manequim 3D vestirá a sua criação instantaneamente.
6.  **Empacotamento:** Se o resultado estiver assustadoramente perfeito, clique em `💾 EXPORTAR L1` na barra inferior para baixar a imagem oficial.

---

## 🧩 Como Integrar o Widget no Seu Site ou Fórum

Quer disponibilizar o terminal J.A.V.I.S. diretamente no site da sua comunidade de jogadores, num Wiki ou num fórum do mod? Criámos uma versão compacta e adaptável (`javis_widget.html`) que funciona perfeitamente de forma incorporada.

Basta copiar e colar o seguinte código HTML no seu site:

```html
<iframe
    src="[https://sergio810.github.io/vexanium-armor-viewer/javis_widget.html](https://sergio810.github.io/vexanium-armor-viewer/javis_widget.html)"
    width="100%"
    height="750px"
    style="border: 2px solid #13c9c9; border-radius: 8px; background: #030508;"
    allow="clipboard-write"
    allowfullscreen>
</iframe>
