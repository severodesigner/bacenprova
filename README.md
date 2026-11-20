# Simulado COSIF · BACEN

App responsivo (celular e desktop), feito com React e Ant Design 5, para resolver as 5 provas do Simulado COSIF no estilo FGV (1.750 questões).

- Tela de boas-vindas
- Escolha da prova, dividida em blocos de até 20 questões
- Simulado aleatório que mistura as questões, com filtro por prova e por tema
- Correção imediata (padrão): gabarito e comentário logo após cada resposta
- Questões V/F com marcação item a item
- Cronômetro opcional (3 min por questão), riscar alternativas e marcar para revisão
- Gabarito comentado com a página do manual e temas para revisar
- Tema claro e escuro

As questões ficam em `data/prova1.json` a `data/prova5.json`. Histórico e progresso ficam salvos só no navegador de quem usa.
