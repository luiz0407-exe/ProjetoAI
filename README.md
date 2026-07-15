# 🤖 Projeto AI: Agente Especialista em Linguagem C (Sistemas Embarcados)

Este projeto apresenta um agente de Inteligência Artificial especializado na linguagem de programação C, desenvolvido especificamente como parte do desafio do Bootcamp. O objetivo é apresentar AI assist responsivo, focado em precisão técnica e livre de alucinações.

Para garantir a confiabilidade das respostas, utilizei a plataforma **NotebookLM**, alimentando sua base de conhecimento com uma curadoria seletiva de conteúdos , que cobrem desde os conceitos fundamentais da linguagem até sua aplicação prática em engenharia de sistemas embarcados.

---

## 🎯 Foco do Projeto e Casos de Uso

O agente funciona como um parceiro de estudos, ideal para:
*   **Revisões Rápidas:** Entender conceitos de sintaxe e estrutura da linguagem.
*   **Exercícios Práticos:** Auxílio na resolução de problemas e testes de lógica.
*   **Garantia de Fatos:** Respostas estritamente ancoradas nas fontes fornecidas, mitigando o risco de alucinações comuns em IAs de propósito geral.

---

## 📚 Fontes de Conhecimento Utilizadas 

A base de conhecimento do agente foi construída com as seguintes referências:

*   [Conceito Histórico da Linguagem C](https://www.nokia.com/bell-labs/about/dennis-m-ritchie/chistPT.html) — Documento histórico sobre Dennis Ritchie e a criação do C.
*   [Guia Completo de Linguagem C](https://embarcados.com.br/linguagem-c-guia-completo/) — Visão geral da linguagem no portal Embarcados.
*   [Sintaxe do C (W3Schools)](https://www-w3schools-com.translate.goog/c/c_syntax.php?_x_tr_sl=en&_x_tr_tl=pt&_x_tr_hl=pt&_x_tr_pto=tc) — Detalhamento prático das regras de escrita e estrutura.
*   [Variáveis em C (W3Schools)](https://www-w3schools-com.translate.goog/c/c_variables.php?_x_tr_sl=en&_x_tr_tl=pt&_x_tr_hl=pt&_x_tr_pto=tc) — Tipagem e alocação de dados.
*   [Protocolos de Comunicação para Embarcados](https://www.totalphase.com/blog/2021/12/i2c-vs-spi-vs-uart-introduction-and-comparison-similarities-differences/) — Comparativo de arquiteturas de hardware (I2C, SPI e UART) que utilizam C como base.

---

## 🚀 Como a Tecnologia Funciona (Ancoragem RAG)

Diferente de uma IA comum que "chuta" respostas baseadas em dados genéricos da internet, este agente utiliza a arquitetura de **Geração Recuperada por Ancoragem (RAG)** proporcionada pelo NotebookLM. Isso significa que ele lê a pergunta do usuário, busca a informação correta dentro das 5 fontes de curadoria listadas acima e formula uma resposta contextualizada apenas com o que é verdade factual desses documentos.

---

## 🧠 O que aprendi com este projeto
*  Como de fato estruturar uma IA para reduzir/evitar alucinações.
*  A utilização prática de RAG para obtenção de resultados acertivos
*  Proximo desafio: utilizar o agente e testar sua capacidade , criando um mini-projeto de semáforo com arduíno

  
## 🛠️ Links rápidos do projeto 

Aproveitando os recursos de geração de formatos dinâmicos do NotebookLM, criei materiais de apoio visual para auxiliar no aprendizado:
* 🚀 [Acesse o Agente no NotebookLM](https://notebooklm.google.com/notebook/e81eb4fe-a512-4cb7-8e63-ae058c0acf68)
*   📇 [Cards Didáticos Interativos](https://notebooklm.google.com/notebook/e81eb4fe-a512-4cb7-8e63-ae058c0acf68/artifact/eeda8654-d992-400a-adf9-df6a1dc9b60c?utm_source=nlm_web_share&utm_medium=google_oo&utm_campaign=art_share_1&utm_content=&utm_smc=nlm_web_share_google_oo_art_share_1_)
*   🗺️ [Mapa Mental do Projeto](https://notebooklm.google.com/notebook/e81eb4fe-a512-4cb7-8e63-ae058c0acf68/artifact/55e74dff-eeb9-4145-a8af-4f991f1a4c91?utm_source=nlm_web_share&utm_medium=google_oo&utm_campaign=art_share_1&utm_content=&utm_smc=nlm_web_share_google_oo_art_share_1_)

