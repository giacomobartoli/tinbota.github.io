---
layout: page
title: 📈 Dati
permalink: /data
nav_order: 3
---

# 📈 Dati

## Grafico

{% vegalite %}
{
  "": "https://vega.github.io/schema/vega-lite/v4.json",
  "description": "A simple bar chart with embedded data.",
  "data": {
    "values": [
      {"x": "2020-02-26T11:00:00.000Z", "type": "quarantene", "y": 2}, 
      {"x": "2020-02-27T11:00:00.000Z", "type": "quarantene", "y": 2}, 
      {"x": "2020-02-28T11:00:00.000Z", "type": "quarantene", "y": 1}, 
      {"x": "2020-02-28T11:00:00.000Z", "type": "positivi", "y": 1}, 
      {"x": "2020-02-29T11:00:00.000Z", "type": "quarantene", "y": 29}, 
      {"x": "2020-02-29T11:00:00.000Z", "type": "tamponi", "y": 19}, 
      {"x": "2020-02-29T11:00:00.000Z", "type": "positivi", "y": 1},
      {"x": "2020-03-01T11:00:00.000Z", "type": "quarantene", "y": 76}, 
      {"x": "2020-03-01T11:00:00.000Z", "type": "tamponi", "y": 25}, 
      {"x": "2020-03-01T11:00:00.000Z", "type": "positivi", "y": 8}, 
      {"x": "2020-03-02T11:00:00.000Z", "type": "quarantene", "y": 80}, 
      {"x": "2020-03-02T11:00:00.000Z", "type": "tamponi", "y": 29}, 
      {"x": "2020-03-02T11:00:00.000Z", "type": "positivi", "y": 9}, 
      {"x": "2020-03-02T11:00:00.000Z", "type": "decessi", "y": 1}, 
      {"x": "2020-03-03T11:00:00.000Z", "type": "quarantene", "y": 98}, 
      {"x": "2020-03-03T11:00:00.000Z", "type": "tamponi", "y": 37}, 
      {"x": "2020-03-03T11:00:00.000Z", "type": "positivi", "y": 11}, 
      {"x": "2020-03-03T11:00:00.000Z", "type": "decessi", "y": 1}, 
      {"x": "2020-03-04T11:00:00.000Z", "type": "quarantene", "y": 97}, 
      {"x": "2020-03-04T11:00:00.000Z", "type": "tamponi", "y": 43}, 
      {"x": "2020-03-04T11:00:00.000Z", "type": "positivi", "y": 16}, 
      {"x": "2020-03-04T11:00:00.000Z", "type": "decessi", "y": 1}, 
      {"x": "2020-03-05T11:00:00.000Z", "type": "quarantene", "y": 116}, 
      {"x": "2020-03-05T11:00:00.000Z", "type": "tamponi", "y": 46}, 
      {"x": "2020-03-05T11:00:00.000Z", "type": "positivi", "y": 22}, 
      {"x": "2020-03-05T11:00:00.000Z", "type": "decessi", "y": 1}, 
      {"x": "2020-03-06T11:00:00.000Z", "type": "quarantene", "y": 130}, 
      {"x": "2020-03-06T11:00:00.000Z", "type": "tamponi", "y": 50}, 
      {"x": "2020-03-06T11:00:00.000Z", "type": "positivi", "y": 24}, 
      {"x": "2020-03-06T11:00:00.000Z", "type": "decessi", "y": 1}, 
      {"x": "2020-03-07T11:00:00.000Z", "type": "quarantene", "y": 137}, 
      {"x": "2020-03-07T11:00:00.000Z", "type": "tamponi", "y": 57}, 
      {"x": "2020-03-07T11:00:00.000Z", "type": "positivi", "y": 27}, 
      {"x": "2020-03-07T11:00:00.000Z", "type": "decessi", "y": 1}, 
      {"x": "2020-03-08T11:00:00.000Z", "type": "quarantene", "y": 121}, 
      {"x": "2020-03-08T11:00:00.000Z", "type": "tamponi", "y": 77}, 
      {"x": "2020-03-08T11:00:00.000Z", "type": "positivi", "y": 37}, 
      {"x": "2020-03-08T11:00:00.000Z", "type": "decessi", "y": 1}, 
      {"x": "2020-03-09T11:00:00.000Z", "type": "quarantene", "y": 164}, 
      {"x": "2020-03-09T11:00:00.000Z", "type": "tamponi", "y": 92}, 
      {"x": "2020-03-09T11:00:00.000Z", "type": "positivi", "y": 51}, 
      {"x": "2020-03-09T11:00:00.000Z", "type": "decessi", "y": 2}, 
      {"x": "2020-03-10T11:00:00.000Z", "type": "quarantene", "y": 176}, 
      {"x": "2020-03-10T11:00:00.000Z", "type": "tamponi", "y": 111}, 
      {"x": "2020-03-10T11:00:00.000Z", "type": "positivi", "y": 62}, 
      {"x": "2020-03-10T11:00:00.000Z", "type": "decessi", "y": 2}
    ]
  },
  "mark": "line",
  "encoding": {
    "x": {"field": "x", "type": "temporal"},
    "y": {
        "field": "y", 
        "type": "quantitative",
        "stack": false
    },
    "color": {
      "field": "type",
      "type": "nominal",
      "scale": {"scheme": "category20"}
    }
  },
  "width": 600,
  "height": 400
}
{% endvegalite %}

## Comunicati Gruppo Emergenza ISS