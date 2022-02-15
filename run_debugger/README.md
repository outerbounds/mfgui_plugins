# run_debugger plugin

This plugin shows the metadata available for a run on the page and in the javascript console.

## Usage

* Run a flow that uses AWS Batch.
* Set the `PLUGINS` environment variable.
``` bash
export PLUGINS='{"run_debugger":{"repository":"https://github.com/outerbounds/mfgui_plugins.git","paths":["run_debugger"],"ref":"origin/main"}}'
```
* Restart `metaflow-service`.
* Navigate to a run in MFGUI.
* Open the `Details` dropdown.
* Open the `Debugger for run plugin` dropdown.
* Open the Javascript Console.
