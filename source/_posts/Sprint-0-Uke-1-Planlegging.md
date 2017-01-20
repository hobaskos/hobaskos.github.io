---
title: 'Sprint 0 - Uke 1 : Planlegging.'
date: 2017-01-13 18:50:50
tags:
---

Denne uken har vi vært hos Accenture hele uken, hvor vi har jobbet mest med planlegging av oppgaven. En av de viktigste problemstillingene var hvilke platformer vi skulle utvikle applikasjonen for. Her har vi diskutert og drøftet utvikling av applikasjon for Android versus iOS versus hybrid-app. Det blir ganske tidlig enighet om at å utvikle en hybrid-app vil medføre en mulig stor og ukjent risiko ettersom ingen av oss har vært borte i utvikling av hybrid-apps tidligere. "Stackoverflow-testen" viser også at det er veldig få spørsmål knyttet mot hybrid-app kontra native Android/iOS. Vi tolker dette som at hybrid-apps ikke i så stor grad blir brukt i næringslivet. 

## Android vs iOS

Den optimale løsningen ville vært å utvikle to native apper (kanskje tilogmed tre: windows); en for Android, og en for iOS, men på grunn av ressurser går vi raskt bort fra denne innfallsvinkelen. Dermed må vi finne ut hvilken plattform vi skal utvikle for. 

Det er enighet i hele gruppen om at det å utvikle en native applikasjon for iOS er det som er mest intressant med tanke på læring, og for å nå flest brukere. Uheldigvis så må man bruke en IDE som heter XCode for å utvikle for iOS, og XCode krever at man benytter Mac. Kun 1 av 4 på gruppen disponerer Mac, så vi går dermed vekk fra hele iOS platformen. 

## Vinneren er Android 

Da er det Android som står igjen som vinneren. Vi ønsker å kombinere Android-appen med et REST-backend som blir skrevet i Spring Boot. 

## Arbeidsmetodikk

Ettersom Accenture benytter Scrum så ønsker vi også å utvikle programvaren ved bruk av smidig arbeidsmetodikk, hvor vi definerer en rekke epics, users stories, issues. Vi skal jobbe i sprinter hvor vi har satt hver sprint til å være to uker. 

Vi skal benytte JetBrains: YouTrack som "Issues Tracking og Project Management" verktøy. 

Utover dette har vi blitt enige om å splitte gruppen i to slik at en gruppe har hovedansvar for android-appen og en gruppe har hovedansvar for server. Samtidig så ønsker vi at hele gruppen skal ha någenlunde oversikt over det meste av kodebasen. For å opprettholde dette innfører vi et sprintmøte den hver mandag hvor vi diskuterer hvordan vi ligger ann. Hver fredag skal vi ha et code-review møte hvor vi raskt går igjennom ukens "commits" slik at vi enkelt kan holde hele gruppen oppdatert over hvordan kodebasen utvikler seg. 

## Milepæler

Vi har i forbindelse med forprosjektrapporten definert et sett med Milepæler etter ønske av veilederen vår ved Høgskolen i Oslo og Akershus. 

20. januar - Forprosjektrapport (Deadline)
8. mars - Midtrapport og presentasjon (Deadline)
1. mai - Kodefrys 
25. mai Sluttrapport 