# wordpress-stats-extractor

There's a, I'm guessing little known, page with visitor statistics (powered by JetPack?) on wordpress.com
at wordpress.com/stats

Unfortunately the interface is quite basic and there is no option to export all data at once.

This project is a set of instructions for a machine for perform the tedious task of selecting a date, reading out numbers from the corresponding page, clicking through cards and downloading CSV files, after which assembling the collected data. Hashtag web scraping.

# Instructions
You would need Selenium and a webdriver for chrome. Lookup the official Selenium docs.

Make a copy of the `conf_template.json` file and fill in the necessary fields.
Run the `axtract.py` script with your configuration file as an argument.

# Disclaimer
This software is provided as is without warranty of any kind. Not sure if this is against Wordpress' terms of service. Use at your own risk.

# Credits
Thanks to this post for inspiration https://paulvanderlaken.com/2019/12/29/python-web-scraping-wordpress-viewing-statistics/
