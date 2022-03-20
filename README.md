## 📚 Seções Portfólios

<h4 align="left"><a href="https://github.com/caroolps/Portfolio01">PROJETO 1º SEMESTRE: Mapeador de Criminalidade ao Redor da FATEC</a></h4>
<h4 align="left"><a href="https://github.com/caroolps/Portfolio02">PROJETO 2º SEMESTRE: Gantt Chart</a></h4>
<h4 align="left"><a href="https://github.com/caroolps/Portfolio03">PROJETO 3º SEMESTRE: Cadastro Positivo</a></h4>
<h4 align="left"><a href="https://github.com/caroolps/Portfolio04">PROJETO 4º SEMESTRE: JobNation</a></h4>
<h4 align="left"><a href="https://github.com/caroolps/Portfolio05">PROJETO 5º SEMESTRE: Educalytics</a></h4>

![image](https://user-images.githubusercontent.com/61089745/158082449-894548ea-e14d-4de7-896d-12d2a9ec1d74.png)

## FATEC & JET SOFT - JOBNATION

### **I - RESUMO DO PROJETO**:page_facing_up: 

Neste quarto Projeto Integrador a FATEC trouxe o Cliente "JET SOFT" para que pudéssemos achar uma solução tecnológica para sanar e atender às necessidades do cliente.
Desenvolvendo uma API que possibilita a busca de candidatos a partir de uma vaga, buscando uma contração veloz e assertiva. Dentre os critérios, deverão ser destaques a segurança e o desempenho da aplicação.



### Proposta:
- Busca por localização: número de conduções para chegar ao local de trabalho.

- Busca por diferentes critérios: rota(s) de pesquisa estão sendo desenhadas para propiciar liberdade de consulta ao BD. Nesse passo, a aplicação varrerá  currículos já cadastrados e identificará candidato(s)  mais adequados à vaga.

## Features

- [x] 1) DIAGRAMA-BASE JOBNATION

![image](https://user-images.githubusercontent.com/61089745/159175589-20bde7c2-7196-4f9b-ab77-7620db50f81d.png)


![image](https://user-images.githubusercontent.com/61089745/159175620-99812ced-b8fa-4a51-9afb-0a8d171d8af0.png)



<details><summary>DUMP.SQL [CRIA AS TABELAS]:</summary><img src="/uploads/63a54f1a92f9b07bbbdab48be138dfc1/1.png" name="1"></details>
  <details><summary>VALIDACÃO DE PREENCHIMENTO DE CAMPOS:</summary><img src="/uploads/12b31e00d9b78283fc5e315a29eba3d5/2.png" name="2"><img src="/uploads/1e507b31e0e997fa66f8e8f9c1c7cdc4/3.png" name="3"></details>
  <details><summary>CAMADA "SERVICE": (LÓGICA DE VALIDAÇÃO)</summary><img src="/uploads/2b49fa8629c6c80507680fc21642e7db/4.png" name="4"></details>
  <details><summary>ROTAS:</summary><img src="/uploads/a0f93b9663ba6210a1c11d2e15882bcb/5.png" name="5"></details>
  <details><summary>PROTEÇÃO DE DADOS SENSÍVEIS:</summary><img src="/uploads/8701ac30a50ff29aadd1dc2f5b112b4d/6.png" name="6"></details>
  <details><summary>ESTRUTURA DO CÓDIGO JAVA - BACKEND:</summary><img src="/uploads/9c9ff99ccc800eb5f36f44e215e39e6d/7.png" name="7"><img src="/uploads/2df96e095229bcd428f5bce621126eb1/8.png" name="8"></details>
  <details><summary>DATA TRANSFER OBJECT:</summary><img src="/uploads/a553e6dec0666f9a5c5f5242eef1cfc3/9.png" name="9"></details>
  <details><summary>CandidateToDtoConverter</summary><img src="/uploads/4295082a6717542a4e7281465f941348/10.png" name="10"></details>
  <details><summary>DtoToCandidateConverter</summary><img src="/uploads/05359c0ec858394f366dac6111615d34/11.png" name="11"></details>
  <details><summary>COM AS VAGAS CADASTRADAS + CANDIDATOS CADASTRADOS = CANDIDATAR-SE À VAGA (APPLY):</summary><img src="/uploads/e4d8e42660bfa2c8dc88f76411388c4c/12.png" name="12"></details>
  <details><summary>APÓS O APPLY, É POSSÍVEL CONCILIAR CANDIDATOS E VAGAS ATRAVES DO MÉTODO MATCH:</summary><img src="/uploads/e4909dc5812f040574277091e215e744/13.png" name="13"></details>
  <details><summary>DEPLOY EM PRODUÇÃO:</summary><img src="/uploads/6b94cdffba2c26439d5f03d50b14cea3/14.png" name="14"></details>
  <details><summary>NODEJS - MAPS:</summary><img src="/uploads/13fac9a7213d4256bb41f2c90a0d3604/15.png" name="15"></details>
  <details><summary>GOOGLE_MAPS_API_KEY:</summary><img src="/uploads/5408653e11c231fc7e84ba656b78145f/16.png" name="16"></details>
  <details><summary>API EXECUTADA:</summary><img src="/uploads/24cf645c4f783288196aa4d7f50e9cf3/17.png" name="17"></details>

- [x]  2) API JOBNATION

![image](https://user-images.githubusercontent.com/61089745/159175730-a6778694-b968-4db9-802a-b57b7dac2802.png)

- [x] 3) API JOBNATION - NODE-JS - BUSCA QUANTIDADE DE MEIOS DE TRANSPORTES NO GOOGLE MAPS.

![image](https://user-images.githubusercontent.com/61089745/159175766-d0d65974-6f41-492b-9c63-979dd9367347.png)


- [x] 4) API JOBNATION - MATCH DE CANDIDATOS (MOST SUITED FOR THE JOB)

![image](https://user-images.githubusercontent.com/61089745/159175866-5d9f6cb9-8642-4cb4-9841-87ca9060b7e0.png)

- [x] 5) SEARCH BY VTn
![VTN-QUERY](/uploads/f3bb885d18f73907c2f6dbd49281e2a7/VTN-QUERY.mp4)

- [x] 6) JOBNATION's DATABASE

