# BPMN.IO desktop app (using electron)
![Demo Screenshot](docs/demo.png "Demo Screenshot")


## installation

1. clone this repository `git clone git@github.com:HSKA-JSNinjas/bpmn-electron.git`
2. `npm install`
3. `grunt build`
4. `npm start`

## development

for development you can still use your normal browser. Just run a development server: `grunt auto-build`.

## Distribution
run `npm run publish-<platform>` to create a <platform> specific distribution.
run `npm run publish-all` to create all possible platforms and architectures.