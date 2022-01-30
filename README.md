# Filetools

> Tools for getting, inspecting and validating files and their information

# Requirements

- Python 3.8 or higher
- Python magic -- https://pypi.org/project/python-magic/

# Installation

## Manual

```bash
python3 -m pip install --user -r requirements.txt
chmod a+rx ./setup.sh
sudo ./setup.sh
```

## Packages

- Linux
  - Gentoo linux: [app-admin/filetools::dinolay](https://ari-web.xyz/gentooatom/app-admin/filetools)

# Tools

- `finfo` -- Get detailed file information
- `fhash` -- Generate file hashes
- `fhashver` -- Verify hashes generated by `fhash`
