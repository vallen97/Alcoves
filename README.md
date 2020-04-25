# New Mexico Museum of Art
Alcove Shows website/in-gallery kiosk


## *notes

One layout design (html) but different color palletes and fonts (css) for each set of Alcove Shows (by year) - bootstrap

Use modal popup or lightbox (originally fancybox - http://fancyapps.com/fancybox/3/) for images in gallery

filter image data by artist - list.js or similar

use of template engine to auto populate templates - handlebars.js or similar (or look into reactjs or vuejs without node)

Organize data for Alcoves (CSV is ideal for the museum, but XML is fine). Program will need to convert data to json - see jquery-xml2json or papaparse.js

Server space is Apache. Best not to use Node/NPM so IT doesn't have to do anything extra on the server.

All libraries should be local (libs folder), not a CDN link. This will allow the museum to run the site offline in the gallery.

Only need to use Node/NPM for Electron. This will allow the museum to run the site as a locked-down kiosk in the gallery.
