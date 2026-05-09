---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

👋I am a **PhD student  in the [MIND Team](https://team.inria.fr/mind/) at CEA / Inria**, based in Paris, and enrolled at **Université Paris-Saclay**. My PhD is supervised by **Dr. Philippe Ciuciu** and **Dr. Chaithya G. R.**, focusing on advanced methods for **functional brain MRI**.

My research centers on **deep learning for accelerated whole-brain, high-resolution functional MRI reconstruction**, with a particular emphasis on combining self-supervised learning and transfer learning with physical modeling of MRI reconstruction. My main research interests include:


- **Deep learning-based reconstruction** from undersampled medical imaging data
- **Joint optimization of non-Cartesian trajectories and physics-driven fMRI reconstruction**

<figure class="research-overview">
  <img src="/images/location-fMRI-Reconstruction.png" alt="Overview of the role of fMRI reconstruction in the imaging and analysis pipeline">
</figure>

- **Foundation models** for brain imaging
- fMRI based **brain decoding**
- Future extensions toward **non-invasive brain-computer interfaces**

I am also passionate about **open-source scientific software** and actively contribute to projects such as **[MRI-NUFFT](https://github.com/mind-inria/mri-nufft)** and **[SNAKE](https://github.com/mind-inria/snake-fmri)**. 

Before starting my PhD in France, I worked on spectral CT and low-field MRI Reconstruction at the Shenzhen Institutes of Advanced Technology (Chinese Academy of Sciences), supervised by Dr. Dong Liang and Dr. Yinsheng Li.

You can find my **[CV](/files/CV-Qiaoxin.pdf)**, my **[LinkedIn](https://www.linkedin.com/in/qiaoxin-li-37a177310/)**, and **[GitHub](https://github.com/joosenli)** here.


🧩Beyond research, I also enjoy a variety of activities that keep my life balanced and inspiring:

<section class="life-dashboard" aria-labelledby="life-dashboard-title">
  <details class="life-dashboard__egg">
    <summary>
      <h2 id="life-dashboard-title">Life Dashboard</h2>
      <span class="life-dashboard__spark" aria-hidden="true">✦</span>
    </summary>
    <p>Good ideas often flicker into view mid-run or beside a train window, then settle after a generous meal or a close conversation with nature.</p>
  </details>
  <div class="life-dashboard__grid">
    <button class="life-card life-card--button life-gallery__open" type="button" data-gallery="lens" aria-haspopup="dialog" aria-controls="life-gallery">
      <span class="life-card__icon" aria-hidden="true">📷</span>
      <span class="life-card__title">Lens</span>
      <span class="life-card__hint">light, details, quiet moments</span>
      <p>Even after ten thousand glances, I am still moved by the slow bloom of sunrise, the unhurried colors of sunset, sudden rainbows, unnoticed flowers, the sea retelling itself, the hush of deserts, and the quiet authority of snow-capped mountains.</p>
      <span class="life-card__ref">Open photo wall</span>
    </button>
    <button class="life-card life-card--button life-gallery__open" type="button" data-gallery="travel" aria-haspopup="dialog" aria-controls="life-gallery">
      <span class="life-card__icon" aria-hidden="true">🚗</span>
      <span class="life-card__title">Roads</span>
      <span class="life-card__hint">travel, trains, open air</span>
      <p>Road trips, train windows, travel, and movies help me reset perspective after dense research weeks.</p>
      <span class="life-card__ref">Open photo wall</span>
    </button>
    <button class="life-card life-card--button life-gallery__open" type="button" data-gallery="kitchen" aria-haspopup="dialog" aria-controls="life-gallery">
      <span class="life-card__icon" aria-hidden="true">🍳</span>
      <span class="life-card__title">Kitchen</span>
      <span class="life-card__hint">small experiments, big appetite</span>
      <p>I like cooking because I like eating first, and the best recipes are often the ones that bring friends to the table.</p>
      <span class="life-card__ref">Open photo wall</span>
    </button>
    <button class="life-card life-card--button life-gallery__open" type="button" data-gallery="run" aria-haspopup="dialog" aria-controls="life-gallery">
      <span class="life-card__icon" aria-hidden="true">🏃</span>
      <span class="life-card__title">Running</span>
      <span class="life-card__hint">rhythm, breath, distance</span>
      <p>Long-distance running gives me a steady rhythm and a quiet sense of vitality, from marathons to ordinary training days.</p>
      <span class="life-card__ref">Open photo wall</span>
    </button>
  </div>
</section>

<dialog class="kitchen-gallery" id="life-gallery" aria-labelledby="life-gallery-title">
  <div class="kitchen-gallery__panel">
    <header class="kitchen-gallery__header">
      <div>
        <h3 id="life-gallery-title">Photo Wall</h3>
        <p class="life-gallery__intro">A few small scenes, changing slowly.</p>
      </div>
      <button class="kitchen-gallery__close" type="button" aria-label="Close photo wall">×</button>
    </header>
    <div class="kitchen-gallery__stage">
      <div class="kitchen-gallery__photos" aria-live="polite"></div>
      <div class="life-gallery__viewer" hidden>
        <button class="life-gallery__viewer-close" type="button" aria-label="Close enlarged photo">×</button>
        <img src="" alt="">
        <div class="life-gallery__viewer-caption"></div>
      </div>
    </div>
  </div>
</dialog>

<script>
  (function () {
    const galleries = {
      run: {
        title: "Running Wall",
        intro: "Race mornings, group runs, and the rhythm of long roads.",
        altPrefix: "Running moment",
        photos: [
          { file: "/images/galleries/run/run-01.jpg", label: "Hometown Run", location: "Hometown, China" },
          { file: "/images/galleries/run/run-02.jpg", label: "Nanshan Half Marathon", location: "Nanshan, Shenzhen, China" },
          { file: "/images/galleries/run/run-03.jpg", label: "Nanshan Marathon", location: "Nanshan, Shenzhen, China" },
          { file: "/images/galleries/run/run-04.jpg", label: "Nanshan Marathon Finish", location: "Nanshan, Shenzhen, China" },
          { file: "/images/galleries/run/run-05.jpg", label: "Nanshan Marathon Day", location: "Nanshan, Shenzhen, China" },
          { file: "/images/galleries/run/run-06.jpg", label: "Running Club Visit", location: "Nankai University, Tianjin, China" },
          { file: "/images/galleries/run/run-07.jpg", label: "Running Club Outing", location: "Tianjin, China" },
          { file: "/images/galleries/run/run-08.jpg", label: "Qinhuangdao Marathon", location: "Qinhuangdao, Hebei, China" },
          { file: "/images/galleries/run/run-09.jpg", label: "Tsinghua Long Run Festival", location: "Tsinghua University, Beijing, China" },
          { file: "/images/galleries/run/run-10.jpg", label: "Qingyuan Marathon", location: "Qingyuan, Guangdong, China" },
          { file: "/images/galleries/run/run-11.jpg", label: "Shenzhen Marathon", location: "Shenzhen, China" },
          { file: "/images/galleries/run/run-12.jpg", label: "Yanqi Lake Run", location: "Yanqi Lake, Beijing, China" },
          { file: "/images/galleries/run/run-13.jpg", label: "Yanqi Lake Running Club", location: "Yanqi Lake, Beijing, China" },
          { file: "/images/galleries/run/run-14.jpg", label: "Yanqi Lake Group Run", location: "Yanqi Lake, Beijing, China" },
          { file: "/images/galleries/run/run-15.jpg", label: "Yanqi Lake Training", location: "Yanqi Lake, Beijing, China" }
        ]
      },
      kitchen: {
        title: "Kitchen Wall",
        intro: "Small experiments, big appetite, and a table that is better when shared.",
        altPrefix: "Homemade dish",
        photos: [
          { file: "/images/galleries/kitchen/kitchen-01.jpg", label: "Crispy Pan-Fried Dumplings", location: "Home Kitchen" },
          { file: "/images/galleries/kitchen/kitchen-02.jpg", label: "Big Plate Chicken", location: "Home Kitchen" },
          { file: "/images/galleries/kitchen/kitchen-03.jpg", label: "Braised Noodles with Green Beans", location: "Home Kitchen" },
          { file: "/images/galleries/kitchen/kitchen-04.jpg", label: "Tomato Potato Beef Brisket", location: "Home Kitchen" },
          { file: "/images/galleries/kitchen/kitchen-05.jpg", label: "Dry-Pot Cabbage", location: "Home Kitchen" },
          { file: "/images/galleries/kitchen/kitchen-06.jpg", label: "Braised Pork Ribs", location: "Home Kitchen" },
          { file: "/images/galleries/kitchen/kitchen-07.jpg", label: "Braised Pork Belly", location: "Home Kitchen" },
          { file: "/images/galleries/kitchen/kitchen-08.jpg", label: "Twice-Cooked Pork", location: "Home Kitchen" },
          { file: "/images/galleries/kitchen/kitchen-09.jpg", label: "Homemade Wrap", location: "Home Kitchen" },
          { file: "/images/galleries/kitchen/kitchen-10.jpg", label: "Street-Style Fried Rice", location: "Home Kitchen" },
          { file: "/images/galleries/kitchen/kitchen-11.jpg", label: "Street-Style Fried Noodles", location: "Home Kitchen" },
          { file: "/images/galleries/kitchen/kitchen-12.jpg", label: "Spicy Tomato Beef", location: "Home Kitchen" },
          { file: "/images/galleries/kitchen/kitchen-13.jpg", label: "Chili Pork Stir-Fry", location: "Home Kitchen" },
          { file: "/images/galleries/kitchen/kitchen-14.jpg", label: "Milk Egg Pancake", location: "Home Kitchen" },
          { file: "/images/galleries/kitchen/kitchen-15.jpg", label: "Tomato Noodle Soup", location: "Home Kitchen" },
          { file: "/images/galleries/kitchen/kitchen-16.jpg", label: "Celery Beef", location: "Home Kitchen" },
          { file: "/images/galleries/kitchen/kitchen-17.jpg", label: "Lava Toast", location: "Home Kitchen" },
          { file: "/images/galleries/kitchen/kitchen-18.jpg", label: "Sichuan Boiled Pork", location: "Home Kitchen" },
          { file: "/images/galleries/kitchen/kitchen-19.jpg", label: "Hot and Sour Cabbage", location: "Home Kitchen" },
          { file: "/images/galleries/kitchen/kitchen-20.jpg", label: "Stir-Fried Beef", location: "Home Kitchen" },
          { file: "/images/galleries/kitchen/kitchen-21.jpg", label: "Homemade Crispy Rice", location: "Home Kitchen" },
          { file: "/images/galleries/kitchen/kitchen-22.jpg", label: "Homemade Pan-Fried Buns", location: "Home Kitchen" }
        ]
      },
      lens: {
        title: "Lens Wall",
        intro: "Light, water, flowers, mountains, and the quiet luck of looking twice.",
        altPrefix: "Photograph",
        photos: [
          { file: "/images/galleries/lens/lens-01.jpg", label: "Alpine Ridge", location: "The Alps" },
          { file: "/images/galleries/lens/lens-02.jpg", label: "Small Alpine Chapel", location: "The Alps" },
          { file: "/images/galleries/lens/lens-03.jpg", label: "Aegean Blue", location: "Aegean Sea, Greece" },
          { file: "/images/galleries/lens/lens-04.jpg", label: "Spring Blossoms", location: "Paris, France" },
          { file: "/images/galleries/lens/lens-05.jpg", label: "Coast From Above", location: "Barcelona, Spain" },
          { file: "/images/galleries/lens/lens-06.jpg", label: "Barcelona Seafront", location: "Barcelona, Spain" },
          { file: "/images/galleries/lens/lens-07.jpg", label: "Seaside Sunset", location: "Barcelona, Spain" },
          { file: "/images/galleries/lens/lens-08.jpg", label: "White Sand Lake", location: "Baisha Lake, Xinjiang, China" },
          { file: "/images/galleries/lens/lens-09.jpg", label: "Brittany Coast", location: "Brittany, France" },
          { file: "/images/galleries/lens/lens-10.jpg", label: "Paraglider Above the Sea", location: "Brittany, France" },
          { file: "/images/galleries/lens/lens-11.jpg", label: "Brittany Sunrise", location: "Brittany, France" },
          { file: "/images/galleries/lens/lens-12.jpg", label: "Sudden Rainbow", location: "France" },
          { file: "/images/galleries/lens/lens-13.jpg", label: "Spring Flowers", location: "France" },
          { file: "/images/galleries/lens/lens-14.jpg", label: "Parc de Sceaux", location: "Sceaux, France" },
          { file: "/images/galleries/lens/lens-15.jpg", label: "Chateau de Sceaux", location: "Sceaux, France" },
          { file: "/images/galleries/lens/lens-16.jpg", label: "Emerald Lake", location: "Qinghai, China" },
          { file: "/images/galleries/lens/lens-17.jpg", label: "Huizhou Coast", location: "Huizhou, Guangdong, China" },
          { file: "/images/galleries/lens/lens-18.jpg", label: "Blue Tears", location: "Dameisha, Shenzhen, China" },
          { file: "/images/galleries/lens/lens-19.jpg", label: "Malaga Evening", location: "Malaga, Spain" },
          { file: "/images/galleries/lens/lens-20.jpg", label: "Malaga Dusk", location: "Malaga, Spain" },
          { file: "/images/galleries/lens/lens-21.jpg", label: "Malaga Beach", location: "Malaga, Spain" },
          { file: "/images/galleries/lens/lens-22.jpg", label: "Malaga Sunset", location: "Malaga, Spain" },
          { file: "/images/galleries/lens/lens-23.jpg", label: "Nuremberg Street", location: "Nuremberg, Germany" },
          { file: "/images/galleries/lens/lens-24.jpg", label: "Pink Field", location: "Nuremberg, Germany" },
          { file: "/images/galleries/lens/lens-25.jpg", label: "Rainbow Mountains", location: "Zhangye Danxia, Gansu, China" },
          { file: "/images/galleries/lens/lens-26.jpg", label: "Danxia Ridges", location: "Zhangye Danxia, Gansu, China" },
          { file: "/images/galleries/lens/lens-27.jpg", label: "Danxia Layers", location: "Zhangye Danxia, Gansu, China" },
          { file: "/images/galleries/lens/lens-28.jpg", label: "Danxia Colors", location: "Zhangye Danxia, Gansu, China" },
          { file: "/images/galleries/lens/lens-29.jpg", label: "Qilian Mountains", location: "Qilian Mountains, Qinghai/Gansu, China" },
          { file: "/images/galleries/lens/lens-30.jpg", label: "Qilian Snow Peaks", location: "Qilian Mountains, China" },
          { file: "/images/galleries/lens/lens-31.jpg", label: "Qinghai Lake", location: "Qinghai, China" },
          { file: "/images/galleries/lens/lens-32.jpg", label: "Shenzhen Light", location: "Shenzhen, China" },
          { file: "/images/galleries/lens/lens-33.jpg", label: "Shuangyue Bay Sunset", location: "Huizhou, Guangdong, China" },
          { file: "/images/galleries/lens/lens-34.jpg", label: "Autumn at Sceaux", location: "Sceaux, France" },
          { file: "/images/galleries/lens/lens-35.jpg", label: "Sceaux Autumn Walk", location: "Sceaux, France" },
          { file: "/images/galleries/lens/lens-36.jpg", label: "Sceaux Autumn Trees", location: "Sceaux, France" },
          { file: "/images/galleries/lens/lens-37.jpg", label: "Wakhan Corridor", location: "Pamir Plateau, Xinjiang, China" },
          { file: "/images/galleries/lens/lens-38.jpg", label: "Malaga Coast", location: "Malaga, Spain" },
          { file: "/images/galleries/lens/lens-39.jpg", label: "Aegean Horizon", location: "Aegean Sea, Greece" },
          { file: "/images/galleries/lens/lens-40.jpg", label: "Sunrise From the Window", location: "In Flight" },
          { file: "/images/galleries/lens/lens-41.jpg", label: "Neuschwanstein", location: "Bavaria, Germany" },
          { file: "/images/galleries/lens/lens-42.jpg", label: "Yanqi Lake", location: "Beijing, China" },
          { file: "/images/galleries/lens/lens-43.jpg", label: "Yanqi Lake Shore", location: "Beijing, China" },
          { file: "/images/galleries/lens/lens-44.jpg", label: "Yanqi Lake Evening", location: "Beijing, China" },
          { file: "/images/galleries/lens/lens-45.jpg", label: "Early Spring Flowers", location: "France" }
        ]
      },
      travel: {
        title: "Roads Wall",
        intro: "Roads, cities, coastlines, mountains, and the feeling of moving through them.",
        altPrefix: "Travel photograph",
        photos: [
          { file: "/images/galleries/travel/travel-01.jpg", label: "Barcelona", location: "Barcelona, Spain" },
          { file: "/images/galleries/travel/travel-02.jpg", label: "Barcelona Afterglow", location: "Barcelona, Spain" },
          { file: "/images/galleries/travel/travel-03.jpg", label: "White Sand Lake", location: "Baisha Lake, Xinjiang, China" },
          { file: "/images/galleries/travel/travel-04.jpg", label: "German Alps", location: "Bavaria, Germany" },
          { file: "/images/galleries/travel/travel-05.jpg", label: "Snow Mountains Near Kashgar", location: "Kashgar Prefecture, Xinjiang, China" },
          { file: "/images/galleries/travel/travel-06.jpg", label: "Horse Ride Near Kashgar", location: "Kashgar, Xinjiang, China" },
          { file: "/images/galleries/travel/travel-07.jpg", label: "Malaga", location: "Malaga, Spain" },
          { file: "/images/galleries/travel/travel-08.jpg", label: "Malaga Beach", location: "Malaga, Spain" },
          { file: "/images/galleries/travel/travel-09.jpg", label: "Malaga Sunset", location: "Malaga, Spain" },
          { file: "/images/galleries/travel/travel-10.jpg", label: "Milan Cathedral", location: "Milan, Italy" },
          { file: "/images/galleries/travel/travel-11.jpg", label: "BMW Museum", location: "Munich, Germany" },
          { file: "/images/galleries/travel/travel-12.jpg", label: "Nuremberg Church", location: "Nuremberg, Germany" },
          { file: "/images/galleries/travel/travel-13.jpg", label: "Rainbow Mountains", location: "Zhangye Danxia, Gansu, China" },
          { file: "/images/galleries/travel/travel-14.jpg", label: "Qinhuangdao Wildlife Park", location: "Qinhuangdao, Hebei, China" },
          { file: "/images/galleries/travel/travel-15.jpg", label: "Desert Highway", location: "Northwest China" },
          { file: "/images/galleries/travel/travel-16.jpg", label: "Fireworks by the Bay", location: "Shuangyue Bay, Huizhou, China" },
          { file: "/images/galleries/travel/travel-17.jpg", label: "Tashkurgan", location: "Tashkurgan, Xinjiang, China" },
          { file: "/images/galleries/travel/travel-18.jpg", label: "Snow Peak Above Tashkurgan", location: "Tashkurgan, Xinjiang, China" },
          { file: "/images/galleries/travel/travel-19.jpg", label: "Tianjin", location: "Tianjin, China" },
          { file: "/images/galleries/travel/travel-20.jpg", label: "Wakhan Corridor", location: "Pamir Plateau, Xinjiang, China" },
          { file: "/images/galleries/travel/travel-21.jpg", label: "Malaga Coast", location: "Malaga, Spain" },
          { file: "/images/galleries/travel/travel-22.jpg", label: "Neuschwanstein and the Alps", location: "Bavaria, Germany" },
          { file: "/images/galleries/travel/travel-23.jpg", label: "Acropolis of Athens", location: "Athens, Greece" },
          { file: "/images/galleries/travel/travel-24.jpg", label: "University of Chinese Academy of Sciences", location: "Yanqi Lake, Beijing, China" }
        ]
      }
    };

    const dialog = document.getElementById("life-gallery");
    if (!dialog) return;

    const title = dialog.querySelector("#life-gallery-title");
    const intro = dialog.querySelector(".life-gallery__intro");
    const wall = dialog.querySelector(".kitchen-gallery__photos");
    const viewer = dialog.querySelector(".life-gallery__viewer");
    const viewerImage = viewer.querySelector("img");
    const viewerCaption = viewer.querySelector(".life-gallery__viewer-caption");
    const viewerClose = viewer.querySelector(".life-gallery__viewer-close");
    const openButtons = document.querySelectorAll(".life-gallery__open");
    const closeButton = dialog.querySelector(".kitchen-gallery__close");
    const slotCount = 9;
    const swapMs = 2400;
    const fragmentRows = 4;
    const fragmentCols = 4;
    const assetVersion = "20260505b";
    const layouts = ["layout-a", "layout-b", "layout-c"];
    let nextPhoto = slotCount;
    let timer = null;
    let activeGallery = null;

    function photoSrc(photo) {
      return photo.file + "?v=" + assetVersion;
    }

    function shuffledPhotos(photos) {
      const copy = photos.slice();
      for (let index = copy.length - 1; index > 0; index -= 1) {
        const swapIndex = Math.floor(Math.random() * (index + 1));
        const current = copy[index];
        copy[index] = copy[swapIndex];
        copy[swapIndex] = current;
      }
      return copy;
    }

    function renderPhotos(gallery) {
      const layout = layouts[Math.floor(Math.random() * layouts.length)];
      const selectedPhotos = shuffledPhotos(gallery.photos).slice(0, slotCount);
      wall.className = "kitchen-gallery__photos " + layout;
      wall.innerHTML = selectedPhotos.map(function (photo, index) {
        return [
          '<figure class="kitchen-photo kitchen-photo--' + index + '" style="--i:' + index + '" data-paused="false" data-photo-index="' + index + '">',
          '<img src="' + photoSrc(photo) + '" alt="' + gallery.altPrefix + ': ' + photo.label + ', ' + photo.location + '" loading="lazy">',
          '<figcaption><span>' + photo.label + '</span><small>' + photo.location + '</small></figcaption>',
          '</figure>'
        ].join("");
      }).join("");
      wall.querySelectorAll(".kitchen-photo").forEach(function (slot) {
        slot.addEventListener("mouseenter", function () {
          slot.dataset.paused = "true";
        });
        slot.addEventListener("mouseleave", function () {
          slot.dataset.paused = "false";
        });
        slot.addEventListener("click", function () {
          openViewer(slot);
        });
      });
      nextPhoto = selectedPhotos.length;
      wall.querySelectorAll(".kitchen-photo").forEach(function (slot, index) {
        slot.dataset.photoIndex = String(gallery.photos.indexOf(selectedPhotos[index]));
      });
    }

    function openViewer(slot) {
      const image = slot.querySelector("img");
      const caption = slot.querySelector("figcaption");
      stopRotation();
      slot.dataset.paused = "true";
      viewerImage.src = image.src;
      viewerImage.alt = image.alt;
      viewerCaption.innerHTML = caption.innerHTML;
      viewer.hidden = false;
    }

    function closeViewer() {
      viewer.hidden = true;
      viewerImage.removeAttribute("src");
      wall.querySelectorAll(".kitchen-photo").forEach(function (slot) {
        slot.dataset.paused = "false";
      });
      if (dialog.open) startRotation();
    }

    function preloadPhoto(photo, callback) {
      const preloaded = new Image();
      preloaded.onload = function () {
        callback();
      };
      preloaded.onerror = function () {
        callback();
      };
      preloaded.src = photoSrc(photo);
    }

    function buildFragments(src) {
      const wrapper = document.createElement("div");
      wrapper.className = "kitchen-photo__shards";
      for (let row = 0; row < fragmentRows; row += 1) {
        for (let col = 0; col < fragmentCols; col += 1) {
          const tile = document.createElement("span");
          const x = fragmentCols === 1 ? 0 : (col / (fragmentCols - 1)) * 100;
          const y = fragmentRows === 1 ? 0 : (row / (fragmentRows - 1)) * 100;
          tile.className = "kitchen-photo__tile";
          tile.style.backgroundImage = 'url("' + src + '")';
          tile.style.backgroundPosition = x + "% " + y + "%";
          tile.style.animationDelay = ((row + col) * 0.035 + Math.random() * 0.08) + "s";
          wrapper.appendChild(tile);
        }
      }
      return wrapper;
    }

    function updateSlot(slot, photo, photoIndex, gallery) {
      if (slot.dataset.photoIndex === String(photoIndex)) return;
      slot.dataset.updating = "true";
      preloadPhoto(photo, function () {
        if (slot.dataset.paused === "true") {
          slot.dataset.updating = "false";
          return;
        }
        const image = slot.querySelector("img");
        const caption = slot.querySelector("figcaption");
        const nextSrc = photoSrc(photo);
        const fragments = buildFragments(nextSrc);

        slot.classList.add("is-fragmenting");
        slot.appendChild(fragments);
        window.requestAnimationFrame(function () {
          fragments.classList.add("is-visible");
        });
        window.setTimeout(function () {
          image.src = nextSrc;
          image.alt = gallery.altPrefix + ": " + photo.label + ", " + photo.location;
          caption.innerHTML = "<span>" + photo.label + "</span><small>" + photo.location + "</small>";
          slot.dataset.photoIndex = String(photoIndex);
          fragments.remove();
          slot.classList.remove("is-fragmenting");
          slot.dataset.updating = "false";
        }, 1050);
      });
    }

    function nextPhotoIndexFor(slot, gallery, reservedIndexes) {
      let attempts = 0;
      let photoIndex = nextPhoto % gallery.photos.length;
      while ((slot.dataset.photoIndex === String(photoIndex) || reservedIndexes.indexOf(String(photoIndex)) !== -1) &&
        attempts < gallery.photos.length) {
        nextPhoto += 1;
        photoIndex = nextPhoto % gallery.photos.length;
        attempts += 1;
      }
      nextPhoto += 1;
      return photoIndex;
    }

    function rotatePhotos() {
      if (!activeGallery) return;
      const slots = Array.prototype.slice.call(wall.querySelectorAll(".kitchen-photo"));
      const visibleIndexes = slots.map(function (slot) {
        return slot.dataset.photoIndex;
      });
      const available = slots.filter(function (slot) {
        return slot.dataset.paused !== "true" &&
          slot.dataset.updating !== "true" &&
          !slot.querySelector(".kitchen-photo__shards");
      });
      if (!available.length) return;
      const shuffledSlots = shuffledPhotos(available);
      const updateCount = Math.min(available.length, 3);
      const reservedIndexes = visibleIndexes.slice();
      for (let index = 0; index < updateCount; index += 1) {
        const slot = shuffledSlots[index];
        const photoIndex = nextPhotoIndexFor(slot, activeGallery, reservedIndexes);
        if (reservedIndexes.indexOf(String(photoIndex)) !== -1) continue;
        reservedIndexes.push(String(photoIndex));
        updateSlot(slot, activeGallery.photos[photoIndex], photoIndex, activeGallery);
      }
    }

    function startRotation() {
      if (timer) return;
      timer = window.setInterval(rotatePhotos, swapMs);
    }

    function stopRotation() {
      if (!timer) return;
      window.clearInterval(timer);
      timer = null;
    }

    openButtons.forEach(function (button) {
      button.addEventListener("click", function () {
        const gallery = galleries[button.dataset.gallery];
        if (!gallery) return;
        stopRotation();
        activeGallery = gallery;
        title.textContent = gallery.title;
        intro.textContent = gallery.intro;
        renderPhotos(gallery);
        if (typeof dialog.showModal === "function") {
          dialog.showModal();
        } else {
          dialog.setAttribute("open", "");
        }
        startRotation();
      });
    });

    closeButton.addEventListener("click", function () {
      dialog.close();
    });

    dialog.addEventListener("click", function (event) {
      if (event.target === dialog) dialog.close();
    });

    viewer.addEventListener("click", function (event) {
      if (event.target === viewer) closeViewer();
    });

    viewerClose.addEventListener("click", closeViewer);

    dialog.addEventListener("cancel", function (event) {
      if (!viewer.hidden) {
        event.preventDefault();
        closeViewer();
      }
    });

    dialog.addEventListener("close", function () {
      closeViewer();
      stopRotation();
    });
  }());
</script>

<section class="news-board" aria-labelledby="-news">
  <div class="news-board__title-row">
    <h1 id="-news">📣 News</h1>
    <span class="news-board__updated">Updated May 2026</span>
  </div>

  <div class="news-board__featured">
    <article class="news-card">
      <span class="news-card__tag">Upcoming</span>
      <time datetime="2026-05">2026.05</time>
      <h2>ISMRM 2026 in Cape Town</h2>
      <p>I will attend <strong>ISMRM 2026</strong> in <strong>Cape Town</strong> from <strong>May 7–19</strong>; happy to connect.</p>
      <a href="http://echo.ismrm.org/p/ISMRM2026/452-02-006">View abstract</a>
    </article>

    <article class="news-card news-card--highlight">
      <span class="news-card__tag">Paper Online</span>
      <time datetime="2026-04">2026.04</time>
      <h2>First Journal Paper Accepted by IEEE TRPMS</h2>
      <p>My Master’s research on INR for sequential-scanning dual-energy CT imaging has been accepted and is now available online.</p>
      <a href="https://ieeexplore.ieee.org/document/11505967">Read the paper</a>
    </article>

    <article class="news-card">
      <span class="news-card__tag">Workshop</span>
      <time datetime="2026-04">2026.04</time>
      <h2>NeuroHack Workshop</h2>
      <p>My application to <strong>NeuroHack</strong> was accepted; I will attend the workshop at the <strong>University of Washington, Seattle</strong> from <strong>July 12–25</strong>.</p>
      <a href="https://neurohackademy.org/">Workshop site</a>
    </article>
  </div>

  <details class="news-board__archive">
    <summary>
      <span>Earlier Updates</span>
      <span>5 items</span>
    </summary>
    <ol class="news-timeline">
      <li>
        <time datetime="2026-02">2026.02</time>
        <span>Received <strong>Educational Stipend Award</strong>, ISMRM 2026.</span>
      </li>
      <li>
        <time datetime="2026-02">2026.02</time>
        <span>Our work <strong><em>Temporal Attention-Induced Scan-Specific fMRI Reconstruction Meets Time-Varying Trajectories</em></strong> was accepted as a <strong>PowerPitch Oral</strong> at <strong>ISMRM 2026</strong>. <a href="http://echo.ismrm.org/p/ISMRM2026/452-02-006">[abstract]</a></span>
      </li>
      <li>
        <time datetime="2025-09">2025.09</time>
        <span>Joined the <strong>MIND Team at CEA / Inria</strong> as a PhD researcher.</span>
      </li>
      <li>
        <time datetime="2025-05">2025.05</time>
        <span>Presented work on improved <strong>spectral CT reconstruction</strong> at <strong>Fully3D 2025 (Oral)</strong>.</span>
      </li>
      <li>
        <time datetime="2024-05">2024.05</time>
        <span>Presented work on <strong>sequentially-scanning DECT imaging</strong> and received <strong>Best Paper Finalist (Top 2%)</strong> and <strong>Student Travel Grant</strong> at <strong>ISBI 2024</strong>.</span>
      </li>
    </ol>
  </details>
</section>

---

# 📝 Publications

### MR Imaging

**DD-INR: Dynamics-Driven Implicit Neural Representation for Accelerated Whole-Brain Functional MRI Reconstruction**  
**Qiaoxin Li**, Caini Pan, Pierre-Antoine Comby, Chaithya Giliyar Radhakrishna, Philippe Ciuciu  
*Under Review*

**Temporal Attention-Induced Scan-Specific fMRI Reconstruction Meets Time-Varying Trajectories**  
**Qiaoxin Li**, Caini Pan, Pierre-Antoine Comby, Chaithya Giliyar Radhakrishna, Philippe Ciuciu  
*ISMRM 2026 – PowerPitch Oral* [[abstract]](http://echo.ismrm.org/p/ISMRM2026/452-02-006)

---

### CT Imaging

**Sequential-Scanning Dual-Energy CT Imaging Using High Temporal Resolution Image Reconstruction and Error-Compensated Material Basis Image Generation**  
**Qiaoxin Li**, Dong Liang, Yinsheng Li  
*Fully3D 2025 – Oral*

**ACCELERATION: Sequential-scanning Dual-Energy Computed Tomography Imaging Using High Temporal Image Reconstruction and Temporal Extrapolation**  
**Qiaoxin Li**, Dong Liang, Yinsheng Li  
*ISBI 2024*  
[[paper]](https://ieeexplore.ieee.org/document/10635705)

**Sequential-Scanning Dual-Energy CT Imaging Using High Temporal Resolution Image Reconstruction and Error-Compensated Material Basis Image Generation**  
**Qiaoxin Li**, Ruifeng Chen, Peng Wang, Guotao Quan, Yanfeng Du, Dong Liang, Yinsheng Li  
*IEEE TRPMS*  
[[paper]](https://ieeexplore.ieee.org/document/11505967)

---

# 🏆 Honors and Awards

- **2026** — Educational Stipend Award, **ISMRM 2026**, Cape Town  
- **2024** — Best Paper Finalist (Top 2%), **ISBI 2024**, Athens  
- **2024** — Student Travel Grant, **ISBI 2024**, Athens  
- **2024** — Oral Academic Presentation Second Prize, **China BME Conference**, Shenzhen  
- **2021** — Second Prize, **National College Mathematics Competition**, Chinese Mathematical Society  
- **2020** — Second Place, **World Artificial Intelligence Innovation Application Competition**, Zhengzhou

---

# 🎓 Educations

**PhD in Medical Imaging**  
Université Paris-Saclay, Saclay, France  
*2025 – Present*

Thesis:  
*Deep Learning for High-Resolution 11.7 Tesla Functional Brain MRI Reconstruction*

---

**M.Eng in Computer Science**  
University of Chinese Academy of Sciences  
<!-- Shenzhen Institutes of Advanced Technology, Chinese Academy of Sciences   -->
*2022 – 2025*

Thesis:  
*High Temporal Resolution CT Imaging Using Deep Learning Methods*

---

**B.Sc. in Computational Mathematics**  
Henan University  
*2018 – 2022*

Thesis:  
*A Variational Model for Removing Concentric Ring Artifacts from CT Images*

---

<section class="connect-map" aria-labelledby="connect-map-title">
  <div class="connect-map__header">
    <h2 id="connect-map-title">Looking forward to our connection 🌍</h2>
  </div>
  <div class="connect-map__legend" aria-label="Map legend">
    <span><i class="connect-map__dot connect-map__dot--home"></i>Home / lived</span>
    <span><i class="connect-map__dot connect-map__dot--work"></i>Study / work</span>
    <span><i class="connect-map__dot connect-map__dot--visited"></i>Visited</span>
    <span><i class="connect-map__dot connect-map__dot--upcoming"></i>Upcoming visit</span>
  </div>
  <div class="connect-map__canvas" role="img" aria-label="World map showing visited and upcoming connection locations">
    <img src="/images/global_map.png" alt="Hand-drawn world map">

    <span class="connect-map__marker connect-map__marker--home" style="--x: 78.0%; --y: 37.5%;" data-label="China" data-note="born / lived"></span>
    <span class="connect-map__marker connect-map__marker--visited" style="--x: 59.6%; --y: 51.8%;" data-label="United Arab Emirates" data-note="visited"></span>
    <span class="connect-map__marker connect-map__marker--visited" style="--x: 58.8%; --y: 50.9%;" data-label="Qatar" data-note="visited"></span>
    <span class="connect-map__marker connect-map__marker--work" style="--x: 45.5%; --y: 38.4%;" data-label="France" data-note="study / work"></span>
    <span class="connect-map__marker connect-map__marker--visited" style="--x: 52.8%; --y: 42.0%;" data-label="Greece" data-note="visited"></span>
    <span class="connect-map__marker connect-map__marker--visited" style="--x: 47.2%; --y: 35.6%;" data-label="Netherlands" data-note="visited"></span>
    <span class="connect-map__marker connect-map__marker--visited" style="--x: 50.5%; --y: 36.6%;" data-label="Germany" data-note="visited"></span>
    <span class="connect-map__marker connect-map__marker--visited" style="--x: 49.0%; --y: 40.5%;" data-label="Italy" data-note="visited"></span>
    <span class="connect-map__marker connect-map__marker--visited" style="--x: 43.9%; --y: 43.1%;" data-label="Spain" data-note="visited"></span>
    <span class="connect-map__marker connect-map__marker--visited" style="--x: 51.2%; --y: 76.5%;" data-label="South Africa" data-note="visited"></span>
    <span class="connect-map__marker connect-map__marker--upcoming" style="--x: 13.2%; --y: 30.4%;" data-label="United States" data-note="upcoming visit"></span>
  </div>
</section>

<span class='anchor' id='blog'></span>

<!-- # ✏️ Blog

I occasionally write about:

- 🧠deep learning in medical imaging
- 📷 Photography
- 🍳 Cooking
- ✈️ Travel

Posts will appear here soon. -->
