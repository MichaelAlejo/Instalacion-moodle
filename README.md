# Instalacion-moodle
## Configuracion de la instalacion del Moodle
**1.** Inicia sessió com a administrador del teu Moodle i realitza les següents tasques prèvies d'administració.
 
 **a)** Canvia la teva direcció de correu electrònic i també la teva contrasenya per una altra. Afegeix-te a més un avatar. Tot això es pot fer anant al teu perfil (opció que apareix sota el teu nom que es veu a la part superior dreta de la finestra del Moodle) i clicant sobre l'enllaç `Editar` (o també anant a l'opció `Preferències`, situada al mateix lloc).
 ![Captura desde 2025-03-13 10-28-08](https://github.com/user-attachments/assets/35942c71-2fb9-481d-a5a5-0c8b01481ef2)

 
  **b)** Canvia el nom del teu lloc (tant llarg com curt) i fes que la pàgina principal no mostri res pels usuaris que no estiguin autentificats. Això es pot fer anant a l'opció `Administració del lloc > Primera plana > Paràmetres`
  ![Captura desde 2025-03-13 10-38-03](https://github.com/user-attachments/assets/cc8b1a1f-93c2-4458-ae47-53218479411e) ![Captura desde 2025-03-13 10-47-23](https://github.com/user-attachments/assets/cccd25d1-3674-4d03-8c29-bc6ee9a56f73)

  **c)** Comprova que la franja horària del teu lloc sigui la correcta. Això es pot fer anant a l'opció `Administració del lloc > Ubicació > Paràmetres`.
  
  ![Captura desde 2025-03-13 10-50-52](https://github.com/user-attachments/assets/c7bb59d8-9890-4de8-abf6-ca44bc50ceca)

   **d)** Canvia l'idioma del teu lloc. Això es pot fer anant a l'opció `Administració del lloc > Idioma > Paràmetres` i tenint en compte tant el checkbox `Detecció automàtica de l'idioma` com el desplegable `Idioma per defecte`.
   ![Captura desde 2025-03-14 14-04-15](https://github.com/user-attachments/assets/f74a68a6-5932-400e-9531-e90d6247a79a)
  
   **e)** Canvia la política de contrasenyes de manera que els usuaris que es creiïn tinguin una contrasenya de com a mínim 4 caràcters incloent-hi, majúscules, minúscules i xifres. Això es pot fer anant a l'opció `Administració del lloc >   Seguretat > Normatives del lloc`.
   
   ![Captura desde 2025-03-14 14-09-28](https://github.com/user-attachments/assets/aa1ce9fc-37f8-4043-b37a-3b6767e9608c)
   
**2.** Crea els següents cursos: un curs anomenat A que estigui format per 3 temes i un altre anomenat B que estigui format per 5 temes. Tot això ho pots fer des de `Administració del lloc > Gestiona cursos i categories` o també des del quadre `Navegació` anant a `Cursos > Afegeix curs`

 **Curso A**
 
 ![Captura desde 2025-03-14 14-13-39](https://github.com/user-attachments/assets/2bea9596-a4f2-433f-9462-cd5b1d704b73) ![Captura desde 2025-03-14 14-13-49](https://github.com/user-attachments/assets/9012e8d3-911e-4a5d-aaed-d7b667a17423)

**Curso B**

![Captura desde 2025-03-14 14-15-21](https://github.com/user-attachments/assets/e250763f-3496-49c6-8efa-830b29e11667) ![Captura desde 2025-03-14 14-25-54](https://github.com/user-attachments/assets/edb38d21-5dd1-47df-af55-aa1c520048ad)

**3.** Vés a algun dels cursos creats al punt anterior (simplement seleccionant-lo dins del quadre `Navegació`) i fes que contingui en algun del seus temes algun tipus de material (un document PDF, per exemple), canvia el títol d'algun tema i, en general, investiga les possibilitats que et dóna el botó `Activar edició` en un curs.
![Captura desde 2025-03-20 13-46-24](https://github.com/user-attachments/assets/eef075af-7670-4f99-b08c-f54af1e5aa2a)

**4.** Creació d’usuaris i alumnes
   
   **a)** Crea manualment un usuari anomenat `Bob` que ha de fer servir el `mètode d'autenticació manual`. Això es pot fer des de `Administració del lloc > Usuaris > Comptes > Afegeix un usuari`
   ![Captura desde 2025-03-20 13-50-38](https://github.com/user-attachments/assets/46f9060c-4a61-4425-9df0-bc099769329c)
   
   **b)** Genera deu alumnes que ho seran dels dos cursos A i B . Fes servir un arxiu CSV per realitzar aquesta creació en bloc. Vés a `Administració del lloc > Usuaris > Comptes > Carrega usuaris` i segueix els passos que et marca. 
![Captura desde 2025-03-20 14-11-28](https://github.com/user-attachments/assets/4fef6662-e06b-4962-b66c-d05bd6ab52eb) ![Captura desde 2025-03-20 14-12-12](https://github.com/user-attachments/assets/eb147fdb-2f7d-4fa0-b3fa-dd68e1a3038a)

 **c)** Elimina dos dels deu alumnes creats a l'apartat anterior fent servir l'opció `Administració del lloc > Usuaris > Accions amb usuaris en bloc`
 
 ![Captura desde 2025-03-20 14-24-14](https://github.com/user-attachments/assets/932627cb-b21b-4570-93ec-fc22e26b03e7) ![Captura desde 2025-03-20 14-24-53](https://github.com/user-attachments/assets/eb3b100e-b3f1-4cb9-8889-54ec4d091e9d)

 **5.** Ara matricula aquests usuaris als diferents cursos.
  
  **a)** Fes que al curs A no hi hagi possibilitat d'inscripció (és a dir, que només es permeti l'accés de visitant de manera que el curs sigui totalment públic sense control d'usuaris -ni alumnes ni professors-). D'altra banda, fes que al curs B es necessiti registre manual d'usuaris (és a dir, que sigui l'administrador -tu- qui matriculi cada usuari al curs, ja sigui com a professor o com a alumne). Tot això ho pots fer des de `Administració del curs > Ususaris > Mètodes d'inscripció`. Si no surt algun mètode d'inscripció disponible, has d'activar-lo a: `Administració de lloc > Connectors > Autenticació > Gestió de l'autenticació`

  **Curso A**![Captura desde 2025-03-21 13-54-49](https://github.com/user-attachments/assets/8d0d13fb-5cb5-48c3-969f-427f86305cf7)

  **Curso B**![Captura desde 2025-03-21 13-58-12](https://github.com/user-attachments/assets/1b0277e7-bd10-439d-87e2-d98ba78281f1)


   **b)** Assigna com a professor del curs B l'usuari "Bob" i com a alumnes a tots els que fas afegir des de l'arxiu CSV Tot això ho pots fer anant a `Administració del curs > Usuaris inscrits > Inscriure`.

   ![Captura desde 2025-03-21 14-00-03](https://github.com/user-attachments/assets/2a6ec9a9-47ac-495b-b910-7a6fb1307208)


   **c)** Comprova que efectivament, el contingut del curs A (afegit per l'administrador del sistema -és a dir, tu- estigui disponible públicament i que per accedir al curs B s'hagi d'iniciar sessió amb un usuari registrat (alumne o professor)
![Captura desde 2025-03-21 14-14-51](https://github.com/user-attachments/assets/40b601d6-359a-4fa4-8cfe-6f72908f7d4f)
 ![Captura desde 2025-03-21 14-20-58](https://github.com/user-attachments/assets/5838519a-13e7-4fe1-a857-063507a08963)

**6.** Canvia l'aparença estètica del teu lloc. Concretament, descarrega't i activa un tema diferent dels que venen per defecte i prova de canviar també la capçalera i el peu de pàgina del lloc. Això ho pots fer primer anant a `Administració del lloc > Connectors > Instal·lar complement` i després a `Administració del lloc > Aparença > Temes > Selector de temes` Sempre pots fer servir l'enllaç `Canvi de rol` del menú de la dreta per observar com es veuria el lloc sent alumne, professor, etc.
![Captura desde 2025-03-21 14-19-15](https://github.com/user-attachments/assets/be66ffa0-0e13-4aca-85c9-e115c63a95c8)

**7.** Assigna un professor i matricula alumnes al curs A.
![Captura desde 2025-03-27 13-46-50](https://github.com/user-attachments/assets/da847b7f-4174-4098-93fa-b77f786bd861)

