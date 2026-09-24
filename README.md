# gearon-catalog

The published `catalog.json` for the Gearon app. The app checks
`https://ekkhogroup-cloud.github.io/gearon-catalog/catalog.json` once per launch,
fully validates a newer version, and uses it from the next launch.

**The current catalog is fictional sample data** (brands like "Trailwright" and
"Northfold" do not exist). Real scraped product data will only be published here
after each source site's terms have been reviewed.

To publish a new catalog: replace `catalog.json` with the catalog pipeline's
`data/catalog.json`, making sure its `version` is higher than the one here.
