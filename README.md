⟁ Vexanium Viewer - Laboratório J.A.V.I.S.

O Visualizador 3D definitivo para texturas e entidades do mod Vexanium. Renderize, inspecione e valide suas criações de armadura e modelos 3D em tempo real, direto do seu navegador, impulsionado por Three.js e skinview3d.

🌐 Acesse o Laboratório Online

https://sergio810.github.io/vexanium-armor-viewer/

🌑 O que é o Vexanium?

Vexanium é um mod NeoForge revolucionário que introduz a Armadura Parasita Alienígena e a inteligência de silício J.A.V.I.S. — uma fusão letal de tecnologia militar avançada com matéria orgânica extraterrestre do Deep Dark.

Este laboratório web foi construído para a comunidade e desenvolvedores testarem rapidamente recursos visuais antes de implementá-los no motor do Minecraft.

✨ Recursos Exclusivos do Laboratório

Para garantir a melhor experiência de design, o nosso terminal foi equipado com tecnologia de ponta:

👁‍🗨 Renderização 360° em Tempo Real

Inspecione cada pixel da sua armadura ou entidade com controles de órbita fluidos, pausa de rotação, captura de ecrã (screenshot) e zoom de precisão.

🛡️ Modo Armadura e Estúdio UV

Suporte completo para moldes padrão e HD (High Definition). Possui um Bloco Operatório (Estúdio Livre) integrado com IA para recortar imagens, remover fundos mágicos e alinhar as peças (Snap Magnético) diretamente no navegador.

👾 Modo Entidade e Armas (GLTF/GLB)

Trouxemos a bancada do Blockbench para a web! Faça upload de modelos 3D de novas armas ou monstros e o sistema ajustará a escala e iluminação automaticamente.

📖 Manual de Operação (Forjando Armaduras)

Siga estes passos táticos para construir a sua primeira simbiose visual:

Iniciação: Abra o Laboratório e vá ao ✂️ ESTÚDIO.

Arte Base: Faça upload de uma imagem do seu PC ou use o botão ✨ 0. Gerar Arte Base (IA) para que a Rede Neural crie uma textura do zero baseada no seu texto.

Limpeza: Caso a sua imagem tenha um fundo sólido indesejado, clique em ✨ 2. Remover Fundo Inteligente.

Fatiamento: Use a ✂️ Varinha Mágica ou a 📐 Seleção Manual para isolar e extrair peças específicas (Capacete, Peito, Botas, Calças).

Montagem UV: Arraste e posicione as peças rigorosamente para dentro da Zona Laranja de Exportação (1024x512), alinhando com as guias verdes.

Simbiose: Clique no botão verde ✅ Fundir Textura Final ao 3D. O manequim vestirá a sua criação instantaneamente.

Empacotamento: Na aba principal, clique em 💾 EXPORTAR L1/L2 para baixar a imagem perfeita, ou baixe o ZIP completo no Estúdio.

🧩 Como Integrar o Widget no Seu Site ou Fórum

Quer disponibilizar o terminal J.A.V.I.S. diretamente no site da sua comunidade de jogadores, num Wiki ou num fórum do mod? Criámos uma versão compacta e adaptável.

Basta copiar e colar o seguinte código HTML no seu site:

<iframe
    src="[https://sergio810.github.io/vexanium-armor-viewer/javis_widget.html](https://sergio810.github.io/vexanium-armor-viewer/javis_widget.html)"
    width="100%"
    height="750px"
    style="border: 2px solid #13c9c9; border-radius: 8px; background: #030508;"
    allow="clipboard-write"
    allowfullscreen>
</iframe>


Nota de Segurança: O nosso sistema possui proteção anti-clone. Para que o widget funcione em domínios fora do localhost ou github.io, o desenvolvedor principal precisa de adicionar o seu site à lista de allowedDomains no código genético.

📐 Especificações de Textura (Armaduras)

Para que a armadura se encaixe perfeitamente, a zona de exportação respeita as regras rigorosas do Minecraft:

Especificação

Valor

Formato de Saída

.PNG ou pacote .ZIP com metadata.json

Proporção

Estritamente 2:1 (A largura deve ser o dobro da altura)

Resolução Exportada

1024x512 pixels (HD Scaled)

Estrutura

Camada 1: Capacete, Peitoral, Botas 



 Camada 2: Calças

🌐 Comunidade e Conexões

Junte-se à iniciativa Vexanium. Compartilhe os seus designs de armadura, sugira ideias para o mod e interaja com os desenvolvedores:

Plataforma

Link

🎮 CurseForge

[Aguardando Link]

💬 Discord Oficial

[Aguardando Link]

📺 YouTube

[Aguardando Link]

💜 Apoie o Projeto (Patreon)

[Aguardando Link]

🙏 Tecnologias e Créditos

O Laboratório J.A.V.I.S. foi construído com arquitetura de código aberto:

Three.js — O poderoso motor WebGL que dá vida aos modelos 3D

skinview3d — Renderizador perfeito da anatomia do Minecraft

OpenCV / JSZip — Motores e bibliotecas de fatiamento e compactação

Vexanium Team — Pelos conceitos e design de interface

"A carne alienígena é forte, mas o silício é perfeito." — Dr. Aldrich

🚀 Desenvolvimento Local

Para testar o visualizador localmente no seu computador:

# 1. Clone o repositório
git clone [https://github.com/seu-usuario/vexanium-armor-viewer.git](https://github.com/seu-usuario/vexanium-armor-viewer.git)
cd vexanium-armor-viewer

# 2. Abra o arquivo index.html em um navegador
# Opção A: Duplo clique no arquivo
# Opção B: Use um servidor local (recomendado)
python -m http.server 8000
# Acesse no navegador: http://localhost:8000


🔮 Roadmap Futuro

[x] Mesa de Trabalho Gigante (Full HD)

[x] Integração com IA Generativa via Base64

[x] Sistema Anti-Clone por Domínio

[ ] Suporte para animações de modelos 3D

[ ] Editor de cores em tempo real (Paleta HSL)

[ ] Integração nativa com a API do CurseForge

Desenvolvido com ⚔️ para a comunidade Vexanium
