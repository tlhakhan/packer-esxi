# README
This folder is embedded into the Go binary.

The folder should be structred as follows:
- `<os>/<version>/packer_template.json` - the packer template file.
- `<os>/<version>/http_templates/` - a folder where every file is processed as a Go `text/template` upon request.
- `<os>/<version>/http_templates/ipxe.sh` - a standard iPXE script called from the packer template.
