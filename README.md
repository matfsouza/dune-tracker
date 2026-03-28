# 🏜️ Dune Awakening — Tracker de Atividades

> Site para acompanhar missões e atividades do jogo **Dune: Awakening** em co-op, com sincronização em tempo real entre os jogadores.

---

## O que é isso?

Dune: Awakening é um jogo de sobrevivência e exploração no planeta deserto Arrakis. Esse tracker foi feito pra dois jogadores conseguirem organizar as tarefas da sessão juntos — quem vai fazer o quê, o que já foi feito, e deixar anotações pra próxima sessão.

**Funcionalidades:**
- ✅ Lista de missões com checkbox para marcar como concluído
- 👥 Filtro por jogador (você, companheiro, ou ambos)
- 📊 Anéis de progresso individuais e geral
- 🔄 Sincronização em tempo real — um marca, o outro vê na hora
- 📝 Campo de notas compartilhadas entre os dois jogadores
- 🔐 Senha de acesso para proteger o site de estranhos

---

## Como acessar

O site está disponível em:

```
https://matfsouza.github.io/dune-tracker
```

Ao abrir, será pedida uma **senha**. Peça ao dono do repositório.

---

## Como alterar a senha

1. Abra o arquivo `index.html`
2. Procure essa linha no início do JavaScript:
```javascript
const SENHA = 'arrakis2024';
```
3. Troque `arrakis2024` pela senha que quiser
4. Salve e faça upload do arquivo no GitHub novamente

---

## Tecnologias usadas

| Tecnologia | Para quê |
|---|---|
| HTML / CSS / JavaScript | Interface do site |
| [Supabase](https://supabase.com) | Banco de dados em tempo real (gratuito) |
| [GitHub Pages](https://pages.github.com) | Hospedagem gratuita do site |

---

## Estrutura do repositório

```
dune-tracker/
└── index.html   ← arquivo único com todo o site
```

---

*A especiaria deve fluir — Arrakis, 10191 AG*
