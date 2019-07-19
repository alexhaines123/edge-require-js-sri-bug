# edge-require-js-sri-bug
This repository shows a bug where Edge does not run an integrity check on files that are included using requireJs.

Open index.html and open the console in Edge and see how the script which is included using requireJS still runs even though the integrity hash is incorrect, but the script included using html fails the integrity check. Do the same in Chrome and you will that both fail the integrity check.
