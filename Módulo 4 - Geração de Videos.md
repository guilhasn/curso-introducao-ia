# Formação — Geração de Vídeo com Inteligência Artificial (IA)

**Formato:** Sessão teórico-prática, com exemplos e exercícios  
**Público:** Profissionais de marketing, criadores de conteúdo, entusiastas de IA  
**Pré-requisitos:** Conta Google, acesso à internet, curiosidade!

---

## Sumário

1. [Introdução à Geração de Vídeos com IA](#1-introdução-à-ia-para-vídeo)
2. [Teoria e Técnicas de Prompting para Vídeo](#2-teoria-e-técnicas-de-prompting)
3. [Geração de Vídeos com Hugging Face](#3-hugging-face)
4. [Geração de Vídeos com Sora (OpenAI)](#4-sora-openai)
5. [Alternativas Gratuitas: Pika Labs, Kaiber, RunwayML](#5-ferramentas-gratuitas)
6. [Stable Video Diffusion & Open Source](#6-stable-video-diffusion)
7. [Exercício Final e Discussão](#7-exercício-final)
8. [Q&A e Fecho](#8-q&a-e-fecho)

---

## 1. Introdução à IA para Vídeo

### Objetivos
- Compreender o que é IA generativa para vídeo
- Tipos de IA para vídeo: texto-para-vídeo, imagem-para-vídeo, vídeo-para-vídeo

### Teoria

A IA generativa de vídeo utiliza modelos de deep learning para criar, transformar ou estender conteúdos visuais animados. As abordagens mais populares hoje incluem:
- **Texto para Vídeo** (ex: "Um dragão voando sobre uma cidade medieval")
- **Imagem para Vídeo** (ex: animar um quadro)
- **Vídeo para Vídeo** (ex: transformar estilo visual de um vídeo)

### Exemplos de uso
- Criação de vídeos para marketing
- Storyboards animados
- Prototipagem rápida para cinema ou publicidade

---

## 2. Teoria e Técnicas de Prompting

### Objetivos
- Aprender a criar prompts eficazes para geração de vídeo
- Evitar ambiguidades e obter resultados de alta qualidade

### Teoria

- **Prompting:** O processo de descrever com precisão o vídeo desejado.
- **Estrutura típica:**
  - Cenário
  - Personagem/objeto
  - Ação/movimento
  - Estilo visual
  - Duração, tipo de plano, emoção

#### Exemplos de Prompts

##### Prompts Simples:
- "Um gato a brincar com um novelo de lã."
- "A city skyline at night."

##### Prompts Detalhados:
- "Uma jovem cientista num laboratório futurista, olhando para um holograma azul, luz suave, estilo Pixar."
- "A close-up of a hummingbird drinking nectar from a bright red flower, filmed in slow motion, 4K, high detail."

##### Exemplos por Tema

**Natureza:**
- "Uma cascata tropical rodeada de vegetação exuberante, pássaros voando, neblina matinal, estilo realista."
- "A wide shot of a snow-covered forest at sunrise, with mist rolling through the trees, cinematic style."

**Ação:**
- "Um atleta a correr numa pista de atletismo, câmara lenta, pôr do sol ao fundo, inspiração motivacional."
- "A futuristic robot jumping across rooftops in a cyberpunk city, neon lights, dynamic camera movement."

**Abstrato:**
- "Formas geométricas coloridas a flutuar num fundo preto, com luzes em movimento, animação digital abstrata."
- "A swirling vortex of neon lights morphing into the shape of a human face, synthwave style."

#### Boas práticas:
- Seja específico: "A samurai in cherry blossoms" vs. "A Japanese samurai wearing traditional armor, standing among blooming cherry blossom trees, at dawn, in anime style"
- Use referências de estilo: "in the style of Pixar", "cyberpunk", "vintage film"
- Adicione ação: "walking", "flying", "dancing"
- Refira iluminação e emoção: "luz dourada", "ambiente misterioso", "tom alegre"
- Limite o tempo: (se a ferramenta permitir)

### Exercício 1 — Prompting
> Escreva 3 prompts de vídeo detalhados, para diferentes temas (natureza, ação, abstrato).  
> Partilhe no Prompt Challange: >https://app--ai-prompt-arena-7e2cd150.base44.app/

---

## 3. Hugging Face

### Objetivos
- Experimentar modelos gratuitos/demo de vídeo
- Testar prompting direto na interface web

### Demonstração

1. Aceda a: [https://huggingface.co/spaces](https://huggingface.co/spaces)
2. Pesquise por "text to video" ou use o modelo [VEO3 Free](https://huggingface.co/spaces/ginigen/VEO3-Free)
3. Experimente prompts curtos e longos.
4. Experimente outros modelos.

#### Exemplos de Prompt para Hugging Face

- "Um panda a comer bambu numa floresta densa e verdejante, com a luz do sol a atravessar as árvores, cores naturais, ambiente tranquilo."
- "Uma astronauta a caminhar lentamente na superfície de Marte, com poeira vermelha e céu escuro, estilo cinematográfico."
- "Um plano aproximado de um livro antigo a abrir-se sozinho, partículas de pó a flutuar, brilho mágico, biblioteca misteriosa, estilo fantasia."
- "O horizonte de uma cidade futurista à noite, com luzes néon, carros voadores, estilo cyberpunk."

### Exercício 2 — Hugging Face
> Gerar um vídeo de 2 a 4 segundos usando um dos modelos disponíveis no Hugging Face Spaces.  
> Partilhe o link do seu vídeo com o grupo.






# Ferramentas de IA para Vídeo e Imagem

## 1. Geradores de Vídeo

### CogVideoX
🔗 [Link](https://huggingface.co/spaces/THUDM/CogVideoX)  
📝 **Descrição**: Modelo avançado de 2B/5B parâmetros para geração de vídeos de alta qualidade  

#### Como usar:
1. Acesse o space  
2. Introduza o prompt detalhado  
3. Configure os parâmetros (50 passos, 49 frames)  
4. Aguarde a geração (pode demorar alguns minutos)  

#### Prompts sugeridos:
- "Um panda tocando guitarra numa floresta de bambu, luz solar filtrada, expressão concentrada"  
- "Criança pintando num cavalete, concentração e criatividade, ambiente acolhedor"  

---

### LTX Video Fast
🔗 [Link](https://huggingface.co/spaces/Lightricks/ltx-video-distilled)  
📝 **Descrição**: Modelo ultra-rápido que gera vídeos de 5 segundos em menos de 1 minuto  

#### Como usar:
1. Escolha entre **Text-to-Video** ou **Image-to-Video**  
2. Para Text-to-Video: insira o prompt  
3. Para Image-to-Video: carregue uma imagem + prompt  
4. Clique em "Generate"  

#### Prompts sugeridos:
- "Câmera a voar sobre montanhas nevadas, perspectiva de drone"  
- "Fogo numa lareira, chamas dançando, ambiente íntimo"  

---

## 2. Ferramentas de Animação de Imagens

### Stable Video Diffusion
🔗 [Link](https://huggingface.co/spaces/stabilityai/stable-video-diffusion-img2vid)  
📝 **Descrição**: Transforma imagens estáticas em vídeos animados (2-4 segundos)  

#### Dicas:
✅ Use imagens bem iluminadas  
❌ Evite imagens muito complexas  

---

### Live Portrait
🔗 [Link](https://huggingface.co/spaces/KwaiVGI/LivePortrait)  
📝 **Descrição**: Anima retratos usando expressões faciais de referência  

#### Aplicações:
- Animar fotos antigas  
- Criar avatares falantes  

---

## 3. Ferramentas de Edição de Vídeo

### Video Background Removal
🔗 [Link](https://huggingface.co/spaces/innova-ai/video-background-removal)  
🛠️ Funcionalidade: Remove/substitui fundos automaticamente  

### AI Video Editor
🔗 [Link](https://huggingface.co/spaces?search=Video+editor)  
✨ Edita vídeos com comandos de texto  

---

## 4. Ferramentas 3D

### InstantMesh
🔗 [Link](https://huggingface.co/spaces/TencentARC/InstantMesh)  
🕒 Cria modelos 3D em 10 segundos  

### 3D Photo Inpainting
🔗 [Link](https://huggingface.co/spaces/Epoching/3D_Photo_Inpainting)  
🖼️ Converte fotos 2D em experiências 3D  

> Dica: Para melhores resultados, use imagens com fundos limpos.






---

## 4. SORA (OpenAI)

### Objetivos
- Utilizar SORA para criar vídeos de alta qualidade
- Experimentar diferentes estilos e técnicas

### Demonstração

1. Aceda ao SORA (apenas para quem tem acesso)
2. Explore a interface:  
   - Texto para vídeo
   - Upload de imagem para animação

#### Exemplos de Prompt para SORA

- "Um carro desportivo vermelho a atravessar uma estrada costeira, ondas a rebentar nas rochas, luz dourada do final da tarde."
- "Um grupo de crianças a empinar papagaios num parque ensolarado, plano aberto, ambiente alegre, estilo Pixar."
- "Um chef a preparar sushi numa cozinha moderna, vapor a subir, ingredientes coloridos, plano aproximado detalhado, estilo japonês."
- "Uma nave espacial a voar através de um campo de asteroides, iluminação dramática, 10 segundos."

### Exercício 3 — SORA
> Crie um vídeo com SORA sobre um tema livre, aplicando pelo menos 2 técnicas de prompting aprendidas antes (ex: descrição de movimento + referência de estilo).  
> Salve o vídeo ou partilhe o link.

---

## 5. Ferramentas Gratuitas: Pika Labs, Kaiber, RunwayML

### 5.1 Pika Labs

- Acesse: [https://www.pika.art/](https://www.pika.art/)
- Crie conta (tem trial grátis)
- Experimente criar vídeo a partir de prompt de texto ou imagem

#### Exemplos de Prompt para Pika Labs

- "Um dragão a voar sobre uma aldeia medieval, chamas azuis a sair da boca, céu noturno estrelado, estilo anime."
- "A magical forest at twilight, glowing mushrooms, fog, fairy lights, fantasy style."

### 5.2 Kaiber

- Acesse: [https://kaiber.ai/](https://kaiber.ai/)
- Use o trial para criar vídeos de até 4 segundos

#### Exemplo de Prompt para Kaiber

- "A futuristic train speeding through a neon-lit tunnel, sparks flying, cyberpunk style, dynamic camera."
- "Uma borboleta a pousar numa flor, macro shot, fundo desfocado, manhã ensolarada."

### 5.3 RunwayML

- Acesse: [https://runwayml.com/](https://runwayml.com/)
- Experimente o modo "Gen-2" para texto-para-vídeo (requer registo)

#### Exemplo de Prompt para RunwayML

- "Uma bailarina a dançar num palco escuro, foco de luz, partículas douradas a rodopiar no ar, câmara lenta, atmosfera mágica."
- "Um time-lapse de nuvens a formar a silhueta de uma baleia gigante no céu, ao nascer do sol, ambiente poético."

### Exercício 4 — Ferramentas Alternativas
> Escolha UMA ferramenta acima.  
> Crie um vídeo curto (3-5s) usando um prompt personalizado.  
> Compare os resultados com colegas.

---

## 6. Stable Video Diffusion & Open Source

### Objetivos
- Entender a base open source dos modelos de vídeo
- Experimentar via interface web, sem instalar nada

### Demonstração

1. AnimateDiff-Lightning
- Link: >https://huggingface.co/spaces/ByteDance/AnimateDiff-Lightning
- Descrição: Modelo ultrarrápido que gera vídeos 10x mais rápido que o AnimateDiff original
- Como usar:
 - Acesse o link
 - Insira o prompt de texto
 - Escolha o modelo base (recomendado: epiCRealism)
 - Selecione o número de passos (recomendado: 4 passos)
 - Clique em "Generate"

2. Prompts sugeridos:

- "Uma bailarina dançando numa floresta encantada, luz suave, movimento gracioso"
- "Gato branco brincando com novelo de lã, movimentos ágeis e divertidos"
- "Ondas do mar batendo numa praia ao pôr do sol, movimento hipnótico"




---

## 7. Exercício Final

> **Desafio:**  
> Escolha uma ferramenta apresentada e crie um vídeo de 10-15 segundos, aplicando as técnicas de prompting (detalhe, ação, estilo) e, se possível, transição de cenas ou narrativa curta.  
> Apresente o resultado para o grupo, explicando suas escolhas de prompt.

#### Exemplos de Prompt Narrativo

- "Um astronauta pousa numa lua desconhecida, observa ao longe um estranho monumento alienígena, começa a caminhar até ele, poeira cósmica, ambiente misterioso, estilo Blade Runner."
- "Uma flor a desabrochar rapidamente, passa para abelhas a recolher pólen, depois para o pôr do sol sobre o campo, timelapse cinematográfico."

---

  - [Prompt Engineering Guide](https://www.promptingguide.ai/)

---

## Recursos Extras
- [Create on-brand visuals with image generation](https://www.youtube.com/watch?v=GAf0KHM4fnk&t=95s&ab_channel=OpenAI)
- [Lista de ferramentas gratuitas e trials](#)
- [Templates de Prompt para Vídeo IA](#)
- [Comunidade: Reddit r/AIArt, Discords oficiais]

---

## Dicas Extra para Prompts

- Use termos de movimento: "a voar", "a correr", "em câmara lenta", "girar", "zoom-in"
- Combine estilos: "estilo Pixar", "realista", "anime", "futurista"
- Refira o ambiente e a iluminação: "luz dourada", "céu nublado", "neon", "luz suave"
- Descreva emoções ou atmosferas: "alegre", "misterioso", "épico", "tranquilo"

---

# FIM






#  Módulo 4 - Criação de Vídeos com IA ###





Gemini VEO 3 (versão free durante 30 dias)

> https://one.google.com/about/google-ai-plans/

**Testar este Prompt:**

- Um plano cinematográfico em câmara lenta de bolachas de chocolate acabadas de sair do forno, numa cozinha acolhedora e iluminada pela luz do sol. Iluminação quente, foco suave, vapor a subir e música suave de fundo.
- Uma bolacha de chocolate gigantesca está no centro de um estádio repleto de gente, rodeada por fãs entusiasmados. A iluminação é dramática, com imagens aéreas captadas por drone, confetti a cair e pessoas a segurar cartazes que dizem "KCC" e "Bolacha do Século". A câmara move-se lentamente em volta da bolacha, ao som de uma música cinematográfica empolgante. Narração: "A história está a ser escrita — a Kevin Cookie Company revela a maior bolacha de chocolate do mundo." 

----


**Caso de Estudo: Kling AI - De Imagem Estática a Vídeo Envolvente**

*Fonte: [Create a Stunning Video from Any Image—Step by Step](https://newsletter.futurepedia.io/p/create-a-stunning-video-from-any-image-step-by-step-06-17-2025)*

**Processo Step-by-Step:**
1. **Criar conta** no Kling AI
2. **Seleccionar "Image to Video"**
3. **Escolher modelo apropriado** (v1.6 para eficiência, v2.0 para movimentos complexos)
4. **Upload de imagens** (início e fim para maior controlo)
5. **Configurar definições** (qualidade profissional, duração 5s)
6. **Criar prompts eficazes** com movimentos de câmara específicos
7. **Rever e iterar** conforme necessário

**Dicas Avançadas:**
- Usar frases como "zoom in", "pan left", "rotate around"
- Aproveitar controlo de frames para animações complexas
- Actualizar para planos VIP para vídeos mais longos sem marca d'água

**Estatísticas de Impacto:**
- 82% dos marketers dizem que vídeo aumenta tempo no site
- 87% relatam que gera mais leads que outros média

---




**https://storyteller.mootion.com/workspace/generate**



*** CapCut’s NEW AI Video Maker is INSANE (FREE!) ***
-  https://x.com/JulianGoldieSEO/status/1939126678967775458
