## Install NX globally

`npm i --global nx@latest --legacy-peer-deps`

## Install http-server for run the builds

`npm install -g http-server`

## Install dependencies

`npm install --legacy-peer-deps`

## Build the app

### To build admin-provider portal

`nx build admin-provider`

### To build patient portal

`nx build patient`

### After the build, navigate to the dist folder and run the builds

`cd dist/apps/admin` <br />
`http-server -p <port>`
<br /> <br />
`cd dist/apps/provider` <br />
`http-server -p <port>`

## Start the app

To start the development server run

### For Admin-Provider Portal

`nx serve admin-provider --port <port>`

### For Patient Portal

`nx serve patient --port <port>`

## Generate New React Project

`nx generate @nrwl/react:app <project_name>`

## Generate Common library

`nx generate @nrwl/react:library <library_name>`
