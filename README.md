>*Note: This repository primarily serves as a submodule for `LittleEngine` (and is bound by the same licence), but is completely standalone and free to be used in any other projects.*

### LittleEngine Logger

*Copyright 2019 Karn Kaul*

Features:
  - Thread-safe
  - Optionnal callback for file logging / in-app etc
  - Severity prefix and date suffix
  - Severity filter
  - Logs to VS Output Window also

Usage:
  - Define `DEBUG_LOGGING 1` to enable `LOG_D`
  - Include this file and call `LOG_X(message, format)` where `X = { E, W, I }` for Error, Warning, Info
  - Set `g_MinLogSeverity` to set the minimum severity threshold
