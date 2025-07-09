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
2. Pesquise por "text to video" ou use o modelo [Stable Video Diffusion - img2vid](https://huggingface.co/spaces/stabilityai/stable-video-diffusion-img2vid)
3. Experimente prompts curtos e longos.

#### Exemplos de Prompt para Hugging Face

- "A panda eating bamboo in a lush green forest, sunlight streaming through the trees, natural colors, peaceful atmosphere."
- "Uma astronauta a caminhar lentamente na superfície de Marte, poeira vermelha, céu escuro, estilo cinematográfico."
- "A close-up of an old book opening by itself, dust particles flying, magical glow, mystical library, fantasy style."
- "A futuristic city skyline at night, neon lights, flying cars, cyberpunk style."

### Exercício 2 — Hugging Face
> Gerar um vídeo de 2 a 4 segundos usando um dos modelos disponíveis no Hugging Face Spaces.  
> Partilhe o link do seu vídeo com o grupo.

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
- "A group of children flying kites in a sunny park, wide angle, joyful mood, Pixar style."
- "A chef cooking sushi in a modern kitchen, steam rising, colorful ingredients, detailed close-up, Japanese style."
- "A spaceship flying through an asteroid belt, dramatic lighting, 10 seconds."

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
- Experimente o modo "Gen-2" para texto-para-vídeo (requer registro)

#### Exemplo de Prompt para RunwayML

- "Uma bailarina a dançar num palco escuro, foco de luz, partículas douradas a rodopiar no ar, câmara lenta, atmosfera mágica."
- "A time-lapse of clouds forming into the shape of a giant whale in the sky, sunrise, poetic mood."

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

1. Stable Video Diffusion (img2vid)  
   [https://huggingface.co/spaces/stabilityai/stable-video-diffusion-img2vid](https://huggingface.co/spaces/stabilityai/stable-video-diffusion-img2vid)
2. Upload de imagem + prompt

#### Sugestão de Imagem
- Foto de um animal, de um objeto ou de uma pessoa.

#### Exemplos de Prompt para Animar Imagem

- "O animal está a correr numa planície, sol a pôr-se, poeira no ar, animação realista."
- "The person is waving hello, gentle smile, natural background, smooth animation."
- "Uma folha a flutuar num lago calmo, reflexo das árvores, movimento suave, estilo zen."

### Exercício 5 — Stable Video Diffusion
> Faça upload de uma imagem e gere um vídeo animado com movimento natural.  
> Salve e partilhe com o grupo.

---

## 7. Exercício Final

> **Desafio:**  
> Escolha uma ferramenta apresentada e crie um vídeo de 10-15 segundos, aplicando as técnicas de prompting (detalhe, ação, estilo) e, se possível, transição de cenas ou narrativa curta.  
> Apresente o resultado para o grupo, explicando suas escolhas de prompt.

#### Exemplos de Prompt Narrativo

- "Um astronauta pousa numa lua desconhecida, observa ao longe um estranho monumento alienígena, começa a caminhar até ele, poeira cósmica, ambiente misterioso, estilo Blade Runner."
- "Uma flor a desabrochar rapidamente, passa para abelhas a recolher pólen, depois para o pôr do sol sobre o campo, timelapse cinematográfico."

---

## 8. Q&A e Fecho

- Discussão de aplicações no mercado/empresa
- Limitações e futuro da IA para vídeo
- Dicas para aprofundamento:  
  - [Awesome Text-to-Video AI](https://github.com/awesome-ai-ml/awesome-text-to-video-ai)
  - [Prompt Engineering Guide](https://www.promptingguide.ai/)

---

## Recursos Extras

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
