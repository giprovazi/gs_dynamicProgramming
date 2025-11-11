# 🧠 Profissões do Futuro

## 👥 **Integrantes do Grupo**
- **Giovanni Romano Provazi**  
- **Vitor de Lima Domingues**

---

## 📘 Descrição do Projeto
Este projeto foi desenvolvido em **Python** com o objetivo de ordenar e gerar relatórios sobre as **profissões mais promissoras do futuro**, de acordo com seu nível de **demanda** no mercado.  

A solução utiliza o **algoritmo Merge Sort**, um método eficiente de ordenação, para organizar as profissões em ordem **decrescente de demanda**.  
O resultado é exibido no terminal e também salvo automaticamente em um arquivo **.txt** contendo todas as informações organizadas.

---

## 🎯 Objetivo
Demonstrar o uso de **estruturas de dados**, **funções**, **arquivos** e **algoritmos de ordenação** em Python, aplicando os conceitos aprendidos para resolver um problema prático e contextualizado no tema **tecnologia e mercado de trabalho do futuro**.

---

## ⚙️ Estrutura do Código

### 🔹 Lista de Profissões
A lista `profissoes` contém **25 dicionários**, cada um representando uma profissão com:
- `nome`: nome da profissão;  
- `demanda`: porcentagem de demanda no mercado (quanto maior, mais promissora);  
- `categoria`: área de atuação.

---

### 🔹 Função `ordenar_profissoes(lista)`
Ordena as profissões com base na **demanda**, utilizando o **algoritmo Merge Sort**.  
O algoritmo divide a lista em partes menores e as combina novamente de forma ordenada.

**Principais etapas:**
1. Divisão da lista em duas partes;
2. Ordenação recursiva de cada metade;
3. Junção das metades em ordem decrescente de demanda.

---

### 🔹 Função `exibir_relatorio(profissoes_ordenadas)`
Mostra o relatório formatado no terminal com:
- Nome da profissão;  
- Porcentagem de demanda.  

Serve para visualização rápida dos dados já ordenados.

---

### 🔹 Função `salvar_relatorio(profissoes_ordenadas, caminho="relatorio_profissoes.txt")`
Cria um **arquivo de texto (.txt)** contendo o relatório completo, incluindo:
- Nome da profissão;  
- Demanda (%);  
- Categoria da profissão.

O arquivo é salvo automaticamente no mesmo diretório do projeto com o nome `relatorio_profissoes.txt`.

---


## 🧠 Tecnologias Utilizadas
- **Python 3**
- Manipulação de **listas e dicionários**
- Estruturas de controle e funções
- **Algoritmo Merge Sort**
- Escrita e leitura de **arquivos de texto**
