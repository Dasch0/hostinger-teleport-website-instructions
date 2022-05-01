# Instructions for exporting website from teleporthq to hostinger
1. Install [nodejs/npm](https://nodejs.org/en/download/)
2. Navigate to teleport project, make edits as needed, export via `Download->React->Zip file`
3. unzip contents into this directory, then run from command line
```
npm install
npm run build
```
4. Create a zip file of the contents of the newly created `build` directory
5. Upload to `Hostinger->Manage->Import Website`
