# Juliano Lopes

**Engenheiro de Software, Especialista em Acessibilidade Digital e Tecnologia Assistiva**  
- Certificado internacionalmente como **Web Accessibility Specialist (WAS — IAAP)** e **NVDA Certified Expert (NV Access)**  
- Pós-graduado em **Engenharia de Software (PUC)**  
- Pós-graduado em **Desenvolvimento de Aplicações Web e Mobile (IF Sudeste MG)**

---

## Links Oficiais e Canais

- **Site Oficial e Artigos Técnicos:** [julianolopes.com.br](https://julianolopes.com.br)
- **Plataforma EAD Continue Desenvolvendo:** [continuedesenvolvendo.com.br](https://continuedesenvolvendo.com.br)
- **Certificação Internacional IAAP (WAS):** [Credencial verificada no Credly](https://www.credly.com/badges/5ef3bae1-0b88-4cd6-897c-6d1e1577b814/public_url)
- **Certificação Oficial NV Access:** [NVDA Certified Expert Directory](https://certification.nvaccess.org)
- **Canal no YouTube:** [Juliano Lopes no YouTube](https://www.youtube.com/channel/UCxWt9IBtZME208X-LFVSRZw)

---

## Principais Áreas de Domínio e Stack Tecnológica

- **Back-End, Microsserviços e Inteligência Artificial:** Python, APIs RESTful, Integração com LLMs (Google Gemini API), Google Cloud Platform (Cloud Storage, Cloud Text-to-Speech), Machine Learning (Scikit-Learn, Random Forest, Pandas, Jupyter), PHP e SQL.
- **Desenvolvimento Mobile (Nativo e Multiplataforma):** Android Nativo com **Kotlin** e **Jetpack Compose**, Java para Android, React Native e Expo.
- **Desenvolvimento Front-End e Full-Stack Web:** TypeScript, JavaScript (ES6+), React, Next.js, Angular, Node.js, HTML5 Semântico, CSS3 e WAI-ARIA.
- **Engenharia de Acessibilidade e Qualidade de Software:** Arquitetura de interfaces acessíveis (WCAG 2.1 / 2.2), inspeção de árvore semântica no Android (TalkBack), desenvolvimento de complementos (add-ons) em Python para o leitor de telas NVDA, testes automatizados (Testes Instrumentados no Android, Pytest/Unittest, Karma/Jasmine e Cypress).
- **DevOps, Gestão Ágil e Versionamento:** Docker, Docker Compose, Firebase, Scrum / Liderança Técnica, Git, GitHub e Git LFS.

---

## Projetos em Destaque (Engenharia de Software e Arquitetura)

### 1. Arquitetura de Microsserviços, Python, Docker e Inteligência Artificial

- **[DubVideos — Orquestração e Arquitetura de Microsserviços (`dub-videos-project`)](https://github.com/juliano-lopes/dub-videos-project)**  
  Sistema distribuído completo para dublagem automatizada de vídeos utilizando Inteligência Artificial, orquestrado com **Docker Compose** em rede isolada de containers:
  - **[Main DubVideos API (`main-dub-videos-api`)](https://github.com/juliano-lopes/main-dub-videos-api):** API principal em **Python** responsável pelo gerenciamento de mídia, extração/conversão de áudio e vídeo e orquestração do pipeline de dublagem.
  - **[Transcription & Translation API (`transcription-api`)](https://github.com/juliano-lopes/transcription-api):** Microsserviço em **Python** integrado ao **Google Gemini AI (`google-generativeai`)** e **Google Cloud Storage** para transcrição de áudio e tradução contextual multilíngue.
  - **[Text-to-Speech API (`text-to-speech-api`)](https://github.com/juliano-lopes/text-to-speech-api):** Microsserviço em **Python** integrado ao **Google Cloud Text-to-Speech** para síntese de voz neural sincronizada.
  - **[DubVideos Front-End (`dub-videos-front-end`)](https://github.com/juliano-lopes/dub-videos-front-end):** Interface web containerizada em Docker para envio de vídeos e consumo assíncrono das APIs.

- **[Sistema Inteligente de Classificação de Score de Crédito (`sistema-inteligente`)](https://github.com/juliano-lopes/sistema-inteligente)**  
  Solução ponta a ponta de **Machine Learning em Python**: inclui o pipeline de treinamento e avaliação do modelo preditivo (*Random Forest* com *MinMaxScaler* no Jupyter Notebook / Colab), empacotamento com **Git LFS**, **API REST em Python** com validação de schemas, suíte de **testes automatizados do modelo (`test_model.py`)** e interface web de consumo.

---

### 2. Engenharia Mobile (Kotlin / Jetpack Compose) e Tecnologia Assistiva (Python)

- **[Accessibility Engineering in Jetpack Compose (`accessibility-engineering-in-jetpack-compose`)](https://github.com/juliano-lopes/accessibility-engineering-in-jetpack-compose)**  
  Artefato de engenharia de software e pesquisa científica desenvolvido em **Kotlin** e **Jetpack Compose** (API 34+). Implementa testes instrumentados para inspeção de árvores semânticas no Android (`A11yTreeLogTest.kt`) e fluxos experimentais comparativos para remoção de barreiras semânticas na navegação com o leitor de telas **TalkBack**.

- **[Virtual Notes for NVDA (`virtual-notes-for-NVDA`)](https://github.com/juliano-lopes/virtual-notes-for-NVDA)**  
  Complemento (*add-on*) oficial em **Python** para o leitor de telas **NVDA**, voltado à produtividade com notas virtuais persistentes de texto e de voz. Conta com arquitetura de plugins globais, persistência em disco, internacionalização (`gettext` em inglês e português), automação de build com **SCons** e controle de lançamentos com *Conventional Commits* e versionamento semântico (`v1.0.0` a `v1.5.0`).

- **[Marciano App — Programação Orientada a Objetos no Android (`pos-mobile-d`)](https://github.com/juliano-lopes/pos-mobile-d)**  
  Aplicativo Android nativo desenvolvido em **Kotlin** aplicando conceitos avançados de Orientação a Objetos (herança, polimorfismo, interfaces funcionais e múltiplas *Activities*).

---

### 3. Desenvolvimento Full-Stack, Liderança Ágil e Mentoria em Git

- **[Coach4me — Plataforma Full-Stack Web, Back-End e Mobile (`pos-web-mobile-mobile-ii`)](https://github.com/juliano-lopes/pos-web-mobile-mobile-ii)**  
  Aplicação completa desenvolvida em **TypeScript** dividida em três camadas integradas:
  - **Back-End (`server/`):** API REST construída com **Node.js**, TypeScript e banco de dados **SQLite**;
  - **Web (`web/`):** Aplicação front-end construída com **React** e **Next.js**;
  - **Mobile (`mobile/`):** Aplicativo móvel multiplataforma desenvolvido com **React Native** e **Expo**.

- **[Catálogo Interativo de Acessibilidade Android em React + TypeScript (`frontend-pos-web-mobile-react-t2`)](https://github.com/juliano-lopes/frontend-pos-web-mobile-react-t2)**  
  Aplicação front-end modular em **React 19**, **TypeScript**, **Vite** e **Bootstrap**, que implementa o catálogo interativo de componentes do trabalho de conclusão *"Guia Prático para o Desenvolvimento de Aplicações Android Acessíveis com Kotlin"*.

- **[Gama News — Atuação como Scrum Master e Mentoria em Git/GitHub (`Gama-News`)](https://github.com/juliano-lopes/Gama-News)**  
  Projeto desenvolvido em equipe multidisciplinar durante processo seletivo do Itaú, no qual atuei como **Scrum Master** e líder técnico, guiando a organização ágil da equipe, o fluxo de trabalho colaborativo no Git/GitHub (branches, revisões e mais de 60 Pull Requests mesclados) e o desenvolvimento web acessível.