![image](/uploads/42d2fb5ba4f7643b910d68777841a68b/image.png)

- [x]  7) BANCO DE DADOS JOBNATION - FUNCTION BUSCA MÚLTIPLOS CRITÉRIOS COM CURSOR.

![7.ORACLE_FUNCTION](/uploads/de7a03e4f2da61f3bce35ecabc604906/2.ORACLE_FUNCTION.mp4)

- [x]  8) BANCO DE DADOS JOBNATION - ANÁLISE DE PERFORMANCE COM 5.000 REGISTROS FICTÍCIOS.

![8-JN-DB - PERFORMANCE-ANTES](/uploads/72c6849e98ebb4b2f464d8b9da78a0b3/Performance_antes_dos_5k.mp4)

![8-AJN-DB - PERFORMANCE-TEST-DEPOIS](/uploads/08fd70fb6e9c73577346e22ed6a5f084/3.ORACLE-PERFORMANCE-TEST.mp4)


## Entregas

| Sprint | Data  | Vídeo                                       |
|--------|-------|---------------------------------------------|
| 1      | 28/03 |----------(no video for this sprint)---------|
| 2      | 18/04 |-----------(video presented live)------------|
| 3      | 16/05 |-----------(video presented live)------------|
| 4      | 06/06 |-------(video will be presented live)--------|

## Requisitos

#### Funcionais

| Requisitos Funcionais                                                  | Código | Prioridade | Sprint |
|------------------------------------------------------------------------|--------|------------|--------|
| Inicializa uma API e se conecta ao/cria BD                | RF01   | 1          | 1      |
| Executa Requisição de Terceiro | RF02   | 1          | 2      |
| Busca candidatos x No de conduções do para chegar ao trabalho                                 | RF03   | 1          | 2      |
| MATCH Candidato-Vaga                                                 | RF04  | 1          | 3     |
| Filtra resultado da Busca | RF05  | 1          | 3      |
| Busca x critérios de uma vaga                            | RF06   | 1          | 4      |



#### Não funcionais

| Requisitos Não Funcionais                            | Código | 
|------------------------------------------------------|--------|
| Regras de segurança da informação           | RNF01  |
| Integridade (BD relacional)                   | RNF02  |
| Flexibilidade quanto aos critérios                                    | RNF03  |
| Regras de performance   | RNF04  |
| Documentação  | RNF05 |


INSERIR TESTES NO README;


## User Stories

| Quem? | O que? | Por quê? |
|-------|--------|----------|
| API de Terceiros | Fornece critérios de busca | Quer  processo de recrutamento em massa
| Jet Soft | Disponibiliza JOBNATION aos seus clientes (terceiros) | Velocidade |
| Tecno Code | Desenvolve a JOBNATION | Para aplicar na prática os conhecimentos de programação adquiridos, além de adquirir experiência profissional em desenvolvimento de projetos |


## Diagrama de Casos de Uso

![CASOS DE USO](/uploads/18cb3c6e95bcaf600b618b6e2199230b/MicrosoftTeams-image__8_.png)


## Banco de dados
## Diagrama Entidade-Relacionamento

![DER-SPRINT-03-](/uploads/19fc541596b0e39ab528b13fbf1c2be7/MicrosoftTeams-image__5_.png)

