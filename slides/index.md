
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

---

# Introduction to the ArcGIS API 4.x for JavaScript

- Simplified and consistent API <!-- .element: class="fragment" data-fragment-index="1" -->
- Write apps in ES6 or TypeScript <!-- .element: class="fragment" data-fragment-index="1" -->
- Modern browser support (IE11+) <!-- .element: class="fragment" data-fragment-index="1" -->
- 3D support (No plugin required!) <!-- .element: class="fragment" data-fragment-index="1" -->
- And many more! <!-- .element: class="fragment" data-fragment-index="1" -->

---

# Where to begin?

<br>

- https://developers.arcgis.com/javascript

<br>

```
<link rel="stylesheet" href="https://js.arcgis.com/4.4/esri/css/main.css">
<script src="https://js.arcgis.com/4.4/"></script>
```

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

# Questions

![questions](./images/questions.gif)


---
