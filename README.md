IIIF APIs in ContentDM Demos
=============

Most of these demos require JQuery. The code is using Google's [hosted JQuery and JQuery UI libraries](https://developers.google.com/speed/libraries/).
Some of the demos use a Javascript library called [blueimp Gallery](https://blueimp.github.io/Gallery/)

The manifests in the demo are created based on 
- [The National Gallery of Art Collection Highlights manifest](https://media.nga.gov/public/manifests/nga_highlights.json)
- [Harvard Museum SElf Portrait Dedicated to Paul Gauguin manifest](https://iiif.harvardartmuseums.org/manifests/object/299843)

## Resources
[CONTENTdm Documentation on IIIF APIs](https://www.oclc.org/support/services/contentdm/help/customizing-website-help/other-customizations/iiif-api-support.en.html)

[IIIF Image API](http://iiif.io/api/image/2.1/) 
[IIIF Presentation API](http://iiif.io/api/presentation/2.1/) 

### Examples API Calls

#### Image API
[Get Image - Resized 25%](https://sandbox.contentdm.oclc.org/digital/iiif/coll16/357/full/pct:25/0/default.jpg)
[Get Info](https://sandbox.contentdm.oclc.org/digital/iiif/coll16/357/info.json)

#### Presentation API
[Manifest Single Object](https://sandbox.contentdm.oclc.org/digital/iiif-info/coll16/357)

[Manifest Compound Object](https://sandbox.contentdm.oclc.org/digital/iiif-info/p10010coll1/42)

[Manifest for a Self Created Collection](https://github.com/OCLC-Developer-Network/iiif_demos/blob/master/kac_cmd_highlights.json)
