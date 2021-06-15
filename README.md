# Batch Obsidian Forward Linker

This script does the following:

- Scans your vault location recursively for .md files and builds a list of note titles
- Imports title aliases from aliases.yml in vault root
- Add the links [[ ]] if the same keyword is also the name of some file in vault
- All links are added in batch, all vault files will be interlinked via [[]]] in body text

## Requirements

* Python 3 + pip
* PyYAML ```pip install pyyaml```

## Running

```python obs-batch-linkr.py {path to obsidian vault root}```

## Aliases

You can use a file named aliases.yml in your vault root to broaden the title matching in your text to include aliases.

## Notes

This plugin is fork version of https://github.com/perkinsben/obs_tools
- edited for bulk interlinking not for single file
