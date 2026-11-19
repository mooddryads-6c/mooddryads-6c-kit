# mooddryads-6c-kit

Count lines, words and characters, with totals.

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m mooddryads_6c_kit.cli --help
```

```python
from mooddryads_6c_kit.core import Mooddryads6cTool

tool = Mooddryads6cTool()
print(tool)
```

## Layout

```
mooddryads_6c_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 mooddryads-6c
