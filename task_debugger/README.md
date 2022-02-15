# task_debugger plugin

This plugin shows the metadata available for a task on the page and in the javascript console.

## Usage

* Run a flow that uses AWS Batch.
* Set the `PLUGINS` environment variable.
``` bash
export PLUGINS='{"task_debugger":{"repository":"https://github.com/outerbounds/mfgui_plugins.git","paths":["task_debugger"],"ref":"origin/main"}}'
```
* Restart `metaflow-service`.
* Navigate to a task in MFGUI.
* Open the `Debugger for task plugin` dropdown.
* Open the Javascript Console.
