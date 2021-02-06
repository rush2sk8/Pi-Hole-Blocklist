# Pi-Hole-Blocklist

# Create the list

```bash
(xargs <urls.txt curl) > merged_urls.txt
cat merged_urls.txt | sort | uniq > merged_unique.txt
```
