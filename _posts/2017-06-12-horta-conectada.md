---
layout:     post
title:      Horta Conectada
date:       2017-06-12 22:21:29
summary:    Criando minha horta conectada.
categories: horta iot
---

Há algum tempo venho querendo automatizar minha horta. O problema é que eu não tinha horta hahah!
Todas as vezes que plantava minhas hortaliças a correria do dia-a-dia fazia com que morressem (falta de água ou excesso de sol msm  ¯\_(ツ)_/¯ ).

Agora, finalmente plantei tomates e estão crescendo (Yeahh!). Fazem 3 semanas e olha só como estão:

![desk](https://user-images.githubusercontent.com/987594/27019201-dafdc586-4f0c-11e7-817c-810edd159b7e.JPG)_

### Próximo passo
Agora que já tenho tomates crescendo saldáveis chegou a hora de automatizar. Para isso pesquisei um pouco sobre o projeto [OpenAg](http://openag.media.mit.edu) (Open Agriculture) do MIT, um projeto de "Máquina de comida", um equipamento que acelera o crescimento das plantas e trabalha com Aeroponia e Hidroponia. No meu caso vou manter o método clássico, mas pretendo construir o sistema de luzes de crescimento, para acelerar um pouco o crescimento do meu tomate ;D

### O Projeto
A ideia é criar um sistema conectado com a internet que controle as luzes (pois devem ser ligadas nos momentos certos) e também a irrigação. Vou tentar ao máximo usar o conceito de "ServiceLess", que consiste em usar serviços prontos e não precisar criar um back-end (programa que roda num servidor e conversa com site, app ou outra aplicação de interface com o usuário ~ front-end ~). Portanto a ideia aqui é que seja tudo automático mas permita alterações nos controles e também envie feedback sobre sensores e o funcionamento do sistema. Ainda não defini qual será esta interface para o controle (pode ser voz ou um bot).

### Os materiais
* Bomba de aquário (ou similar)
* Fita de LED RGB endereçavel
* Node MCU v3
* Fonte de Energia 5V 1A
* Sensor de Temperatura/Humidade Ar
* Sensor de Luz
* Sensor de Humidade do Solo
* Mangueira/Tubo
* Suporte em acrilico ou madeira para o sistema

É isso, agora vou verificar se faltou algo e comprar os materiais.
