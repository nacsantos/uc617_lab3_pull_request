# UC00617 — Laboratório 3: Fork, Clone e _pull request_ (Frases Inspiradoras)

Este repositório serve para praticar o fluxo de colaboração no GitHub:
**fork → clone → branch → commit → push → _pull request_**.

## Objetivo
Cada aluno deve:
1. criar um **fork** deste repositório;
2. clonar o seu fork;
3. criar uma **branch**;
4. adicionar a sua **frase inspiradora** ao ficheiro `frases.md`;
5. acrescentar o **nome** na lista abaixo (neste `README.md`);
6. abrir um **\texttt{pull request}** para o repositório do formador.

## Como participar (passo a passo)
1. **Fork**
   - No GitHub, clica em **Fork** neste repositório.

2. **Clone**
   ```bash
   git clone <URL-do-teu-fork>
   cd <pasta-do-repo>
   ```

3. **Branch nova**
   ```bash
   git checkout -b add-nome-e-frase
   ```

4. **Editar**
   - Abre `frases.md` e adiciona **a tua frase** no formato:
     ```
     - "A tua frase aqui." — Teu Nome
     ```
   - Neste `README.md`, adiciona **o teu nome** na lista de participantes (abaixo).

5. **Commit**
   ```bash
   git add .
   git commit -m "Adicionei a minha frase e nome"
   ```

6. **Push**
   ```bash
   git push origin add-nome-e-frase
   ```

7. **Abrir \texttt{pull request}**
   - No GitHub, no teu fork, clica em **Compare & pull request**.
   - Escreve um título claro (ex.: *Adicionar frase — Teu Nome*) e uma breve descrição.
   - Submete o **\texttt{pull request}**.

---

## Regras simples
- Uma frase por aluno.  
- Não alteres frases de colegas.  
- Resolve conflitos caso ocorram (pede ajuda se necessário).  
- Mantém mensagens de commit claras.  

---

## Lista de participantes
> **Adiciona aqui o teu nome** quando submeteres a tua contribuição.

- [Exemplo] João Silva — _PR_ #0  
- <!-- Adiciona a tua linha abaixo seguindo o formato: -->
- Teu Nome — _PR_ #N
