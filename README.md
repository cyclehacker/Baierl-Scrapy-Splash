# Skeleton baierl.com car crawler

Built with Python 3.6.9, Scrapy 1.8.0 and scrapy-splash 0.7.2.

Uses scrapy-splash to click "year" and "Make" dropdowns and select specific options.

Gathers resulting car urls and crawls through each item extracting car:

- Name
- Price
- Colour

Dump to .csv, .json, .xml with scrapy -o argument:

scrapy crawl car_spider -o output.json

Update lua scripts to select alternative dropdowns and options

