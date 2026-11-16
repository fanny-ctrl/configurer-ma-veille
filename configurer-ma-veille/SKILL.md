---
name: "configurer-ma-veille"
description: "Compose et installe la veille juridique hebdomadaire d'un avocat : choix des matières, sélection des sources dans un catalogue de plus de cent sources, test, puis tâche planifiée. À lancer sur « configure ma veille »."
---

# Configurer ma veille juridique

Tu aides un avocat à composer sa veille juridique hebdomadaire à partir du catalogue de sources ci-dessous, puis à l'installer sous forme de tâche planifiée. La veille ne traite que des sources publiques et aucune donnée client.

## Règles de conduite

- Français, ton professionnel et posé, vouvoiement, sans formule creuse ni tiret cadratin, typographie française.
- Questions une par une, ou par groupes de trois au plus, avec des réponses types.
- N'ajoute au catalogue aucune source dont tu n'es pas certain ; si l'avocat en propose une, ajoute-la telle qu'il la donne.
- La tâche ne doit jamais être reliée à la messagerie ni aux dossiers du cabinet.

## Étape 1 : le profil de veille

Recueille :

1. **Les matières**, parmi la liste du catalogue (plusieurs choix possibles), et les sous-thèmes à privilégier (par exemple, en droit social : rupture du contrat, santé au travail).
2. **Les clients types** : particuliers, TPE, PME, grands comptes, secteur public, et les secteurs d'activité dominants.
3. **Les abonnements** dont il dispose (Dalloz, Lexis, Lextenso, Lexbase, Lefebvre, Lamy, Doctrine) : ils servent à sa lecture, la tâche ne pouvant en général pas y accéder.
4. **Le rythme** : jour et heure (par défaut le lundi à 8 h), et le format souhaité (synthèse courte ou détaillée).
5. **La destination** : compte rendu dans Claude seulement, ou versement dans un outil de notes déjà connecté (Notion, OneNote, Google Docs), à condition qu'il ne contienne que la veille.

## Étape 2 : la sélection des sources

Propose de cinq à quinze sources, selon ces règles :

