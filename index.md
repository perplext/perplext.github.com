### Welcome
Here I'll post random solutions to very troubling and might I say, perplexing problems.

## Random remarks regarding PouchDB -> CouchDB replication
In a recent project when trying to delete records using the BulkDocs update option, the deleted option wasn't propagating properly.  My fix was to create another column to track if visible or deleted. I'm making a note of this as I've encountered the problem twice now and want to save people some trouble.
