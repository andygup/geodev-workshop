
# GeoDev Workshop

<br>
<br>

### Andy Gup – [@agup](https://twitter.com/agup)
### AL Laframboise – [@al_laframboise](https://twitter.com/al_laframboise)

---

# Agenda

- Goals and objectives
- Setting up your environment
- Introduce ArcGIS JS API and ArcGIS Online
- Lab 1 - Data
- Lab 2 - Design
- Lab 3 - Develop
- Wrap-up

---

## Goals and Objectives

- Learn basic patterns for using ArcGIS API for JavaScript
- Create services and webmaps in ArcGIS Online
- Consuming services and webmaps in custom JavaScript apps

---

## Setting up your environment

- Get a free developer subscription => [developers.arcgis.com](https://developers.arcgis.com)
- Sign up for [jsbin.com](https://jsbin.com) if you want to save your work
- Nice-to-have: Git and Github
- Activate a Voucher Code for 1000 credits

    * **Code:** DEN1017WK
    * **Validation time window:** 10/11 - 10/25/17
    * **Credits Expire:** 3/25/18

---

## Workshop Repo

<br><br>
[https://github.com/andygup/geodev-workshop](https://github.com/andygup/geodev-workshop)

---

## Introduction to the ArcGIS API 4.x for JavaScript

- Simplified and consistent API <!-- .element: class="fragment" data-fragment-index="1" -->
- Write apps in ES6 or TypeScript <!-- .element: class="fragment" data-fragment-index="1" -->
- Modern browser support (IE11+) <!-- .element: class="fragment" data-fragment-index="1" -->
- 3D support (No plugin required!) <!-- .element: class="fragment" data-fragment-index="1" -->
- And many more! <!-- .element: class="fragment" data-fragment-index="1" -->

---

## Where to begin?

<br>

- https://developers.arcgis.com/javascript

<br>


```
<link rel="stylesheet" href="https://js.arcgis.com/4.5/esri/css/main.css">
<script src="https://js.arcgis.com/4.5/"></script>
```
<br>
- Guide
- API Reference
- Samples!

---

## Hello World Map

<br>

```js
  const map = new Map({
    basemap: "streets"
  });

  const view = new MapView({
    container: "viewDiv",  
    map: map               
  });

```

---

## Data

---

## Design

---

## Develop

---

# Questions?
