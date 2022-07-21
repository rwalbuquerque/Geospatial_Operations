# Geospatial_Operations

I used some of these python notebooks in my academic paper that assesses biodiversity indicators and species recognition on images acquired by drones: https://www.mdpi.com/2072-4292/14/4/830

Analises_Resultados_Retauracao.ipynb is a backup to extract some properties of geospatial matrices and vector data.

Avaliacao_Acuracia.ipynb outputs the accuracy of binary classification for object detection and segmentation and area assessment of binary classification (like a pixel to pixel, but involving vector data).

DeleteEmpty_Merge_OverlappingShapefiles.ipynb can be used to prepare data obtained from a binary classification process and are located in different folders. This script deletes empty vector data, merge the overlapping ones, delete the small ones (errors from raster to vector conversion), and eliminates rings in the polygons (when mapping tree crowns, rings don't exist).

FOTO_Lacunarity_Skew_Kurt.ipynb outputs different texture properties of geospatial images.

Kmeans_Unsupervised_Classif.ipynb outputs a kmeans classification on geospatial images.

Mudar_Nomes_Arquivos.ipynb changes the name of different files in a folder to a different pattern. For instance, change the name of files "tile1.tif, tile2.tif, tile3.tif" to "image1.tif, image2.tif, image3.tif".

PR2y_Merge_OverlappingShapefiles.ipynb merges vector outputs from different overlapping tiles into one single file. After all, outputs in the border of each tile may overlap with outputs of the borders of the neighboring tiles.

Plot_Train_Val_lossData.ipynb creates a graph of the neural network training process showing train and validation errors along the epochs.

Pre_Process_Tiles.ipynb can be used to delete the alpha band of raster files, check the number of bands, create tiles from images overlapping pixels between them, and create vector data that correspond to the area of each image tile.

Recall_Precision_IoU_TruePositives.ipynb generates bounding boxes to perform the IoU (Intersection over Union) accuracy assessment.

Savitzky_Golay_filter.ipynb applies the Savitzky-Golay filter.

ShapeFromTiles.ipynb create vector data that correspond to the area of each image tile.

delete_alpha_band.ipynb deletes the alpha band of raster files.
