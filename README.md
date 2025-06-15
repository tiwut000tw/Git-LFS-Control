# Git-LFS-Control
Automation Tool


🇬🇧 
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


🇩🇪 
Bedienungsanleitung: Git LFS GUI Tool
Zweck des Tools
Dieses Programm bietet eine einfache grafische Benutzeroberfläche (GUI), um häufig verwendete Befehle von git und git lfs auszuführen. Es ist ideal für Benutzer, die eine visuelle Alternative zur Kommandozeile bevorzugen und die Ausgabe ihrer Befehle in Echtzeit sehen möchten.
Voraussetzungen
Bevor Sie das Tool verwenden, stellen Sie sicher, dass die folgenden Komponenten auf Ihrem System installiert sind:
Python 3: python.org
Git & Git LFS: git-scm.com und git-lfs.github.com. (Stellen Sie sicher, dass beide zum System-PATH hinzugefügt sind).
CustomTkinter-Bibliothek: Öffnen Sie ein Terminal/eine Eingabeaufforderung und führen Sie aus: pip install customtkinter
Ausführen des Skripts
Speichern Sie den Python-Code in einer Datei, z.B. git_lfs_gui_en.py.
Öffnen Sie ein Terminal im selben Ordner, in dem Sie die Datei gespeichert haben.
Führen Sie das Skript mit dem Befehl aus: python git_lfs_gui_en.py
Schritt-für-Schritt-Anleitung
Repository auswählen (WICHTIGSTER SCHRITT):
Klicken Sie auf den Button "Select Repository".
Wählen Sie den Hauptordner Ihres lokalen Git-Projekts aus. Dies ist zwingend erforderlich, da alle Befehle in diesem Ordner ausgeführt werden.
LFS initialisieren (falls erforderlich):
Wenn Sie Git LFS zum ersten Mal in diesem Repository verwenden, klicken Sie auf git lfs install. Dies muss nur einmal pro Repository geschehen.
Dateitypen zum Tracken festlegen:
Geben Sie ein Dateimuster in das Textfeld ein (z.B. *.blend, *.uasset).
Oder: Verwenden Sie die Preset-Buttons (*.*, *.zip, *.psd, *.mp4), um das Feld automatisch auszufüllen.
Klicken Sie anschließend auf git lfs track, um Git anzuweisen, diese Dateitypen mit LFS zu verwalten.
Standard-Git-Workflow:
git status: Überprüfen Sie den aktuellen Status Ihres Repositories.
git add .: Fügen Sie alle neuen oder geänderten Dateien (einschließlich der LFS-Dateien) zur Staging Area hinzu.
git commit: Geben Sie eine kurze Beschreibung Ihrer Änderungen in das Feld "Commit message" ein und klicken Sie dann auf den git commit-Button.
git push: Laden Sie Ihre Commits und die LFS-Dateien auf den Remote-Server (z.B. GitHub, GitLab) hoch.
Überprüfen der LFS-Dateien:
Klicken Sie auf git lfs ls-files, um eine Liste aller Dateien anzuzeigen, die aktuell von Git LFS in Ihrem Repository verwaltet werden.


🇪🇸 
Manual de Usuario: Herramienta GUI para Git LFS
Propósito de la Herramienta
Este programa proporciona una interfaz gráfica de usuario (GUI) sencilla para ejecutar comandos comunes de git y git lfs. Es ideal para usuarios que prefieren una alternativa visual a la línea de comandos y desean ver la salida de sus comandos en tiempo real.
Requisitos Previos
Antes de usar la herramienta, asegúrese de que los siguientes componentes estén instalados en su sistema:
Python 3: python.org
Git y Git LFS: git-scm.com y git-lfs.github.com. (Asegúrese de que ambos estén agregados al PATH de su sistema).
Librería CustomTkinter: Abra una terminal/símbolo del sistema y ejecute: pip install customtkinter
Cómo Ejecutar el Script
Guarde el código Python en un archivo, por ejemplo, git_lfs_gui_en.py.
Abra una terminal en la misma carpeta donde guardó el archivo.
Ejecute el script con el comando: python git_lfs_gui_en.py
Guía Paso a Paso
Seleccionar Repositorio (EL PASO MÁS IMPORTANTE):
Haga clic en el botón "Select Repository".
Elija la carpeta principal de su proyecto Git local. Este paso es obligatorio, ya que todos los comandos se ejecutarán dentro de este directorio.
Inicializar LFS (si es necesario):
Si es la primera vez que usa Git LFS en este repositorio, haga clic en git lfs install. Esto solo necesita hacerse una vez por repositorio.
Rastrear Tipos de Archivo:
Ingrese un patrón de archivo en el cuadro de texto (p. ej., *.blend, *.uasset).
O: Use los botones preestablecidos (*.*, *.zip, *.psd, *.mp4) para rellenar el campo automáticamente.
Luego, haga clic en git lfs track para indicarle a Git que gestione estos tipos de archivo con LFS.
Flujo de Trabajo Estándar de Git:
git status: Verifique el estado actual de su repositorio.
git add .: Agregue todos los archivos nuevos o modificados (incluidos los de LFS) al área de preparación (staging).
git commit: Ingrese una breve descripción de sus cambios en el campo "Commit message" y luego haga clic en el botón git commit.
git push: Suba sus commits y los archivos LFS al servidor remoto (p. ej., GitHub, GitLab).
Verificar Archivos LFS:
Haga clic en git lfs ls-files para ver una lista de todos los archivos que Git LFS está gestionando actualmente en su repositorio.
