[![](https://img.shields.io/badge/IBM%20Cloud-powered-blue.svg)](https://cloud.ibm.com)
[![Platform](https://img.shields.io/badge/platform-nodejs-lightgrey.svg?style=flat)](https://developer.ibm.com/node/)

## 1. Desafio

O controle de pragas continua sendo um grande desafio para empresas do ramo do agronegócio. Saber identificar rapidamente qual agente está se aproveitando da lavoura é vital para que se possa tomar a ação mais adequada sem comprometer uma grande parte da safra.

As pragas são amplamente conhecidas e, o que falta é um mecanismo rápido de identificação que auxilie o agrônomo na sua tarefa de proteger a lavoura. Sua tarefa é auxiliar na criação dessa ferramenta e aproximar a tecnologia do campo, pois, afinal, agro é tech.

A ideia do desafio é auxiliar o dia a dia do produtor, fornecendo para ele uma ferramenta de reconhecimento visual que o ajude a identificar as pragas.

## 2. Objetivo

O objetivo deste desafio é criar um sistema automático de identificação das pragas que atingem a lavoura de soja citadas acima. Para esse desafio aconselhamos que o participante utilize o _IBM Watson Visual Recognition_ e monte o seu classificador através dele. Antes o participante terá que separar manualmente as imagens da base nas classes citadas anteriormente. Caso considere pertinente, cada participante pode manipular as imagens da base previamente afim de melhorar a acurácia de classificação do modelo do Watson Visual Recognition.

Vamos focar somente nas quatro principais pragas que atigem a lavoura de soja, são elas:

1. Lagarta da soja
2. Percevejo marrom
3. Percevejo pequeno
4. Percevejo verde

*Obs: Os nomes das classes esperadas são apresentados mais abaixo. Não utilize os nomes acima como nome das classes.*

Sua tarefa é buscar imagens dessas pragas e criar um modelo de reconhecimento visual capaz de identificar corretamente cada uma delas, de modo que o agrônomo consiga dar o tratamento adequado.

## 3. Resumo das tarefas

1. Instanciar o IBM Watson Visual Recognition na IBM Cloud;
2. Instanciar o Watson Studio (Cloud Pak for Data as a Service) na IBM Cloud;
3. Instanciar o Cloud Object Storage na IBM Cloud;
4. Buscar por imagens que representam as classes especificadas: `lagarta`, `percevejo_marrom`, `percevejo_pequeno` e `percevejo_verde`;
5. Treinar o modelo;
6. Subir a aplicação de submissão;
7. Acessar a aplicação de submissão e submeter sua solução.

## 4. Preview Online

<a href="https://bit.ly/ibm-challenge">Clique aqui</a>

## 5. Preview Image

<div align="center" >
  <img src="https://i.ibb.co/Xk9bYgy/cocamartwo.jpg">
</div>

<div align="center" >
  <img src="https://i.ibb.co/0hHT7mT/0-1.jpg">
</div>

<div align="center" >
  <img src="https://i.ibb.co/j5gJ5sC/0-2.jpg">
</div>

<div align="center" >
  <img src="https://i.ibb.co/D9HRMkL/image.jpg">
</div>

<div align="center" >
  <img src="https://i.ibb.co/25DK4v3/1597636353389.jpg">
</div>

</br>

[LinkedIn](https://www.linkedin.com/in/kelvenluiz/) | [Email](mailto:kelvenluiz@usp.br) </br>
Made with by Kelven Luiz