## Diagrama Lógico
![LOGICAL-SPRINT-03-](/uploads/ea7c9eade4119499aa05097656d7389c/MicrosoftTeams-image__6_.png)


## Inovation

Criamos o 1o BD com benchmarking no LINKEDIN, subsequentemente alterando o protagonismo para a entidade vaga (VACANCY).

Então, estudamos quais ferramentas servirão aos requisitos (não) funcionais: 

- No BACK-END - Mais de uma linguagem de programação;

- No BD - FUNCTIONS para dar flexibilidade às QUERIES;


## Backlog do Projeto
Atividades de cada sprint, com prioridade.

#### Sprint 00
- reunião de kick-off  com JETSOFT
- Criação de repositório
- Definição de cargos (SM e PO)
- Definição de nome para a equipe
- Brainstorm para discussão de primeiras ideias
- Apresentação de proposta de aplicação;

#### Sprint 01
- Criação do README.MD com informações sobre o projeto e instruções para execução da aplicação;

- Criação de modelo entidade relacionamento para definir como os dados serão estruturados;

- Início do Desenvolvimento do Core da Aplicação: Controller, Model (Arquitetura REST) e Banco de Dados (Oracle)

- Associação das informações do banco de dados a um diagrama de classes;

- BONUS; FRONT-END - Construção do design da plataforma;

- BONUS: FRONT-END - Desenvolvimento do recurso de busca por proximidade do local da vaga


#### Sprint 02

- Core da Aplicação Funcionando: Controller, Model (Arquitetura REST) e Banco de Dados (Oracle);

- CRUD: 1a Rota de submissão de requisições:  Benefícios oferecidos pela vaga (via POSTMAN);

- Criação ou atualização automática das tabelas (Hibernate- MODEL);

- Segurança no Código: Sigilo de dados sensíveis/prescindíveis (payloads, DTO,Converter);
	
- Validação de Dados: Campos que NÃO  podem estar vazios;

- Testes - Início de implementação de teste unitário de métodos;

- PROCEDURE PL/SQL: Consulta candidatos por distância (LAT,LONG);

#### Sprint 03.

- BD - PROCEDURE  de devolução de listas por Múltiplos  Critérios com CURSOR;

- BD - População do BD com dados fictícios para teste de PERFORMANCE;

- Back-end - 2a API-JN para buscar quantidade de meios de transporte necessárias ao candidato chegar ao local de trabalho;

- Back-end - MATCH Candidato-Vaga;

#### Sprint 04.
#### 06 de junho de 2021.

# Back-end - Criação pesquisa por Múltiplos Critérios (Priority);

# BD - Busca por qualquer critério (Priority);

- Adaptação do Código para novas classes e tabelas;

- Adaptação do BD para novas tabelas;

#### Apresentação Final - 11 de junho de 2021.

- Bugs e Documentação;

#### Feira de Soluções - 18 de junho de 2021.


## Equipe:

#### Caroline Paz de Sousa (Java back-end developer)
* [Git Lab](https://gitlab.com/CarolPaz)
* [Linkedin](https://www.linkedin.com/in/caroline-sousa-53a27972/)
* RA: 1460281923049

#### Fabio Odaguiri LL.M. (Scrum master e database developer)
* [Git Lab](https://gitlab.com/ODAGAMMXIX)
* [Linkedin](https://www.linkedin.com/in/fabioodaguiri/)
* RA: 1460281923008

#### Felipe Santos Carvalho (Product owner e database developer)
* [Git Lab](https://gitlab.com/felipefsc)
* [Linkedin](https://www.linkedin.com/in/felipe-santos-carvalho-454060187/)
* RA: 1460281923011

#### Gabriela Momilli (Java back-end developer)
* [Git Lab](https://gitlab.com/gabsmomilli)
* [Linkedin](https://www.linkedin.com/in/gabriela-momilli-105b1a184/)
* RA: 1460281923058

#### Rafael Estevam de Oliveira (Oracle dabase developer)
* [Git Lab](https://gitlab.com/rafaelEstevam)
* [Linkedin](https://www.linkedin.com/in/rafael-estevam-de-oliveira/)
* RA: 1460281823040

#### Wilson Amore Vieira Filho (Java back-end developer)
* [Git Lab](https://gitlab.com/ZVIEWIL)
* [Linkedin](https://www.linkedin.com/in/wilson-amore-vieira-filho-7a4420183)
* RA: 1460281923041

## Running it up
Deployment
No seu dispositivo
Vide Pasta "DEPLOYMENT-FIND-STEPS-HERE" acima)

## Ferramentas Tecnologicas
💻

- Oracle 11g (Sql developer)
- Java (IntelliJ / Eclipse))
- Javascript )Node-JS)
- React (Insomnia/POSTMAN)
- Git (GitLab)
- OBS Studio / Kdenlive

