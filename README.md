# Crawl-Manga

A simple script to download chapters of a manga from [NetTruyenViet](https://nettruyenviet.com).

## Requirements

- **Python**: 3.9+
- **Packages**:
  - [`requests`](https://pypi.org/project/requests/)
  - [`beautifulsoup4`](https://pypi.org/project/beautifulsoup4/)

Install the packages using:

```bash
pip install requests beautifulsoup4
```

## Usage

1. Open `main.py` and set the `url` variable to the manga page you want to download.
2. Run the script:

```bash
python main.py
```

The images for each chapter will be saved under the `E:/Data Manga/<manga-name>/` directory.
