# Local Connector plugin marketplace

Installable native plugin for Apple Silicon macOS and Windows x64. No Node/npm runtime is required.

```sh
codex plugin marketplace add whzxc/clc-plugins --ref stable
codex plugin add clc@local-connector
```

Update with `codex plugin marketplace upgrade local-connector`, then reload the host. Existing sessions keep their running version until reloaded.

[Installation and migration](https://github.com/whzxc/chatgpt-local-connector/blob/main/docs/plugin.md) · [Source and releases](https://github.com/whzxc/chatgpt-local-connector)

The stable branch contains signed release payloads assembled by the source repository's release workflow. Version tags preserve each published snapshot. Do not edit generated files here. MIT licensed.
