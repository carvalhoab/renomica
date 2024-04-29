---
title: Equipe
nav:
  order: 3
  tooltip: Conheça a nossa equipe
---

# {% include icon.html icon="fa-solid fa-users" %}Equipe

A RENOMICA só é possível porque tem a contribuição de inúmeros cientistas, médicos, biomédicos, enfermeiros, fisioterapeutas, farmacêuticos e biólogos espalhados pelo Brasil.

## <center> COORDENADORES <center>

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

## <center> PROFISSIONAIS DE SAÚDE <center>

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

## <center> ESTUDANTES <center>

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}
