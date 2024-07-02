# Python RSS Reader

The Python RSS Reader is a powerful and versatile tool designed to fetch and parse RSS feeds, providing users with a streamlined way to stay updated with the latest news and content from their favorite websites. This project leverages Python’s robust libraries to deliver a seamless experience in aggregating and displaying RSS feed data.

## Key Features

Fetch and Parse RSS Feeds: Utilize Python's requests and xml.etree.ElementTree libraries to fetch and parse RSS feeds from various sources.

User-Friendly Output: Display feed data, such as titles, links, publication dates, descriptions, and media content, in a clear and readable format.

Enhanced Readability: Integrate colorama to highlight important information like titles, making it easier to scan through feed items.

Namespace Handling: Properly handle namespaces to accurately extract media-specific elements and other namespaced data.

Extensibility: Easily extend the reader to include additional RSS feed sources and customize the output format to suit specific needs.


## Install 

```bash 
  git clone https://github.com/erkankavas/python-rss-reader.git
  cd python-rss-reader
  pip install requests colorama
  ```

## How to Run?

The sample code below uses rss_feed_url set to a popular Turkish news website. If you want to use a different RSS feed, please edit the rss_feed_url variable in main.py accordingly.

## Support

https://x.com/erkankavas

https://www.linkedin.com/in/erkankavas/