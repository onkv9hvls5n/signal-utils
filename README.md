# signal-utils

Helpers for handling SIGTERM/SIGINT and draining work before exit.

## Why

Extracted from a larger codebase where it had grown organically.

## Install

```bash
pip install signal-utils
```

## Usage

```python
from signal_utils import signalUtils

result = signalUtils("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
