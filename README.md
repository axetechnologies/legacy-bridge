# LegBri — Legacy Bridge

Run modern macOS on unsupported Macs.

LegBri patches and configures OpenCore for legacy Mac hardware, enabling macOS Ventura, Sonoma, and Sequoia on machines Apple no longer supports.

## Features

- OpenCore-based boot configuration for unsupported Macs
- Automated root volume patching for hardware compatibility
- macOS installer creation from Apple's software catalog
- GUI and CLI operation modes

## Supported Hardware

Mac models from 2007–2017 depending on macOS target version. See the [compatibility guide](https://axetechnologies.github.io/legacy-bridge/) for full details.

## Usage

```bash
python3 Build-LegBri.command
```

Or download a pre-built release from [Releases](https://github.com/axetechnologies/legacy-bridge/releases).

## Requirements

- Python 3.6+
- wxPython (for GUI mode)
- macOS 11+ host for building

## License

BSD-3-Clause. See [LICENSE.txt](LICENSE.txt).

## Attribution

LegBri is based on [OpenCore Legacy Patcher](https://github.com/dortania/OpenCore-Legacy-Patcher) by Dortania, licensed under BSD-3-Clause.
