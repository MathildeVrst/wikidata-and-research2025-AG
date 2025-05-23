---
title: "Authoritative Practices and Collective Validation: Wikidata within the Collaborative Digital Edition of the *Greek Anthology*"
format: html
---

## Introduction @àdécider


- Hello, we are happy to be here 
- Not a surprise, Wikidata is now a commonly used tool in the DH community 
- (Parallèles) As DH, Wikidata functions as a knowledge base, enabling a sort of collective verification and semantic linking of information.

But somehow, that creates a conflict: Unlike traditional academic publishing, where authority is centralised and often restricted to established institutions or recognised experts, Wikidata operates through a model of continuous, multilingual, and community-based editing that promotes the dissemination of free and accessible knowledge globally. This paradigmatic shift invites a fundamental rethinking of authority, editorial responsibility, and the epistemological foundations of data.

- That brings us to the question with which we will work with today: 

How, then, can expert-led projects — whether developed by academics, government agencies or GLAM institutions <!--(Galleries, Libraries, Archives and Museums)--> — work with a generalist platform such as Wikidata to generate new forms of knowledge? How do these hybrid models, which combine scholarly expertise with public participation, challenge traditional boundaries between academic and amateur contributors, and between knowledge production and validation?

- In the next 20 minutes, we will : 
  - start by exploring how the infrastructure and logic of Wikidata can be integrated into DH projects 
  - talk a bit about the Anthologia Graeca project, a collaborative digital edition of the *Greek Anthology* 
  - We will analyse how Wikidata is embedded in the project’s data model — particularly through our treatment of the keyword “authors” — and how this integration opens new spaces for knowledge production.
  - Finally, drawing on those concrete examples, we will reflect on the tensions between authority and collective intelligence that shape such initiatives, and the ways in which digital infrastructures can both challenge and extend traditional scholarly practices.

## Wikidata and Digital Humanities @maxime

- à résumer en 1 minute (@maxime)

## Wikidata as a linking hub @maxime

- As you already know, one of the key benefits of Wikidata, as identified by many DH projects and GLAM institutions, is in its function as a hub for linking heterogeneous external resources and datasets (Neubert 2017). This is achieved through the creation of external identifier properties, which connect Wikidata items to their corresponding entities across different databases.

- Aller sur la page Wikidata de Mégara + liens qu'on cite 

Take, for example, the case of Megara, an ancient Greek πόλις (pólis) located in the northern part of the Isthmus of Corinth. Its Wikidata item is linked to a wide range of sources, including dictionaries, library catalogues and domain-specific databases on Greco-Roman antiquity, such as Pleiades, ToposText and MANTO. Through such links, Wikidata facilitates cross-referencing and acts as a form of authority control (Fagerving 2023). As LOD is designed to enrich data with contextual relationships, it becomes much more efficient to enrich a dataset either directly through Wikidata or through cross-queries across databases all linked to a common Q-item.

Some scholars have gone further, suggesting that Wikidata should not only serve as a hub for linking external identifiers, but should actually function as the reference identifier (Van Veen 2019). The multiplication of identifiers for the same entity (such as Megara) can lead to confusion and poor data reconciliation over time. Adopting Wikidata as a universal identifier could offer several benefits: a unified description model, a single SPARQL endpoint and API for querying, and a sustainable infrastructure for data access and storage.

While this position may seem more radical, it highlights another important aspect of Wikidata’s relationship with external resources: that of reciprocal contribution. As demonstrated in a paper on the interaction between Wikidata and VIAF — a global platform that aggregates name authority files from multiple institutions — bi-directional comparison and contribution can improve data quality on both sides (Bianchini, Bargioni, and Pellizzari di San Girolamo 2021). In this way, GLAM institutions such as libraries can not only contribute to Wikidata but also benefit from it.

## Authority on Digital Platforms @maxime

This brings us to our central question: how can academic projects and Wikidata be mutually enriching, given the different systems of validation and recognition that operate within each other? While many Wikidata editors have deep expertise, the platform’s structure is built on principles of openness, peer consensus, and collaborative editing rather than formal academic credentials. In contrast, academia tends to associate authority with disciplinary expertise, institutional affiliation, and scholarly output. Similarly, institutions such as governments or GLAM organisations are often recognised as authoritative because of their perceived reliability and structured oversight. These different frameworks can create asymmetries in how contributions are valued and trusted: while academia often operates through top-down models of validation, collaborative platforms like Wikidata rely more on distributed forms of consensus. Understanding and negotiating these differences is key to enhance productive dialogue and collaboration between the two ecosystems. 

We argue, however, that this top-down hierarchy model is contextual and not always best suited for knowledge dissemination, particularly in the case of digital platforms. As collaborative, crowdsourced, and peer-contributed infrastructures like Wikidata increasingly assert themselves as alternative forms of authority — both within and beyond academia — they challenge conventional assumptions about data reliability and the guaranty of expertise. This is mainly because, in most cases, anyone can contribute to these platforms, leading some to question the quality of the data (Santos, Schwabe, and Lifschitz 2024). 

