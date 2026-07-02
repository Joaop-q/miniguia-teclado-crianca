# Miniguia de Estudos - O Som da Luz (Teclado para Iniciantes)

## 📌 Contexto e Objetivos
Este repositório foi criado como parte de um desafio prático na plataforma DIO, utilizando a Inteligência Artificial **NotebookLM** como ferramenta de aprendizagem ativa. O objetivo principal deste projeto é estruturar e documentar um material pedagógico em quadrinhos voltado para o ensino básico de música e mapeamento de notas no teclado/piano.

---

## 🔍 Curadoria de Fontes
Para a construção do caderno temático e geração do material visual no NotebookLM, foram utilizadas as seguintes fontes de dados base:
1. Apostila Teórica de Musicalização Infantil (PDF de Domínio Público).
2. Guia Prático de Iniciação ao Piano e Teclado (Texto Técnico de Apoio).
3. Manual Prático de Anatomia Aplicada à Execução Instrumental (Mapeamento dos Dedos).

---

## ⚙️ Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

### Prompts Testados e Variações
* **Prompt 1 (Focado em Metáforas):** *"Transforme a explicação técnica sobre a localização das notas Dó e Fá no teclado em uma metáfora visual simples utilizando animais para crianças."*
  * **Resultado:** A IA gerou com sucesso as metáforas do "grupo da borboleta" (2 teclas pretas) e "grupo da lagarta" (3 teclas pretas).
* **Prompt 2 (Ajuste Pedagógico):** *"Crie uma representação de escada para explicar as notas naturais de forma ascendente."*
  * **Resultado:** Gerou a analogia perfeita de caminhar para cima em direção aos céus (Dó, Ré, Mi, Fá, Sol, Lá, Si).

### Dificuldades Encontradas ("Cicatrizes")
Durante o desenvolvimento, a IA inicialmente gerou numerações de dedos confusas para a mão esquerda. O processo de *troubleshooting* exigiu restringir o escopo do prompt especificamente para a **Mão Direita**, definindo de forma literal que o número 1 sempre corresponderá ao polegar.

---

## 📖 Miniguia de Estudo (Entrega Final)

### Resumo Estruturado do Assunto
O aprendizado inicial do teclado baseia-se no reconhecimento de padrões visuais formados pelas teclas pretas sobre as teclas brancas. O teclado é dividido em:
* **As 7 Notas Naturais:** Dó, Ré, Mi, Fá, Sol, Lá e Si, dispostas em uma ordem linear e ascendente (grave para o agudo).
* **O Padrão das Teclas Pretas:** Elas se dividem em blocos que se repetem de forma infinita: grupos de 2 teclas e grupos de 3 teclas.

### Glossário dos Principais Conceitos
* **Grupo da Borboleta:** Bloco de 2 teclas pretas juntas. Serve de referência para achar a nota **DÓ** (localizada imediatamente à esquerda deste grupo).
* **Grupo da Lagarta:** Bloco de 3 teclas pretas juntas. Serve de referência para achar a nota **FÁ** (localizada imediatamente à esquerda deste grupo).
* **Dedilhado Básico (Mão Direita):** Sistema de numeração dos dedos para execução precisa, onde:
  * 1 = Polegar
  * 2 = Indicador
  * 3 = Médio
  * 4 = Anelar
  * 5 = Mínimo
* **Posição de DÓ:** Posicionamento inicial onde o Dedo 1 (Polegar) repousa sobre a nota Dó e os demais dedos descansam sequencialmente nas teclas vizinhas (Ré, Mi, Fá, Sol).

### Prompts Reutilizáveis para Revisão
```text
- "Atue como um tutor de música e me faça 3 perguntas aleatórias para testar se sei localizar o Dó e o Fá no teclado."
- "Explique como transpor a Posição de Dó da mão direita para a mão esquerda mantendo a lógica de numeração dos dedos."

