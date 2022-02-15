# aws-batch plugin

This plugin provides a link to the AWS Batch job page for tasks that uses AWS Batch.

## Usage

* Run a flow that uses AWS Batch.
* Set the `PLUGINS` environment variable.
``` bash
export PLUGINS='{"aws-batch":{"repository":"https://github.com/outerbounds/mfgui_plugins.git","paths":["aws-batch"],"ref":"origin/main","parameters":{"sandbox":"allow-popups allow-popups-to-escape-sandbox"}}}'
```
* Restart `metaflow-service`.
* Navigate to the task that uses AWS Batch in your instance of MFGUI.
