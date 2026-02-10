# Aula de Git e GitHub (3DS)

```
=========================================
	G I T   M I S S I O N   // 3 D S
	mode: collaborative
	status: ready
=========================================
```

## Instrucoes da atividade

O objetivo e praticar fluxo de trabalho com branches, commits, push e merge.

### Missao do grupo (3 alunos)

- Dev 1: responsavel por [usuarios.js](usuarios.js)
- Dev 2: responsavel por [produtos.js](produtos.js)
- Dev 3: responsavel por [pedidos.js](pedidos.js)

### Regras do jogo

- Cada um trabalha exclusivamente na sua propria branch.
- Proibido mexer no arquivo do colega.
- Finalize com push e merge no repositorio principal.

## Passo a passo sugerido

1. Crie uma branch com seu nome (ex: `dev1-usuarios`).
2. Abra somente o arquivo da sua missao e siga os comentarios de tarefa.
3. Faça commit com uma mensagem clara (ex: `Atualiza usuarios`).
4. Faça push da sua branch.
5. Abra um Pull Request e faça o merge na branch principal.

## Dicas

- Edite apenas os dados no arquivo indicado.
- Mantenha os campos no formato de string para facilitar a leitura.
- Se houver conflito, converse com o grupo antes de resolver.

## Console rapido

```bash
# crie sua branch
git checkout -b devX-sua-missao

# edite somente seu arquivo
git status

# commit e push
git add .
git commit -m "Atualiza minha parte"
git push -u origin devX-sua-missao
```
