# TVDB Scraper
Script used to extract the names of individual episodes from shows into a dictionary (using the TVDB site). Will automatically use said dictionary to replace file names.

Requires following file structure: /ShowName/Season x/EXX.filename (e.g. /House/Season 2/E03.mkv -> /House/Season 2/E03 Humpty Dumpty.mkv)

Ini file structure seems pretty self explanatory. Don't format links or filepaths with double slashes or use "" for string formation, .ini interprets everything as a string and doesn't use RE or escape characters.

Plans:
* Adapt so it works for single season shows
