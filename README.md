# vscode-portforward-quirk

## Reproduce

* Clone this repository on a remote host
* Open a session to the remote host and open project1
* Run `./reopen.sh`
* In the project3 window
  * Install node modules (`npm install` or `yarn install`)
  * Start environment (`npm start` or `yarn start`)

## Expected behavior
* Port forward for port 3000 is added to all remote windows
* 3 tabs are open in the local browser
