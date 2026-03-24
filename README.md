# pdf-extractor

Layout-aware PDF text + embedded link extractor built on PyMuPDF.

## Install

```bash
pip install git+https://github.com/your-company/pdf-extractor
```

## Usage

```python
from pdf_extractor import process_one

text = process_one(Path("resume.pdf"))
print(text)
```

## License

AGPL-3.0
