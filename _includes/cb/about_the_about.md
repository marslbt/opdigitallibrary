{% assign imagesample = site.data[site.metadata] | where_exp: 'item','item.format contains "image"' | first %}
{% capture imagesampleid %}{{imagesample.objectid | default: "https://www.lib.uidaho.edu/collectionbuilder/demo-objects/mg101_b6_photographs_01.jpg"}}{% endcapture %}

## About the About Page

This is a curation of promoted products tagged as 'Great Budol Finds' from Shopee, Lazada, and other online shops. Product affiliate links, descriptions, images, and location are provided for easy access of references for GBF Admin.

{% include feature/image.html objectid="gbh001" width="75" %}

{% include feature/button.html text="GBF Facebook Page" link="https://www.facebook.com/greatbudolfindsph/" color="success" centered=true %}
  
