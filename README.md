<p align = "center">
 
# ANÁLISE DO FLUXO DE IMPORTAÇÃO E EXPORTAÇÃO DE PRODUTOS PARA O AEROPORTO DE SJK


Projeto API - 1° Semestre - Logística 2023, baseado na metodologia ágil SCRUM, procurando desenvolver a Proatividade, Autonomia, Colaboração e Entrega de Resultados dos estudantes envolvidos.

</p>

## ÍNDICE
 + [PROJETO](#projeto)
 + [EMPRESA](#empresa)
 + [EQUIPE](#equipe)
 + [PRAZOS](#prazos)
 + [BACKLOG DAS SPRINTS](#backlog-das-sprints)
 + [FUNCIONALIDADES E REGISTROS DAS SPRINTS](#funcionalidades-e-registros-das-sprints)
 + [REGRAS DE NEGÓCIO](#regras-de-negócio)
 + [COMPETÊNCIAS DESENVOLVIDAS](#competências-desenvolvidas)
 + [FERRAMENTAS UTILIZADAS](#ferramentas-utilizadas)


## PROJETO

- ### Introdução
     Mapeamento de dados coletados pelo site do governo, possibilitando a análise do fluxo de transporte de mercadorias importadas e exportadas a um raio de 200 km do aeropoerto de SJK, disponibilizando assim, atraves de uma interface grafica a melhor interpretação ao cliente.

- ### Objetivo
     Desenvolvimento de uma interface gráfica, permitindo que o cliente possa ter uma análise visual, interativa e ágil do fluxo relacionado à importação e exportação referente ao aeroporto SJK. Tendo em base, os dados retirados do ComexStat (base de dados do governo), e por meio destes criar uma interface que auxilie e melhore a análise de possíveis novos investimentos, realocando  para o aeroporto SJK .

- ### Projeto (API) 
     Projeto pedagógico alicerçado na Metodologia API para ensino-aprendizado focado no desenvolvimento de competências e fundamentada nos pilares de aprendizado com problemas reais (RPBL), validação externa e mentalidade ágil. 
     Uso de estratégias para entender o problema, conceber uma solução viável ao desenvolver e implementar o MVP seguido de sua operação (CDIO). 

## EMPRESA

<p align="center">
  <img src="https://github.com/ATLASlog/ATLASlog/assets/141978742/b6963ca7-bbe6-47e7-ad1c-2abec96e9520" alt="Sublime's custom image"/>

</p>

 
Missão
 
 >Facilitar e impulsionar o sucesso de nossos clientes por meio da análise de dados de aeroportos, comprometemo-nos a fornecer percepções precisas e estratégicas que otimizem a eficiência operacional e a tomada de decisões.

Visão

 >Ser reconhecida como a principal autoridade em análise de dados de aeroportos, criando um impacto significativo no setor logístico. Pretendemos expandir nossos serviços para novas regiões e ser o parceiro de confiança de empresas em todo o mundo.

Valores

 >Excelência, inovação, integridade, colaboração e sustentabilidade.

## EQUIPE

|NOME | FUNÇÃO | LINKEDIN | IDENTIFICAÇÃO |
|-----|--------|----------|---------------|
| Aline Cristina de Azevedo Silva | Product Owner |<a href="https://www.linkedin.com/in/aline-cristina-azevedo-silva-870b22161" target="blank"> <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"> <a href="https://github.com/alineazevedos" target ="blank"> <img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white60px" target="blank" width="90px">|<img src="https://media.licdn.com/dms/image/D4D03AQFFAYT0Zl8MrQ/profile-displayphoto-shrink_800_800/0/1689631460398?e=1700697600&v=beta&t=SdA8pDhc59TWA4Z8FwPXX8XNEC_XnUU6ztCB27wVCgw" width="60px"> |
| André Carneiro Ribeiro | Desenvolvedor | <a href="https://www.linkedin.com/in/andr%C3%A9-carneiro-ribeiro-073b73259" target="blank" > <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"> <a href="https://github.com/RibeiroAcr" target="blank"> <img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white60px" target="blank" width="90px">|<img src= "https://github.com/ATLASlog/ATLASlog/assets/141978742/49e88b77-ab1e-4d5e-b76d-19cce99936c6" width="60px"> |
| Cauê Santos da Silva | Desenvolvedor | <a href="https://br.linkedin.com/in/caue-santos-a01228288" target="blank"> <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"> <a href="https://github.com/cauesantossilva" target="blank"> <img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white60px" target="blank" width="90px"> |<img src= "https://media.licdn.com/dms/image/D4D03AQGCBF3w-dTFYg/profile-displayphoto-shrink_800_800/0/1695077480764?e=1700697600&v=beta&t=VPyPLnAqgMlrGLIZWlHxpzkSdfhmaoXlDlqC4SDdO7g" width="60px"> |
| Denise da Silva Oliveira | Desenvolvedor | <a href="https://www.linkedin.com/in/denise-oliveira-32099a287" target="blank"> <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"> <a href="https://github.com/Doliveira11" target="blank"> <img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white60px" target="blank" width="90px"> |<img src= "https://media.licdn.com/dms/image/D4E03AQFZslt4fSwPWg/profile-displayphoto-shrink_800_800/0/1691794503206?e=1700697600&v=beta&t=RvPnjGG4zrpyMB2UmSHILkgA2VvpL8DSYEccNDAQz_c" width="60px"> |
| Josimar Pereira dos Santos | Desenvolvedor | <a href="https://www.linkedin.com/in/josimar-santos-2b4329288/" target="blank"> <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"> <a href="https://github.com/josimarpsantos" target="blank"> <img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white60px" target="blank" width="90px"> |<img src= "https://avatars.githubusercontent.com/u/141979608?v=4" width="60px"> |
| Kauan Araujo Oliveira | Desenvolvedor | <a href="https://br.linkedin.com/in/kauan-oliveira-4b54b5291" target="blank"> <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"> <a href="https://github.com/kauanoliveira7" target="blank"> <img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white60px" target="blank" width="90px">  | <img src= "https://media.licdn.com/dms/image/D4D03AQFH7Kuv1DjOnw/profile-displayphoto-shrink_800_800/0/1695078025758?e=1700697600&v=beta&t=AYU0Kqr_9_-j39zVkIOfpqRKlBoOPcw5jNwGtSCZtkU" width="60px"> | 
| Mariana Cassia Santos Rodrigues de Almeida | Desenvolvedor | <a href="https://www.linkedin.com/in/marianac%C3%A1ssia/" target="blank"> <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"> <a href="https://github.com/Mcsalme" target="blank"> <img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white60px" target="blank" width="90px"> |<img src= "https://avatars.githubusercontent.com/u/111469327?v=4" width="60px"> |
| Vinicius Moreira de Sousa | Scrum Master | <a href="https://www.linkedin.com/in/vinicius-moreira-de-sousa-146359287" target="blank"> <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"> <a href="https://github.com/viniihsousa" target="blank"> <img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white60px" target="blank" width="90px">|<img src= "https://media.licdn.com/dms/image/D4E03AQHnFFtchFJbSg/profile-displayphoto-shrink_800_800/0/1691760851823?e=1700697600&v=beta&t=3h3eEh45iPttodecYqxVGCu_WWkKFac4qG-6OHGzjKk" width="60px"> |


## PRAZOS

> - [X] Kick-off do Projeto - 04/09/2023    | [Apresentação](https://github.com/ATLASlog/ATLASlog/files/12787368/Kick-off.API.1N.1.pptx) | 
> - [X] Entrega Sprint 00   - 25/09/2023    | [Relatório](https://github.com/ATLASlog/ATLASlog/files/12810882/leis.de.morgan.pdf) | 
> - [X] Entrega Sprint 01   - 16/10/2023    | [Relatório](https://fatecsjc-prd.azurewebsites.net/downloads/estagio/modelo_relatorio_estagio_gpi.docx) | 
> - [X] Entrega Sprint 02   - 06/11/2023    | [Relatório](https://fatecsjc-prd.azurewebsites.net/downloads/estagio/modelo_relatorio_estagio_gpi.docx) | 
> - [X] Entrega Sprint 03   - 27/11/2023    | [Relatório](https://fatecsjc-prd.azurewebsites.net/downloads/estagio/modelo_relatorio_estagio_gpi.docx) | 
> - [X] Feira de Soluções   - 12/12/2023    | [Relatório](https://fatecsjc-prd.azurewebsites.net/downloads/estagio/modelo_relatorio_estagio_gpi.docx) | 


### Cronograma
Ao clicar você será redirecionado ao cronograma detalhado desse projeto, lá é possivel encontar as datas das atividades, o responsável por cada atividade, o estágio em que cada atividade se encontra e a qual sprint cada atividade pertence.

#### [Cronograma das Sprints](https://alinecazevedosilva.atlassian.net/jira/software/projects/AA/boards/2/backlog)


## BACKLOG DAS SPRINTS

- ### Sprint 01 - Desenvolvimento do Projeto

![Sprint 01](https://github.com/ATLASlog/ATLASlog/assets/141978742/1ea75b1e-47c6-45d9-99c8-6bbda172a2ba)

- ### Sprint 02 - Implementação

![Sprint 02](https://github.com/ATLASlog/ATLASlog/assets/141978742/61e606d1-7ff3-4f81-8240-a4260952a747)


- ### Sprint 03 - Operacionalização

![Sprint 03](https://github.com/ATLASlog/ATLASlog/assets/141978742/994a9422-d2f0-4a26-97eb-05444c96f9c4)


## FUNCIONALIDADES E REGISTROS DAS SPRINTS

Apresentação dos vídeos e documentos:<p align="center">
 <img src="https://img.shields.io/badge/STATUS-EM_PROGRESSO-yellow"/>
</p>


## REGRAS DE NEGÓCIO

- Desenvolvimento de estrutura relacional de tabelas com base nos dados disponibilizados.

- Criação de um Dashboard intuitivo para visualização dos dados apresentados.

- Documentação no GitHub e gestão do projeto desenvolvida no JIRA SOFTWARE

- Documentação do projeto de forma clara e de fácil acesso.

- Utilização da Metodologia ágil

- Power BI / Jira / Canvas

## COMPETÊNCIAS DESENVOLVIDAS 

- ### Hard Skill (saber tecnológico)
<details>
<summary>Hard Skills desenvolvidas</summary>
  
| Tecnologia/Metodologia | Classificação |
| ---------------------- | ------------- |
| GitHub | ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ |
| Gestão de Projetos | ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ |
| Scrum Master | ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ |
| Prodct Owner | ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ |
| Markdown | ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ |
| Git Projects | ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ |

 </details>

- ### Soft Skill (saber comportamental)
<details>
<summary>Soft Skills desenvolvidas</summary>

| Habilidades | Classificação |
| ---------------------- | ------------- |
| Colaboração | ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ |
| Proatividade| ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ |
| Pensamento Crítico | ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ |
| Gerenciamento de Tempo | ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ |
| Adaptabilidade | ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ |
| Resiliência | ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ ☆ |

</details>

## FERRAMENTAS UTILIZADAS 

- ### Produto
<p align="center">
 <img src="https://img.shields.io/badge/STATUS-EM_PROGRESSO-yellow"/>
</p>

- ### Tecnologias Específicas/Apoio
<img src= "https://github.com/ATLASlog/ATLASlog/assets/111469327/a2b2af85-35be-45c2-8aa4-ac50af949e3f" width="40px"> 
<img src= "https://github.com/ATLASlog/ATLASlog/assets/111469327/8e762ff1-717d-4e80-a7c8-dd6da9a90b6f" width="40px"> 
<img src= "https://github.com/ATLASlog/ATLASlog/assets/111469327/e9dccc1f-a057-483d-b9c1-a8f1b570c3fb" width="40px"> 
<img src= "https://github.com/ATLASlog/ATLASlog/assets/111469327/54ef2cf0-a0b0-4a94-b67d-3c5afb0ac89b" width="40px"> 

- ### Mindset Digital
- Backlog
- [![MVP](https://img.youtube.com/vi/Ipg6Ox6qlC8/0.jpg)](https://www.youtube.com/embed/Ipg6Ox6qlC8)
- Scrum para iniciantes
- [![Scrum para iniciantes](https://img.youtube.com/vi/1DkmzynmRHk/0.jpg)](https://www.youtube.com/embed/1DkmzynmRHk)
