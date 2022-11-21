{% assign imagesample = site.data[site.metadata] | where_exp: 'item','item.format contains "image"' | first %} {% capture imagesampleid %}{{imagesample.objectid | default: "https://www.lib.uidaho.edu/collectionbuilder/demo-objects/mg101_b6_photographs_01.jpg"}}{% endcapture %} {% assign pdfsample = site.data[site.metadata] | where_exp: 'item','item.format contains "pdf"' | first %} {% capture pdfsampleid %}{{pdfsample.objectid | default: "https://digital.lib.uidaho.edu/utils/getfile/collection/ui_ep/id/21768/filename/uiext21768.pdf"}}{% endcapture %} {% assign videosample = site.data[site.metadata] | where_exp: 'item','item.format contains "video"' | first %} {% capture videosampleid %}{{videosample.objectid | default: "https://cdil.lib.uidaho.edu/storying-extinction/objects/trailcams/videos/ballcreek-cedarrub-birdonpath.mp4"}}{% endcapture %} {% assign audiosample = site.data[site.metadata] | where_exp: 'item','item.format contains "audio"' | first %} {% capture audiosampleid %}{{audiosample.objectid | default: "https://www.lib.uidaho.edu/digital/mp3s/Clouds.mp3"}}{% endcapture %}

## About the About Page

This is a curation of promoted products tagged as 'Great Budol Finds' from Shopee, Lazada, and other online shops. Product affiliate links, descriptions, images, and location are provided for easy access of references for GBF Admin.

{% include feature/image.html objectid="gbf001" width="75" %}

{% include feature/button.html text="GBF Facebook Page" link="https://www.facebook.com/greatbudolfindsph/" color="success" centered=true %}
  
