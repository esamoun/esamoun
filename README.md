## Eithan Samoun

Earth Observation & Geomatics, MSc student in Strasbourg. Remote sensing, deep learning
and geospatial data engineering.

**Looking for a 6-month internship, March to September 2027**, in Earth observation or
geospatial AI.

### Dark vessel detection

Detecting undeclared vessels with deep learning on Sentinel-1 SAR, fused with AIS over
Danish waters. 189 detections over 50 acquisitions of the northern Kattegat, 40 of them
undeclared. Supervised object detection and self-supervised embeddings on radar,
full-scene georeferenced inference, spatio-temporal fusion with declared positions, and a
spatial analysis of where undeclared traffic concentrates.

[The code](https://github.com/esamoun/dark-vessel-detection) ·
[the detections on a map](https://esamoun.github.io/dark-vessel-detection/)

### Satellite image registration

Aligning two Sentinel-2 images to a fraction of a pixel, classic methods against deep
learning. Displacements simulated on real imagery give an exact ground truth, and twelve
methods are compared on accuracy and on compute cost. RAFT fine-tuned on this data and
evaluated once on two landscapes it never saw: 0.069 px against 0.095 px for the
pretrained model, and no pair failed. A command that registers a pair of your own, int8
ONNX models, and a container image.

[The code](https://github.com/esamoun/ai-satellite-image-registration) ·
[the demo](https://esamoun.github.io/ai-satellite-image-registration/)

### Tools

Sentinel-1 SAR, Sentinel-2, LiDAR, Google Earth Engine. PyTorch, scikit-learn, object
detection, self-supervised representations. Python (rasterio, geopandas), QGIS, PostGIS, R.

### Reach me

[LinkedIn](https://www.linkedin.com/in/eithan-samoun-a04934368)
