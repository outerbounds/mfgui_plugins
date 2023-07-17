# charts plugin

This plugin can be used to show charts based on metrics from the service

## Usage

- Set up a proxy server so that requests to get metrics will be on the same domain as MFGUI
- Set the `PLUGINS` environment variable.

```bash
export PLUGINS='{"charts":{"repository":"https://github.com/outerbounds/mfgui_plugins.git","paths":["charts"],"ref":"origin/main"}}'
```

- Restart `metaflow-service`.
- Navigate to a task in MFGUI.
- See the charts on the page
