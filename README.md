# Desafio: Mega-Sena

Simulador da Mega-Sena com geraÃ§Ã£o de nÃºmeros sorteados.

## ðŸŽ¯ DescriÃ§Ã£o

Projeto educacional que simula o jogo da Mega-Sena, permitindo gerar apostas aleatÃ³rias, verificar acertos e calcular prÃªmios.

## ðŸ› ï¸ Tecnologias Utilizadas

- **Python 3** - Linguagem de programaÃ§Ã£o
- **Random** - GeraÃ§Ã£o de nÃºmeros aleatÃ³rios

## ðŸš€ ExecuÃ§Ã£o

`ash
# Executar o simulador
python mega_sena.py
`

## ðŸ“‹ Funcionalidades

- Gerar nÃºmeros aleatÃ³rios (1-60)
- Sortear 6 nÃºmeros
- Fazer apostas
- Verificar acertos
- Calcular prÃªmios baseado em acertos

## ðŸ’¡ Exemplo

`python
jogo = MegaSena()
numeros_sorteados = jogo.sortear()
minha_aposta = [5, 12, 23, 34, 45, 56]
acertos = jogo.verificar_acertos(minha_aposta)
`

---
