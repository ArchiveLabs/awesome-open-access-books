# Awesome Open Access Books [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A collection of awesome open access book producers online

## Contributing

The resource should be a **direct** URL to a listing of at least 10 open access books. It should not be a landing page, but rather  [OpenStax](https://openstax.org/subjects) is a great example. Please submit a pull request to suggest a new portal of open access books.

## Open Access Textbooks

* [OpenStax](https://openstax.org/subjects)
  * List of all books: `curl -s https://openstax.org/sitemap.xml | grep -o 'https://openstax.org/details/books/[^<]*'`
* [UMN Open Textbook Library](https://open.umn.edu/opentextbooks)
* [BCcampus Open Textbooks](https://collection.bccampus.ca/search/)
* [MIT Press Open Access Books](https://direct.mit.edu/books/search-results?fl_SiteID=5&f_ContentType=Book&access_openaccess=true)
* [LibreTexts](https://libretexts.org/Libraries)
* [Milne Open Textbooks (SUNY)](https://milneopentextbooks.org)
* [OER Commons – Open Textbooks Hub](https://oercommons.org/hubs/open-textbooks)
* [CORE Econ Textbooks](https://www.core-econ.org)
* [MERLOT Free Online Textbooks](https://www.merlot.org/merlot/materials.htm?fromAdvancedSearch=true&keywords=&categoryBasic=&materialType=15&_audience=on&_audience=on&_audience=on&_audience=on&_audience=on&_audience=on&_audience=on&_audience=on&_audience=on&_hasPeerReviews=on&_selectedForReview=on&_hasExternalReview=on&_hasComments=on&_hasRatings=on&_hasAssignments=on&_hasCollections=on&_hasCourses=on&_hasSercActivitySheets=on&_hasAwards=on&_isContentBuilder=on&_hasEtextReviews=on&_hasAccessibilityForm=on&_technicalFormat=on&_technicalFormat=on&_technicalFormat=on&_technicalFormat=on&_technicalFormat=on&_technicalFormat=on&_technicalFormat=on&_technicalFormat=on&_technicalFormat=on&_technicalFormat=on&_technicalFormat=on&_technicalFormat=on&_technicalFormat=on&_technicalFormat=on&_technicalFormat=on&_mobile=on&_mobile=on&_mobile=on&_mobile=on&msi=0&msiSubmitter=0&ccOrZero=&cost=&codeAvailable=&language=&cefr=&dateRange=0&days=7&createdSince=&createdBefore=&sort.property=overallRating)
* [Cambridge Core](https://www.cambridge.org/core/publications/open-access/listing?aggs[productTypes][filters]=BOOK&sort=canonical.date:desc)
* [Wikibooks](https://wikibooks.org/) -- structured as web pages
* [National Academies](https://nap.nationalacademies.org/collection/) -- has multiple collections, not a single portal

## Open Access Children's Books

* [BookDash.org](https://bookdash.org/books) beautiful open access children's books for all
  * List all books: `curl -s https://bookdash.org/books-sitemap.xml | grep -o 'https://bookdash.org/books/[^<]*'`
  * [Not yet in Open Library](https://github.com/internetarchive/openlibrary/issues/10856#issue-3094159822)
 
## Other Open Access Web Books

* https://github.com/learn-anything/books also has a subset of presumably open access books that can be extracted via:
  * `curl -s https://raw.githubusercontent.com/learn-anything/books/refs/heads/master/readme.md | grep -Ei '\.pdf|\.html|\.epub'`

