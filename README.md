<h1 align="center">AUTOMAÇÃO DE CADASTRO COM PYAUTOGUI</h1>			
<br>
<h4 align="center"> 🚀 Concluído 🚀 </h4>
	

Tabela de conteúdos
=================
<!--ts-->
   * [Sobre o projeto](#-sobre-o-projeto)
   * [Layout](#-layout)
   * [Como executar o projeto](#-como-executar-o-projeto)
     * [Pré-requisitos](#pré-requisitos)
     * [Funcionalidades](#funcionalidades)
     * [Guia do Usuário](#guia-do-usuário)
   * [Tecnologias](#-tecnologias)
   * [Autor](#-autor)
   * [Licença](#-licença)
<!--te-->


## 💻 Sobre o projeto

Este projeto automatiza o preenchimento de formulários web com base em dados extraídos de arquivos CSV. A automação é feita com Python usando a biblioteca PyAutoGUI para simular a interação do usuário com o navegador (abrir o Chrome, preencher campos e enviar formulários). Os dados são lidos com a biblioteca Pandas e utilizados para alimentar os campos de cadastro de produtos em um site específico.

Principais vantagens:
- Eliminação de tarefas repetitivas
- Redução de erros manuais
- Ganho de tempo em processos de entrada de dados

---

## 🚧 Problemas resolvidos

```bash
❌ Entrada manual de dados
	Antes: cada produto era inserido manualmente no sistema web.
	Depois: todos os produtos são inseridos automaticamente com precisão.
	⏱ Redução de tempo: de horas para segundos por item.
```
```bash
❌ Erros de digitação e inconsistência
	Antes: alta taxa de erros por digitação e campos incompletos.
	Depois: os dados são lidos diretamente de um CSV validado.
	✅ Precisão aumentada: redução de praticamente 100% dos erros humanos.
```
```bash
❌ Trabalho repetitivo e cansativo
	Antes: era necessário repetir os mesmos cliques e comandos dezenas de vezes.
	Depois: um único clique inicia toda a operação.
	🧠 Melhoria na produtividade: permite foco em tarefas mais estratégicas.
```
## 🎨 Layout
### A automação segue um fluxo visual orientado por scripts:

<p align="center" style="display: flex; align-items: flex-start; justify-content: center;"> <img alt="Automação com PyAutoGUI" title="#pyautogui-automation" src="https://i.pinimg.com/originals/48/49/94/484994f3c735c6cf0282a420d5fd203b.png" style="width:500px";/> </p>

```bash
Componentes Principais:
- pyautogui: Biblioteca para simular cliques, digitação e rolagens.
- pandas: Leitura e manipulação dos dados CSV.
- Chrome: Navegador padrão onde o formulário web é preenchido.
- produtos.csv: Arquivo contendo os dados dos produtos a serem cadastrados.
```
## 🚀 Como executar o projeto
### Pré-requisitos

- Python 3 instalado
- Google Chrome instalado e como navegador padrão
- Bibliotecas: pyautogui, pandas
- Arquivo produtos.csv no mesmo diretório do script

### Instalação:
```bash
pip install pyautogui pandas
```

- Ajuste a posição dos cliques (pyautogui.click(x=..., y=...)) conforme seu monitor.

- Edite o CSV com os dados reais dos produtos.

- Execute o script Python e não mova o mouse durante a execução.

### Funcionalidades

```bash
Abrir o navegador:
  A automação abre o navegador Chrome automaticamente.

Login no sistema:
  Preenche o campo de login e senha de forma simulada.

Leitura de CSV:
  Utiliza pandas para extrair os dados do arquivo produtos.csv.

Preenchimento do formulário:
  Percorre campo a campo preenchendo com os dados do produto.

Envio automático:
  Submete o formulário e reinicia o processo com o próximo item.
```
### Guia do Usuário:
```bash
1. Prepare o arquivo produtos.csv com os dados dos produtos.
2. Execute o script Python com o ambiente configurado.
3. O sistema abrirá o navegador, fará o login e iniciará o cadastro automático.
4. Aguarde a finalização da automação e não interfira com o teclado/mouse durante o processo.
```
## 🛠 Tecnologias
### As seguintes tecnologias foram usadas na construção do projeto:

- Python
- PyAutoGUI
- Pandas
- Automação de Interface Gráfica

## 🦸🏻‍♂️ Autor

 <br>
  <sub><b><p>Christopher Silva</p></b></sub></a>
 <br />

[![Linkedin Badge](https://img.shields.io/badge/-Christopher%20Silva-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/chris-f-silva//)](https://www.linkedin.com/in/chris-f-silva/) 
[![Gmail Badge](https://img.shields.io/badge/-chrisspfc.silva@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:daniel.rodrigues.soarees@gmail.com)](mailto:chrisspfc.silva@gmail.com)

---

## 📝 Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para mais detalhes. [MIT](./LICENSE)

Feito por: Christopher Silva
