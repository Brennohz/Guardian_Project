# Guardian

O **Guardian** é uma landing page moderna, elegante e responsiva desenvolvida para apresentar um aplicativo assistente inteligente de suporte técnico. Ele foi projetado para ajudar usuários a diagnosticar e solucionar problemas de hardware e software em seus computadores (desktops e laptops), de forma rápida, eficiente e acessível.

 **Acesse o site online:** (https://guardian-project-brennohz.web.app)

O projeto inclui uma interface rica em detalhes visuais, transições fluidas, suporte nativo a temas escuro/claro com salvamento automático de preferência e está configurado para deploy imediato com o Firebase Hosting.

---

## Funcionalidades Principais

- **Tema Escuro & Claro (Dark Mode):** Alternância dinâmica com persistência automática de preferência no navegador via `localStorage`.
- **Responsividade Total:** Layout adaptado com precisão para dispositivos móveis (Android, iOS), tablets e computadores.
- **Animações de Scroll Dinâmicas:** Utilização da API `IntersectionObserver` do JavaScript para exibir elementos de forma fluida conforme o usuário rola a página.
- **Seções Interativas:**
  - **Tabs de Serviços:** Apresentação dinâmica de serviços como Hardware, Software e Atualizações com transição animada.
  - **Fluxo de Trabalho em Vídeo:** Player interativo passo a passo exibindo vídeos curtos ilustrativos sobre o funcionamento do assistente.
  - **FAQ Acordeão (FAQ Accordion):** Seção de perguntas frequentes intuitiva com expansão suave.
  - **Carrossel de Avaliações:** Depoimentos e feedbacks de usuários com navegação lateral por botões.

---

## Tecnologias Utilizadas

- **HTML:** Estrutura semântica e acessível.
- **CSS:** Estilização customizada avançada, variáveis CSS (para suporte a temas), transições animadas e Flexbox/Grid layouts.
- **JavaScript:** Lógica e interações do DOM (carrossel, alternância de tabs, persistência de temas e observador de scroll).
- **Ícones:** Integrado com [FontAwesome 6](https://fontawesome.com/) e [Boxicons](https://boxicons.com/).
- **Firebase:** Hospedagem configurada através do Firebase Hosting.

---

## Estrutura de Pastas

```
Guardian_Project/
├── Firebase/
│   ├── public/
│   │   ├── Imagens/          # Assets de imagens e logotipos
│   │   ├── Videos/           # Vídeos explicativos curtos
│   │   ├── index.html        # Estrutura HTML principal da página
│   │   ├── Guardian.css      # Estilização completa do projeto
│   │   └── Central.js        # Lógica JS de interatividade
│   ├── .firebaserc           # Associação ao projeto default no Firebase (guardian-project-brennohz)
│   ├── firebase.json         # Diretrizes de deploy e hosting do Firebase
│   └── .gitignore
└── README.md                 # Este arquivo de documentação
```

---
