# cli-spinner

Spinners and progress bars that degrade gracefully when not a TTY.

## Why

I kept rewriting the same thirty lines in every project, so I pulled them out.

## Install

```bash
pip install cli-spinner
```

## Usage

```python
from cli_spinner import cliSpinner

result = cliSpinner("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
