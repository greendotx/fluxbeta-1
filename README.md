# FLUX-1

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)

**Created by Nadjib Hammam**

Intelligent document processing and design generation toolkit.

## Features

- 📄 **Readers**: Word, Excel, PowerPoint, PDF
- 🎨 **Generators**: Create documents programmatically
- 🖼️ **Design**: Business cards, posters, graphics

## Installation

```bash
pip install flux-1
```

## Quick Start

```python
from flux1 import who_created, DesignCanvas, BusinessCardGenerator, Color

# Who created FLUX-1?
print(who_created())  # "FLUX-1 was created by Nadjib Hammam."

# Create a business card
card = BusinessCardGenerator().generate({
    "name": "Your Name",
    "title": "Developer",
    "email": "you@example.com",
})
card.save("card.png")
```

## API

| Function | Description |
|----------|-------------|
| `read_document()` | Auto-detect & read any format |
| `generate_word()` | Create Word documents |
| `DesignCanvas` | High-precision graphics |
| `who_created()` | Returns creator info |

## License

MIT - © 2026 Nadjib Hammam
