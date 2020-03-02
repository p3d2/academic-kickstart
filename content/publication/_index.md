---
title: Publications

# View.
#   1 = List
#   2 = Compact
#   3 = Card
#   4 = Citation
view: 4

# Optional header image (relative to `static/img/` folder).
header:
  caption: ""
  image: ""
---
ol.count-backwards
{
    list-style-type:none;
}
ol.count-backwards > li
{
    counter-increment:start-from -1;
}
ol.count-backwards > li:before
{
    content:counter(start-from) ". ";
}

* html ol.count-backwards { list-style-type:decimal; }
*+html ol.count-backwards { list-style-type:decimal; }
