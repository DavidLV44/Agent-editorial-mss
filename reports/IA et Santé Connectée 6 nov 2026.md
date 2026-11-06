# athenahealth + Claude, ESC Basel, PATIENT AI Act : la semaine s'accélère

*Compte rendu quotidien — IA & Santé Connectée | 6 novembre 2026 | mysentinelsolutions.com*

---

## Synthèse du jour

Cette semaine marque une double accélération : côté interopérabilité, l'intégration officielle des dossiers médicaux athenahealth dans Claude (Anthropic) est désormais live aux États-Unis, ouvrant un nouveau front dans la bataille pour l'accès patient aux données de santé. Côté régulation, le sénateur Cassidy publie le draft du PATIENT AI Act, première tentative américaine sérieuse d'encadrer la revue continue des logiciels IA médicaux — avec un appel à contributions avant le 1er décembre. En Europe, le compte à rebours est lancé pour l'ESC Digital & AI Summit (12–13 novembre, Bâle).

---

## 1. athenaPatient MCP : les dossiers médicaux entrent dans Claude

Le 2 novembre, **athenahealth** a lancé **athenaPatient MCP**, un connecteur officiel basé sur le protocole ouvert **Model Context Protocol (MCP)** d'Anthropic. Il permet aux abonnés **Claude Pro** et **Claude Max** aux États-Unis d'accéder à leurs données médicales directement dans Claude.

**Données accessibles :** résultats de laboratoire, médicaments, constantes vitales, pathologies, comptes rendus diagnostiques, immunisations, historique de consultations, allergies, procédures, plans de soins.

**Mécanisme :** les patients s'authentifient avec leurs identifiants du portail athenahealth et choisissent ce que Claude peut voir. athenahealth précise que ses identifiants ne sont pas transmis à Anthropic. L'accès est restreint aux IA qui n'utilisent pas les données patients pour entraîner leurs modèles.

**Le point de vigilance :** les abonnements Claude Pro/Max sont des offres grand public — Anthropic ne signe pas de **Business Associate Agreement (BAA)** pour ces plans. L'outil est destiné aux patients, pas aux cliniciens, et ne constitue pas une solution clinique HIPAA-compliant. Ce distinguo sera central dans les débats sur l'adoption.

**Pourquoi c'est important :** c'est la première fois qu'un DPI (Dossier Patient Informatisé) majeur déploie un connecteur MCP officiel pour Claude. Cela positionne le MCP d'Anthropic comme une infrastructure d'interopérabilité santé — avec un précédent qui pourrait accélérer les intégrations Epic, Oracle Health et autres.

---

## 2. PATIENT AI Act (Cassidy) : la FDA face à l'IA adaptive

Le sénateur républicain **Bill Cassidy** a publié fin octobre le draft du **PATIENT AI Act**, soumis à consultation jusqu'au **1er décembre 2026**.

**Contenu clé :**
- Autorité élargie de la FDA pour réviser les **modifications de logiciels IA** en continu (rolling review), adaptée aux modèles qui apprennent et évoluent
- Création d'une **voie de remboursement Medicare/Medicaid** pour accélérer l'adoption des dispositifs IA validés
- Cadre de prévisibilité réglementaire pour les industriels — sans sacrifier la sécurité patient

**Le diagnostic de Cassidy :** la réglementation FDA actuelle est conçue pour des dispositifs statiques ; elle ne convient pas aux logiciels IA qui s'améliorent dans le temps. L'objectif est de combler ce vide sans créer un cadre fédéral unifié — le sénateur préconise des régulations sectorielles ciblées.

**Contexte législatif :** ce draft intervient après la publication en août 2026 de l'étude PLOS Digital Health révélant que seulement 3 des 1 357 dispositifs IA autorisés par la FDA ont été testés sur des résultats patients réels. La pression réglementaire monte des deux côtés de l'Atlantique.

**À surveiller :** la fenêtre de consultation se ferme le 1er décembre — les industriels healthtech ont intérêt à s'y positionner.

---

## 3. ESC Digital & AI Summit — Bâle, 12–13 novembre

L'édition 2026 du sommet de la Société Européenne de Cardiologie dédié au numérique et à l'IA se tient dans six jours au **Congress Center Basel**. Programme :

- **Deux keynotes** sur les agents IA médicaux et l'avenir de l'IA en cardiologie
- **12 symposia** : détection précoce par wearables et apps, IA inclusive, implémentation en point-of-care, financement de l'innovation numérique
- **Hackathon inaugural** — première édition avec compétition en direct
- **Tables rondes** sur les freins à l'adoption de l'IA au chevet du patient

**Leadership :** Folkert Asselbergs, Sandy Engelhardt, Nico Bruining. Après l'événement, les présentations seront disponibles sur **ESC 365** pendant un an.

---

## 4. Royaume-Uni : l'IA pourrait réduire les effectifs du NHS — Cooper devant les MPs

Le 4 novembre, la ministre de la Santé **Yvette Cooper** a déclaré devant les parlementaires que l'IA pourrait réduire les besoins en effectifs dans certaines parties du NHS. Conséquence immédiate : le **plan décennal sur les effectifs NHS** est repoussé au premier trimestre 2027.

**Réactions :**
- **Royal College of Nursing** : demande une pause du plan, arguant qu'il ne prévoit pas de croissance d'effectifs suffisante et sur-estime les capacités de l'IA
- **British Medical Association** : l'IA ne peut pas remplacer les médecins
- **Gouvernement :** le fonds IA de £900 millions vise l'intégration d'outils sans réduction des effectifs — message contradictoire avec les déclarations de Cooper

