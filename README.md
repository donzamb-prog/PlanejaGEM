# ⚜️ PlanejaGEM - Programação de Atividades Escoteiras

O **PlanejaGEM** é uma aplicação web progressiva (PWA) desenvolvida para facilitar a elaboração, organização e partilha das fichas de programação de atividades (Sede e Externa) dos chefes do **Grupo Escoteiro Memorial 350 SP**.

A aplicação funciona diretamente no navegador de qualquer dispositivo (smartphone, tablet ou computador), podendo ser instalada na ecrã principal e utilizada **100% offline**, ideal para uso em campo e acampamentos sem sinal de internet.

---

## 🚀 Funcionalidades

- 📱 **PWA e Suporte Offline:** Funciona sem ligação à internet através de *Service Worker* e pode ser instalado no Android, iOS e PC.
- 💾 **Salvamento Automático (Anti-perda):** Guarda o progresso em tempo real no dispositivo (`localStorage`). Se a aba for fechada ou o telemóvel desligar, os dados permanecem salvos.
- 💬 **Envio Formatado via WhatsApp:** Gera uma mensagem de texto limpa, organizada com emojis e tópicos, pronta para enviar ao grupo de chefia da seção.
- 📄 **Exportação em Ficheiro de Texto (.txt):** Permite descarregar a programação completa formatada diretamente para o dispositivo.
- 🔄 **Formulário Dinâmico:** 
  - Adição automática de múltiplos jogos e atividades sequenciais.
  - Campos específicos para responsável, horários, F.A.C.E.I.S, materiais e ambientação.
  - Suporte a atividades de Sede e Externas de até 3 dias (com Fogo de Conselho e Jogos Noturnos).

---

## 📁 Estrutura do Repositório

```text
planejagem/
├── index.html          # Interface principal e lógica da aplicação
├── manifest.json       # Configurações de PWA (ícone, nome e cores)
├── sw.js               # Service Worker para cache e funcionamento offline
├── logo_gem.png        # Emblema do Grupo Escoteiro Memorial 350 SP
├── logo_ueb.png        # Logótipo da União dos Escoteiros do Brasil
├── icons/              # Ícones do aplicativo para instalação
│   ├── icon-192.png
│   └── icon-512.png
├── README.md           # Documentação do projeto
└── LICENSE             # Licença de utilização
