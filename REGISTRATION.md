# Registration

Add each supervisor as an agent in `openclaw.json`:

```json
{
  "agents": {
    "entries": [
      {
        "id": "luna",
        "soul": "/path/to/my-workforce/Luna.md",
        "memory": "~/memory/luna",
        "logs": "~/logs/luna"
      },
      {
        "id": "orion",
        "soul": "/path/to/my-workforce/Orion.md",
        "memory": "~/memory/orion",
        "logs": "~/logs/orion"
      },
      {
        "id": "lens",
        "soul": "/path/to/my-workforce/Lens.md",
        "memory": "~/memory/lens",
        "logs": "~/logs/lens"
      },
      // ... repeat for each supervisor
    ]
  }
}
```

Restart the gateway after adding entries.

For spawning from templates, ensure your supervisors' SOULs include instructions to use `sessions_spawn` with the template SOUL file path or URL.
EOF