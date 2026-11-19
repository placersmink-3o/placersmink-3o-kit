# placersmink-3o-kit

Count lines, words and characters, with totals.

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m placersmink_3o_kit.cli --help
```

```python
from placersmink_3o_kit.core import Placersmink3oTool

tool = Placersmink3oTool()
print(tool)
```

## Layout

```
placersmink_3o_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 placersmink-3o
