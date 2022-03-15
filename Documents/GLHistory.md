# OpenGL

OpenGL est issue de la librairie graphique IRIS GL (Graphics Library) de l'entreprise SGI (Silicon Graphics Inc.). Les premiers postes de travail avec du graphisme de haute qualité étaient très dispendieux et utilisaient des API (Application Programming Interface) propriétaires.

Dans les années 1990, SGI réalise l'importance de la compatibilité multiplateforme et entreprend de nettoyer sa librairie IRIS GL en y retirant tout ce qui était dédié à du matériel spécifique. Elle développe un standard et, en 1992, publie la première version de la librairie OpenGL (Open Graphics Library) en y incluant le code source, d'où le nom « Librairie Graphique Ouverte ».

## Évolution

La même année, SGI forme le comité ARB (Architectural Review Board), incluant des membres comme IBM, Intel, Microsoft, etc. Le comité fait maintenant partie du Khronos Group, un large consortium de compagnies s'occupant de plusieurs standards:

Année | Version
:----:|:------:
1992  | 1.0
2004  | 2.0
2008  | 3.0
2010  | 4.0

### Profils

Si le comité a toujours défendu l'importance de la rétrocompatibilité, l'évolution du matériel graphique a rendu la position intenable. En 2008, avec la version 3.0, la librairie a été dérivée en deux profils:

Profil                     | Description
---------------------------|-----------------------------------------------------------
Compatible (Compatibility) | Maintiens de la rétrocompatibilité jusqu'à la version 1.0.
Essentiel (Core)           | Utilise que des techniques de matériel graphique moderne.

Le profil (Core) sera utilisé dans le cadre de ce cours afin de soutirer le maximum des capacités du matériel graphique actuel.
