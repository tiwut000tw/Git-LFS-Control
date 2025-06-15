version https://git-lfs.github.com/spec/v1
oid sha256:0ae022c155ffac4fd261e4d1feb03f6a327b7c93dad3d4ada33004ea2e782c1b
size 6711

EN
User Manual: Git LFS GUI Tool
Purpose of the Tool
This program provides a simple graphical user interface (GUI) to execute common git and git lfs commands. It is ideal for users who prefer a visual alternative to the command line and want to see the real-time output of their commands.
Prerequisites
Before using the tool, ensure the following are installed on your system:
Python 3: python.org
Git & Git LFS: git-scm.com and git-lfs.github.com. (Make sure both are added to your system's PATH).
CustomTkinter Library: Open a terminal/command prompt and run: pip install customtkinter
How to Run the Script
Save the Python code to a file, e.g., git_lfs_gui_en.py.
Open a terminal in the same folder where you saved the file.
Execute the script with the command: python git_lfs_gui_en.py
Step-by-Step Guide
Select Repository (MOST IMPORTANT STEP):
Click the "Select Repository" button.
Choose the main folder of your local Git project. This is mandatory, as all commands will be executed within this directory.
Initialize LFS (if needed):
If this is the first time you are using Git LFS in this repository, click git lfs install. This only needs to be done once per repository.
Track File Types:
Enter a file pattern into the text box (e.g., *.blend, *.uasset).
Or: Use the preset buttons (*.*, *.zip, *.psd, *.mp4) to automatically fill the field.
Then, click git lfs track to tell Git to manage these file types with LFS.
Standard Git Workflow:
git status: Check the current status of your repository.
git add .: Add all new or modified files (including LFS files) to the staging area.
git commit: Enter a short description of your changes into the "Commit message" field, then click the git commit button.
git push: Upload your commits and LFS files to the remote server (e.g., GitHub, GitLab).
Check LFS Files:
Click git lfs ls-files to see a list of all files currently being managed by Git LFS in your repository.


DE 
Bedienungsanleitung: Git LFS GUI Tool
Zweck des Tools
Dieses Programm bietet eine einfache grafische BenutzeroberflÃ¤che (GUI), um hÃ¤ufig verwendete Befehle von git und git lfs auszufÃ¼hren. Es ist ideal fÃ¼r Benutzer, die eine visuelle Alternative zur Kommandozeile bevorzugen und die Ausgabe ihrer Befehle in Echtzeit sehen mÃ¶chten.
Voraussetzungen
Bevor Sie das Tool verwenden, stellen Sie sicher, dass die folgenden Komponenten auf Ihrem System installiert sind:
Python 3: python.org
Git & Git LFS: git-scm.com und git-lfs.github.com. (Stellen Sie sicher, dass beide zum System-PATH hinzugefÃ¼gt sind).
CustomTkinter-Bibliothek: Ã–ffnen Sie ein Terminal/eine Eingabeaufforderung und fÃ¼hren Sie aus: pip install customtkinter
AusfÃ¼hren des Skripts
Speichern Sie den Python-Code in einer Datei, z.B. git_lfs_gui_en.py.
Ã–ffnen Sie ein Terminal im selben Ordner, in dem Sie die Datei gespeichert haben.
FÃ¼hren Sie das Skript mit dem Befehl aus: python git_lfs_gui_en.py
Schritt-fÃ¼r-Schritt-Anleitung
Repository auswÃ¤hlen (WICHTIGSTER SCHRITT):
Klicken Sie auf den Button "Select Repository".
WÃ¤hlen Sie den Hauptordner Ihres lokalen Git-Projekts aus. Dies ist zwingend erforderlich, da alle Befehle in diesem Ordner ausgefÃ¼hrt werden.
LFS initialisieren (falls erforderlich):
Wenn Sie Git LFS zum ersten Mal in diesem Repository verwenden, klicken Sie auf git lfs install. Dies muss nur einmal pro Repository geschehen.
Dateitypen zum Tracken festlegen:
Geben Sie ein Dateimuster in das Textfeld ein (z.B. *.blend, *.uasset).
Oder: Verwenden Sie die Preset-Buttons (*.*, *.zip, *.psd, *.mp4), um das Feld automatisch auszufÃ¼llen.
Klicken Sie anschlieÃŸend auf git lfs track, um Git anzuweisen, diese Dateitypen mit LFS zu verwalten.
Standard-Git-Workflow:
git status: ÃœberprÃ¼fen Sie den aktuellen Status Ihres Repositories.
git add .: FÃ¼gen Sie alle neuen oder geÃ¤nderten Dateien (einschlieÃŸlich der LFS-Dateien) zur Staging Area hinzu.
git commit: Geben Sie eine kurze Beschreibung Ihrer Ã„nderungen in das Feld "Commit message" ein und klicken Sie dann auf den git commit-Button.
git push: Laden Sie Ihre Commits und die LFS-Dateien auf den Remote-Server (z.B. GitHub, GitLab) hoch.
ÃœberprÃ¼fen der LFS-Dateien:
Klicken Sie auf git lfs ls-files, um eine Liste aller Dateien anzuzeigen, die aktuell von Git LFS in Ihrem Repository verwaltet werden.


ES
Manual de Usuario: Herramienta GUI para Git LFS
PropÃ³sito de la Herramienta
Este programa proporciona una interfaz grÃ¡fica de usuario (GUI) sencilla para ejecutar comandos comunes de git y git lfs. Es ideal para usuarios que prefieren una alternativa visual a la lÃ­nea de comandos y desean ver la salida de sus comandos en tiempo real.
Requisitos Previos
Antes de usar la herramienta, asegÃºrese de que los siguientes componentes estÃ©n instalados en su sistema:
Python 3: python.org
Git y Git LFS: git-scm.com y git-lfs.github.com. (AsegÃºrese de que ambos estÃ©n agregados al PATH de su sistema).
LibrerÃ­a CustomTkinter: Abra una terminal/sÃ­mbolo del sistema y ejecute: pip install customtkinter
CÃ³mo Ejecutar el Script
Guarde el cÃ³digo Python en un archivo, por ejemplo, git_lfs_gui_en.py.
Abra una terminal en la misma carpeta donde guardÃ³ el archivo.
Ejecute el script con el comando: python git_lfs_gui_en.py
GuÃ­a Paso a Paso
Seleccionar Repositorio (EL PASO MÃS IMPORTANTE):
Haga clic en el botÃ³n "Select Repository".
Elija la carpeta principal de su proyecto Git local. Este paso es obligatorio, ya que todos los comandos se ejecutarÃ¡n dentro de este directorio.
Inicializar LFS (si es necesario):
Si es la primera vez que usa Git LFS en este repositorio, haga clic en git lfs install. Esto solo necesita hacerse una vez por repositorio.
Rastrear Tipos de Archivo:
Ingrese un patrÃ³n de archivo en el cuadro de texto (p. ej., *.blend, *.uasset).
O: Use los botones preestablecidos (*.*, *.zip, *.psd, *.mp4) para rellenar el campo automÃ¡ticamente.
Luego, haga clic en git lfs track para indicarle a Git que gestione estos tipos de archivo con LFS.
Flujo de Trabajo EstÃ¡ndar de Git:
git status: Verifique el estado actual de su repositorio.
git add .: Agregue todos los archivos nuevos o modificados (incluidos los de LFS) al Ã¡rea de preparaciÃ³n (staging).
git commit: Ingrese una breve descripciÃ³n de sus cambios en el campo "Commit message" y luego haga clic en el botÃ³n git commit.
git push: Suba sus commits y los archivos LFS al servidor remoto (p. ej., GitHub, GitLab).
Verificar Archivos LFS:
Haga clic en git lfs ls-files para ver una lista de todos los archivos que Git LFS estÃ¡ gestionando actualmente en su repositorio.
