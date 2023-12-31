﻿# Circuit Quantique avec Qiskit

Ce programme utilise Qiskit, un framework pour la programmation quantique, pour construire et visualiser un circuit quantique. Il comprend plusieurs opérations fondamentales sur les qubits et illustre l'utilisation de mesures.

## Composition du Circuit
**Qubits et Bits Classiques :** Le circuit est composé de 3 qubits et 3 bits classiques. Les qubits sont les unités de base pour le traitement quantique, tandis que les bits classiques sont utilisés pour stocker les résultats des mesures des qubits.
## Opérations sur les Qubits
**Porte de Hadamard (H) :** Appliquée aux premier et troisième qubits, cette porte met les qubits dans une superposition, un état fondamental en informatique quantique.

**Porte CNOT :** Plusieurs portes CNOT (Controlled NOT) sont appliquées entre différentes paires de qubits. Cette porte est une opération fondamentale pour créer des états intriqués et réaliser des calculs quantiques.

**Porte X (NOT) :** La porte NOT quantique, appelée aussi porte X, est appliquée à différents qubits à plusieurs reprises. Elle permet d'inverser l'état d'un qubit (de |0> à |1> et vice versa).

**Barrières :** Des barrières sont insérées pour séparer visuellement les différentes étapes du circuit. Bien qu'elles n'affectent pas les opérations, elles sont utiles pour l'analyse et la visualisation du circuit.

**Opération SWAP :** Une opération SWAP est utilisée pour échanger les états de deux qubits.

## Mesure et Résultats
**Mesure des Qubits :** À la fin, chaque qubit est mesuré, et le résultat de cette mesure est stocké dans un bit classique correspondant. Cela permet de convertir l'information quantique en information classique lisible.
## Visualisation
**Dessin du Circuit :** Le circuit est dessiné à la fin du script, fournissant une représentation visuelle de toutes les opérations et mesures appliquées.
