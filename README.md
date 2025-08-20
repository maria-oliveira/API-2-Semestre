# API 2° Semestre

## Tópicos 

:small_blue_diamond: [Descrição do projeto](#Descrição)

:small_blue_diamond: [Tecnologias Utilizadas](#Tecnologias-Utilizadas)

:small_blue_diamond: [Funcionalidades](#Funcionalidades)

:small_blue_diamond: [Backlog do Produto](#Backlog-do-Produto)

:small_blue_diamond: [Backlog da Sprint](#Backlog-da-Sprint)

:small_blue_diamond: [Burndown](#Burndown)

:small_blue_diamond: [Documentação](#Documentação)

:small_blue_diamond: [Código](#Codigo)

:small_blue_diamond: [Equipe](#Equipe)

## Descrição

> > Desenvolvimento de Aplicação de Cálculo de Sequências Lógicas. Projeto desenvolvido para trabalho acadêmico no curso de Banco de Dados na FATEC SJC.

## Tecnologias Utilizadas

- 💻 **Linguagem:** Portugol
- 🔧 **Ferramentas:**  VisuAlg, Trello, Notion, Git e GitHub
- 🗃️ **Metodologia:** Scrum

## Funcionalidades

- **Menu Principal**: Apresenta as opções de Sequências Númericas disponíveis para calculo.

- **Número Fatorial**: Apresenta o resultado de uma sequência de números naturais inteiros positivos que é calculada a partir da multiplicação de um número por todos os seus antecessores maiores que zero.
  
- **Cubos**: Apresenta o resultado do calculo do volume de um cubo, elevação do comprimento da aresta a três.
  
- **Sequência de Fibonacci**: Apresenta o resultado e o intervalo de resultado dos primeiros numeros de uma sequência em que cada número é a soma dos dois anteriores, começando por 1.

- **Sequência de Tribonacci**: Apresenta o resultado e o intervalo de resultado dos primeiros numeros de uma sequência em que cada número é a soma dos três anteriores, começando por 1.

- **Sequência de Números Primos**: Apresenta uma posição específica ou um intervalo de posições de acordo com o número digitado, um número primo é um número inteiro que pode ser dividido por 1 e por ele mesmo.

- **Quadrados Perfeitos**: Apresenta o resultado do calculo do volume de um quadrado, elevação do comprimento da aresta a dois.

- **Sequência Gemométrica**: Apresenta o resultado e o intervalo de resultado dos primeiros numeros de uma sequência a partir de um número inicial digitado, em que cada resultado é a multiplicação do termo anterior ao número digitado.

- **Sequência Alternada**: Apresenta uma posição específica ou um intervalo de posições de acordo com o número digitado, em que se mostra apenas números ímpares, com cada número variando de positivo e negativo.

- **Sequência Triangular**: Apresenta o resultado e o intervalo de resultado dos primeiros numeros de uma sequência em que cada número é resultado da seguinte fórmula: n(n+1)/2, em que n é a posição do valor a ser calculado.

 ## Backlog do Produto
 
 | Função | User Story | Prioridade | Status |
 | - | - | - | - |
 | Menu | Como usuário, gostaria de poder interagir com todas as funções do programa, sendo ele a parte principal do programa | Alta | Concluída |
 | Sequência Fibonacci | Como usuário, gostaria de ter duas formas de interagir com essa sequência: 1. Exigir o valor da posição de um número dessa sequência 2. Exigir uma lista de todos os valores de posições anteriores de uma posição desejada dessa sequência. A sequência deve seguir a seguinte regra: o valor de uma posição da sequência é igual a soma das DUAS posições anteriores, sendo que os dois primeiros valores da sequência são iguais a 1 | Alta | Concluída |
 | Números triangulares | Como usuário, gostaria de ter duas formas de interagir com essa sequência: 1. Exigir o valor da posição de um número dessa sequência 2. Exigir uma lista de todos os valores de posições anteriores de uma posição desejada dessa sequência. A sequência deve seguir a seguinte regra: o valor de uma posição da sequência é dado pela devida fórmula: Tn = n(n+1)/2, em que n é a posição do valor a ser calculado | Alta | Concluída |
 | Sequência de números primos | Como usuário, gostaria de ter duas formas de interagir com essa sequência: 1. Exigir o valor da posição de um número dessa sequência 2. Exigir uma lista de todos os valores de posições anteriores de uma posição desejada dessa sequência. A sequência deve seguir a seguinte regra: o valor de uma posição da sequência só pode ser um número em que é divisível por 1 e por ele mesmo, não havendo resto | Baixa | Concluída |
 | Números fatoriais | Como usuário, gostaria de um programa que me peça um número e, com base nele, me retornar apenas o fatorial dele | Média | Concluída |
 | Números quadrados perfeitos | Como usuário, gostaria de um programa que me peça um número e, com base nele, me retornar apenas o número escolhido elevado a DOIS | Alta  | Concluída |
 | Números cúbicos | Como usuário, gostaria de um programa que me peça um número e, com base nele, me retornar apenas o número escolhido elevado a TRÊS | Baixa |  Concluída |
 | Sequência Geométrica | Como usuário, gostaria de escolher um número e com base nele fazer a sequência com ele. Quero poder interagir de duas formas com essa sequência: 1. Exigir o valor da posição de um número dessa sequência 2. Exigir uma lista de todos os valores de posições anteriores de uma posição desejada dessa sequência. A sequência deve seguir a seguinte regra: O valor da posição é o valor da posição anterior multiplicado pelo número escolhido na primeira interação. | Baixa | Concluída |
 | Sequência alternada | Como usuário, gostaria de ter duas formas de interagir com essa sequência: 1. Exigir o valor da posição de um número dessa sequência 2. Exigir uma lista de todos os valores de posições anteriores de uma posição desejada dessa sequência. A sequência deve seguir a seguinte regra: serão exibidos apenas números ímpares, variando entre valores positivos e negativos, começando com um valor positivo | Média | Concluída |
 | Sequência Tribonacci | Como usuário, gostaria de ter duas formas de interagir com essa sequência: 1. Exigir o valor da posição de um número dessa sequência 2. Exigir uma lista de todos os valores de posições anteriores de uma posição desejada dessa sequência. A sequência deve seguir a seguinte regra: o valor de uma posição da sequência é igual a soma das TRÊS posições anteriores, sendo que os dois primeiros valores da sequência são iguais a 1 | Média | Concluída |

## Sprints

<!--Sprint 1-->
<details>
  <summary>Sprint 1</summary>
  <ul>
    <li>
      <div>
        <h2>
          Backlog
        </h2>
        <!-- Tabela -->
        <table>
          <thead>
            <tr>
              <th>Função</th>
              <th>User Story</th>
              <th>Prioridade</th>
              <th>Status</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>Menu</td>
              <td>Como usuário, gostaria de poder interagir com todas as funções do programa, sendo ele a parte principal do programa</td>
              <td>Alta</td>
              <td>Movido para a próxima Sprint</td>
            </tr>
            <tr>
              <td>Sequência Fibonacci</td>
              <td>
                Como usuário, gostaria de ter duas formas de interagir com essa sequência: 1. Exigir o valor da posição de um número dessa sequência 2. Exigir uma lista de                 todos os valores de posições anteriores de uma posição desejada dessa sequência. A sequência deve seguir a seguinte regra: o valor de uma posição da                        sequência é igual a soma das DUAS posições anteriores, sendo que os dois primeiros valores da sequência são iguais a 1
              </td>
              <td>Alta</td>
              <td>Concluída</td>
            </tr>
            <tr>
              <td>Números fatoriais</td>
              <td>Como usuário, gostaria de um programa que me peça um número e, com base nele, me retornar apenas o fatorial dele</td>
              <td>Média</td>
              <td>Concluída</td>
            </tr>
            <tr>
              <td>Números Cúbicos</td>
              <td>Como usuário, gostaria de um programa que me peça um número e, com base nele, me retornar apenas o número escolhido elevado a TRÊS</td>
              <td>Baixa</td>
              <td>Concluída</td>
            </tr>
          </tbody>
        </table>
      </div></li>
    <li>
      <h2>
        Burndown
      </h2>
      <img src= "https://github.com/user-attachments/assets/3223b677-cd2c-4bde-ad81-00c20a792f91" alt= "Captura de tela 2025-03-30 224050">
    </li>
  </ul>
</details>

<!--Sprint 2-->
<details>
  <summary>Sprint 2</summary>
  <ul>
    <li>
      <div>
        <h2>
          Backlog
        </h2>
        <!-- Tabela -->
        <table>
          <thead>
            <tr>
              <th>Função</th>
              <th>User Story</th>
              <th>Prioridade</th>
              <th>Status</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>Menu</td>
              <td>Como usuário, gostaria de poder interagir com todas as funções do programa, sendo ele a parte principal do programa</td>
              <td>Alta</td>
              <td>Em andamento</td>
            </tr>
            <tr>
              <td>Quadrados perfeitos</td>
              <td>Como usuário, gostaria de um programa que me peça um número e, com base nele, me retornar apenas o número escolhido elevado a DOIS</td>
              <td>Alta</td>
              <td>Concluída</td>
            </tr>
            <tr>
              <td>Sequência de Tribonacci</td>
              <td>
                Como usuário, gostaria de ter duas formas de interagir com essa sequência: 1. Exigir o valor da posição de um número dessa sequência 2. Exigir uma lista de                 todos os valores de posições anteriores de uma posição desejada dessa sequência. A sequência deve seguir a seguinte regra: o valor de uma posição da                        sequência é igual a soma das TRÊS posições anteriores, sendo que os dois primeiros valores da sequência são iguais a 1
              </td>
              <td>Média</td>
              <td>Concluída</td>
            </tr>
            <tr>
              <td>Sequência de números primos</td>
              <td>
                Como usuário, gostaria de ter duas formas de interagir com essa sequência: 1. Exigir o valor da posição de um número dessa sequência 2. Exigir uma lista de                 todos os valores de posições anteriores de uma posição desejada dessa sequência. A sequência deve seguir a seguinte regra: o valor de uma posição da                        sequência só pode ser um número em que é divisível por 1 e por ele mesmo, não havendo resto
              </td>
              <td>Baixa</td>
              <td>Concluída</td>
            </tr>
          </tbody>
        </table>
      </div></li>
    <li>
      <h2>
        Burndown
      </h2>
      <img src= "https://github.com/user-attachments/assets/2b42ac41-0f2b-4f31-b5d2-47f2f74b2bd9" alt= "Burndown2">
    </li>
  </ul>
</details>

<!--Sprint 3-->
<details>
  <summary>Sprint 3</summary>
  <ul>
    <li>
      <div>
        <h2>
          Backlog
        </h2>
        <!-- Tabela -->
        <table>
          <thead>
            <tr>
              <th>Função</th>
              <th>User Story</th>
              <th>Prioridade</th>
              <th>Status</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>Menu</td>
              <td>Como usuário, gostaria de poder interagir com todas as funções do programa, sendo ele a parte principal do programa</td>
              <td>Alta</td>
              <td>Concluída</td>
            </tr>
            <tr>
              <td>Números triangulares</td>
              <td>
                Como usuário, gostaria de ter duas formas de interagir com essa sequência: 1. Exigir o valor da posição de um número dessa sequência 2. Exigir uma lista de todos os valores de                     posições anteriores de uma posição desejada dessa sequência. A sequência deve seguir a seguinte regra: o valor de uma posição da sequência é dado pela devida fórmula: Tn =                         n(n+1)/2, em que n é a posição do valor a ser calculado
              </td>
              <td>Alta</td>
              <td>Concluída</td>
            </tr>
            <tr>
              <td>Sequência alternada</td>
              <td>
                Como usuário, gostaria de ter duas formas de interagir com essa sequência: 1. Exigir o valor da posição de um número dessa sequência 2. Exigir uma lista de todos os valores de                     posições anteriores de uma posição desejada dessa sequência. A sequência deve seguir a seguinte regra: serão exibidos apenas números ímpares, variando entre valores positivos e                    negativos, começando com um valor positivo
              </td>
              <td>Média</td>
              <td>Concluída</td>
            </tr>
            <tr>
              <td>Sequência geométrica</td>
              <td>
                Como usuário, gostaria de escolher um número e com base nele fazer a sequência com ele. Quero poder interagir de duas formas com essa sequência: 1. Exigir o valor da posição de um                 número dessa sequência 2. Exigir uma lista de todos os valores de posições anteriores de uma posição desejada dessa sequência. A sequência deve seguir a seguinte regra: O valor da                 posição é o valor da posição anterior multiplicado pelo número escolhido na primeira interação.
              </td>
              <td>Baixa</td>
              <td>Concluída</td>
            </tr>
          </tbody>
        </table>
      </div></li>
    <!--Burndown-->
    <li>
      <h2>
        Burndown
      </h2>
      <img src= "https://github.com/user-attachments/assets/5a49c2cd-7097-4ffb-94cb-b4c4b37b7cb7" alt= "Burndown3">
    </li>
  </ul>
</details>

## Documentação

[Manual do Usuário]()
  
## Código

## Equipe

 | Função      | Nome                                     |  Github  |
 | -           | -                                        | -        | 
 |Scrum Master | Leonardo Amon Sumiyoshi Hashimoto        |   [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Leonardo1022) |
 |Team Member  | Gabriel Valente Belarmino                |  [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/gabrielvalentesjc)|
 |Product Owner| Maria Eduarda Teixeira Miller de Oliveira|  [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/maria-oliveira)|
 |Team Member  | Natália Pereira da Silva                 |  [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/nataliapersis)|
 |Team Member  | Niuan Spolidorio da Rocha Souza          |  [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/NiuanSouza)|
 |Team Member  | Vitor Samuel Ribeiro de Souza            |   [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/VitorRibeiro09)|
 |Team Member  | Guilherme Almeida de Arruda              |   [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/guiggaaz)|
 |Team Member  |             |   [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/)|



