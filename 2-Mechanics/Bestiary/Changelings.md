---
aliases: Changeling
Description: À medida que a corrupção que dorme sob Nerekhall desperta, ela parece se espalhar entre a população. Se os metamorfos, como são chamados, são criaturas demoníacas que duplicam e substituem civis inocentes, ou se esses civis são de alguma forma transformados nesses seres terríveis, é desconhecido. De qualquer forma, algo precisa ser feito antes que toda Nerekhall caia sob seu domínio. Esses monstros são rápidos e fortes, possuindo ataques e defesas poderosos, mas sua verdadeira ameaça reside em suas habilidades especiais e no poder que ganham através das cartas de Corrupt Citizen . Essas cartas são recebidas como recompensas por vencer uma missão e são jogadas quando um metamorfo mestre é colocado no mapa, concedendo-lhe saúde adicional, dados de defesa e outros bônus especiais.
tags:
  - monster
trait:
  - civilized
  - cursed
cover: https://static.wikia.nocookie.net/descent2e/images/1/11/Changelingartwork.jpg/revision/latest/scale-to-width-down/170?cb=20151119155318
cssclasses:
  - full-width
  - justified
---
```statblock
layout: Descent
name: Changeling
size: small
trait:
- civilized
- cursed
image: "https://static.wikia.nocookie.net/descent2e/images/1/11/Changelingartwork.jpg/revision/latest/scale-to-width-down/170?cb=20151119155318"
description: À medida que a corrupção que dorme sob [[Nerekhall]] desperta, ela parece se espalhar entre a população. Se os metamorfos, como são chamados, são criaturas demoníacas que duplicam e substituem civis inocentes, ou se esses civis são de alguma forma transformados nesses seres terríveis, é desconhecido. De qualquer forma, algo precisa ser feito antes que toda [[Nerekhall]] caia sob seu domínio. Esses monstros são rápidos e fortes, possuindo ataques e defesas poderosos, mas sua verdadeira ameaça reside em suas habilidades especiais e no poder que ganham através das cartas de [[Corrupt Citizen]]. Essas cartas são recebidas como recompensas por vencer uma missão e são jogadas quando um metamorfo mestre é colocado no mapa, concedendo-lhe saúde adicional, dados de defesa e outros bônus especiais. **The Civilian** +2 de Vida por herói, 1🟫 adicional de defesa. **The Scholar** Trocas de forma subordinadas dentro de 5 espaços adicionam 1 ◻️ à defesa e +1♥️ em cada ataque. A troca de forma mestre ganha [[Hidden]] Cada vez que este monstro for alvo de um ataque, esse ataque falha a menos que o atacante gaste 1 ⚡. **The Magistrate** +1 de Vida por herói, 1◻️ de defesa. A habilidade [[Hideous Laughter]] do mestre afeta heróis dentro de 5 espaços em vez de 3. **The Guardsman** +2 de Vida por herói, 1⬛ de defesa. O mestre ganha [[Shambling]] Este monstro não pode realizar mais de 1 ação de movimento durante um único turno. **The Executioner** +2 de Vida por herói. O mestre ganha ⚡[[Coup de Grace]] Este ataque ganha +2♥️ para cada carta ou marcador de Condição na área de jogo do alvo. **The Mage** +1 de Vida por herói, ganha o ícone de Ataque à Distância e 1🟩ataque. O mestre ganha [[Blast]] Este ataque afeta todas as figuras adjacentes ao espaço alvo. **The Siren** +2 de Vida por herói, ganha o ícone de Ataque à Distância. O mestre ganha ⚡ [[Call]] Cada monstro dentro de 3 espaços deste monstro recupera 2♥️, e cada herói dentro de 3 espaços sofre 1![Fatigue](https://static.wikia.nocookie.net/descent2e/images/b/b4/Fatigue.png/revision/latest/scale-to-width-down/10?cb=20121016005054). **The Scoundrel** +1 de Vida por herói, 1🟫 defesa e 3 pontos de movimento cada vez que é ativado. O mestre ganha [[Ravage]] Ambas as ações deste monstro em um turno podem ser ações de ataque. **The Hero** +2 de Vida por herói, 1⬛ defesa. O mestre ganha [[Corruption]] Quando este monstro realiza um ataque, escolha um herói em sua linha de visão. Em seguida, escolha uma das armas desse herói. Este monstro pode realizar o ataque usando o tipo de ataque, dados e habilidades dessa arma.
group-size:
  - 1/2/3
  - 1/1/1
  
Act1MinionStats:
  - 4
  - 4
  - ◻️🟫
  - 🟦🟥
Act1MinionSpecials:
  - name: ↗️[[Whisper]]
    desc: "Cada herói adjacente a este monstro testa ![Willpower](https://static.wikia.nocookie.net/descent2e/images/8/88/Willpower.png/revision/latest/scale-to-width-down/15?cb=20121013062622) Cada herói que falhar move 1 espaço na direção que o [[overlord]] quiser."
  - name: ⚡[[Wither]]
    desc: "O alvo sofre 1 ![Fatigue](https://static.wikia.nocookie.net/descent2e/images/b/b4/Fatigue.png/revision/latest/scale-to-width-down/10?cb=20121016005054)."
  - name: ⚡[[Bleed]]
    desc: "Se este ataque causar ao menos 1 ❤️ o alvo fica com [[bleeding]]." 
  
Act2MinionStats:
  - 4
  - 6
  - ⬛🟫
  - 🟦🟥
Act2MinionSpecials:
  - name: ↗️[[Whisper]]
    desc: "Cada herói adjacente a este monstro testa ![Willpower](https://static.wikia.nocookie.net/descent2e/images/8/88/Willpower.png/revision/latest/scale-to-width-down/15?cb=20121013062622) Cada herói que falhar move 1 espaço na direção que o [[overlord]] quiser."
  - name: ⚡[[Wither]]
    desc: "O alvo sofre 1 ![Fatigue](https://static.wikia.nocookie.net/descent2e/images/b/b4/Fatigue.png/revision/latest/scale-to-width-down/10?cb=20121016005054)."
  - name: ⚡ [[Bleed]]
    desc: "Se este ataque causar ao menos 1 ❤️ o alvo fica com [[bleeding]]." 

Act1MasterStats:
  - 4
  - 6
  - ◻️🟫
  - 🟦🟥
Act1MasterSpecials:
  - name: [[Hideous Laughter]]
    desc: "Cada herói dentro de 3 espaços desde monstro aplica -1 nos testes de ![Might](https://static.wikia.nocookie.net/descent2e/images/7/7c/Might.png/revision/latest/scale-to-width-down/11?cb=20121013062601), ![Willpower](https://static.wikia.nocookie.net/descent2e/images/8/88/Willpower.png/revision/latest/scale-to-width-down/15?cb=20121013062622), ![Knowledge](https://static.wikia.nocookie.net/descent2e/images/a/ad/Knowledge.png/revision/latest/scale-to-width-down/32?cb=20121013062540) e ![Awareness](https://static.wikia.nocookie.net/descent2e/images/f/f5/Awareness.png/revision/latest/scale-to-width-down/20?cb=20121013062510) (para um mínimo de 1 no atributo)"
  - name: ↗️[[Whisper]]
    desc: "Cada herói adjacente a este monstro testa ![Willpower](https://static.wikia.nocookie.net/descent2e/images/8/88/Willpower.png/revision/latest/scale-to-width-down/15?cb=20121013062622) Cada herói que falhar move 1 espaço na direção que o [[overlord]] quiser."
  - name: ⚡[[Wither]]
    desc: "O alvo sofre 1 ![Fatigue](https://static.wikia.nocookie.net/descent2e/images/b/b4/Fatigue.png/revision/latest/scale-to-width-down/10?cb=20121016005054)."
  - name: ⚡[[Bleed]]
    desc: "Se este ataque causar ao menos 1 ❤️ o alvo fica com [[bleeding]]."  

Act2MasterStats:
  - 4
  - 8
  - ⬛🟫
  - 🟦🟥🟨
Act2MasterSpecials:
  - name: [[Hideous Laughter]]
    desc: "Cada herói dentro de 3 espaços desde monstro aplica -1 nos testes de ![Might](https://static.wikia.nocookie.net/descent2e/images/7/7c/Might.png/revision/latest/scale-to-width-down/11?cb=20121013062601), ![Willpower](https://static.wikia.nocookie.net/descent2e/images/8/88/Willpower.png/revision/latest/scale-to-width-down/15?cb=20121013062622), ![Knowledge](https://static.wikia.nocookie.net/descent2e/images/a/ad/Knowledge.png/revision/latest/scale-to-width-down/32?cb=20121013062540) e ![Awareness](https://static.wikia.nocookie.net/descent2e/images/f/f5/Awareness.png/revision/latest/scale-to-width-down/20?cb=20121013062510) (para um mínimo de 1 no atributo)"
  - name: ↗️[[Whisper]]
    desc: "Cada herói adjacente a este monstro testa ![Willpower](https://static.wikia.nocookie.net/descent2e/images/8/88/Willpower.png/revision/latest/scale-to-width-down/15?cb=20121013062622) Cada herói que falhar move 1 espaço na direção que o [[overlord]] quiser."
  - name: ⚡[[Wither]]
    desc: "O alvo sofre 1 ![Fatigue](https://static.wikia.nocookie.net/descent2e/images/b/b4/Fatigue.png/revision/latest/scale-to-width-down/10?cb=20121016005054)."
  - name: ⚡[[Bleed]]
    desc: "Se este ataque causar ao menos 1 ❤️ o alvo fica com [[bleeding]]." 
```
