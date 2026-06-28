# favicon-generator

A tiny Bash utility for generating a complete favicon set from a single image using ImageMagick.

## Requirements

- Bash
- ImageMagick (`convert`)

## Installation

```bash
git clone https://github.com/<your-username>/favicon-generator.git
cd favicon-generator
chmod +x generate_favicons.sh

mkdir -p ~/.bin
cp generate_favicons.sh ~/.bin/favicon-generator
```

Ensure `~/.bin` is on your `PATH`.

## Usage

```bash
favicon-generator <input-image> <output-directory>
```

Example:

```bash
favicon-generator logo.png ./favicons
```

## License

MIT