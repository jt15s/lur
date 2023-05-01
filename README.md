# lur
The wayfinding for the Lumea Unified Railways, a player-owned and operated railway network on Harlon City Server's Lumea Isles.

This signage uses the [Harlon Integrated Wayfinding System (HIWS)](https://github.com/HarlonServer/HIWS) with modifications.

### Naming scheme
Like the HIWS, the LUR's wayfinding system uses a code system to denote signs. The LUR is a single-mode railway network which is classified as metro, so filenames won't specify the mode of transport. 
* For **general** signage (i.e., informational, regulatory, warning, or promotional signage/graphics), the format is `XX-filename` - `XX` being the operator's abbreviated name/code - in the LURs's case, `LUR` for Lumea Unified Railways and `filename` being a good description of what the file is, for example, a "No Entry" sign could have the filename  `no-entry`.
* For **station-specific** signage, the format is `XX-YY-filename-Z` - `XX` again being 'LUR' for Lumea Unified Railways, `YY` being the station code (please see below for the list) and `filename` being the purpose of the signage. Usually this will be `entrance`, for station entrance signage.
* For **platform-specific** signage within stations, the format is `XX-YY-PlatformLineDirection`. `XX` and `YY` are the same as above, `Platform` is simply to denote that this is a platform-specific sign, `Line` is the line number the diagram is made for, for example, `LumeaEast`, and `Direction` is a geographical direction to denote the direction of travel along the line the diagram is showing, i.e., `East`. `Line` and `Direction` are optional if the signage is just general platform signage, such as the station name signs used on station platforms.

### Station codes
The list of station codes is as follows:
- **stk** Stonewall -K.
- **eha** Easthaven
- **oyn** Oyrdensai 
- **pyb** Pykke Beach
- **pab** Pure Azz Beach
- **crv** Caravas
- **bci** BTV City
- **stc** St. Tiffany's Cross
- **cwr** Lumea Central West Railway Station (referred to on signage as "Lumea Central West")
