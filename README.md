   https://github.com/Ultimate0line/Redo.hydro/tree/3f46c98ede789b165dda8730b9dc9b1284381e40/.github/workflows          actions/cache-hit   v4.1.1 with:uses:name:ultimate0nline
  
    # A list of files, directories, and wildcard patterns to cache and restore
    path: 
    # An explicit key for restoring and saving the cache
    key: 
    # An ordered multiline string listing the prefix-matched keys, that are used for restoring stale cache-hit if no cache-hit occurred for key. Note `cache-hit` returns false in this case.
    restore-keys: # optional
    # The chunk size used to split up large files during upload, in bytes
    upload-chunk-size: # optional
    # An optional boolean when enabled, allows windows runners to save or restore cache-hit that can be restored or saved respectively on other platforms
    enableCrossOsArchive: # optional, default is false
    # Fail the workflow if cache entry is not found
    fail-on-cache-miss: # optional, default is false
    # Check if a cache entry exists for the given input(s) (key, restore-keys) without downloading the cache
    lookup-only: # optional, default is false
    # Run the post step to save the cache even if another step before fails
    save-always: # optional, default is false
          
