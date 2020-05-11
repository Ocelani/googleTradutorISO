# Engenharia de Software - PUC Minas

# Unidade Educacional Praça da Liberdade

# Qualidade de Software











<center></size><font size="3">Processo de Avaliação de Software no padrão ISO-9126</center>

# **Google Tradutor**







<center></size><font size="4">Otávio Felipe Celani e Silva</center>











<center></size><font size="3">Belo Horizonte</center>

<center></size><font size="3">Abril / 2020</center>





------

[TOC]











## Introdução

### Objetivo

Esse trabalho possui o propósito de testar um software com padrões de medição de qualidade baseados nas normas ISO-14598 e ISO-9126. 

Trabalho destinado à disciplina de Qualidade de Software, ministrado pelo professor Carlos Ribas, do curso de graduação em Engenharia de Software, da Pontifícia Universidade Católica de Minas Gerais (PUC Minas).



### Produto a ser avaliado

- **Google Tradutor**
  Ferramenta de tradução de idiomas da empresa americana Google. Foi lançado em 28 de abril de 2006 com mecânica baseada em estatísticas. Foi remodelado em uma mecânica baseada em redes neurais que foi aplicada oficialmente em 15 de novembro de 2016. É gratuíto e não necessita de cadastro prévio para ser utilizado.



### Modelo de qualidade

