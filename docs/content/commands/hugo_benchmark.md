---
date: 2017-04-26T22:40:07+02:00
title: "hugo benchmark"
slug: hugo_benchmark
url: /commands/hugo_benchmark/
---
## hugo benchmark

Benchmark Hugo by building a site a number of times.

### Synopsis


Hugo can build a site many times over and analyze the running process
creating a benchmark.

```
hugo benchmark
```

### Options

```
  -b, --baseURL string             hostname (and path) to the root, e.g. http://spf13.com/
  -D, --buildDrafts                include content marked as draft
  -E, --buildExpired               include expired content
  -F, --buildFuture                include content with publishdate in the future
      --cacheDir string            filesystem path to cache directory. Defaults: $TMPDIR/hugo_cache/
      --canonifyURLs               if true, all relative URLs will be canonicalized using baseURL
      --cleanDestinationDir        remove files from destination not found in static directories
  -c, --contentDir string          filesystem path to content directory
  -n, --count int                  number of times to build the site (default 13)
      --cpuprofile string          path/filename for the CPU profile file
  -d, --destination string         filesystem path to write files to
      --disable404                 do not render 404 page
      --disableKinds stringSlice   disable different kind of pages (home, RSS etc.)
      --disableRSS                 do not build RSS files
      --disableSitemap             do not build Sitemap file
      --enableGitInfo              add Git revision, date and author info to the pages
      --forceSyncStatic            copy all files when static is changed.
      --i18n-warnings              print missing translations
      --ignoreCache                ignores the cache directory
  -l, --layoutDir string           filesystem path to layout directory
      --memprofile string          path/filename for the memory profile file
      --noChmod                    don't sync permission mode of files
      --noTimes                    don't sync modification time of files
      --pluralizeListTitles        pluralize titles in lists using inflect (default true)
      --preserveTaxonomyNames      preserve taxonomy names as written ("Gérard Depardieu" vs "gerard-depardieu")
      --renderToMemory             render to memory (only useful for benchmark testing)
  -s, --source string              filesystem path to read files relative from
      --stepAnalysis               display memory and timing of different steps of the program
  -t, --theme string               theme to use (located in /themes/THEMENAME/)
      --themesDir string           filesystem path to themes directory
      --uglyURLs                   if true, use /filename.html instead of /filename/
```

### Options inherited from parent commands

```
      --config string    config file (default is path/config.yaml|json|toml)
      --log              enable Logging
      --logFile string   log File path (if set, logging enabled automatically)
      --quiet            build in quiet mode
  -v, --verbose          verbose output
      --verboseLog       verbose logging
```

### SEE ALSO
* [hugo](/commands/hugo/)	 - hugo builds your site

###### Auto generated by spf13/cobra on 26-Apr-2017