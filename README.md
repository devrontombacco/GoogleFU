# GoogleFU

## How to google better


### Exact Match 
When you search an error message on google, wrap it in quotes. This tells google to search for an exact match. Otherwise it'll just look for synonyms and related terms.

### Specific Site 
If you want google to show results from a specific site use: `site:YourSiteHere` followed by the search term
e.g. `site:stackoverflow.com yourSearchTermHere`

### Exclude result
You can exclude stuff from the results by using the minus sign:
e.g. Don't return results using jquery: `how to grab an element from the dom -jquery`

### Don't get information from obsolete sources
To ensure you don't get information from obsolete sources, use the "after" keyword: 'tableViews after:2020'

### Don't get information from new sources
This is handy when maintaining a legacy project: 
'yourSearchTermHere before:2020'

### Seach range of dates, numbers etc. 
Simply use two dots:
- `2015..2020 `
- `$10..$20`
- `#..#`
- 
e.g.
- `angular 2 announement 2013..2015`

### Search for A OR B
Use the pipe operator "|"
- `(A|B)`

You can even add a third thing like so:
`(A|B)C `

### Wilcard operator
You also have the wildcard option (an asterisk) which stands for "ALL".
e.g.
`How to build * with css`

### Find subdomains of a website: 
In the example below you can find all the subdomains of a website:
`site:*fireship.io -www`

### Specific Filetype
You may also want a specific filetype:
`filetype:pdf`

### Find competitor websites
Find competitor websites to the one you are looking at:
`related:url `
`related:angular.io `


### Has google cached the latest version of your website?
`cache:url`
cache:yourWebsiteHere.com`(you will see your website the way google sees it)
