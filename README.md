# jsonbreak
Breaks down large JSON files into a neat directory structure.

# Usage
Place jsonbreak and/or jsonrebuild into your python project's folder and import their functions:
```python
from jsonbreak.py import disassemble_json
from jsonrebuild.py import rebuild_json
```
Then, use the functions like so:
## `disassemble_json`
```python
disassemble_json(data, path, *, split_arrays=True/False)
```
- `data`: The raw JSON data to be disassembled (JSON dump, not file path)
- `path`: the path where to save the disassembled JSON directory structure

## `rebuild_json`
```python
rebuild_json(path)
```
- `path`: The generated directory structure to reassemble.
> `rebuild_json` returns a direct dump of the rebuilt json.
