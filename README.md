# Sanke-Bet
🐍 Snake Casino Engine  Um jogo de Snake reinventado com mecânicas inspiradas em cassinos modernos, combinando IA adaptativa, manipulação de tensão emocional e sistemas dinâmicos de recompensa.  🎰 Não é apenas um jogo — é um sistema de experiência projetado para engajar.
🧠 Conceito

Este projeto transforma o clássico Snake em um sistema avançado com:

IA que simula comportamento "quase humano"
Sistema de "quase vitória" (near-miss)
Curva de tensão dinâmica (early → clutch)
Mecânicas inspiradas em jogos de cassino
Ajuste automático baseado no comportamento do jogador
🎮 Principais Mecânicas
🐍 Movimento Inteligente (IA)

A cobra não se move aleatoriamente — ela:

Avalia risco (paredes e corpo)
Prioriza frutas próximas
Evita colisões de forma dinâmica
Possui variação comportamental (parece "viva")
🎰 Sistema de Tensão (Cassino Feel)

O jogo controla a experiência emocional:

Near Miss (Quase ganhar)
→ A fruta aparece estrategicamente próxima
Slow Motion Dinâmico
→ Ativado em momentos críticos
Eventos visuais
🍎 QUASE PEGOU!
💥 efeitos de impacto
✨ pulsação de recompensa
📈 Sistema de Sorte Dinâmica
luckState (0 → 1)
Aumenta quando o jogador está perdendo
Diminui quando está ganhando muito
Influencia:
spawn de frutas
decisões da IA
frequência de bônus
📊 Perfil do Jogador (Auto-Adaptação)

O jogo aprende com cada partida:

playerProfile = {
  skill,
  aggression,
  consistency
}

Com base nisso:

Jogadores iniciantes recebem ajuda
Jogadores avançados enfrentam maior dificuldade
Sistema ajusta dificuldade em tempo real
⏱️ Sistema de Tempo
Tempo base da partida
Ao comer fruta:
relógio retrocede (ganho indireto)
A cobra nunca para
A partida termina apenas quando o tempo acaba
💰 Sistema de Multiplicador
Combos aumentam o multiplicador
Bônus aparecem com maior frequência em apostas altas
Balanceamento automático evita quebra do jogo
🧩 Arquitetura

O projeto é dividido em:

Game Loop (lógica) → movimento da cobra
Render Loop (visual) → animações suaves (FPS independente)
IA Engine → decisões da cobra
Event System → efeitos e feedback
Adaptive System → comportamento dinâmico
⚙️ Tecnologias
HTML5
CSS3 (animações e efeitos)
JavaScript Vanilla (sem frameworks)
💡 Diferenciais

✔ Sistema de IA leve, mas altamente eficiente
✔ Mecânicas psicológicas de retenção
✔ Experiência dinâmica a cada partida
✔ Arquitetura desacoplada (lógica vs render)
✔ Projeto ideal para portfólio de jogos / frontend avançado

🎯 Objetivo do Projeto

Este projeto foi desenvolvido com foco em:

Demonstrar domínio em JavaScript
Criar sistemas interativos complexos
Aplicar conceitos de game design moderno
Simular mecânicas reais de retenção utilizadas em jogos comerciais
🚧 Possíveis melhorias
🔊 Sistema de áudio dinâmico
🎥 Efeitos de câmera (zoom / shake)
🧠 IA com aprendizado contínuo
🎰 Sistema de jackpot raro
🌐 Backend para ranking online
