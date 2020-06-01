# Windows 10 Recovery

## Enter Safe Mode
- In recovery menu go `Repair Your Computer` > `Troubleshoot` > `Advanced options` > `Command Prompt`.

- Run in command prompt:
  ```
  bcdedit /set {default} safeboot minimal
  ```

## Restart in Normal Mode
- `Win + R` > `msconfig`
- In `Boot` tab, uncheck `Safe boot`
- `OK`,
- Restart.
