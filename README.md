# Glacial Lake Change Detection using U-Net and Sentinel-2 Imagery

This repository contains a deep learning pipeline to detect and quantify changes in Himalayan glacial lakes using satellite data from Sentinel-2. Built as part of the **ISRO Hackathon 2025** challenge on AI/ML-driven glacial lake monitoring.

## What It Does

- Uses a U-Net model to segment glacial lakes in 2018 and 2024 Sentinel-2 images
- Computes lake area change (in sq.km)
- Visualizes expansion or shrinkage using a color-coded change map

## Project Files

- `Glacial_Lake_Change_UNet.ipynb`: Full working Colab notebook
- `Glacial_Lake_Change_Report.pdf`: Final report
- `example_outputs/`: (Add predicted lake masks and change map here)
- `data/`: (Optional: small sample dataset)

## Tools Used

- Google Colab
- TensorFlow / Keras
- OpenCV
- Rasterio
- Google Earth Engine

## Results

| Year | Lake Area (sq.km) |
|------|-------------------|
| 2018 | ~0.0432           |
| 2024 | ~0.0651           |
| **Change** | **+0.0219** |

## Future Work

- Add DEM (terrain) filtering
- Expand to other regions
- Train on higher-res data

## Contributing

Feel free to fork and adapt this to other glacial lakes!

