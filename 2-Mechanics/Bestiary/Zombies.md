---
aliases:
  - Zombie
Description: Criados a partir do cadáver ainda em decomposição de um homem morto, zumbis são comuns tanto como lacaios de necromantes vis quanto como efeitos colaterais infelizes de magia sombria. Todos os zumbis podem carregar doenças nocivas, e os tipos mais fortes e espertos são conhecidos por agarrar suas presas e mantê-las no lugar, esperando que a horda de movimento lento os alcance.
tags:
  - monster
trait:
  - building
  - cursed
cover: https://static.wikia.nocookie.net/descent2e/images/e/e7/Zombie.jpg/revision/latest/scale-to-width-down/160?cb=20140723014013
cssclasses:
  - full-width
  - justified
---


```statblock
layout: Descent

name: Zombie

size: small

trait:
- building
- cursed

image: "https://static.wikia.nocookie.net/descent2e/images/e/e7/Zombie.jpg/revision/latest/scale-to-width-down/160?cb=20140723014013"

description: Criados a partir do cadáver ainda em decomposição de um homem morto, zumbis são comuns tanto como lacaios de necromantes vis quanto como efeitos colaterais infelizes de magia sombria. Todos os zumbis podem carregar doenças nocivas, e os tipos mais fortes e espertos são conhecidos por agarrar suas presas e mantê-las no lugar, esperando que a horda de movimento lento os alcance.

group-size:
  - 2/2/1
  - 3/3/1
  - 4/4/1

Act1MinionStats:
  - 3
  - 3
  - 🟫
  - 🟦🟨
Act1MinionSpecials:
  - name: [[Shambling]]
    desc: "Esse monstro só pode fazer uma ação de movimento por turno."
  - name: ⚡[[Disease]]
    desc: "Se o ataque de ao menos 1♥️, o alvo está [diseased](app://obsidian.md/diseased)."
  - name: ⚡+1♥️
 
Act2MinionStats:
  - 3
  - 5
  - 🟫
  - 🟦🟨
Act2MinionSpecials:
  - name: [[Shambling]]
    desc: "Esse monstro só pode fazer uma ação de movimento por turno."
  - name: ⚡[[Disease]]
    desc: "Se o ataque de ao menos 1♥️, o alvo está [diseased](app://obsidian.md/diseased)."
  - name: ⚡+2♥️

Act1MasterStats:
  - 3
  - 6
  - 🟫
  - 🟦🟨
Act1MasterSpecials:
  - name: [[Shambling]]
    desc: "Esse monstro só pode fazer uma ação de movimento por turno."
  - name: ↗️[[Grab]]
    desc: "Escolha um herói adjacente. Esse herói deve testar ![Pasted image 20251004201351.png](app://e9b2809435cdc17d8af2692cedb31b5c7f85/C:/Users/carlo/OneDrive%20-%20PRODESP/Descent/Pasted/Pasted%20image%2020251004201351.png?1759619631235). Se falhar ele está [immobilized](app://obsidian.md/immobilized)."
  - name: ⚡[[Disease]]
    desc: "Se o ataque de ao menos 1♥️, o alvo está [diseased](app://obsidian.md/diseased)."
  - name: ⚡+1♥️ 
Act2MasterStats:
  - 3
  - 9
  - 🟫
  - 🟦🟨🟥
Act2MasterSpecials:
  - name: [[Shambling]]
    desc: "Esse monstro só pode fazer uma ação de movimento por turno."
  - name: ↗️[[Grab]]
    desc: "Escolha um herói adjacente. Esse herói deve testar ![Pasted image 20251004201351.png](app://e9b2809435cdc17d8af2692cedb31b5c7f85/C:/Users/carlo/OneDrive%20-%20PRODESP/Descent/Pasted/Pasted%20image%2020251004201351.png?1759619631235). Se falhar ele está [immobilized](app://obsidian.md/immobilized)."
  - name: ⚡[[Disease]]
    desc: "Se o ataque de ao menos 1♥️, o alvo está [diseased](app://obsidian.md/diseased)."
  - name: ⚡+2♥️   
```