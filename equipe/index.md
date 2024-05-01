---
title: Equipe
nav:
  order: 3
  tooltip: 
---

# {% include icon.html icon="fa-solid fa-users" %}Equipe

A RENOMICA só é possível porque tem a contribuição de inúmeros cientistas, médicos, biomédicos, enfermeiros, fisioterapeutas, farmacêuticos e biólogos espalhados pelo Brasil. Conheça nossos profissionais.

{% include section.html %}

## <center> COMITÊ GESTOR <center>

{% include list.html data="members" component="portrait" filters="role: pi, group: coord" %}

{% include section.html %}

## <center> PESQUISADORES <center>

{% include list.html data="members" component="portrait" filters="role: programmer, group: pesq" %}

{% include section.html %}

## <center> PÓS-GRADUANDOS <center>

{% include list.html data="members" component="portrait" filters="role: phd, group: est" %}
