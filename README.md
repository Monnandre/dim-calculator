# Calculatrice de Dimensions Physiques

## Fonctionnalités

- **Manipulation de Dimensions Physiques** : Masse (M), Longueur (L) et Temps (T).
- **Opérations Disponibles** : Multiplication, Division.
- **Affichage des Dimensions** : Les dimensions sont affichées dans un format lisible (ex. : `M^(1)L^(2)T^(-3)`).
- **Parsing de Chaînes de Caractères** : Permet d'interpréter des dimensions données sous forme de texte (ex. : `M2L-1T3`).

## Exemple d'Utilisation

```python
from dimension_calculator import Dimension

# Définir des dimensions physiques
force = Dimension(M=1, L=1, T=-2)  # Force (exemple : Newton)
vitesse = Dimension(L=1, T=-1)  # Vitesse (exemple : mètre par seconde)

# Calculer une dimension résultante
resultat = force / vitesse
print(f"Résultat : {resultat}")  # Résultat : M^(1)L^(0)T^(-1)
```
