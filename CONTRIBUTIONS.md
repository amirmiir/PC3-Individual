# Contribuciones de [Amir Canto Gamboa]

## Sprint 1

### feature/add_config

Añado las características base del proyecto
commit f6243e6a1f2708482d87072b30a62bb9cabe734f
Date: Sat Jun 7 2025
feat: initial version 0 for project development
feat: added app.py & run\_app.sh

### feature/no-direct-push-gh [DEPRECATED]

En los siguientes commits añado y realizo pruebas para controlar los pushes en main.
Esto se maneja mejor a través de la configuración de GH.

commit 697ac0cfaefd5e511243d7a59ace79f36a0938ab
Date: Sun Jun 8 2025
feat: create gh actions to prevent pushes on main
feat: add .github/workflow/no-direct-push.yml

commit 320e448548b10aec449173d2a48e5147554926e7
Date: Sun Jun 8 2025
feat: create gh actions to prevent pushes on main
feat: create gh actions to prevent pushes on main

commit 857aeb7458d1a743136d61ce02b105dfda1baf54
Date: Sun Jun 8 2025
chore: testing the gh actions: no-direct-push.yml

commit 4b7c5116a7d2a8f4ccafed97b86363599acaeb9a
Date: Sun Jun 8 2025
chore: second test for gh action no-direct-push.yml

commit 07337b7a87ce1c0253273ba5861520381a6e2252
Date: Sun Jun 8 2025
chore: add test-file for testing pushes

### feature/frontend/forms-base-ui

Modifiqué el template de Jinja
commit 6f1ed502f2eab0b75e294ebafeecf25b57ce99c2
Date: Mon Jun 9 2025
feat: add styles for index.html for ui/ux

### feature/frontend/forms-result

Implementé el formato para el dashboard
commit 49720b006c48b9138c4a67cf06c575edb2a6b5a7
Date: Mon Jun 9 2025
feat: add styles for result.html for ui/ux

### feature/frontend/dashboard-ui

En los siguientes commits se modifica el aspecto visual y lógica en Jinja

commit a979fde7493630709b4414cfc67a69566ab7cda6
Date: Mon Jun 16 2025
feat: add empty file dashboard in /templates/dashboard.html
style: refined styles in /templates/index.html & /templates/result.html

commit 6376b8f810330794fa38a659ea44b203d870ab60
Date: Mon Jun 16 2025
feat: add dashboard html ui/ux in /templates/dashboard.html
chore: swap places at /templates/result.html
style: change minimal color styles at /templates/index.html & /templates/result.html

commit c4319cf476efa1cf05dde6ba011f6558788e5f07
Date: Tue Jun 17 2025
chore: <h1> headers have been changed for better visuals

## Sprint 2

### feature/dummy-database

En los siguientes commits implementé funcionalidades básicas para una base de datos de prueba, previa a la conexión a Supabase

commit daa8c26aebb24088502a413069cc9c13db0ff06d
Date: Tue Jun 17 2025
feat: URLData class defined for handling information from a URL

commit 5a4f5f2d356c4bc16e520c17cf85752369353e19
Date: Tue Jun 17 2025
feat: URLDatabase class created as a singleton handling multiple URLData

commit d1d62211d6a9f22b4baf427954b1d5da1a037210
Date: Tue Jun 17 2025
chore: proper formatting space after import

commit cf58c2d874b564a42ccd94628384c6c64833c1b3
Date: Tue Jun 17 2025
docs: correct language ES change in /core/db.py docstrings

### feature/cli_ops

En este commit añado la función cli()

commit b29e5644893402a3759af037361d7e223fb4568b
Date: Tue Jun 17 2025
feat: add base function cli and logic for **main**

En este commit implemento el parseo de argumentos

commit ce62e74d21e21ad81bc0bfe05c3408d0f9475a
Date: Tue Jun 17 2025
feat: cli argument parser implemented

En este commit añado el testing en /tests/

commit d9c52881c721985ba0404b900e1b4f098013d66e
Date: Tue Jun 17 2025
feat: add test for cli operations with pytest

commit 8bf4d961e65440bc9dd8821f7d05f788bb217068
Date: Wed Jun 18 2025
Merge branch 'develop' into feature/cli\_ops

### feature/dash-connection

En este commit modificamos el formateo de Jinja/HTML para las fechas AAAA-MM-DD

commit 890518a9334ea32a4822260e3233ada57d705ee5
Date: Wed Jun 18 2025
chore: add proper formatting for dates

Creación de la tabla

commit fc93a88f4c0b99a08f9354858cc2480635349426
Date: Wed Jun 18 2025
feat: add table for user's urls display and styling

Solución de un error de sintaxis

commit 748b85ab27f5b4acc9487a24321b590867ee64b
Date: Wed Jun 18 2025
fix: solved Jinja's syntax errors

Implementamos la función de shorter\_url.py

commit 8333916d0e69aa17112d6ed4ce394036a22ea6af
Date: Wed Jun 18 2025
feat: add dashboard functionality with live user data

Solucionamos que se estaba imprimiendo nuestro URL de .env para la conexión con la base de datos

commit fb22496c331c0a083e4d4985da38774d99094eda
Date: Wed Jun 18 2025
chore: delete print URL

### feature/frontend/design-update

Actualizamos el aspecto de la aplicación

commit e41f22bfd2de1c51b879fb0c888003ea47db120d
Date: Thu Jun 19 2025
chore: reordered displaye of subtitiles

commit 1b2743aeb67c1f8b763c6a7d9b94cb91abe35a87
Date: Thu Jun 19 2025
Merge branch feature/frontend/design-update into develop
chore: username displayed at landing

## Sprint 3

### hotfix/1.0.1

Arreglamos la ejecución de la aplicación en UNIX

commit 26881fe4aa87a2ec55967c38911c8003fdd31dcf
Date: Thu Jun 19 2025
fix: run_app.sh properly working

Añadimos lógica al index.html con Jinja

commit b737837890d0c55449b6f8cbf1082bd273be1f48
Date: Thu Jun 19 2025
fix: show username only when user is logged

Modificamos la versión como string

commit 6c61e8647a82add88ce554a18203ea39dd07d09d
Date: Thu Jun 19 2025
chore: update release version

Actualizamos la versión en testing

commit 8836446e705fd40ecf32f852984cc82bb2390d6e
Date: Thu Jun 19 2025
fix: version for testing

### release/1.1.0

Realizamos retoques al archivo (lo trabajamos en Google Drive y en grupo)

commit 12200b8dc366a324c19fc882e6d85c29b81a172b
Date: Fri Jun 20 2025
docs: git-workflow docs updated
