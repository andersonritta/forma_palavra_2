# forma_palavra_2
Repositório do Grupo Forma Palavra 2 - 2024/2

# Especificação para Log de Dados do Jogo Letra Mania

**Grupo: 6**  
**Responsáveis:** Bianca Beppler, Gabriel Moura, Luis Eduardo Rasch, Pâmela Braga e Renan Pinho

--- Arquivo CSV salvo em: "/storage/emulated/0/Download"

## 1. Dados da Sessão
- **ID:** Código único para cada sessão.
- **Completo?:** Indica se a sessão foi concluída.
- **Horário de Início:** Registro de início da sessão.
- **Horário de Término:** Registro de término da sessão.
- **Tempo de Partida (s):** Tempo total da sessão em segundos.

---

## 2. Marcadores de Interação (Dados do Log do Jogo)

### 2.1. Interações com a Interface
- **Total de Letras Selecionadas:** Número total de letras escolhidas.
- **Acertos:** Número total de letras corretamente posicionadas.
- **Erros:** Número total de erros.
- **Erros de Escolha:** Quantidade de vezes que uma letra incorreta foi escolhida.
- **Erros de Posição:** Quantidade de vezes que uma letra foi colocada em uma posição errada.
- **Erro em Área Inválida:** Tentativa de selecionar uma área não interativa.

### 2.2. Tempo e Desempenho
- **Tempo de Ociosidade Total (s):** Período sem interação durante toda a sessão.
- **Pontuação Total:** Pontos acumulados na sessão.

### 2.3. Dados por Fase
#### **Fase 1:**
- **Tempo f1 (s):** Tempo gasto na fase 1.
- **Tempo de Ociosidade f1 (s):** Tempo de inatividade na fase 1.
- **Acertos f1:** Número de acertos na fase 1.
- **Erros f1:** Número de erros na fase 1.
- **Erros de Escolha f1:** Erros de seleção na fase 1.
- **Erros de Posição f1:** Erros de posicionamento na fase 1.
- **Pontos f1:** Pontuação obtida na fase 1.

#### **Fase 2:**
- **Tempo f2 (s):** Tempo gasto na fase 2.
- **Tempo de Ociosidade f2 (s):** Tempo de inatividade na fase 2.
- **Acertos f2:** Número de acertos na fase 2.
- **Erros f2:** Número de erros na fase 2.
- **Erros de Escolha f2:** Erros de seleção na fase 2.
- **Erros de Posição f2:** Erros de posicionamento na fase 2.
- **Pontos f2:** Pontuação obtida na fase 2.

#### **Fase 3:**
- **Tempo f3 (s):** Tempo gasto na fase 3.
- **Tempo de Ociosidade f3 (s):** Tempo de inatividade na fase 3.
- **Acertos f3:** Número de acertos na fase 3.
- **Erros f3:** Número de erros na fase 3.
- **Erros de Escolha f3:** Erros de seleção na fase 3.
- **Erros de Posição f3:** Erros de posicionamento na fase 3.
- **Pontos f3:** Pontuação obtida na fase 3.

### 2.4. Métricas Gerais
- **Tempo Médio por Letra (s):** Tempo gasto, em média, para selecionar cada letra.
- **Tempo Médio por Acerto (s):** Tempo gasto, em média, para acertar uma letra.


