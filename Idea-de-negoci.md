**MECU!** és una aplicació didàctica on hi ha diferents usuaris de diferents rols amb possibilitats de fer concursos de preguntes de diferents tipus.

Els concursos tenen com a màxim 10 preguntes. Les preguntes son tipo test, formada per la mateixa pregunta i 4 possibles respostes.

Les preguntes estan dividides en diferents matèries i els usuaris podran afegir preguntes. Aquestes preguntes no passaràn a ser preguntes "reals" de l'aplicació fins que hagin passat un procés de validació.

El procés d'avaluació de preguntes es basarà en el següent:

- Un usuari "professor" podrà validar les preguntes
- Varis usuaris (no "professor") validaran les preguntes. Es requeriran 3 aprovacions per a passar a ser preguntes "reals" de l'aplicació.

A els usuaris se'ls assignarà un nivell d'usuari. Aquests augmentaran el seu nivell a mida que vagin jugant (participant en concursos) i responent correctament preguntes. El seu nivell augmenta al respondre correctament una pregunta però també disminueix al respondre malament

Hi haurà varis modes de joc:

1. **Mode concurs.** Concurs entre usuaris. 
2. **Mode classe.** Concurs preparat per un usuari "professor".

Diferents rols d'usuari:

1. **Rol professor:** Podrà validar preguntes a l'instant. També podrà crear concursos "privats" per la seva classe.
2. **Rol usuari/alumne:** Un usuari sense privilegis especials.

**MECU!** també tindrà una sèrie de trofeus.
Es dividiran en 4 categories i seran els següents:

- **Fail**
    - Has acabat últim en un concurs
    - Has contestat 10 preguntes seguides incorrectament
    - Acomules més de 10 abandonaments
    - Has respost malament una pregunta teva
- **Principiant**
    - Primera pregunta correcta
    - Primer concurs finalitzat
    - Has acabat en el top 3 en un concurs
- **Amateur**
    - Has respost correctament una pregunta de cada categoria
    - Has acabat 1r en un concurs
    - Has respost correctament 100 preguntes
    - Has contestat 10 preguntes seguides correctament
- **Pro**
    - Has contestat 50 preguntes seguides correctament
    - Has respost correctament 500 preguntes
    - Has guanyat 5 concursos seguits

Les preguntes de **MECU!** es divideixen en vàries categories:

- **Matemàtiques**
- **Anglès**
- **Castellà**
- **Història**
- **Biologia/Geologia**
- **Física/Química**
- **Altres**

### Funcionalitats:

- Usuaris amb diferents rols on s'hi podran loggejar i registrar
    - Usuaris amb rol `Profe`
    - Usuaris amb rol `User`
- Hi ha relacions entre usuaris. Estil *seguiment* entre usuaris.
- Un usuari `Profe` pot fer el mateix que un usuari `User` amb alguns extres. *P.e. Validar preguntes sense procés de validació.*
- Diferents trofeus. *Especificats en el punt anterior.*
- Diferents categories. Es corresponen a diferents assignatures de la ESO. *Especificats en el punt anterior.*
- Hi ha diferents nivells de preguntes. Les preguntes estaran classificades en:
    - **Principiant**
    - **Amateur**
    - **Pro**
- Propostes de preguntes de diferents usuaris. *Els usuaris amb rol `User` hauran de passar un procés de validació*
- Hi ha un cercador d'usuaris.
- Hi ha un cercador de concursos
- Un usuari veurà els seus propis concursos.
- Un usuari veurà tots els concursos.
- Un concurs actiu és el que està en fase de búsqueda de concursants o s'està concursant.
- Concursos: (*especificats en el punt anterior*)
    - Mode concurs
    - Mode classe
- Hi ha 4 respostes per cada pregunta de les quals només 1 és correcte.