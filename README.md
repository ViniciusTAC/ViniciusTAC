# Olá, eu sou Vinícius Tadeu

<!-- <div align="center">
  <img src="https://media1.tenor.com/m/0fPnYtQ4KTkAAAAC/jinbe-jinbei.gif" alt="Jinbe" />
</div>  -->

## Engenheiro de Software

Sou formado em **Engenharia de Computação pelo Instituto Federal de Minas Gerais — IFMG Campus Bambuí**.

Trabalho com desenvolvimento de sistemas corporativos, APIs, automações, integrações e bancos de dados. Minha atuação é principalmente voltada ao backend, utilizando **Java, Spring Boot, SQL Server, Python e Node.js**, mas também desenvolvo interfaces com **Angular, Vue.js, JavaScript e TypeScript**.

No meu dia a dia, participo desde o entendimento das regras de negócio até a implementação, manutenção e implantação das soluções. Tenho interesse especial por projetos que resolvem problemas reais, organizam processos e transformam dados em informações úteis.

---

## Meu principal projeto

### TCC — Automação de dados da CVM para análise fundamentalista

Meu Trabalho de Conclusão de Curso foi desenvolvido para automatizar a coleta e a estruturação de dados financeiros públicos disponibilizados pela **Comissão de Valores Mobiliários — CVM**.

A proposta do projeto é reunir dados que normalmente estão distribuídos em diferentes arquivos e formatos, processá-los e armazená-los em uma estrutura organizada, facilitando sua utilização em análises fundamentalistas de empresas brasileiras de capital aberto.

O sistema trabalha com documentos como:

* Demonstrações Financeiras Padronizadas — DFP;
* Informações Trimestrais — ITR;
* Formulário Cadastral — FCA;
* Informações Periódicas e Eventuais — IPE;
* Formulário de Referência — FRE.

O processamento segue um fluxo de **ETL**, passando pela coleta, extração, transformação, armazenamento e preparação dos dados para análise.

<div align="center">
  <a href="https://github.com/ViniciusTAC/cvm-fundamentalist-analysis">
    <img src="https://img.shields.io/badge/Acessar_meu_TCC-181717?style=for-the-badge&logo=github&logoColor=white" alt="Acessar projeto do TCC">
  </a>
</div>

### O que o projeto realiza

* Coleta arquivos públicos disponibilizados pela CVM;
* Extrai e trata os dados encontrados nos documentos;
* Padroniza informações financeiras de diferentes períodos;
* Armazena os dados em banco relacional;
* Registra logs de execução, sucessos e falhas;
* Prepara uma base para consultas e indicadores fundamentalistas;
* Permite expandir o processamento para novas fontes e análises.

### Fluxo principal

```text
CVM
 │
 ▼
Coleta dos arquivos
 │
 ▼
Extração e transformação
 │
 ▼
Validação dos dados
 │
 ▼
Armazenamento no banco
 │
 ▼
Consultas e análises fundamentalistas
```

### Estrutura do projeto

```text
src/
├── collectors/       # Coleta e download dos arquivos da CVM
├── extractor/        # Extração e transformação dos dados
├── models/           # Entidades e estruturas utilizadas pelo sistema
├── service/          # Regras de processamento
├── repository/       # Comunicação e persistência no banco de dados
├── utils/            # Funções auxiliares e configuração de logs
└── main.py           # Ponto inicial da aplicação
```

### Tecnologias utilizadas no TCC

