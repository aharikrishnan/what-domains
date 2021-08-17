# What domains

A naive script to get domains from stream

### Usage:

```bash
hari:~/src/what-domains⚡ ./what-domains --help

Usage: 
         ./what_domains [ --invalid-tlds ] [ --exclude-emails ]
Piped with find:
         find . -type f -exec cat '{}' \; 2> /dev/null |  ./what_domains [--tld-sort] [ --invalid-tlds ] [ --exclude-emails ]

```

