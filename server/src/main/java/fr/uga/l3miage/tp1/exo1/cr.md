
1)Décrivez ce que vous observez en base de données lorsque l'on déclare une classe comme ClassTestJPA ?
    
Nous n'avons pas de @column mais JPA crée de lui même les colonnes.
Nous n'avons pas donné de nom à la table il sera le nom de la classe
Nous n'avons pas de @enumerated 

2)Quels sont les effets des propriétés ajoutées dans les @Column dans la classe ClassTestJPATwo ?

nous changeons la précision le nombre de chiffres à 1.
nous faisons en sorte que le test_name soit unique.

3)À votre avis, dans quels cas est-il nécessaire de mettre les annotations @Column ?
il est nécessaire d'ajouter le @column seulement lorqsque nous sommes en validate mais pas en create 