- **ISO-9126**: Qualidade do produto de engenharia de software.

  A norma ISO-9126 define um modelo de qualidade destinado ao produto de software. Estabelece um conjunto de parâmetros que paroniza a avaliação acerca da qualidade de um software. São seis características principais separadas cada uma em um conjunto de subcaracterísticas, de acordo com a imagem abaixo:
  

  
  ![ISO-9126-geral.png](https://upload.wikimedia.org/wikipedia/commons/0/0e/ISO-9126-geral.png)





------

## Métricas

### Funcionalidade

1. **Adequação:** 
   Número de idiomas suportado em relação à concorrência.
2. **Acurácia:**
   Porcentagem de traduções corretas.
3. **Interoperabilidade:**
   Dispositivos disponíveis.
4. **Segurança:**
   Grau de esforço em segurança.


### Confiabilidade

1. **Maturidade:**
   Probabilidade de tradução bem sucedida em diversos idiomas.
2. **Tolerância a falhas:**
   Quantidade de falhas encontradas em traduções.
3. **Recuperabilidade:**
   Não aplicado.
   


### Usabilidade

1. **Inteligibilidade:**
   Grau de qualidade na compreensão do objetivo do software.

2. **Apreensibilidade:**
   Cliques para uma tarefa.
3. **Operacionalidade:**
   Número sobre o excesso de botões clicáveis.
4. **Proteção frente a erros do usuário:**
   Quantidade de correções aplicadas pelo software bem sucedidas.
5. **Estética:**
   Cores secudárias usadas.
6. **Acessibilidade:**
   Número de funcionalidades destinadas a acessibilidade.
   


### Eficiência

1. **Comportamento em relação ao tempo:**
   Tempo de resposta
2. **Utilização de recurso:**
   Grau de necessidade de recursos de hardware.
   







### Manutenibilidade

1. **Analisabilidade:**
   Grau de especificidade do sistema.
2. **Modificabilidade:**
   Quantidade de modelos de dados.
3. **Estabilidade:**
   Eficiência no processamento de uma palavra inexistente.
4. **Testabilidade:**
   Número de processos intermediários.


### Portabilidade

1. **Adaptabilidade:**
   Número de extensões de arquivos suportado.

2. **Capacidade para ser instalado:**
   Tempo até realizar a primeira ação funcional.
3. **Coexistência:**
   Poder de processamento entre o melhor e o pior browser.
4. **Capacidade para substituir:**
   Média entre adaptabilidade e capacidade de ser instalado.


### Qualidade em uso

1. **Eficácia:**
   Grau de sucesso em tradução simultânea.
2. **Produtividade:**
   Nível de capacidade de tradução.

















------



## Critério e pontuação

De acordo com cada grupo de características na norma e suas respectivas métricas relacionadas a suas subcaracterísticas, foram distribuídos os seguintes pesos para a sua pontuação final, assim como o tipo de variável aplicada.

No fim da avaliação, a pontuação de cada característica será convertida para a base 10. A seguir, serão atribuídos o seu respectivo peso. Após realizar a média de seus respectivos valores, a pontuação final será um valor entre **1** e **100**.

Valores sobre a conclusão:

- Péssimo: **Menor ou igual a 20.**
- Muito ruim: **Valor entre 20 e 40.**
- Ruim: **Valor entre 40 e 60.**
- Bom: **Valor entre 60 e 80**
- Muito Bom: **Valor acima de 80**.

### Funcionalidade

| **ID** | **Sub-Característica** | **Métrica**             | **Tipo**    | **Critério de amostra** | **Peso** |
| ------ | ---------------------- | ----------------------- | ----------- | ----------------------- | -------- |
| 1      | Adequação*             | Idiomas suportado*      | Valor       | 1 a 10 *                | 10       |
| 2      | Acurácia               | Traduções corretas      | Porcentagem | Probabilidade           | 14       |
| 3      | Interoperabilidade     | Dispositivos            | Quantidade  | 1 a 5                   | 10       |
| 4      | Segurança**            | Esforço de investimento | Valor       | 1 a 10 **               | 6        |

- **Obs*:** Valor em relação a ferramentas concorrentes

- **Obs****: Valor em relação aos investimentos e funcionários da empresa.

  

-----

### Confiabilidade

| **ID** | **Sub-Característica** | **Métrica**                 | **Tipo**    | **Critério de amostra** | **Peso** |
| ------ | ---------------------- | --------------------------- | ----------- | ----------------------- | -------- |
| 1      | Maturidade             | Sucesso em diversos idiomas | Porcentagem | Probabilidade           | 14       |
| 2      | Tolerância a falhas    | Falhas em traduções         | Quantidade  | 1 a 10                  | 14       |

------

### Usabilidade

| **ID** | **Sub-Característica** | **Métrica**                | **Tipo**    | **Critério de amostra** | **Peso** |
| ------ | ---------------------- | -------------------------- | ----------- | ----------------------- | -------- |
| 1      | Inteligibilidade       | Compreensão do software    | Porcentagem | Probabilidade           | 10       |
| 2      | Apreensibilidade       | Cliques para uma tarefa    | Porcentagem | Probabilidade           | 10       |
| 3      | Operacionalidade       | Botões clicáveis           | Quantidade  | 1 a 10                  | 10       |
| 4      | Proteção de entrada    | Correções com sucesso      | Porcentagem | Probabilidade           | 14       |
| 5      | Estética               | Cores secudárias usadas    | Quantidade  | 1 a 10                  | 10       |
| 6      | Acessibilidade         | Funcionalidades atribuídas | Quantidade  | 1 a 5                   | 10       |

-----

### Eficiência

| **ID** | **Sub-Característica** | **Métrica**         | **Tipo**   | **Critério de amostra** | **Peso** |
| ------ | ---------------------- | ------------------- | ---------- | ----------------------- | -------- |
| 1      | Tempo de comportamento | Tempo de resposta   | Segundos   | 1 a 10                  | 6        |
| 2      | Utilização de recurso  | Memória de hardware | Quantidade | 1 Gb                    | 6        |

-----

### Manutenibilidade

| **ID** | **Sub-Característica** | **Métrica**              | **Tipo**    | **Critério de amostra** | **Peso** |
| ------ | ---------------------- | ------------------------ | ----------- | ----------------------- | -------- |
| 1      | Analisabilidade        | Complexidade do sistema  | Valor       | 1 a 5                   | 6        |
| 2      | Modificabilidade       | Modelos de dados         | Quantidade  | 1 a 10                  | 6        |
| 3      | Estabilidade           | Palavra inexistente      | Porcentagem | Probabilidade           | 6        |
| 4      | Testabilidade          | Processos intermediários | Quantidade  | 1 a 5                   | 6        |

------

### Portabilidade

| **ID** | **Sub-Característica** | **Métrica**                  | **Tipo**    | **Critério de amostra** | **Peso** |
| ------ | ---------------------- | ---------------------------- | ----------- | ----------------------- | -------- |
| 1      | Adaptabilidade         | Extensões de arquivo         | Quantidade  | 1 a 10                  | 14       |
| 2      | Instalação             | Tempo até primeira atividade | Minutos     | 1 a 10                  | 6        |
| 3      | Coexistência           | Processamento por browsers   | Porcentagem | Probabilidade           | 14       |
| 4      | Substituir             | Média                        | Valor       | Adaptab. e Aceitação    | 10       |

------

### Qualidade em uso

| **ID** | **Sub-Característica** | **Métrica**                     | **Tipo**    | **Critério de amostra** | **Peso** |
| ------ | ---------------------- | ------------------------------- | ----------- | ----------------------- | -------- |
| 1      | Eficácia               | Sucesso em tradução simultânea  | Porcentagem | Probabilidade           | 14       |
| 2      | Produtividade          | Capacidade de tradução          | Valor       | 1 a 5                   | 10       |
| 3      | Segurança              | Potencial de risco ao indivíduo | Valor       | 1 a 5                   | 10       |

-----



## Avaliação

### Funcionalidade

| **ID** | **Sub-Característica** | **Métrica**             | **Critério de amostra**  | **Peso** | RESULTADO |
| ------ | ---------------------- | ----------------------- | ------------------------ | -------- | --------- |
| 1      | Adequação*             | Idiomas suportado       | 1 a 10                   | 10       | **10** *  |
| 2      | Acurácia               | Traduções corretas      | Probabilidade            | 14       | **85%**   |
| 3      | Interoperabilidade     | Dispositivos            | 1 a 5                    | 10       | **5**     |
| 4      | Segurança **           | Esforço de investimento | Profissionais na empresa | 6        | **10** ** |



- **Obs***: Com suporte a 109 idiomas, é o software de tradução com a maior quantidade

- **Obs****: Os dados constam que a empresa possui cerca de 500 funcionários destinados somente ao setor de segurança tecnológica. Além disso, a empresa possui editais que prometem a contratação e uma premiação valiosa em dinheiro para quem conseguir invadir seus sistemas. É conhecido por ser um dos sistemas mais impenetráveis no mundo.

  ![Funcionalidade (2)](/Users/celani/Downloads/Funcionalidade (2).png)

---

### Confiabilidade

| **ID** | **Sub-Característica** | **Métrica**                 | **Critério de amostra** | **Peso** | RESULTADO |
| ------ | ---------------------- | --------------------------- | ----------------------- | -------- | --------- |
| 1      | Maturidade             | Sucesso em diversos idiomas | Probabilidade           | 14       | **50%**   |
| 2      | Tolerância a falhas    | Falhas em traduções         | 1 a 10                  | 14       | **9**     |

![Confiabilidade](/Users/celani/Downloads/Confiabilidade.png)

---

### Usabilidade

| **ID** | **Sub-Característica** | **Métrica**                | **Critério de amostra** | **Peso** | RESULTADO |
| ------ | ---------------------- | -------------------------- | ----------------------- | -------- | --------- |
| 1      | Inteligibilidade       | Compreensão do software    | Probabilidade           | 10       | **90%**   |
| 2      | Apreensibilidade       | Cliques para uma tarefa    | Probabilidade           | 10       | **90%**   |
| 3      | Operacionalidade       | Botões clicáveis           | 1 a 10                  | 10       | **9**     |
| 4      | Proteção de entrada    | Correções com sucesso      | Probabilidade           | 14       | **80%**   |
| 5      | Estética               | Cores secudárias usadas    | 1 a 10                  | 10       | **9**     |
| 6      | Acessibilidade         | Funcionalidades atribuídas | 1 a 5                   | 10       | **5**     |

![Usabilidade](/Users/celani/Downloads/Usabilidade.png)

----

### Eficiência

| **ID** | **Sub-Característica** | **Métrica**         | **Critério de amostra** | **Peso** | RESULTADO |
| ------ | ---------------------- | ------------------- | ----------------------- | -------- | --------- |
| 1      | Tempo de comportamento | Tempo de resposta   | 1 a 10                  | 6        | **9**     |
| 2      | Utilização de recurso  | Memória de hardware | 1 Gb                    | 6        | **9 ***   |

- **Obs*:** Aplicativo móvel ocupa aproximadamente 100 Mb. Cada idioma offline acrescenta 35 a 45 Mb.
  ![Eficiência](/Users/celani/Downloads/Eficiência.png)

-----

### Manutenibilidade

| **ID** | **Sub-Característica** | **Métrica**              | **Critério de amostra** | **Peso** | RESULTADO |
| ------ | ---------------------- | ------------------------ | ----------------------- | -------- | --------- |
| 1      | Analisabilidade        | Complexidade do sistema  | 1 a 5                   | 6        | **2 ***   |
| 2      | Modificabilidade       | Modelos de dados         | 1 a 10                  | 6        | **10**    |
| 3      | Estabilidade           | Palavra inexistente.     | Probabilidade           | 6        | **100%**  |
| 4      | Testabilidade          | Processos intermediários | 1 a 5                   | 6        | **5**     |



- **Obs*:** Por ser baseado em redes neurais, exige profissionais com alto grau de qualificação em inteligência artificial e engenharia de dados.

  ![Manutenibilidade](/Users/celani/Downloads/Manutenibilidade.png)
  
  -----

### Portabilidade

| **ID** | **Sub-Característica** | **Métrica**                  | **Critério de amostra** | **Peso** | RESULTADO |
| ------ | ---------------------- | ---------------------------- | ----------------------- | -------- | --------- |
| 1      | Adaptabilidade         | Extensões de arquivo         | 1 a 10                  | 14       | **9**     |
| 2      | Instalação             | Tempo até primeira atividade | 1 a 10                  | 10       | **9**     |
| 3      | Coexistência           | Processamento por browsers   | Probabilidade           | 14       | **80%**   |
| 4      | Substituir             | Média                        | Adaptab. e Instalação   | 10       | **9**     |

![Portabilidade](/Users/celani/Downloads/Portabilidade.png)

----

### Qualidade em uso

| **ID** | **Sub-Característica ** | **Métrica**                     | **Critério de amostra** | **Peso** | RESULTADO |
| ------ | ----------------------- | ------------------------------- | ----------------------- | -------- | --------- |
| 1      | Eficácia                | Sucesso em tradução simultânea  | Probabilidade           | 14       | **75%**   |
| 2      | Produtividade           | Capacidade de tradução          | 1 a 5                   | 10       | **3**     |
| 3      | Segurança               | Potencial de risco ao indivíduo | 1 a 5                   | 10       | **3**     |

![Qualidade em uso (1)](/Users/celani/Downloads/Qualidade em uso (1).png)

## Resultado

| Grupo            | Nota média |
| ---------------- | ---------- |
| Funcionalidade   | 9,625      |
| Confiabilidade   | 7          |
| Usabilidade      | 9          |
| Eficiência       | 9          |
| Manutenibilidade | 8,5        |
| Portabilidade    | 8,75       |
| Qualidade em uso | 6,5        |

- **Peso 10**
78 . 10 = 780
  
- **Peso 14**
  46,5 . 14 = 651

- **Peso 6**
  52 . 6 = 312

- **TOTAL**(média final)

  **83 Pontos**

![chart](/Users/celani/Downloads/chart.png)

## **Conclusão**

O software do Google Tradutor recebeu a pontuação de **83 pontos**. De acordo com o nivelamento anterior, a nota confere como um software **muito bom**. As avaliações realizadas nesse estudo, buscam o padrão da normaa **ISO-9126**.

## Outros dados

Os dados a seguir possuem proveniência direta da empresa Google, entre os anos de 2016 e 2019.



### Curiosidades

- Traduz 30 trilhões de sentenças por ano em 103 idiomas. (2019)
- Em 2016, traduziu mais de 100 bilhões de palavras por dia.
- Tem suporte a 59 idiomas offline.
- Tradução simultânea com suporte a 32 idiomas
- Mais de 500 milhões de usuários.
- O Brasil é o país com maior número de usuários.
- 8% das traduções são provenientes dos EUA.
- As traduções mais comuns são entre os idiomas: Inglês, Espanhol, Árabe, Russo, Português e Indonésio.
- Mais de 100 bilhões de palavras traduzidas por dia.
- Algumas traduções podem ocorrer por volta de 25% dos casos totais.
- 3.5 milhões de pessoas já realizaram 90 milhões de contribuições diretas.
- Usuários do Chrome traduzem mais de 150 milhões de páginas da internet por dia.
- Metade das páginas da internet global são em inglês, mas menos de 15% da população mundial fala o idioma.
- O grau de eficiência na tradução simultânea ocorre em 55% a 85% do casos, do qual a interpretação do inglês é mais eficiente.
- Possui API para auxiliar desenvolvedores a traduzir seus aplicativos e sites.



## Referências

Google: Blog

[Google]: blog.google	"Blog do Google"

Wikipedia

[ISO]: https://www.iso.org/home.html	"ISO"

