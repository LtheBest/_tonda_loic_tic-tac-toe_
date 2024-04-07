workflow git 
 -une branche principal main 
 pour le deploiement en prod
 -une branche preprod 
 pour les fusions des fonctionalités et les tests avant la prod
 -une branche dev 
 pour developper nos fonctionaliter 


 #Avantages :

-Isolation des fonctionnalités : Chaque fonctionnalité ou correction de bogue peut être développée dans une branche distincte, ce qui permet de travailler sur des fonctionnalités sans perturber le code principal.

-Stabilité du code principal : La branche "main" (ou "master") représente le code de production stable. En travaillant dans des branches séparées et en fusionnant uniquement les modifications testées et approuvées dans "main", on maintient la stabilité du code en production.

-Pré-production pour les tests : La branche "preprod" (ou "staging") est utilisée pour tester les nouvelles fonctionnalités avant qu'elles ne soient déployées en production. Cela permet de détecter les problèmes potentiels avant qu'ils n'affectent les utilisateurs finaux.

-Environnement de développement isolé : La branche "dev" (ou "develop") est utilisée pour intégrer les nouvelles fonctionnalités et les corrections de bogues avant qu'elles ne soient testées dans l'environnement de pré-production. Cela permet de garder l'environnement de développement isolé du code en production et de faciliter la collaboration entre les membres de l'équipe.

-Facilite la collaboration : Chaque développeur peut travailler sur sa propre branche, ce qui réduit les conflits de fusion et facilite la collaboration sur des fonctionnalités distinctes.


#Inconvénients :


-Complexité accrue : La gestion de plusieurs branches peut devenir complexe, surtout lorsque plusieurs fonctionnalités sont développées simultanément et nécessitent des modifications dans des parties différentes du code.

-Risque de divergence : Si les branches ne sont pas régulièrement fusionnées et synchronisées, cela peut entraîner des divergences entre les différentes branches, ce qui peut compliquer la fusion ultérieure des modifications.

-Surcharge administrative : Le maintien de plusieurs branches nécessite une certaine surcharge administrative pour garantir que les modifications sont correctement intégrées et testées à chaque étape du processus.

-Potentiel de retard dans les déploiements : Si le processus de test dans la branche "preprod" est long ou si des problèmes sont découverts tardivement, cela peut retarder les déploiements en production.

-Besoin de coordination : Pour éviter les conflits et assurer une intégration harmonieuse, une coordination étroite entre les membres de l'équipe est nécessaire, ce qui peut être difficile dans les équipes largement distribuées ou très nombreuses.

