# Translate a term by looking it up in the Wikipedia

## Usage

```
usage: wptr [options] term

Query Wikipedia for translations of a term.

positional arguments:
  term                  the term to translate

optional arguments:
  -h, --help            show this help message and exit
  --version             show program's version number and exit
  -l LANGUAGE, --language LANGUAGE, --from LANGUAGE
                        set language the terms are in [default: en]. You can
                        also prefix the search term with the language, e. g.,
                        ‘en:Mirror’
  -t TO, --to TO        translate to this language. Can be used more than once
                        or with a comma-separated list, e.g. --to de,fr,es
  -f {plain,console,csv,short,html,json}, --format {plain,console,csv,short,html,json}
                        format output (possible values are: plain, console,
                        csv, short, html, json)
  -q, --quiet           be quiet (short for --format=short)
  --color WHEN          colorize the output. WHEN defaults to ‘auto’ or can be
                        ‘never’ or ‘always’
  --show-query          print the SPARQL query that would be used and exit
```