The status of Wikidata editors as authoritative actors is therefore often questioned. Many scholars and professionals consider them to be amateurs5 or citizen scientists rather than experts. Despite the increasing involvement of non-professionals in cultural initiatives, especially online, their contributions often remain undervalued or require validation by recognised professionals to be considered reliable. This tension highlights the ambiguous relationship between new actors in knowledge creation and traditional epistemic authorities who are still unsure about how to integrate them. 

In Wikidata, this dynamic manifests in conflicting perceptions of authority. While the platform is designed to support collaborative knowledge production and open participation, its data is frequently considered trustworthy only when curated or approved by recognised experts. Yet, recent studies suggest that although Wikidata still has room for improvement, the platform is increasingly being recognised as a high-quality knowledge graph — one whose quality depends on context and must be assessed on a case-by-case basis (Piscopo and Simperl 2019; Shenoy et al. 2022; Zhao 2023). The platform’s growing and active community contributes significantly to its data quality, while tools such as Shape Expressions (ShEx) Schemas are being implemented to enforce model conformity and internal consistency (see Thornton et al. 2019; Thornton, Seals Nutt, and Chen 2024). These community-driven standards not only support data consistency but also reflect the platform’s commitment to a decentralised yet structured form of knowledge governance. 

One of the most effective ways to ensure the quality and relevance of Wikidata is not only to assess it from the outside, but rather to engage directly with it. Through engagement with the platform — adding statements, creating data models, correcting mistakes, and discussing over ontologies — researchers, cultural institutions and engaged amateurs alike help to shape the platform and its knowledge graph. Wikidata is not a finished product to be critiqued, but an open, iterative space where quality emerges through collective interaction.

Another way to reconceptualise authority in DH projects is to integrate Wikidata not only as a reference point, but as a core infrastructural layer for data modelling, curation and publication. In this way, the authoritative role traditionally held by academic experts is distributed and shared with a broader community of Wikidata contributors. Authority is thus reframed — not as a fixed attribute derived from institutional status, but as an emergent property of collaborative practices. Such reframing invites researchers to reconsider their own position — not above or outside the platform, but alongside a distributed network of contributors who collectively construct meaning, value, and trust in data. 

In order to examine these dynamics more thoroughly, we now turn to our case study: the AG project. We will examine how the project builds its digital infrastructure around Wikidata, collective intelligence and participatory practices to challenge and reshape the status of authoritative figures within academic knowledge production.

## A collaborative and digital edition of the *Greek Anthology* 

- Présenter le projet 
- Présenter l'historique des plateformes 
- Parler rapidement des partenaires éventuellement (ou pas) 
- Keyworkds dans l'AG 

## The Authors of the *Greek Anthology*

- On va revenir sur la réalisation d'un chantier qui a été particulièrement long: celui du "nettoyage" des auteurs présents jusqu'alors sur la plateforme. 
- Pour la plupart, assez facile, pour d'autres, beaucoup moins : 

### Phanias

### Diodoros 

### Dionysios

### Archias 


- Marcello voulait aussi aller plus loin en ajoutant les floruit des auteurs etc, ce que j'ai refusé (manque de sources) -- Maxime a dit qu'on pouvait utiliser les références (dont j'admets ne pas avoir connaissance à l'époque, oups) -> à voir, un jour peut-être 
- Wikidata utilisé dès lors pour des connaissances qui sont relativement fragmentaires à l'image de notre objet d'étude 

## Some comments on the outcome and future work @mathilde 

- Faire la même chose pour les autres types de mots-clés (villes -- presque fini) et les personnages, les thèmes, etc. ce qui fait émerger de nouvelles questions méthodologique etc (donner les exemples)
- travail en cours, on est heureux d'avoir vos retours dessus et on veillera à les intégrer à notre pratique 

## Conclusion @maxime

Wikidata is not just a technical tool for data storage and retrieval; it is a dynamic epistemic space where academic knowledge is collaboratively shaped, revised, and legitimised. By delegating (while taking part of) some of our curatorial authority to Wikidata, the AG project participates in a broader shift towards distributed models of knowledge production (Benkler, Shaw, and Mako Hill 2015; Bücheler et al. 2010). This delegation does not imply an abandonment of academic rigor, but rather a reconfiguration of expertise — one that recognises the value of collective intelligence (Lévy 1994) and the potential of community- driven platforms to maintain high-quality, multilingual, and interoperable data (Surowiecki 2004). 

The implications of this shift are manifold. It invites researchers to rethink their role not only as producers of content, but also as facilitators of open, dialogical knowledge systems. It also raises critical questions: To what extent can academic standards be reconciled with the epistemological norms of a platform like Wikidata? How do we balance openness with accuracy, and participation with control? Far from erasing these tensions, the integration of Wikidata into our project foregrounds them — and in doing so, creates an opportunity for scholars to collectively reflect on the processes of validation, authorship, and authority.

Ultimately, we suggest that embracing platforms like Wikidata means accepting that academic knowledge is always provisional, situated, and co-produced. It is a move toward a more resilient and plural form of scholarship — one that recognises the potential of the many without losing sight of the responsibility of the few.

