### Introduction

Example file for allowing PlayCanvas Scripts 2 to read source from a local server, especially
useful for webpack-dev-server. 

### Installation

```language-shell
npm install --save playcanvas-local-host
```

### Usage

Create a loading screen for your project.

*Either* paste the contents of loading_screen.js into the file that PlayCanvas creates.

*Or* if you already have a loading screen insert the code from `exerpt.js` at the top of the
function, just below `pc.script.createLoadingScreen(function (app) {`. 

Now append a parameter to the query string of `?local=http://localhost:8081` substituting your
local server port.

### Requirements

Requires PlayCanvas Engine. 
