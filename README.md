# test-python-scheduler-
Charge processeur = 2/5 + 3/15 + 5/5 + 3/5 = 2.2=> 220%
Cette charge processeur n'est pas optimale mais on peut en déduire que la majeur partie des tâches ne seront pas exécutées.

Pour améliorer ce résultat, j’ai décidé de pénaliser les tâches “Machine 1” et “Machine 2” en considérant que ce n’est pas critique pour le système. Par exemple si je diminue le temps d’execution de ces tâches de 5 à 1 et de 3 à 1, le calcul de charge donne :
Charge processeur = 2/5 + 3/15 + 1/5 + 1/5 = 100%
Ce calcul est théorique et ne prends pas en compte les problématiques d’ordonnancement mais c’est
une piste de travail.
