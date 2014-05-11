
# **Introduction / intérêt de la recherche**
## D'où nous est venu l'idée?
Utilisant fréquemment les transports publics de la région lausannoise, nous avons constaté que les espaces dédiés aux déplacements des personnes entre les divers arrêts et quais sont facilement saturés à l'heure de pointe. Nous nous sommes donc interrogés sur l'origine de ces perturbations: est-ce un manque de place ou une organisation des flux peu efficaces ?
Nous avons donc tenté de modéliser un espace où deux flux venant de sens inverse se rencontrent. Quels paramètres influences sur l'efficacité du déplacement, comment optimiser ce dernier en conservant l'espace intact mais en agissant sur le comportement des individus ?

# **Objectifs et hypothèses**
Nous voulons déterminer l'aspect des flux de déplacement selon des configurations spaciales et de comportement des individus données.
Aussi, déterminer si les configurations adoptées sont satisfaisantes et si elles peuvent être améliorées.

Nous avons émis plusieurs hypothèses comme suit:
Plus un espace est occupé par des individus appartement à des flux de courant contraire, moins le déplacement et la traversées de l'espaces sont aisés
Plus les individus adoptent un comportement "chacun pour soi", plus la difficulté de déplacement augmente.
Inversément, plus les individus sont disposés à s'organiser dans l'espace et suivre les individus du même flux, plus la mobilité est aisée
Plus l'espace est chargé d'obstacles, plus le temps de parcours augmente par cause de détours fréquents.

# **Méthodes et procédures**
## Développement du programme
Voici les différentes étapes:
-Mise en place d'un modèle simple composé d'un couloir avec 2 entrées/sorties faits grâce a des patches ainsi que la possibilité de placer des obstacles aléatoires.!
-Ajout des turtles représentants des humains qui vont parcourir le couloir d'un coté a l'autre. Ils meurent des qu'ils arrivent de l'autre coté.
-Implémentation d'un mécanisme de détection pour que chaque agent s’arrête s'il a un obstacle ou un autre agent en face de lui. 
-Changement de direction des turtles lorsqu'ils rencontrent un obstacle pour éviter celui-ci et puis de nouveau un changement de la direction vers la sortie.
-Mémoire du sol par-rapport au nombres de personnes étant passé sur ce patch.
 
# **Résultats**



# **Discussion et conclusion**
