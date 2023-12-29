---
language: @(Projekt.shortlang)
author:  @(Autor['name'])
email: @(Autor['mail'])
title: @(Projekt.title)
pagetitle: @(Projekt.pagetitle)
subtitle: @(Projekt.subtitle)
shorttitle: @(Projekt.shorttitle)
cover: @(Projekt.cover)
date: @(Monat[heute.month].MMMM) @(heute.year)
git: @(GetShortGITHash "")
---
@include "BuchfuehrungWiedereinstieg.md"
