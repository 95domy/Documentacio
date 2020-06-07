Quan s'obre l'aplicació hi ha l'opció d'iniciar sessió, registrar-se o recuperar contrasenya.
Per a iniciar sessió com a professor posarem:
Usuari: usuari
Contrasenya: 12345

Si es posa l'opció de registrar-se, l'aplicació et pregunta si tens llicència de professor o no, depenguent de la resposta s'obren dos formularis diferents, un per a professor o un per a alumne.

Un cop obreta l'aplicació se'ns posa a la pagina principal, en aquesta pàgina tenim les següents opcions:

- Revisar les batalles que tinc actives: En aquest apartat tenim un llistat de les batalles en que estas registrat i les que són teves pròpies.

- Crear una nova batalla: En aquest apartat se'ns obre un formulari per a posar informació de la batalla que s'està creant, els camps obligatoris estan marcats amb un *. Un cop posada l'informació, hi ha un icone abaix a la dreta per a guardar-la.

- Crear una nova pregunta: En aquest apartat se'ns obre un formulari on posem l'informació d'una nova pregunta (la pregunta, tres respostes incorrectes i una correcte). Quan acceptes la pregunta passa a estar a una fase d'aprovació.

- Validar una pregunta: Es planteja una pregunta aleatoria que esta en fase d'aprovació i es vota si agrada la pregunta o si no.

A part de la pàgina principal tenim els apartats de les batalles, el buscador d'usuaris i el perfil propi.

En l'apartat de battalles tenim un llistat de les batalles actives, tancades i pendents per obrir. En aquest apartat tenim un icone per a crear noves batalles, les batalles estàn pàginades en grups de 10 batalles.

En la pantalla del buscador hi ha el llistat d'usuaris existents en l'aplicació i una barra de buscador per la part de sobre per filtrar usuaris (per nom o correu). Si clickem en qualsevol usuari se'ns obre el seu perfil, en aquesta part tenim les opcions de veure els trofeus o seguir-lo:

- Trofeus: S'obre un llistat de trofeus, els aconseguits i no aconseguits per aquell usuari.

- Seguir: Agumenta en 1 el nombre de seguidors d'aquell usuari i el nombre de seguint per al usuari loguejat.

Finalment en l'apartat de perfil propi es pot veure l'informació del usuari logejat. En aquest apartat tenim les següents opcions:

- Editar perfil: Obre una pantalla on l'usuari pot modficiar la seva informació personal, cambiar la contrasenya i cambiar el seu avatar.

- Tancar sessió: Es tanca la sessió del usuari loguejat i el porta a la pantalla d'iniciar sessió.

- Trofeus: Igual que amb els altres perfils d'usuaris es mostra l'informació dels trofeus aconseguits i no aconseguits per l'usuari loguejat.

- Classes: Es la entitat que relaciona els professors amb els seus corresponens alumnes. Un estudiant unit a una classes pot unir-se a les batalles fetes pel professor que ha creat aquesta classes.

Per comprovar el funcionament de les notificacions necessitem dos emuladors:

- E1. Logejat com a usuari privilegiat. (pe Nom: usuari password: 123456)

- E2. Logejat com a usuari sense privilegis.(fer el sign up amb qualsevol usuari)

Un cop tinguem tots els passos anteriors completat, ara ja podem procedir a comprovar de què efectivament s'envien les notificacions.

En primer lloc per comprovar quan accepten/rebutjant una pregunta meva. Hem d'anar a l'emulador 1 (Logejat com a usuari sense llicencia), a continuació anem a l'opció crear una pregunta, creem una pregunta qualsevol i les seves respectives respostes i la guardem. Un cop tinguem la pregunta creada ara anem a l'emulador E1, busquem el botó on diu validar preguntes, i ens apareixerà totes les preguntes pendents de validar, busquem la pregunta que hem creat anteriorment a l'emulador E1, un cop la trobem, la validem i ara en principi hi hauria d'aparèixer a l'emulador E2 una notificació de què s'ha validat/rebutjat la pregunta.

En segon lloc, per comprovar quan un usuari participa en una batalla meva. Anem a l'emulador E2, a continuació anem a batalles, busquem una batalla de l'usuari logejat com a usuari(E1) (pe English 1), i quan hàgim acabat de participar en la batalla, l'emulador E1 hauria de rebre una notificació de què un usuari ha participat en la seva batalla.