- Toujours Légifrance ; EUR-Lex dès qu'une matière est influencée par le droit de l'Union.
- La ou les juridictions qui font la jurisprudence de la matière (Cour de cassation, Conseil d'État, CJUE, juridiction spécialisée).
- Les autorités et administrations qui régulent la matière.
- Une ou deux sources de presse ou de doctrine en accès libre ou partiellement libre.
- Les sources sous abonnement sont signalées à part, comme lecture conseillée, et non intégrées à la tâche.

Présente la sélection sous forme de tableau (Source, Lien, Pourquoi elle est retenue), fais-la valider et accepte tout ajout ou retrait.

## Étape 3 : les outils

Vérifie si le connecteur Légifrance est disponible dans la session : s'il l'est, la tâche l'utilise pour fiabiliser les références ; sinon, propose à l'avocat de l'activer, sans en faire une condition. Rappelle que la tâche ne lira aucune messagerie.

## Étape 4 : le test

Propose de lancer immédiatement un passage d'essai sur les sept derniers jours avec la consigne de l'étape 5. Montre le résultat, demande ce qu'il faut ajuster (sources trop bavardes, sujets manquants, longueur) et corrige la consigne avant l'installation.

## Étape 5 : l'installation

Rédige la consigne définitive en complétant le modèle ci-dessous, puis :

- si l'outil de création de tâche planifiée est disponible, crée la tâche « Veille juridique hebdomadaire » avec cette consigne, au jour et à l'heure retenus (fuseau Europe/Paris), en indiquant que le modèle Sonnet suffit ;
- sinon, livre la consigne dans un fichier .md et explique comment créer la tâche dans Cowork (nouvelle tâche, fichier joint, « Crée une tâche planifiée à partir de ce fichier, chaque lundi à 8 h »).

### Modèle de consigne

```
Tu réalises la veille juridique hebdomadaire d'un avocat ou d'une avocate. Couvre les sept derniers jours. Réponds en français, ton professionnel, sans formule creuse.

Matières : [matières et sous-thèmes]
Clients types : [clients types et secteurs]
Sources : [liste nom : lien]

Méthode. Consulte chaque source de la liste, ainsi que Légifrance par le connecteur s'il est disponible. Retiens uniquement les nouveautés de la période qui relèvent des matières : textes publiés ou entrés en vigueur, décisions de justice, décisions et recommandations des autorités, consultations publiques, textes en préparation ayant franchi une étape.

Fiabilité. Ne retiens une information que si tu as pu l'ouvrir à sa source pendant ce passage. Pour chaque décision, indique la juridiction, la date et le numéro ; pour chaque texte, sa référence exacte et sa date d'entrée en vigueur. N'invente jamais une référence. Signale à la fin les sources inaccessibles.

Restitution. Classe les nouveautés par importance pour les clients types. Pour chacune : la référence, ce qui change en deux phrases, les clients concernés et l'action éventuelle (conseil à adresser, trame à mettre à jour, échéance à noter). Termine par les échéances des trois prochains mois et la liste des sources consultées. Si la semaine est calme, dis-le en une phrase.

Interdits. N'accède à aucune messagerie et ne traite aucune donnée client.
```

## Pour finir

Récapitule en quelques lignes : matières, sources retenues, lectures conseillées sous abonnement, jour et heure, destination. Rappelle qu'une veille automatisée peut mal résumer un texte ou manquer une nouveauté : chaque référence s'ouvre à sa source avant d'être citée à un client, et la veille outillée complète la lecture de l'avocat sans la remplacer. Pour modifier la veille plus tard, il suffit de relancer ce skill.

## Catalogue des sources

Les sources marquées (abonnement) servent à la lecture de l'avocat ; les autres sont en accès libre ou partiellement libre.

### Toutes matières
- Légifrance : https://www.legifrance.gouv.fr
- Vie publique : https://www.vie-publique.fr
- Assemblée nationale : https://www.assemblee-nationale.fr
- Sénat : https://www.senat.fr
- Service-public.fr : https://www.service-public.fr
- Cour de cassation et Judilibre : https://www.courdecassation.fr
- Conseil constitutionnel : https://www.conseil-constitutionnel.fr
- Ministère de la Justice : https://www.justice.gouv.fr
- EUR-Lex : https://eur-lex.europa.eu
- Cour de justice de l'UE : https://curia.europa.eu
- Cour européenne des droits de l'homme : https://hudoc.echr.coe.int
- Dalloz Actualité : https://www.dalloz-actualite.fr
- Actu-Juridique : https://www.actu-juridique.fr
- Le Club des juristes : https://www.leclubdesjuristes.com
- Le Monde du droit : https://www.lemondedudroit.fr
- Village de la Justice : https://www.village-justice.com
- Dalloz, revues (abonnement) : https://www.dalloz.fr
- Lexis 360 (abonnement) : https://www.lexisnexis.fr
- Lextenso (abonnement) : https://www.lextenso.fr
- Lexbase (abonnement) : https://www.lexbase.fr
- Doctrine (abonnement) : https://www.doctrine.fr

### Civil et famille
- Notaires de France : https://www.notaires.fr
- ANIL : https://www.anil.org
- Défenseur des droits : https://www.defenseurdesdroits.fr
- ONIAM : https://www.oniam.fr

### Immobilier et construction
- ANIL : https://www.anil.org
- Notaires de France : https://www.notaires.fr
- Le Moniteur : https://www.lemoniteur.fr
- Ministère de la Transition écologique : https://www.ecologie.gouv.fr
- Géoportail de l'urbanisme : https://www.geoportail-urbanisme.gouv.fr
- Éditions Francis Lefebvre : https://www.efl.fr

### Affaires et sociétés
- AMF : https://www.amf-france.org
- BODACC : https://www.bodacc.fr
- Infogreffe : https://www.infogreffe.fr
- Pappers : https://www.pappers.fr
- Autorité des normes comptables : https://www.anc.gouv.fr
- H2A (commissariat aux comptes) : https://www.h2a.fr
- Agence française anticorruption : https://www.agence-francaise-anticorruption.gouv.fr
- ESMA : https://www.esma.europa.eu
- INPI : https://www.inpi.fr
- Éditions Francis Lefebvre : https://www.efl.fr
- Affiches Parisiennes : https://www.affiches-parisiennes.com
- Décideurs Juridiques : https://www.magazine-decideurs.com

### Concurrence et distribution
- Autorité de la concurrence : https://www.autoritedelaconcurrence.fr
- Commission européenne, concurrence : https://competition-policy.ec.europa.eu
- CEPC : https://www.economie.gouv.fr/cepc
- DGCCRF : https://www.economie.gouv.fr/dgccrf
- Arcep : https://www.arcep.fr
- Commission de régulation de l'énergie : https://www.cre.fr
- Autorité de régulation des transports : https://www.autorite-transports.fr
- Médiateur des entreprises : https://www.economie.gouv.fr/mediateur-des-entreprises

### Consommation
- DGCCRF : https://www.economie.gouv.fr/dgccrf
- Commission des clauses abusives : https://www.clauses-abusives.fr
- Institut national de la consommation : https://www.inc-conso.fr
- Médiation de la consommation : https://www.economie.gouv.fr/mediation-conso
- Cybermalveillance.gouv.fr : https://www.cybermalveillance.gouv.fr
- Service-public.fr : https://www.service-public.fr

### Travail et social
- Ministère du Travail : https://travail-emploi.gouv.fr
- Code du travail numérique : https://code.travail.gouv.fr
- BOSS : https://boss.gouv.fr
- Urssaf : https://www.urssaf.fr
- Défenseur des droits : https://www.defenseurdesdroits.fr
- CNIL : https://www.cnil.fr
- Légisocial : https://www.legisocial.fr
- Éditions Législatives : https://www.editions-legislatives.fr
- Wolters Kluwer, Lamy et Liaisons sociales (abonnement) : https://www.wolterskluwer.com/fr-fr

### Pénal
- Ministère de la Justice : https://www.justice.gouv.fr
- Agence française anticorruption : https://www.agence-francaise-anticorruption.gouv.fr
- Tracfin : https://www.economie.gouv.fr/tracfin
- CGLPL : https://www.cglpl.fr
- Cybermalveillance.gouv.fr : https://www.cybermalveillance.gouv.fr

### Public et administratif
- Conseil d'État : https://www.conseil-etat.fr
- Tribunal des conflits : https://www.tribunal-conflits.fr
- Cour des comptes : https://www.ccomptes.fr
- CADA : https://www.cada.fr
- DAJ de Bercy, commande publique : https://www.economie.gouv.fr/daj
- BOAMP : https://www.boamp.fr
- TED : https://ted.europa.eu
- Le Moniteur : https://www.lemoniteur.fr

### Urbanisme et environnement
- Ministère de la Transition écologique : https://www.ecologie.gouv.fr
- Géoportail de l'urbanisme : https://www.geoportail-urbanisme.gouv.fr
- AIDA (INERIS) : https://aida.ineris.fr
- Commission nationale du débat public : https://www.debatpublic.fr
- Commission de régulation de l'énergie : https://www.cre.fr
- Conseil d'État : https://www.conseil-etat.fr
- Actu-Environnement : https://www.actu-environnement.com
- Éditions Législatives : https://www.editions-legislatives.fr

### Fiscal
- BOFiP-Impôts : https://bofip.impots.gouv.fr
- impots.gouv.fr : https://www.impots.gouv.fr
- Conseil d'État : https://www.conseil-etat.fr
- Autorité des normes comptables : https://www.anc.gouv.fr
- OCDE : https://www.oecd.org
- Éditions Francis Lefebvre : https://www.efl.fr

### Banque, finance et assurance
- ACPR : https://acpr.banque-france.fr
- Banque de France : https://www.banque-france.fr
- AMF : https://www.amf-france.org
- Autorité bancaire européenne : https://www.eba.europa.eu
- ESMA : https://www.esma.europa.eu
- EIOPA : https://www.eiopa.europa.eu
- La Médiation de l'assurance : https://www.mediation-assurance.org
- Tracfin : https://www.economie.gouv.fr/tracfin

### Numérique et données
- CNIL : https://www.cnil.fr
- Comité européen de la protection des données : https://www.edpb.europa.eu
- Commission européenne, stratégie numérique : https://digital-strategy.ec.europa.eu
- Commission européenne, salle de presse : https://ec.europa.eu/commission/presscorner
- ANSSI : https://cyber.gouv.fr
- Cybermalveillance.gouv.fr : https://www.cybermalveillance.gouv.fr
- Arcom : https://www.arcom.fr
- Arcep : https://www.arcep.fr
- Legalis : https://www.legalis.net

### Propriété intellectuelle
- INPI : https://www.inpi.fr
- Data INPI : https://data.inpi.fr
- EUIPO : https://www.euipo.europa.eu
- TMview : https://www.tmdn.org/tmview
- OMPI : https://www.wipo.int
- Office européen des brevets : https://www.epo.org
- Juridiction unifiée du brevet : https://www.unifiedpatentcourt.org
- Arcom : https://www.arcom.fr
- Legalis : https://www.legalis.net

### Santé
- Haute Autorité de santé : https://www.has-sante.fr
- ANSM : https://ansm.sante.fr
- Ministère de la Santé : https://sante.gouv.fr
- Conseil national de l'Ordre des médecins : https://www.conseil-national.medecin.fr
- ONIAM : https://www.oniam.fr
- CNIL : https://www.cnil.fr

### Étrangers et droits fondamentaux
- Immigration, ministère de l'Intérieur : https://www.immigration.interieur.gouv.fr
- Cour nationale du droit d'asile : https://www.cnda.fr
- OFPRA : https://www.ofpra.gouv.fr
- Défenseur des droits : https://www.defenseurdesdroits.fr
- CGLPL : https://www.cglpl.fr
- Conseil de l'Europe : https://www.coe.int
- GISTI : https://www.gisti.org
- La Cimade : https://www.lacimade.org

### Procédure et exécution
- Ministère de la Justice : https://www.justice.gouv.fr
- Chambre nationale des commissaires de justice : https://commissaires-justice.fr
- Tribunal des conflits : https://www.tribunal-conflits.fr

### Entreprises en difficulté
- CNAJMJ : https://www.cnajmj.fr
- BODACC : https://www.bodacc.fr
- Infogreffe : https://www.infogreffe.fr
- Banque de France : https://www.banque-france.fr

### Européen et international
- EUR-Lex : https://eur-lex.europa.eu
- Cour de justice de l'UE : https://curia.europa.eu
- Observatoire législatif du Parlement européen : https://oeil.secure.europarl.europa.eu
- Commission européenne, salle de presse : https://ec.europa.eu/commission/presscorner
- Conseil de l'Europe : https://www.coe.int
- CNUDCI : https://uncitral.un.org
- OCDE : https://www.oecd.org

### Profession et déontologie
- Conseil national des barreaux : https://www.cnb.avocat.fr
- Barreau de Paris : https://www.avocatparis.org
- Conférence des bâtonniers : https://conferencedesbatonniers.com
- UJA de Paris : https://www.uja.fr
- Village de la Justice : https://www.village-justice.com

### Arbitrage et modes amiables
- Chambre de commerce internationale : https://iccwbo.org
- CMAP : https://www.cmap.fr
- CNUDCI : https://uncitral.un.org
- OMPI, centre d'arbitrage et de médiation : https://www.wipo.int
- Médiateur des entreprises : https://www.economie.gouv.fr/mediateur-des-entreprises
- Médiation de la consommation : https://www.economie.gouv.fr/mediation-conso