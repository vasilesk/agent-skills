# agent-skills

The Claude Code marketplace by **vasilesk**: an index of plugins with Agent Skills. Each plugin lives in its own repository; this one only lists them.

## Plugins

| Plugin | What it covers |
| --- | --- |
| [`coding-rules`](https://github.com/vasilesk/coding-rules) | General programming conventions, Go coding conventions, and a hexagonal project layout sliced by bounded contexts |

## Installation

```
/plugin marketplace add vasilesk/agent-skills
/plugin install coding-rules@vasilesk
```

Or from the terminal:

```bash
claude plugin marketplace add vasilesk/agent-skills
claude plugin install coding-rules@vasilesk
```

Restart the session afterwards. To get updates automatically, enable auto-update for the `vasilesk` marketplace in the `/plugin` menu.

The skills follow the [Agent Skills](https://agentskills.io) format, so they also work outside Claude Code: see each plugin's README.

## License

[MIT](LICENSE)
