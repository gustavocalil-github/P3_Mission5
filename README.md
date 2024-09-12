![Capa do projeto com logo da Estácio](logo_m5.svg)

<div align="center">

---

[Projeto](#-projeto) • [Como baixar e executar](#-como-baixar-e-executar) • [Procedimentos](#-procedimentos) • [Tecnologias utilizadas](#-tecnologias-utilizadas) • [Autor](#-autor) • [Licença](#-licença)

---

</div>

## 📋 Projeto

Missão Prática com o objetivo de desenvolver servidor e client Java utilizando Sockets, com acesso a banco de dados via JPA e implementação de Threads para processamento paralelo apresentado no **`Nível 5: Por que não paralelizar?`** do **`Mundo 3`** do curso de **`Desenvolvimento Full Stack`** da **`Estácio`**, do semestre de **`2024.2`**, sob a tutoria de Guilherme Dutra Gonzaga Jaime.

Projeto elaborado de acordo com as diretrizes especificadas para a Missão Prática, que podem ser conferidas [**`clicando aqui`**](https://sway.cloud.microsoft/s/6eQbYBJ7lKlCFXm9/embed).

## 📥 Como baixar e executar

Para baixar os arquivos deste repositório, você deve ter o [GitHub](https://github.com/) instalado em seu dispositivo.



Além disso, faz-se necessário ter previamente instalado os softwares [SQL Server](https://www.microsoft.com/pt-br/sql-server/sql-server-downloads) e [SQL Server Management Studio](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16#download-ssms), além de uma IDE para desenvolvimento em Java.

## 🔗 Procedimentos

Durante o projeto foram desenvolvidos 03 procedimentos descritos abaixo:

<table>
  <tr>
    <th>Procedimento</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td>Criando o servidor e cliente de teste</td>
    <td>
      <ul>
        <li>Criar o projeto do servidor com a implementação do protocolo de conexão.</li>
        <li>Configurar a camada de persistência.</li>
        <li>Implementar a camada de controle para validação de credenciais.</li>
        <li>Adicionar uma Thread de comunicação no servidor para lidar com múltiplos clientes.</li>
        <li>Criar o cliente de teste para interagir com o servidor.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>Servidor completo e cliente assíncrono</td>
    <td>
      <ul>
        <li>Aprimorar a Thread de comunicação do servidor para aceitar comandos de entrada e saída de produtos.</li>
        <li>Criar um cliente assíncrono capaz de enviar e receber mensagens do servidor de forma interativa.</li>
        <li>Configurar uma janela para apresentação de mensagens no cliente assíncrono.</li>
        <li>Definir uma Thread de preenchimento assíncrono para atualizar dinamicamente a interface do cliente com as mensagens recebidas do servidor.</li>
      </ul>
    </td>
  </tr>
</table>

Para acessar o relatório da Missão Prática, clique no botão abaixo:

<div align="center">

[![Link de acesso ao relatório](https://img.shields.io/badge/-Acesse%20o%20relatório-000000?style=for-the-badge)](./Universidade%20Estácio%20de%20Sá%20P3%20-%20M5.pdf)

</div>

## 🛠 Tecnologias utilizadas

Para a construção e execução do projeto foram utilizadas as seguintes tecnologias:

<div align="center">

[![NetBeans](https://img.shields.io/badge/-NetBeans-1B6AC6?style=for-the-badge&logo=apachenetbeanside&logoColor=white)](https://netbeans.apache.org/front/main/download/index.html) [![Java](https://img.shields.io/badge/-Java-e82d2c?style=for-the-badge&logo=java&logoColor=white)](https://www.oracle.com/br/java/technologies/downloads/) [![SQL Server Management Studio](https://img.shields.io/badge/-SQL%20Server%20Management%20Studio-2f2f2f?style=for-the-badge)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16#download-ssms)

</div>

## 👥 Autor

| Aluno                                                  | Matrícula    | E-mail                                      |
| ------------------------------------------------------ | ------------ | ------------------------------------------- |
| [GUSTAVO CALIL](https://github.com/gustavocalil-github) | 202304625751 | [📧](mailto:202304625751@alunos.estacio.br) |

## 📃 Licença

Este repositório está licensiado sob a [Licença MIT](./LICENSE).

<div align=center>

</div>
