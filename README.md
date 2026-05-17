[README.txt](https://github.com/user-attachments/files/27902090/README.txt)
CAMPVANAA — IMAGE SETUP GUIDE
==============================

Your folder structure must look like this:

campvanaa/
├── index.html
├── hero.mp4
└── images/
    ├── belief.jpg
    ├── bleed.jpg
    ├── exp1.jpg
    ├── exp2.jpg
    ├── exp3.jpg
    ├── exp4.jpg
    ├── exp5.jpg
    ├── exp6.jpg
    ├── loc1.jpg
    ├── loc2.jpg
    ├── strip1.jpg
    ├── strip2.jpg
    ├── strip3.jpg
    ├── strip4.jpg
    ├── strip5.jpg
    ├── strip6.jpg
    └── strip7.jpg


STEP 1 — Download these free images from Unsplash
===================================================
Go to each link, click the free Download button, rename and save:

belief.jpg   → https://unsplash.com/photos/green-trees-on-mountain-during-foggy-day-1448375240586
bleed.jpg    → https://unsplash.com/photos/green-forest-426604966848
exp1.jpg     → https://unsplash.com/photos/tent-camping-night-stars-1504280390367   (Canvas & Stars)
exp2.jpg     → https://unsplash.com/photos/bonfire-night-1551632811                (Fire & Fellowship)
exp3.jpg     → https://unsplash.com/photos/forest-trail-morning-1441974231531      (Into the Green)
exp4.jpg     → https://unsplash.com/photos/yoga-outdoor-sunrise-1506126613408      (Yoga)
exp5.jpg     → https://unsplash.com/photos/milky-way-stars-night-1475924156734     (Star Gazing)
exp6.jpg     → https://unsplash.com/photos/campfire-cooking-outdoor-1471513671800  (Cook Under Sky)
loc1.jpg     → https://unsplash.com/photos/green-hills-india-1596782074697         (Nandi Hills)
loc2.jpg     → https://unsplash.com/photos/forest-karnataka-1508193638397          (Bannerghatta)
strip1.jpg   → https://unsplash.com/photos/tent-camping-1504280390367
strip2.jpg   → https://unsplash.com/photos/aerial-forest-1501854140801
strip3.jpg   → https://unsplash.com/photos/forest-path-1441974231531
strip4.jpg   → https://unsplash.com/photos/friends-campfire-1519331379826
strip5.jpg   → https://unsplash.com/photos/misty-mountain-1472214103451
strip6.jpg   → https://unsplash.com/photos/hammock-forest-1500534314209
strip7.jpg   → https://unsplash.com/photos/starry-night-camp-1532339142463

OR use simpler Unsplash shortlinks:
https://unsplash.com/photos/{PHOTO-ID}
Just search on unsplash.com for: "camping tent night", "campfire", "forest trail", etc.
Download any good photo, rename it, and put it in the images/ folder.


STEP 2 — Create the images folder
===================================
On your computer:
1. Create a folder called "images" 
2. Put all 17 downloaded photos inside it
3. Make sure the folder is next to your index.html file


STEP 3 — Deploy to Vercel
===========================
1. Go to vercel.com → New Project
2. Select "Deploy without a framework"
3. Drag the ENTIRE campvanaa/ folder (containing index.html, hero.mp4, and images/ folder)
4. Done — all images will load perfectly!

NOTE: When deploying, always upload the WHOLE FOLDER, not individual files.
This ensures the images/ subfolder is included.
