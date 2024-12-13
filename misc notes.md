# misc notes on best practice
so i get that there is such a thing as best practice for contributing to repos. HOWEVER, idk if it's worth doing it all for this. with that said, there are a couple of things i would like to try to stick with

## 1 - commit messages
so wrt the commit messages, i wanna stick to meaningful messages, possibly with a 'tag' at the start (similar to how i was working on the 2048 repo). i reckon categories should include:

- docs - updates to documentation. from hereon i'll also use this tag for misc notes as well (ie updates to files like this one)
- fix - bugfix / fixed broken functionality
- refactor - for refactoring / rewriting code to make better / neater / more efficient etc
- feature - added new feature

(will add more down the line if i feel the need)

## things i probably won't do but i think are worth noting

### pre-commit hooks
so this is probably quite useful actually and maybe something i'll implement later down the line, but for now, most of this project will be research anyways, so i sorta doubt it'll be that useful. worth looking into though

# random things
## gads.png
bro why are there google ads on the met office data page? and a comment saying not to delete? i'd assume it's built into one of the deployment modules / package thingies used but still? kinda mad
the website doesn't even host ads so what's it doing there? is it just for site analytics? perhaps search engine reasons?
**thought** decent chance it's built into whatever template / deployment thing they used it for and that's just where the google ads stuff would go if the website actually had ads

## arcgis.png
so source is [arcgis](https://www.arcgis.com/index.html) which in itself is a product of [esri](https://www.esri.com/en-us/arcgis/products/arcgis-online/overview). it's described as a 'SaaS for geospatial workflows' whatever that means.
quote from website is ` Improve decision-making by collecting and managing data, analyzing it, and easily sharing maps and apps within a connected and collaborative web geographic information system (GIS).`

ah so a small amount of further research does indeed show that a GIS is a thing (eg [wikipedia](https://en.wikipedia.org/wiki/Geographic_information_system)) that basically 'does stuff to' geographic data (processing + visualisation)

indeed, according to [wikipedia](https://en.wikipedia.org/wiki/Geographic_information_system), ArcGIS currently 'dominates the GIS market' although apparently AutoDesk also has a product (i mean what don't they have a ridiculously expensive product for let's be honest here)