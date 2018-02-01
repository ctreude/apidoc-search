# Where does Google find API documentation?
## Online Appendix

The documentation of popular APIs is spread across many formats, from vendor-curated reference documentation to Stack Overflow threads. For developers, it is often not obvious from where a particular piece of information can be retrieved. To understand this documentation landscape, we systematically conducted Google searches for the elements of [ten popular APIs](https://github.com/ctreude/apidoc-search/blob/master/projects.csv). 

All raw data as well as aggregated data are available in this online appendix. The [data directory](https://github.com/ctreude/apidoc-search/tree/master/data) contains one directory per API, with five files each: `input.txt` lists all API elements along with the source URL; `recent-input.txt` lists all API elements used as recent elements; `raw.csv` contains, for each API element, all links returned by Google on the first page of search results, along with their domain and rank; `aggregate.csv` aggregates this data by domain and shows coverage (absolute and relative) and median rank for each domain; and `recent-aggregate.csv` shows the same data for recent API elements only.

The paper describing the details of data collection and analysis is available [here (preprint)](https://cs.adelaide.edu.au/~christoph/apidoc_search.pdf).

We encourage other researchers to use this data to study API documentation returned by Google searches.
