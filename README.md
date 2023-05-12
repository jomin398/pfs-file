
# pfs-file

Decrypt and Extract(unpack) *.pfs game resource files

for example, someof emote's game.

(the file magic number is `pf8`/`pf6`)  

### Extract guide
1. Rename the copyed target file (`<gameName>.pfs.000`) to `root.pfs.000`
2. move that file to this tools root folder. as like below.

- root (this tool's folder)
  - main.js
  - README.md
  - ....
  - **root.pfs.000**

3. excute this command once on cmd.exe
```sh
npm i
```
4. excute this command as try to convert each file on cmd.exe
```sh
node main.js
```
after then. chack out created `out` folder on root folder.

- root (this tool's folder)
  - out << a folder, which is extracted data.

### note.
rename or replace the `out` folder as you want.
(OR else, just kept it to Override the existed contents.)
