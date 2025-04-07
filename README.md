Algorithmes : 

Tri à bulles (Bubble Sort) : 

C’est un algorithme qui permet prendre deux valeurs qui sont cote à cote (gauche et droite) en commençant de l’indice du premier élément (1) jusqu’à l’indice du dernier élément moins 1 et de comparer leurs valeurs, si la valeur de l’élément situé à gauche est plus grand  que celle de droite :si en effet l’élément de gauche est plus grand une instruction va alors permuter ces deux valeurs et incrémenter de 1 pour vérifier si oui ou non l’élément de gauche est plus grand que celle de droite et la même instruction va encore s’exécuter jusqu’à ce que tous les éléments soient dans le bon ordre (c’est à dire du plus grand au plus petit) 

Tri par sélection (Sélection Sort) : 

C'est un algorithme qui parcourt une liste en trouvant l’élément le plus petit parmi les éléments non triés, après cela ce même élément est placé à la première position de la partie non triée (il est échangé) avec l’élément en cours Ensuite, il cherche le plus petit élément dans la sous-liste restante et le place à la position suivante. Cela continue jusqu'à ce que toute la liste soit triée. 

Tri par insertion (Insertion Sort) : 

L'algorithme considère la liste comme deux parties : une partie triée (au début) et une partie non triée (le reste). À chaque itération, l'algorithme prend le premier élément de la partie non triée. Il le place à sa position correcte dans la partie triée en le décalant par comparaison avec les éléments déjà triés. Les éléments non triés sont progressivement insérés dans la partie triée, jusqu'à ce que toute la liste soit triée. 

Tri fusion (Merge Sort): 

La liste est divisée en deux moitiés égales (ou presque égales) de manière récursive jusqu'à ce que chaque sous-liste contienne un seul élément (qui est, par définition, trié). Une fois que les sous-listes atteignent une taille minimale, elles sont fusionnées deux par deux en une seule liste triée. Pendant la fusion, les éléments des deux sous-listes sont comparés un par un, et le plus petit élément est ajouté à la nouvelle liste. Ce processus de fusion continue jusqu'à ce que toutes les sous-listes soient fusionnées en une seule liste triée. 

Tri rapide (Quick Sort): 

 Un élément, appelé pivot, est choisi dans la liste (souvent le premier, dernier, ou un élément aléatoire). Les éléments de la liste sont réorganisés autour du pivot : Les éléments plus petits que le pivot sont placés à gauche,les éléments plus grands que le pivot sont placés à droite. Le processus est répété de manière récursive pour les sous-listes à gauche et à droite du pivot. Lorsque les sous-listes sont réduites à un seul élément, elles sont combinées pour former une liste triée. 

Tri par comptage (Counting Sort): 

 Un tableau de comptage est initialisé pour suivre la fréquence d'apparition de chaque valeur dans la plage des entiers. Chaque élément de la liste d'entrée est utilisé pour incrémenter la valeur correspondante dans le tableau de comptage. Les valeurs du tableau de comptage sont modifiées pour représenter la position cumulative des éléments (où chaque valeur indique la position de fin de cet élément dans la liste triée). Une liste de sortie est construite en plaçant chaque élément de la liste d'entrée à sa position correcte en se basant sur le tableau de comptage. 

Radix Sort: 

  Les nombres sont triés par leurs chiffres, un à un, en commençant par le chiffre le moins significatif (chiffre des unités). Pour chaque position de chiffre (unités, dizaines, centaines, etc.), un tri stable (par exemple, Counting Sort) est utilisé. Les nombres sont triés de manière itérative pour chaque position de chiffre jusqu'à ce que tous les chiffres aient été pris en compte. 

 

 

 
