---
layout: page
title: Beyond Research
permalink: /beyond_research/
nav: true
nav_order: 4
---

> **"Life outside the office keeps my intuition fresh and my energy high. Here is a glimpse into my community initiatives, travel footprints, and creative passions."**

---

### 👭 Community & Impact

#### She Shapes AI — Female Tech Community & Hackathon
* **Role:** She Shapes AI Fellow *(Aug. 2026 – Present)*
* **Focus:** Transitioning from an AI user to an AI builder alongside an inspiring community of female peers.
* **Project:** Collaborating with a multidisciplinary team to design and prototype an AI product demo, promoting female representation and empowerment in technology.
* **Event Recap:** [Read Icebreaking Event Highlights (Chinese)](https://mp.weixin.qq.com/s/OL5yBSqpUCZPnQ0NCSyaRQ)

---

### 🗺️ Travel Footprints

> *"Fieldwork broadens the empirical scope; travel expands the human horizon."*

I love exploring different cultures, landscapes, and social contexts. To date, my journey spans **4 countries** and **24+ provinces/regions** across China.

* **🌏 International:** Japan, Malaysia, South Korea, Thailand
* **🇨🇳 Domestic Footprints:** Beijing, Chongqing, Fujian, Guangdong, Guangxi, Guizhou, Hainan, Hebei, Heilongjiang, Hong Kong SAR, Hubei, Hunan, Inner Mongolia, Jiangxi, Jilin, Macao SAR, Qinghai, Shaanxi, Shandong, Shanghai, Tianjin, Xinjiang, Yunnan, Zhejiang

<!-- 动态地图依赖库 -->
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" />
<script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"></script>

<!-- 地图容器 -->
<div id="travel-map" style="height: 420px; width: 100%; margin-top: 15px; margin-bottom: 25px; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1); position: relative; z-index: 1;"></div>

<script>
  document.addEventListener("DOMContentLoaded", function() {
    // 初始化地图视野 (以中国及东亚为中心)
    var map = L.map('travel-map').setView([33.0, 108.0], 4);

    // 加载极简优雅的浅色底图
    L.tileLayer('https://{s}.basemaps.cartocdn.com/light_all/{z}/{x}/{y}{r}.png', {
      attribution: '&copy; OpenStreetMap &copy; CARTO',
      maxZoom: 18
    }).addTo(map);

    // 1. 国际足迹 (4个国家 - 蓝色标记点)
    var internationalSpots = [
      { name: "Japan (日本)", coords: [35.6762, 139.6503] },
      { name: "Malaysia (马来西亚)", coords: [3.1390, 101.6869] },
      { name: "South Korea (韩国)", coords: [37.5665, 126.9780] },
      { name: "Thailand (泰国)", coords: [13.7563, 100.5018] }
    ];

    internationalSpots.forEach(function(spot) {
      L.marker(spot.coords).addTo(map)
        .bindPopup('<b>🌏 ' + spot.name + '</b>');
    });

    // 2. 国内足迹 (全量 24 个省/直辖市/特别行政区 - 紫色圆点标记)
    var domesticSpots = [
      { name: "Beijing (北京)", coords: [39.9042, 116.4074] },
      { name: "Tianjin (天津)", coords: [39.0842, 117.2009] },
      { name: "Shanghai (上海)", coords: [31.2304, 121.4737] },
      { name: "Chongqing (重庆)", coords: [29.5630, 106.5516] },
      { name: "Hong Kong SAR (香港)", coords: [22.3193, 114.1694] },
      { name: "Macao SAR (澳门)", coords: [22.1987, 113.5439] },
      { name: "Xinjiang (新疆)", coords: [43.8256, 87.6168] },
      { name: "Qinghai (青海)", coords: [36.6232, 101.7782] },
      { name: "Inner Mongolia (内蒙古)", coords: [40.8426, 111.7492] },
      { name: "Heilongjiang (黑龙江)", coords: [45.8038, 126.5350] },
      { name: "Jilin (吉林)", coords: [43.8171, 125.3235] },
      { name: "Hebei (河北)", coords: [38.0428, 114.5149] },
      { name: "Shaanxi (陕西)", coords: [34.3416, 108.9398] },
      { name: "Shandong (山东)", coords: [36.6512, 117.1201] },
      { name: "Yunnan (云南)", coords: [25.0406, 102.7123] },
      { name: "Guizhou (贵州)", coords: [26.6470, 106.6302] },
      { name: "Hunan (湖南)", coords: [28.2282, 112.9388] },
      { name: "Hubei (湖北)", coords: [30.5928, 114.3055] },
      { name: "Jiangxi (江西)", coords: [28.6820, 115.8579] },
      { name: "Fujian (福建)", coords: [26.0745, 119.2965] },
      { name: "Zhejiang (浙江)", coords: [30.2741, 120.1551] },
      { name: "Guangxi (广西)", coords: [22.8170, 108.3665] },
      { name: "Guangdong (广东)", coords: [23.1291, 113.2644] },
      { name: "Hainan (海南)", coords: [20.0440, 110.3297] }
    ];

    domesticSpots.forEach(function(spot) {
      L.circleMarker(spot.coords, {
        color: '#8a2be2',
        fillColor: '#8a2be2',
        fillOpacity: 0.7,
        radius: 6
      }).addTo(map).bindPopup('<b>🇨🇳 ' + spot.name + '</b>');
    });
  });
</script>

---

### 🎸 Personal Interests & Vibe

#### 🎵 Rhythm, Beats & Sound
* **Music Enthusiast:** Heavy listener of Rock and Rap; thriving in the raw energy of Livehouses and outdoor music festivals.
* **Active Creator:** Play a bit of drums, dance Jazz, and occasionally try my hand at rapping.

#### 🎿 Outdoor & Sports
* **Active Lifestyle:** Passionate about carving down snowy mountains (Skiing), mountain Hiking, and playing Badminton to recharge and stay energized.

#### 📷 Visuals & Aesthetics
* **Art & Photography:** Avid visitor of art exhibitions; enthusiastic photography lover capturing everyday moments, architectural geometries, and structural details during field trips and travels.

<!-- Vibe / Interests Photo Gallery -->
<div class="row mt-3">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/life/life_1.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/life/life_2.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/life/life_3.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row mt-3">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/life/life_4.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/life/life_5.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/life/life_6.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
