# Pi-Hole-Blocklist

# Create the list

```bash
(xargs <urls.txt curl) | sort | uniq | sed -e 's/^[ \t]*//' |  grep -Ev '^#|^-' > pihole.txt
```
