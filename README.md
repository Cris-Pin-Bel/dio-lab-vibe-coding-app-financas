# 💸 Meu Protótipo de App de Finanças Pessoais com Vibe Coding

PRD refinado no Copilot:

```txt
# Documento de Requisitos de Produto (PRD)

## Contexto
Aplicativo de Organização de Finanças Pessoais baseado em conversas.  
Objetivo: facilitar o controle financeiro sem formulários manuais ou planilhas complexas.

## Problema
Usuários desistem de controlar gastos porque os apps atuais exigem muita entrada manual e oferecem pouca personalização.  
Solução proposta: experiência de conversa com recomendações automáticas de economia.

## Público-Alvo
Pessoas que desejam iniciar a organização de suas finanças de forma prática e sem complicação, especialmente iniciantes.

## Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente transações por categoria.  
3. Definir e acompanhar metas financeiras.  
4. Visualizar relatórios simples e personalizados.  

## MVP - Entregável
- **Telas principais:**
  - Tela inicial com chat interativo.
  - Tela de metas financeiras (definição e progresso).
  - Tela de relatórios simples (gráficos básicos em HTML/CSS).
- **Recursos necessários:**
  - Parser simples em JavaScript para interpretar entradas de texto.
  - Estrutura de dados em JSON para armazenar transações e metas.
  - CSS para layout limpo e responsivo.
- **Validação inicial:**
  - Testar com usuários simulando conversas reais.
  - Avaliar clareza das respostas do “Agente Financeiro”.
  - Medir se o usuário consegue registrar gastos e visualizar relatórios sem dificuldade.

## Tom e Linguagem
- Educativo e acessível.  
- Explicações simples em português.  
- Evitar termos técnicos complexos.
```
Interações com o Copilot:
  
  Instrução:
  - Crie um App de Finanças Pessoais com base no seguinte PRD (Product Requirements Document) revisado acima.

  Copilot:
  - Vamos transformar aquele PRD revisado em um protótipo simples usando apenas HTML, CSS e JavaScript.
  - A ideia é simular a experiência de conversa, metas e relatórios de forma estática, sem backend.
  - Aqui está um exemplo de estrutura inicial que você pode copiar e colar em um arquivo index.html para começar:
    
Resumo do que o App faz:
  - Chat interativo: o usuário digita mensagens como “gastei 50 reais com comida” ou “meta economizar 200 reais”.
  - Registro simples: gastos são armazenados em memória (array) e exibidos em relatórios básicos.
  - Metas: qualquer mensagem com “meta” é registrada e exibida.
  - Agente Financeiro: responde com mensagens educativas e orientações simples.
  - Você pode expandir adicionando gráficos em CSS/JS (por exemplo, usando Canvas), ou até integrar bibliotecas leves como Chart.js para relatórios visuais.


<img width="1887" height="752" alt="image" src="https://github.com/user-attachments/assets/27c248af-77ea-4fcc-bf65-8ab4e8bbda48" />

  
Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?
  
    A eficiência da IA para entender os comandos.
  - O que não funcionou como o esperado?
    
    Tudo funcionou como esperado, não houve alucinação da IA. 
  - O que aprendeu sobre conversar com IAs?
    
    Aprendi o quanto é importante especificar a instrução para a IA, pois a resposta é feita por probabilidades dentro de um gigantesco conteúdo de informações. 