![Python](https://img.shields.io/badge/Python-000?style=flat\&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-000?style=flat\&logo=pandas)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-000?style=flat\&logo=sqlalchemy)
![SQLite](https://img.shields.io/badge/SQLite-000?style=flat\&logo=sqlite)
![Beautiful Soup](https://img.shields.io/badge/Beautiful_Soup-000?style=flat\&logo=python)
![Requests](https://img.shields.io/badge/Requests-000?style=flat\&logo=python)

### Requisitos para execução

* Python 3.11 ou superior;
* Dependências instaladas por meio do `requirements.txt`;
* Aproximadamente 16 GB de espaço livre;
* Recomendação de pelo menos 8 GB de memória RAM.

---

## Tecnologias que utilizo

Minha experiência foi construída por meio da graduação, estudos independentes, cursos, bootcamps e, principalmente, pela aplicação dessas tecnologias em projetos acadêmicos e sistemas utilizados em ambientes profissionais.

### Backend

![Java](https://img.shields.io/badge/Java-000?style=flat\&logo=openjdk)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-000?style=flat\&logo=springboot)
![Python](https://img.shields.io/badge/Python-000?style=flat\&logo=python)
![Node.js](https://img.shields.io/badge/Node.js-000?style=flat\&logo=nodedotjs)
![Ruby](https://img.shields.io/badge/Ruby-000?style=flat\&logo=ruby)

### Frontend

![Angular](https://img.shields.io/badge/Angular-000?style=flat\&logo=angular)
![Vue.js](https://img.shields.io/badge/Vue.js-000?style=flat\&logo=vuedotjs)
![Vuetify](https://img.shields.io/badge/Vuetify-000?style=flat\&logo=vuetify)
![TypeScript](https://img.shields.io/badge/TypeScript-000?style=flat\&logo=typescript)
![JavaScript](https://img.shields.io/badge/JavaScript-000?style=flat\&logo=javascript)
![HTML5](https://img.shields.io/badge/HTML5-000?style=flat\&logo=html5)
![CSS3](https://img.shields.io/badge/CSS3-000?style=flat\&logo=css3\&logoColor=264CE4)

### Bancos de dados

![SQL Server](https://img.shields.io/badge/SQL_Server-000?style=flat\&logo=microsoftsqlserver)
![MySQL](https://img.shields.io/badge/MySQL-000?style=flat\&logo=mysql)
![SQLite](https://img.shields.io/badge/SQLite-000?style=flat\&logo=sqlite)

### Ferramentas e ambientes

![Git](https://img.shields.io/badge/Git-000?style=flat\&logo=git)
![GitHub](https://img.shields.io/badge/GitHub-000?style=flat\&logo=github)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-000?style=flat\&logo=githubactions)
![Linux](https://img.shields.io/badge/Linux-000?style=flat\&logo=linux)
![Maven](https://img.shields.io/badge/Maven-000?style=flat\&logo=apachemaven)

---

## Além do código

Também valorizo competências que ajudam a transformar uma implementação técnica em uma solução que realmente pode ser utilizada e mantida.

| Competência            | Como aplico                                                     |
| ---------------------- | --------------------------------------------------------------- |
| Resolução de problemas | Investigo falhas, identifico causas e desenvolvo correções      |
| Comunicação            | Traduzo necessidades de negócio para soluções técnicas          |
| Organização            | Estruturo tarefas, documentação e etapas de desenvolvimento     |
| Pensamento crítico     | Avalio impactos antes de implementar alterações                 |
| Trabalho em equipe     | Compartilho conhecimento e colaboro nas decisões técnicas       |
| Adaptabilidade         | Aprendo novas ferramentas conforme as necessidades dos projetos |
| Liderança              | Apoio colegas e contribuo com a organização das atividades      |

---

## Formação acadêmica

**Bacharelado em Engenharia de Computação**
Instituto Federal de Educação, Ciência e Tecnologia de Minas Gerais
**IFMG — Campus Bambuí**

---

## Contato

<div align="center">
  <a href="mailto:viniciustacosta@gmail.com">
    <img src="https://img.shields.io/badge/Email-333333?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://www.linkedin.com/in/vinícius-tadeu-andrade-costa/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://www.instagram.com/vinicius.tac/" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">
  </a>
</div>

<!-- <br clear="both">

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ViniciusTAC&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=false&count_private=true&disable_animations=true&theme=synthwave&locale=pt-br&hide_border=false&order=1&custom_title=Estat%C3%ADsticas%20do%20ViniciusTAC" height="150" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=ViniciusTAC&locale=pt-br&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=synthwave&hide_border=false&order=2" height="150" alt="languages graph"  />
  <img src="https://streak-stats.demolab.com?user=ViniciusTAC&locale=pt-br&mode=daily&theme=synthwave&hide_border=false&border_radius=5&order=3" height="150" alt="streak graph"  />
  <img src="https://github-profile-trophy.vercel.app?username=ViniciusTAC&theme=dracula&column=-1&row=1&margin-w=8&margin-h=8&no-bg=false&no-frame=false&order=4" height="150" alt="trophy graph"  />
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ViniciusTAC&radius=16&theme=synthwave-84&area=true&order=5&custom_title=Gr%C3%A1fico%20do%20ViniciusTAC" height="300" alt="activity-graph graph"  />
</div>

<br>

<div align="center"> -->

<!--   <img src="https://profile-counter.glitch.me/ViniciusTAC/count.svg?"  /> -->

<!-- </div> -->

<!--
<div align="center">
  <a href="https://spotify-github-profile.vercel.app/api/view?uid=noix-4&redirect=true">
    <img src="https://spotify-github-profile.vercel.app/api/view?uid=noix-4&cover_image=true&theme=default&show_offline=true&background_color=21012d&interchange=true&bar_color=ff00a2&bar_color_cover=true" alt="Spotify Profile">
  </a>
</div>
-->

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ViniciusTAC/ViniciusTAC/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ViniciusTAC/ViniciusTAC/output/pacman-contribution-graph.svg">
  <img alt="Pacman contribution graph" src="https://raw.githubusercontent.com/ViniciusTAC/ViniciusTAC/output/pacman-contribution-graph.svg">
</picture>
