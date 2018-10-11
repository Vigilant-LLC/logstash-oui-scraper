# logstash-oui-scraper
ls-oui-scraper is used to download oui data from standards-oui.ieee.org

usage: ls-oui-scraper -d /tmp

This tool will create two files:
oui-raw.txt = original downloaded file
oui-logstash.txt = formatted oui data file to be used with the logstash-filter-ieee_oui plugin