**Lecture :** ce débat illustre la tension systémique entre les promesses d'efficience de l'IA et les réalités syndicales et de gouvernance. Le Royaume-Uni devient un observatoire en temps réel de ce dilemme.

---

## 5. PulseAI : FDA 510(k) pour la détection IA de l'arythmie sur wearables

**PulseAI** a annoncé le 5 novembre l'obtention de la **clearance FDA 510(k)** pour son modèle d'analyse IA des arythmies sur dispositifs portables.

**Performances cliniques** (étude Heart Rhythm, 296 participants) :
- Amélioration significative de la sensibilité de détection FA vs algorithme natif Apple Watch
- **Réduction de 92 %** des interprétations non conclusives

**Signification :** au-delà des performances brutes, cette clearance démontre que les algorithmes tiers peuvent obtenir une autorisation FDA pour améliorer des plateformes wearables existantes — sans dépendre d'un accord OEM. Un modèle industriel à surveiller.

---

## 6. France : patients vs IA, et 17 M€ pour la patho numérique

**Baromètre soignants :** selon un baromètre relayé par franceinfo, **38 % des professionnels de santé** ont constaté qu'un patient a contesté leur diagnostic après avoir consulté une IA, et **28 %** ont vu un patient refuser un traitement prescrit. Signal de tension croissante entre IA grand public et autorité médicale.

**InnoPath-Fr :** l'État et Bpifrance ont accordé **17 M€** au consortium porté par le CHU de Reims et Enovacom pour développer une plateforme souveraine d'**anatomopathologie numérique**. Objectif : traitement IA des lames histologiques dans les flux cliniques — en cohérence avec les travaux de l'article arXiv sur STEP (voir rapport du 2 novembre).

**Agenda France :** les **Universités de la e-santé** se tiendront les **18–19 novembre 2026** (TICsanté).

---

## 7. Signal de gouvernance : IA autonome sans cadre

Une note de veille sectorielle (Yesil Science, semaine du 2 novembre) alerte sur un phénomène émergent : des **logiciels IA autonomes** exécutent désormais des actions à l'intérieur de systèmes de santé — avant que les cadres de gouvernance soient en place pour encadrer ces décisions.

Ce signal rejoint les observations du dernier rapport sur les agents IA de triage clinique (arXiv 2603.09052). La question n'est plus "est-ce que l'IA peut agir ?" mais "qui est responsable quand elle agit ?"

---

## Signaux à surveiller cette semaine

| Signal | Intensité | Tendance |
|--------|-----------|----------|
| Interopérabilité DPI + IA (athenahealth/Claude MCP) | 🔴 Très fort | ↑ Nouveau |
| Régulation FDA adaptive (PATIENT AI Act) | 🟠 Fort | ↑ Nouveau |
| ESC Digital & AI Summit Bâle (12–13 nov) | 🟠 Fort | → À suivre |
| NHS / IA et effectifs (UK) | 🟡 Modéré-fort | ↑ |
| IA autonome sans gouvernance | 🟡 Modéré | ↑ Signal émergent |
| Wearables FA / PulseAI FDA | 🟢 Modéré | → Stable |

---

## Agenda — Novembre 2026

- **10–11 nov.** — aiHealth2026, Muttenz / Bâle (FHNW)
- **12–13 nov.** — ESC Digital & AI Summit, Bâle *(EN APPROCHE)*
- **16–17 nov.** — MEDICA 2026 + WT Conference Europe, Düsseldorf
- **18–19 nov.** — Universités de la e-santé, France

---

## Contenu réseaux sociaux

### LinkedIn (post long)

> Vos dossiers médicaux dans votre IA personnelle. C'est maintenant possible.
>
> Depuis le 2 novembre, athenahealth permet aux patients américains de connecter leurs données de santé directement à Claude (Anthropic) — via le protocole ouvert MCP. Résultats de labo, médicaments, antécédents, plans de soins : tout accessible dans une conversation IA.
>
> C'est un tournant pour l'interopérabilité en santé. Mais aussi un signal d'alerte : ces plans sont des offres grand public. Pas de BAA HIPAA. L'outil est pensé pour le patient informé, pas pour le clinicien en responsabilité.
>
> En parallèle, le sénateur Cassidy publie le draft du PATIENT AI Act — première tentative sérieuse aux États-Unis d'adapter la réglementation FDA aux logiciels IA qui apprennent et évoluent dans le temps. Consultation ouverte jusqu'au 1er décembre.
>
> Deux mouvements simultanés : l'accès aux données se libéralise, et la gouvernance tente de rattraper son retard.
>
> La tension de fond reste la même : qui est responsable quand l'IA agit dans un système de santé — et sur quelle base a-t-elle été autorisée à le faire ?

*#SantéConnectée #IA #DigitalHealth #Interopérabilité #FDA #HealthTech #HIPAA #EHR*

---

### X / Twitter

> athenahealth connecte les dossiers médicaux patients à Claude (Anthropic) via MCP.
>
> Première intégration DPI → IA grand public officiellement live aux États-Unis.
>
> Pendant ce temps, le sénateur Cassidy propose le PATIENT AI Act : une FDA capable de réviser les logiciels IA en continu.
>
> L'accélération est réelle. Le cadre de responsabilité, lui, court derrière.

*#HealthTech #IA #FDA #EHR #DigitalHealth #MCP*

---

*Sources principales : Fierce Healthcare (athenahealth/Claude MCP) · Digital Health News · Healthcare IT News (PATIENT AI Act) · ESC Cardio / Europawire (ESC Digital & AI Summit) · PR Newswire (PulseAI FDA) · resultsense.com (Cooper/NHS) · franceinfo (baromètre soignants) · Yesil Science Health AI Brief 2026-11-02*
