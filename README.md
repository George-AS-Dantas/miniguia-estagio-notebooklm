# 🚀 Miniguia de Estudos: Preparação para Entrevistas Bancárias (NotebookLM)

Este projeto demonstra o uso da Inteligência Artificial como uma ferramenta de aprendizagem ativa, utilizando o **NotebookLM** para a criação de um "Segundo Cérebro" focado em preparação para processos seletivos no setor financeiro.

## 🎯 Contexto e Objetivos
O objetivo deste projeto foi centralizar e sintetizar dados culturais, históricos e operacionais de três gigantes do setor financeiro (**Itaú, Bradesco e Nubank**). A ferramenta atua como um simulador de recrutadores, permitindo treinar respostas comportamentais alinhadas aos valores específicos de cada instituição.

### Objetivos de Estudo:
1. Analisar a diferença cultural entre bancos tradicionais em transformação digital e fintechs nativas.
2. Mapear palavras-chave e valores fundamentais para alinhar o discurso em entrevistas.
3. Utilizar engenharia de prompts para simular rodadas de perguntas e respostas comportamentais.

## 📚 Curadoria de Fontes
Foram selecionadas fontes textuais e audiovisuais para alimentar o NotebookLM:
* **Itaú:** Foco em Transformação Digital e "Foco no Cliente".
* **Bradesco:** Foco em Tradição, Inclusão Social e Carreira Interna.
* **Nubank:** Foco em Tech, Escala e "Ownership".
*(Links das fontes disponíveis no painel do NotebookLM)*

## 🧪 Engenharia de Prompts e "Cicatrizes"
Para extrair o melhor resultado da IA, utilizei a técnica de **Roleplay Constrained Prompting**.

* **A "Cicatriz" (Aprendizado):** Identifiquei que, inicialmente, a IA tendia a fornecer a resposta correta junto com a pergunta. Isso descaracterizava o treino.
* **A Solução:** Adicionei a restrição: *"Não me dê a resposta, faça a pergunta e aguarde eu responder"*. Essa simples alteração tornou a simulação um exercício real de entrevista.

## 📝 Miniguia de Estudo

### Tabela Comparativa de Cultura
| Banco | Foco Cultural | Termo Chave |
| :--- | :--- | :--- |
| **Itaú** | Cliente no Centro | *Ituber* |
| **Bradesco** | Inclusão e Tradição | *Carreira Interna* |
| **Nubank** | Tecnologia e Agilidade | *Ownership* |

### Biblioteca de Prompts (Reutilizáveis)
Copie e cole estes prompts no seu NotebookLM para iniciar seus treinos:

1. **Simulação Comportamental:** *"Atue como um recrutador do [NOME DO BANCO]. Faça uma pergunta de entrevista comportamental sobre [VALOR DA EMPRESA]. Não me dê a resposta, faça a pergunta e aguarde eu responder."*
2. **Resolução de Conflitos:** *"Atue como um recrutador do [NOME DO BANCO]. Apresente um cenário de conflito entre time tech e negócios. Faça uma pergunta sobre como eu resolveria isso mantendo o foco no cliente. Aguarde minha resposta."*
3. **Fit Cultural:** *"Atue como um recrutador do [NOME DO BANCO]. Pergunte por que escolhi a cultura da sua empresa para desenvolver minha carreira. Avalie se minha resposta demonstra conhecimento real dos seus pilares culturais."*

---
*Projeto desenvolvido como parte do desafio prático de Inteligência Artificial da DIO.*
