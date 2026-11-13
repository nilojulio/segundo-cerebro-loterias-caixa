# Segundo Cérebro: Loterias da CAIXA

Notebook especialista criado no **Gemini Notebook (antigo NotebookLM)** como parte do desafio da DIO "Segundo Cérebro com IA".

## 🎯 Tema e objetivo

> Criar um segundo cérebro que explique as modalidades das loterias da CAIXA, suas regras e o funcionamento das apostas, com base apenas em fontes selecionadas e verificadas.

## 📚 Fontes utilizadas

Adicionei as fontes uma a uma e abri cada uma delas para conferir o texto importado. Eliminei as que trouxeram só aviso de cookies, menus ou tela de login, e também as que fugiam do tema (vídeos sobre a própria ferramenta, por exemplo).

| Fonte | Formato | Por que confio |
|---|---|---|
| Loterias — Ministério da Fazenda | Site | Órgão federal responsável pela regulamentação das loterias |
| Loterias Online CAIXA | Site | Canal oficial da CAIXA, operadora das loterias federais |
| Loterias Mobile CAIXA | Site | Canal oficial da CAIXA |
| TechTudo | Site | Portal de tecnologia conhecido, com conteúdo explicativo sobre os jogos e as apostas online |
| COLOGA | Site | Baixei, usei e testei na prática. Achei muito útil e é a base para a próxima etapa do projeto |

**Critério de seleção:** priorizar fontes oficiais (CAIXA e governo federal) e manter só as que trouxeram conteúdo real sobre regras e modalidades depois da importação.

## 🧭 Diretriz de comportamento

```
Comporte-se como um especialista em loterias da CAIXA e na legislação brasileira sobre o tema. Responda sempre com base nas fontes do notebook, de forma clara e objetiva, citando de onde veio cada informação. Se a resposta não estiver nas fontes, diga que não encontrou em vez de inventar.
```

## 💬 Perguntas e respostas

### 1. Como funciona a aposta simples na Mega-Sena e na Lotofácil?
**Resposta:** Na Mega-Sena, o apostador escolhe 6 números entre 60 dezenas disponíveis (01 a 60) e são sorteadas 6 dezenas. Na Lotofácil, escolhe 15 números entre 25 dezenas (01 a 25) e são sorteadas 15.
**Fontes citadas:** [1] e [2], ver `prints/pergunta-1.png`

### 2. Quais são as chances de ganhar na Mega-Sena?
**Resposta:** Com base na regulamentação do Ministério da Fazenda, o notebook explicou que o jogo consiste em escolher de 6 números entre 60 dezenas (01 a 60), com 6 dezenas sorteadas por concurso, e que há prêmios por rateio para quem acerta de 4 a 6 números. Também informou que as fontes **não trazem o valor numérico da probabilidade de acerto**. Em vez de inventar um número, avisou que a informação não estava nas fontes.
**Fonte citada:** [1] Loterias — Ministério da Fazenda
**Aprendizado:** isso mostra que o notebook responde só pelo que foi selecionado. Para cobrir esse ponto, o próximo passo seria incluir o Manual de Produtos da CAIXA, que traz as tabelas de probabilidade.
**Evidência:** `prints/pergunta-2.png`

### 3. [preencher pergunta]
**Resposta:** [preencher]
**Fontes citadas:** [preencher]

## 🗂️ Materiais gerados no Estúdio

- Mapa mental: `materiais/mapa-mental.png`
- [Outro material, se gerar]

## 🔗 Notebook compartilhado

[Colar aqui o link do notebook]

## 🚀 Próximos passos

Este projeto começou como desafio da DIO, mas quero continuar com ele. Os planos para a próxima etapa são:

- Explorar mais a fundo o COLOGA, que já testei na prática, e integrar o que ele oferece ao notebook.
- Incluir o Manual de Produtos da CAIXA para cobrir as probabilidades de cada modalidade.
- Ampliar o notebook com novas fontes conforme o projeto evoluir.

## 📝 O que aprendi

- Adicionar uma fonte não significa adicionar conhecimento: várias páginas importaram só avisos de cookies e precisaram ser removidas.
- Poucas fontes bem escolhidas rendem respostas melhores do que muitas fontes sem critério.
- Quando a informação não está nas fontes, o notebook avisa em vez de inventar, e isso é o que torna as respostas confiáveis.
