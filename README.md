# BibliothekDeployment
Dieses Repository wird verwendet um das Deployment des Bibliothek-Systems (eines anderen Repositorys) zu ermöglichen. Dieses Repository soll öffentlich zugänglich sein.

# Voraussetzungen im Quellcode
- Stelle sicher dass die SQLStrings der Production verwendet werden. ProductionSQLStrings in Program.cs
- ```dotnet publish -c Release -r win-x64 --self-contained true -o ../deploy/dotnetpublished ``` Dieser Command wird im "Bibliothek-System" Ordner ausgeführt.
- Stelle sicher dass dieser "deploy" Ordner zu github gepushed wird. 
