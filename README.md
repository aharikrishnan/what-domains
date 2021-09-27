# What domains

A naive script to get domains from stream

### Usage:

```bash
hari:~/src/what-domains⚡ ./what-domains --help

Usage: 
  ./what-domains [ --invalid-tlds ] [ --exclude-emails ]

Piped with find:
  find . -type f -not -path '*/\.*' -exec grep -Il '.' {} \; 2> /dev/null | xargs -L 1 cat  2> /dev/null |  ./what-domains [--tld-sort] [ --invalid-tlds ] [ --exclude-emails ]

```

