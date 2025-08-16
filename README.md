<h1 align="center" style="font-weight: bold;">Projeto de Teoria dos Grafos 💻</h1>

<p align="center">
  <a href="#started">Introdução</a> • 
  <a href="#tech">Tecnologias</a> • 
  <a href="#colab">Contribuidores</a> •
</p>

<p align="center">
    <b>Neste projetos foram utilizados dados das bases de dados abertas para criação de grafos de análise dos acidentes automobilisticos na Paraíba em 2024</b>
</p>

<h2 id="started">🚀 Introdução</h2>

Devido ao Plano de Dados abertos da PRF, hoje é possível ter acesso as informações registradas nos Boletim de Acidente de Trânsito). Essas informações estão em arquivos do tipo csv, que
são atualizados mensalmente e divididos de forma anual, agrupados por ocorrências,
por pessoa e por pessoa com todas as causas e tipos de acidentes.

Neste trabalho, foi realizada uma análise dos dados de acidentes ocorridos no
estado da Paraíba no ano de 2024 agrupados por ocorrências, visando encontrar rela-
ções interessantes entre os registros. Para isso, foram elaborados grafos na tentativa
de identificar essas relações e visualizar os locais em que mais obtiveram registros
de acidentes, a fase do dia com mais registros, as gravidades dos acidentes, entre
outras analises que são mostradas e descritas em detalhes no trabalho.

<h3>Clonando o repositório</h3>

Interssados neste projeto podem clonar este repositório para acessar as bases de dados usadas, os códigos criados para plotagem dos grafos, bem como
do PDF do trabalho.

```bash
git clone https://github.com/IsabellaTito/Projeto_Grafos.git
```
<h3>Um breve spoiler</h3>

Dentre as análises feitas, foi constatado que as BRs 101 e 230 são as que mais foram registrados acidentes ao longo do ano de 2024. Desse modo,
um dos grafos mais interessantes obtidos neste projetos foi a relação entre as maiores causas de acidentes nestas BRs

<p align="center">
  <img width="700" height="450" alt="acidentes-brs-causas-pb" src="https://github.com/user-attachments/assets/f5ede511-d94d-424a-8e6e-dfc1d7468ea7" align="center"/>
</p>

<h2 id="technologies">💻 Tecnologias</h2>

O Google Colab, a linguagem de programação Python e a biblioteca Pandas
foram as ferramentas báicas para o desenvolvimento deste trabalho. Por outro lado,
as bibliotecas NetworkX e Matplotlib foram as bibliotecas específicas que os autores
optaram para criação e plotagem dos grafos. Assim, temos a seguinte lista

- Google Colab
- Python
- Pandas
- Matplotlib
- NetworkX


<h2 id="colab">🤝 Contribuidores</h2>

<a href="https://github.com/IsabellaTito/Projeto_Grafos/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=IsabellaTito/Projeto_Grafos"/>
</a>
