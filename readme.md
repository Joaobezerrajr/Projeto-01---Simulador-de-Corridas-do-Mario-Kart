# 🏁 Simulador de Corrida

Este projeto é um simples **simulador de corrida** baseado em turnos, no qual dois personagens competem rolando dados e testando suas habilidades em três tipos de blocos: reta, curva e confronto. A pontuação é atribuída com base nos resultados dos dados e nas habilidades de cada personagem.

## 🚀 Funcionalidades

- Dois personagens competem (Mario e Luige) em 5 rodadas.
- Cada rodada é composta por um tipo de bloco (reta, curva ou confronto) selecionado aleatoriamente.
- Os personagens rolam um dado, e o resultado é somado à habilidade correspondente (velocidade, manobrabilidade ou poder).
- Pontos são atribuídos com base em quem tem a maior pontuação em cada rodada.
- Confrontos permitem que um personagem cause a perda de pontos do oponente.
- Após 5 rodadas, o vencedor é declarado com base no número de pontos.

## 🕹️ Como Funciona

O simulador segue as seguintes regras:

1. **Tipos de blocos**: Reta (testa a velocidade), Curva (testa a manobrabilidade), e Confronto (testa o poder).
2. **Rolagem de dados**: Cada personagem rola um dado de 6 lados.
3. **Atributos dos personagens**: 
   - Mario tem maior velocidade (4) e manobrabilidade moderada (3).
   - Luige tem maior poder (4) e manobrabilidade mais alta (4).
4. **Pontuação**:
   - Quem tiver a maior soma de rolagem + atributo ganha 1 ponto na rodada.
   - Nos confrontos, se um personagem perder, ele também perde 1 ponto.

## 🛠️ Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/simulador-corrida.git

2. Acesse o diretório do projeto:
   ```bash
   cd simulador-corrida

3. Instale as dependências (se houver):
   ```bash
   npm install

4. Execute o simulador:
   ```bash
   node index.js

Observe o progresso da corrida e o vencedor no console!


## 📄 Exemplo de Saída
```
🏁🚨 Corrida entre Mario e Luige começando... 
🏁 Rodada 1
Bloco: CURVA
Mario 🎲 rolou um dado de manobrabilidade 5 + 3 = 8
Luige 🎲 rolou um dado de manobrabilidade 4 + 4 = 8
...
Resultado final:
Mario: 2 ponto(s)
Luige: 3 ponto(s)

Luige venceu a corrida! Parabéns! 🏆🏆

