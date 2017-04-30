# Dropbox - Folder Sync and Backup
(Version 2.0 30/04/2017)

1. **[Incipit](#1Incipit);**
2. **[Brief Description](#2brief-description);**
3. **[State of the Project](#3state-of-the-project)**
4. **[Copyright](#4copyright)**

## 1.Incipit

Project created for the course "Programmazione di sistema", year 2015, of Politecnico di Torino.
Is developed in collaboration between me and @marc0l92.

## 2.Brief Description

The project implement a Client-Server application written in C#. 
The purpose of this application is to save and backup a folder and its sub-folders, with the possibility to restore older versions through the versioning system.
The app routine is so implemented:
- The Client is waiting, with low resource use, the interrupt of "file changes" by the O.S.;
- Than, it sends the modifications and files to the Server;
- The remote Server stores the files and create a versioning system using a SQLite database, waiting further changes;
- The Client can ask an old version of each file to the Server.

## 3.State of the Project
- No further Mantained

## 4.Copyright

- According to the LICENSE file of the original code,
- Me and original author hold no liability for any damages;
- Do not use this on commercial!.
