# PCL-RandomForest-Classification
This package explaines how to implement Random Forest algorithm for handheld based LiDAR point cloud data in urban area.

# Installation and Run
Run the `src/classification.R` file. It has the `data` file hardcoded from the `data` directory. 

The data is from: https://hri.fi/data/en_GB/dataset/helsingin-laserkeilausaineistot

### Original Author

Dr. Zeybek's fine work at: https://github.com/mzeybek583/PCL-RandomForest-Classification

### Note 
You need a `.laz` or `.laz` file that has RGB channels (aka, it needs to be "colorized"). You can check this by looking at the output of the `print()` method after you load a lidar point cloud file. 

### If you want to create your own colorized Lidar Point Cloud

Here's a lead on how to do this: 

- https://community.esri.com/t5/imagery-and-remote-sensing-blog/fun-with-colorizing-lidar-with-imagery/ba-p/884803

## References 

- Fun with Colorizing Lidar with Imagery. (2020, June 23). Esri Community. https://community.esri.com/t5/imagery-and-remote-sensing-blog/fun-with-colorizing-lidar-with-imagery/ba-p/884803

- Helsinki point cloud—Overview. (n.d.). Retrieved March 12, 2022, from https://www.arcgis.com/home/item.html?id=f9eeed099fba4eecb6531c4fdde9369d

- https://hri.fi/data/en_GB/dataset/helsingin-laserkeilausaineistot

- https://kartta.hel.fi/?link=aw4R8i



