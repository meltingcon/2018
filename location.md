---
layout: page
title: "위치 안내"
icon: <i class="fas fa-map"></i><i class="fas fa-map-marker-alt"></i>
permalink: /location/
---
- {{ site.location }}
  - {{ site.address }}

## 대중교통 안내
- 지하철
  - 5호선 광화문역 2번출구
  - 3호선 안국역 6번출구
  - 1호선 종각역 2번출구

## 안내사항
  - 주차지원을 따로 제공하지 않는 행사입니다. 되도록 대중교통을 이용해 주시기 바랍니다.


<iframe
  width="100%"
  height="450"
  frameborder="0" style="border:0"
  src="https://www.google.com/maps/embed/v1/place?key={{site.gmaps_embed_api_key}}
  &q={{site.location_query}}" allowfullscreen>
</iframe>
