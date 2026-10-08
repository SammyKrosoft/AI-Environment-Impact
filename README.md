# 🌍 IA et environnement

> Synthèse visuelle et sourcée sur l’impact environnemental de l’IA

## Infographies

![Consommation électrique des usages numériques](<assets/Environnement - IA Perspective Conso Electricite.png>)

![Consommation d'eau des usages numériques](<assets/Environnement - IA perspective Conso eau.png>)

## À retenir

- ⚡ Les workloads IA augmentent fortement la demande électrique des datacenters
- 💧 Ils peuvent également augmenter leur consommation d’eau, notamment pour le refroidissement
- 🌫️ Les émissions de CO₂ dépendent fortement du mix électrique utilisé
- 🏗️ La fabrication des GPU et la construction de nouveaux datacenters ont aussi une empreinte importante
- 🤖 Un prompt texte individuel reste relativement peu énergivore
- 📈 Le principal problème vient de l’échelle : milliards de requêtes, millions de GPU et nouveaux datacenters

---

## Quel est réellement l’impact environnemental de l’intelligence artificielle ?

L’arrivée massive de l’intelligence artificielle dans les datacenters pose une question légitime :

> **L’IA consomme-t-elle davantage d’électricité et d’eau, et génère-t-elle davantage de CO₂ que les usages numériques traditionnels ?**

La réponse courte est **oui, à l’échelle globale**.

Mais la réalité est beaucoup plus nuancée que certaines affirmations du type *« une question à ChatGPT consomme une bouteille d’eau »*.

Cette page rassemble quelques ordres de grandeur permettant de replacer l’impact de l’IA dans le contexte plus large de nos usages numériques quotidiens.

---

# ⚡ 1. Consommation électrique

Les applications traditionnelles hébergées dans les datacenters — sites web, messagerie, bases de données, stockage, email — utilisaient principalement des processeurs généralistes.

L’IA moderne ajoute des infrastructures spécialisées contenant de grandes quantités de :

- GPU
- accélérateurs IA
- mémoire haute performance
- équipements réseau très rapides

Ces systèmes fonctionnent souvent à des puissances beaucoup plus élevées par rack.

L’International Energy Agency estime que la consommation mondiale des datacenters pourrait atteindre environ :

> **945 TWh par an en 2030**

soit plus du double de leur consommation récente.

L’IA constitue l’un des principaux moteurs de cette croissance.


---

# 💧 2. Consommation d’eau

L’eau intervient de deux façons.

### Eau directement consommée par les datacenters

Les serveurs produisent de la chaleur.

Cette chaleur doit être évacuée, et certains datacenters utilisent des systèmes de refroidissement dans lesquels une partie de l’eau est évaporée.

### Eau indirectement consommée

Produire de l’électricité peut également nécessiter de l’eau.

C’est notamment le cas de certaines centrales thermiques et nucléaires utilisant de grandes quantités d’eau pour leur refroidissement.

Il faut donc distinguer :

> **eau du datacenter + eau liée à la production de son électricité**

---

## Combien d’eau consomme un prompt IA ?

Les chiffres varient énormément selon :

- le modèle
- la longueur de la requête
- le datacenter
- sa localisation
- la météo
- le système de refroidissement
- le mix électrique

Google a publié en 2025 une mesure particulièrement intéressante concernant Gemini.

Pour un prompt texte médian :

| Ressource | Consommation |
|---|---:|
| ⚡ Électricité | ~0,24 Wh |
| 💧 Eau | ~0,26 mL |
| 🌫️ CO₂e | ~0,03 g |

Cela correspond à environ :

> 💧 **5 gouttes d’eau par prompt**

dans l’infrastructure et selon la méthodologie mesurées par Google.

---

# 🚰 Mais alors… d’où vient l’histoire de la bouteille d’eau ?

Une étude universitaire publiée initialement en 2023 estimait que :

> environ **20 à 50 échanges avec un modèle IA pouvaient correspondre à environ 500 mL d’eau**

dans certaines conditions.

Cette estimation a parfois été transformée sur Internet en :

> ❌ « Une question à ChatGPT consomme une bouteille d’eau »

Ce n’était pas la conclusion de l’étude.

Les infrastructures et les modèles ont également beaucoup évolué depuis.

---

# 🌫️ 3. Émissions de CO₂

Un GPU ne produit évidemment pas directement de CO₂.

L’empreinte carbone vient principalement de trois sources.

### ⚡ Production d’électricité

Un datacenter alimenté principalement par :

- charbon
- gaz naturel

aura une empreinte carbone beaucoup plus élevée qu’un datacenter alimenté par :

- hydroélectricité
- nucléaire
- éolien
- solaire

Deux modèles IA consommant exactement la même quantité d’électricité peuvent donc avoir des empreintes carbone très différentes.

---

### 🏭 Fabrication du matériel

L’IA nécessite de grandes quantités de :

- GPU
- mémoire
- serveurs
- équipements réseau
- alimentations électriques
- systèmes de refroidissement

La fabrication de ces équipements possède elle aussi une empreinte environnementale.

---

### 🏗️ Construction des datacenters

La croissance de l’IA entraîne également la construction rapide de nouvelles infrastructures.

Cela nécessite notamment :

- béton
- acier
- cuivre
- équipements électriques
- bâtiments
- groupes électrogènes
- systèmes de refroidissement

Ces émissions sont souvent classées dans les émissions **Scope 3** des entreprises.

---

# 📊 4. Comparaison avec quelques usages numériques quotidiens

Les valeurs suivantes sont des **ordres de grandeur**, et non des constantes universelles.

| Usage | Consommation électrique indicative |
|---|---:|
| 💬 Message texte | très faible |
| 📧 Email texte | très faible |
| 🔎 Recherche web classique | quelques dixièmes de Wh |
| 🤖 Prompt IA simple | ~0,2–0,6 Wh |
| 🧠 Requête IA avec raisonnement important | ~4 Wh ou davantage |
| 🎵 1 h de streaming audio | quelques Wh à quelques dizaines de Wh |
| 📹 1 h de visioconférence | ~20–50 Wh |
| 📱 1 h de vidéo sur smartphone | ~30–40 Wh |
| 📺 1 h de streaming vidéo | ~77 Wh |
| 🎮 1 h de jeu sur PC gaming | ~100–300 Wh ou davantage |

---

# 📺 5. Une comparaison intéressante : IA vs Netflix

Prenons comme référence :

> 🤖 **~0,3 Wh pour un prompt IA texte simple**

et :

> 📺 **~77 Wh pour une heure de streaming vidéo**

On obtient :

```text
77 Wh / 0,3 Wh ≈ 257
```

Donc, en ordre de grandeur :

> **📺 1 heure de streaming vidéo ≈ 250 prompts IA texte simples**

Cette comparaison ne signifie pas que les deux activités ont exactement la même empreinte environnementale.

Le périmètre de mesure n’est notamment pas toujours identique.

Pour le streaming vidéo, une grande partie de l’électricité consommée provient de :

- la télévision
- l’ordinateur
- le smartphone
- le réseau

et pas uniquement du datacenter.

---

# 🧠 6. Toutes les requêtes IA ne se valent pas

Dire :

> « un prompt consomme X »

est en réalité assez trompeur.

Comparez par exemple :

```text
Quelle est la capitale de l’Australie ?
```

avec :

```text
Analyse 150 pages de documents,
compare plusieurs scénarios,
recherche des informations,
exécute du code,
vérifie les résultats
et rédige un rapport détaillé.
```

Ces deux actions comptent toutes les deux comme **un prompt**, mais elles peuvent nécessiter des quantités de calcul radicalement différentes.

Les modèles utilisant beaucoup de raisonnement ou de *test-time compute* peuvent consommer plusieurs fois plus d’énergie qu’une requête conversationnelle courte.

---

# 📈 7. Le véritable problème est l’échelle

Supposons qu’un prompt moyen consomme :

```text
0,3 Wh
```

Cela semble très faible.

Mais :

```text
1 milliard de prompts × 0,3 Wh
```

représente déjà :

```text
300 MWh
```

Et cela ne comprend pas nécessairement :

- l’entraînement des modèles
- la fabrication des GPU
- la fabrication des serveurs
- la construction des datacenters
- les infrastructures électriques
- les réseaux
- le remplacement du matériel

C’est donc essentiellement **l’utilisation massive de l’IA** qui transforme une petite consommation individuelle en enjeu énergétique mondial.

---

# ♻️ 8. L’efficacité progresse également très rapidement

Il existe cependant un autre phénomène important.

Les modèles, les GPU et les datacenters deviennent rapidement plus efficaces.

Les améliorations portent notamment sur :

- les architectures de modèles
- la quantification
- les GPU
- les accélérateurs spécialisés
- le refroidissement liquide
- l’utilisation de modèles plus petits
- le routage des requêtes
- les datacenters sans consommation d’eau pour le refroidissement
- l’approvisionnement en électricité bas carbone

Le problème est que ces gains d’efficacité sont pour l’instant accompagnés d’une augmentation encore plus rapide de l’utilisation de l’IA.

C’est un exemple classique d’**effet rebond** :

> chaque opération devient moins coûteuse, mais nous en effectuons énormément plus.

---

# 🎯 Conclusion

Il serait incorrect d’affirmer que :

> ❌ « L’IA n’a pratiquement aucun impact environnemental »

mais il serait tout aussi trompeur d’affirmer que :

> ❌ « Chaque question posée à une IA représente une catastrophe écologique »

Une formulation plus juste serait :

> **Une requête IA individuelle moderne peut avoir une empreinte relativement faible, mais l’adoption massive de l’IA augmente considérablement la demande mondiale en calcul, en électricité, en eau et en nouvelles infrastructures.**

La question environnementale de l’IA est donc principalement une question :

> **d’échelle, d’efficacité et de source d’énergie.**

---

# 🖼️ Infographies

Les infographies associées à cette analyse peuvent être ajoutées dans un dossier `assets`.

```markdown
![Consommation électrique des usages numériques](assets/digital-energy-consumption.png)

![Consommation d'eau des usages numériques](assets/digital-water-consumption.png)
```

---

# 📚 Sources principales

Les chiffres et ordres de grandeur présentés ici s’appuient notamment sur :

1. **Google — Measuring the environmental impact of AI inference**  
   Mesures de l’énergie, de l’eau et du CO₂ associés à l’inférence Gemini

2. **Microsoft Research — Energy use of AI inference, efficiency pathways, and test-time scaling**  
   Analyse de la consommation des LLM et du coût supplémentaire du raisonnement

3. **International Energy Agency — Energy and AI**  
   Prévisions concernant la croissance de la consommation électrique des datacenters

4. **International Energy Agency — The carbon footprint of streaming video**  
   Ordres de grandeur pour le streaming vidéo

5. **Lawrence Berkeley National Laboratory — U.S. Data Center Energy Usage Report**  
   Consommation énergétique et évolution des datacenters

6. **npj Clean Water — Data centre water consumption**  
   Analyse de la consommation directe et indirecte d’eau des datacenters

7. **Li et al. — Making AI Less “Thirsty”**  
   Étude sur l’empreinte hydrique des modèles d’intelligence artificielle

8. **Nature Communications — The environmental sustainability of digital content consumption**  
   Analyse du cycle de vie des principaux usages numériques

---

## ⚠️ Note méthodologique

Les estimations présentées sur cette page ne doivent pas être interprétées comme des valeurs universelles.

Les résultats peuvent varier de plusieurs ordres de grandeur selon :

- le modèle utilisé
- la taille de la réponse
- le matériel
- le taux d’utilisation des serveurs
- le datacenter
- la température extérieure
- le système de refroidissement
- le pays
- le mix électrique
- les limites choisies pour l’analyse du cycle de vie

L’objectif de cette page est donc de fournir des **ordres de grandeur permettant de comparer les usages**, et non d’attribuer une valeur environnementale absolue à chaque requête.
