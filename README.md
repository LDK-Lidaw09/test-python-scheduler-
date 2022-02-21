# test-python-scheduler-
Charge processeur = 2/5 + 3/15 + 5/5 + 3/5 = 2.2=> 220%
Cette charge processeur n'est pas optimale mais on peut en déduire que la majeur partie des tâches ne seront pas exécutées.

Pour améliorer ce résultat, j’ai décidé de pénaliser les tâches “Machine 1” et “Machine 2” en considérant que ce n’est pas critique pour le système. Par exemple si je diminue le temps d’execution de ces tâches de 5 à 1 et de 3 à 1, le calcul de charge donne :
Charge processeur = 2/5 + 3/15 + 1/5 + 1/5 = 100%
Ce calcul est théorique et ne prends pas en compte les problématiques d’ordonnancement mais c’est
une piste de travail.


Logs:
0	Idle
1	=> Pump 1 completed without interruption.
2	=> Pump 2 completed without interruption.
3	=> Pump 1 completed without interruption.
	Task Machine 1\ŧFAILED deadline.	100.0% done.
4	=> Machine 1 completed without interruption.
	Task Machine 2\ŧFAILED deadline.	100.0% done.
5	=> Machine 2 completed without interruption.
6	=> Pump 1 completed without interruption.
7	=> Machine 1 completed without interruption.
8	=> Machine 2 completed without interruption.
9	Idle
10	=> Pump 1 completed without interruption.
11	=> Pump 2 completed without interruption.
12	=> Pump 1 completed without interruption.
	Task Machine 1\ŧFAILED deadline.	0.0% done.
13	=> Machine 1 completed without interruption.
	Task Machine 2\ŧFAILED deadline.	0.0% done.
14	=> Machine 2 completed without interruption.
15	Idle
16	=> Pump 1 completed without interruption.
17	=> Machine 1 completed without interruption.
18	=> Machine 2 completed without interruption.
19	Idle
20	=> Pump 1 completed without interruption.
21	=> Pump 2 completed without interruption.
22	=> Pump 1 completed without interruption.
	Task Machine 1\ŧFAILED deadline.	0.0% done.
23	=> Machine 1 completed without interruption.
	Task Machine 2\ŧFAILED deadline.	0.0% done.
24	=> Machine 2 completed without interruption.
25	Idle
26	=> Pump 1 completed without interruption.
27	=> Machine 1 completed without interruption.
28	=> Machine 2 completed without interruption.
29	Idle
30	=> Pump 1 completed without interruption.
31	=> Pump 2 completed without interruption.
32	=> Pump 1 completed without interruption.
	Task Machine 1\ŧFAILED deadline.	0.0% done.
33	=> Machine 1 completed without interruption.
	Task Machine 2\ŧFAILED deadline.	0.0% done.
34	=> Machine 2 completed without interruption.
35	Idle
36	=> Pump 1 completed without interruption.
37	=> Machine 1 completed without interruption.
38	=> Machine 2 completed without interruption.
39	Idle
40	=> Pump 1 completed without interruption.
41	=> Pump 2 completed without interruption.
42	=> Pump 1 completed without interruption.
	Task Machine 1\ŧFAILED deadline.	0.0% done.
43	=> Machine 1 completed without interruption.
	Task Machine 2\ŧFAILED deadline.	0.0% done.
44	=> Machine 2 completed without interruption.
45	Idle
46	=> Pump 1 completed without interruption.
47	=> Machine 1 completed without interruption.
48	=> Machine 2 completed without interruption.
49	Idle
50	=> Pump 1 completed without interruption.
51	=> Pump 2 completed without interruption.
52	=> Pump 1 completed without interruption.
	Task Machine 1\ŧFAILED deadline.	0.0% done.
53	=> Machine 1 completed without interruption.
	Task Machine 2\ŧFAILED deadline.	0.0% done.
54	=> Machine 2 completed without interruption.
55	Idle
56	=> Pump 1 completed without interruption.
57	=> Machine 1 completed without interruption.
58	=> Machine 2 completed without interruption.
59	Idle
60	=> Pump 1 completed without interruption.
61	=> Pump 2 completed without interruption.
62	=> Pump 1 completed without interruption.
	Task Machine 1\ŧFAILED deadline.	0.0% done.
63	=> Machine 1 completed without interruption.
	Task Machine 2\ŧFAILED deadline.	0.0% done.
64	=> Machine 2 completed without interruption.
65	Idle
66	=> Pump 1 completed without interruption.
67	=> Machine 1 completed without interruption.
68	=> Machine 2 completed without interruption.
69	Idle
70	=> Pump 1 completed without interruption.
71	=> Pump 2 completed without interruption.
72	=> Pump 1 completed without interruption.
	Task Machine 1\ŧFAILED deadline.	0.0% done.
73	=> Machine 1 completed without interruption.
	Task Machine 2\ŧFAILED deadline.	0.0% done.
