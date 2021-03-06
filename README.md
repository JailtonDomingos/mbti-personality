# MBTI Personality Test
## Aplicação de Métodos de Aprendizagem de Máquina 
#### Autor: Jailton Guilherme Marcelino Domingos<br>


> Status do Projeto: :warning: (em desenvolvimento)
> 
### Definição do tema
*A personalidade ou em outras palavras o conjunto de peculiaridades de um indivíduo são a força ativa do seu ser, esta determina sua individualidade pessoal e social, seu jeito de pensar, agir ou sentir. Estes valores quando usado da maneira correta podem se tornar ferramentas eficazes no meio pessoal e profissional.*

*Os testes psicológicos por sua vez, são ferramentas científicas da área de psicologia que envolvem diversos fatores de análise buscando traçar a personalidade(características) de um indivíduo, seja para o objetivo de auto-conhecimento, o uso desta informação para a busca de uma contratação mais síncrona com os valores de certa empresa ou até mesmo para direcionar serviços e produtos para um público alvo, assim adicionando uma variável significativa para a competitividade do negócio.*

*Atualmente as empresas estão buscando cada vez mais pela identificação das preferências do seu público alvo e com o passar do tempo os aprimoramentos da tecnologia aliviam o processo humano para uma forma aprimorada de classificação e identificação de perfis dos indivíduos, usando do beneficio da expansão do mundo digital e o mar de informações aumentando dia após dia.*

*Justamente com este aumento de informações geradas pela rede mundial de computadores, este trabalho irá corporificar o uso de métodos de aprendizado de máquina(Machine Learning) para realizar a identificação e classificação dos perfis de indivíduos com base nos seus últimos 50 posts e utilizando a tipologia de personalidade 'Myers-Briggs Type Indicator(MBTI)' como indicador.*

### Objetivo do projeto
*O objetivo deste estudo é a aplicação de algoritmos de aprendizados de máquina para classificação da personalidade do indivíduo com base nos seus últimos registros escritos.*


### Especificações técnicas
*A base de dados está em formato .CSV e está composta por múltiplas linhas, as quais cada uma representa um indivíduo. Dentro destas linhas existem duas colunas que são:* 

- *types: Tipo de personalidade;*
- *posts: Últimos 50 posts deste indivíduo;*

*O dataset que será utilizado pode ser encontrado em: < https://www.kaggle.com/datasnaek/mbti-type >*

*Existe um Database maior que pode ser encontrado em: < https://zenodo.org/record/1323873#.YezB2PXMLx5 >*

*Este dataset contém apenas 8675 linhas de dados textuais, os quais necessitam do tratamento de dados por incorporarem caracteres especiais, links e emojis.*

- Métodos de Machine Learning utilizados
  - ???
  
- Como a base de dados será dividida
  - ???

- Métricas de avaliação utilizadas
  - ???

### Preparação dos dados
- Aplicação dos métodos de pré-processamento
  - O dataset utilizado contém dados textuais, por esse motivo, ocorrerá os seguintes processos de pré-processamento:
    - Adequação e formatação dos dados.
    - Limpeza da base, onde serão removidos termos de divisória dos dados, remoção de espaços em branco e remoção de caracteres especiais.
    - Remoção de stop-words: Remover as ditas palavras de parada, como uma forma de otimizar o desempenho dos algoritmos

- Tarefa de Aprendizado: O dataset utilizado se trata de dados textuais que corporificam classes para pessoas, com isto, será utilizada a tarefa de Classificação.
- Distribuição dos dados
  - Treino/teste e cross-validation

- Treinamento
  - Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
  - 
- Teste
  - Teste 1
    - Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
  - Teste 2
    - Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.


### Resultado e predição
- Demonstração das métricas
   - Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
   
- Predição
  - Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

## Linguagens, libs e recursos utilizados

- [Python](https://www.python.org/)
- [Kaggle](https://www.kaggle.com/)
- [Kaggle Database](https://www.kaggle.com/datasnaek/mbti-type)
- [Personality Explanation](https://www.verywellmind.com/what-is-personality-testing-2795420)
- [Personality Explanation 2](https://www.quickin.io/2021/04/22/teste-mbti-para-que-serve-e-como-usar/)
- [The Cult of Personality Testing Book](https://books.google.com.br/books?id=Njh9KgwSjs0C&dq=%22Personality+tests%22&lr=&hl=pt-BR&source=gbs_navlinks_s)

## Desenvolvedor

[<img src="https://avatars.githubusercontent.com/u/31225679?v=4" width=115 > <br> <sub> Jailton Domingos </sub>](https://github.com/JailtonDomingos) |
| :---: |  

## Licença 

Este projeto está licenciado nos termos da [licença MIT](LICENSE).

Copyright :copyright: 2022 - MBTI Personality Detectation
