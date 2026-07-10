# ⚽ Mister 11

Jogo de gestão de futebol no browser — instalável como app (PWA), funciona **100% offline**, num único ficheiro HTML, sem contas, sem anúncios.

**🎮 Jogar agora:** https://gcalvinho.github.io/mister-11/

---

## 📲 Como instalar no telemóvel

1. Abre o link acima no **Safari** (iPhone) ou **Chrome** (Android)
2. **Partilhar → Adicionar ao ecrã principal**
3. O jogo abre em ecrã completo, com o ícone próprio, e funciona sem ligação à internet — incluindo o som de estádio, que vai todo embutido na app

As carreiras ficam gravadas no próprio dispositivo (não há servidor nem contas).

---

## 🏆 O que tem o jogo

### Carreira
- **8 ligas em 7 países**, Europa e América do Sul: Liga Portugal, Liga Portugal 2, La Liga, Premier League, Ligue 1, Serie A, Brasileirão e Liga Argentina
- Taça da Liga, Taça de Portugal, Copa del Rey e apuramento para a **Liga dos Campeões**
- Confiança da direção, reputação e objetivos de época — maus resultados levam ao despedimento (com convites de outros clubes se a coisa correr bem)
- Contratos, renovações, moral do plantel e cartões acumulados
- Lesões com substituições ao vivo
- Academia de formação com jovens promissores a subir de nível a cada época

### Tática
- Onze inicial por arrastar, com zonas e *roles* específicos por posição
- Instruções de equipa (mentalidade, posse, pressão, contra-ataque) que se refletem no jogo
- Ajustes táticos ao intervalo e ao vivo

### Repetições 2.5D
- Motor de repetição de golos e lances de perigo construído de raiz em Canvas, com câmara e perspetiva próprias
- Equipas movem-se como bloco tático, com o ponta de lança sempre no ombro do último defesa
- Grandes defesas, bolas ao poste, desarmes — e contra-ataques que nascem de um desarme
- Condução de bola realista e passes rasteiros
- Som de estádio real embutido (ambiente + explosão de golo), com apito e efeitos sintetizados

### Mercado
- Janelas de transferências com propostas da IA baseadas em valor de mercado realista
- Evolução de jogadores por utilização em jogo

---

## 🛠️ Sobre o projeto

Construído em vanilla JavaScript, HTML e CSS — sem frameworks, sem dependências, sem build step além de uma minificação para produção. Alojado gratuitamente no GitHub Pages.

- `index.html` — a app pronta para produção (minificada)
- `index.src.html` — código-fonte legível, é aqui que se mexe
- `sw.js` — service worker (cache offline)

Feito com a ajuda do Claude (Anthropic).
