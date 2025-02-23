# Supervised-Land-Cover-Classification-using-Machine-Learning

## Short Description
In this project, we undertake the challenge of land use and land cover classification using Landsat 8 satellite imagery, inspired by the methodologies applied to the USGS dataset in a case study of Can Tho, Vietnam. It demonstrates how to leverage satellite imagery and analysis tools to identify and monitor various land covers in the region. Utilizing Google Earth Engine (GEE), this initiative applies advanced remote sensing techniques and machine learning algorithms to analyze and classify different 4 types of land cover. The purpose is to aid in urban planning, agricultural monitoring, and environmental conservation by providing accurate, up-to-date land cover information.
* This code and the exported results of these GEE scripts:
  [https://code.earthengine.google.com/?accept_repo=users/nguyenloctkp/github ](https://code.earthengine.google.com/?accept_repo=users%2Fdaviddaou%2Ftestdelta&scriptPath=users%2Fnguyenloctkp%2Fgithub%3ARandom%20Forest%20LULC%20Classification%20)

## Methods and Dataset
The dataset for this project comprises geo-referenced, labeled images from Landsat 8, ensuring comprehensive coverage and precise classification. The adaptation of machine learning techniques, particularly the utilization of Random Forest, Support Vector Machine (SVM) and Decision Trees, has allowed us to explore a novel approach in land cover classification with Landsat 8 imagery, achieving an overall classification and Kappa accuracy of over 80% and 70% respectively.


<img width="363" alt="image" src="https://github.com/LocNguyenTKP/Landsat_Supervised-Machine-Learning-Classification/assets/66542803/efa00c57-8964-4280-a155-ec0caa28955f">

*<img width="615" alt="image" src="https://github.com/LocNguyenTKP/Landsat_Supervised-Machine-Learning-Classification/assets/66542803/e9e71b40-42f8-4184-920a-59a3d35103f6">


## Dataset =======
 * Source: Google Earth Engine - USGS Landsat 8 Level 2, Collection 2, Tier 1 metadata
 * Region: Can Tho city, Vietnam
 * Time of the year: 2013 - 2023
 * Wavelength range: 0.4 – 2.5 micron
 * Number of spectral bands: 11
 * Size of image: 30x30m pixel resolution
 * Number of land-cover classes: 4

<img width="636" alt="image" src="https://github.com/LocNguyenTKP/Landsat_Supervised-Machine-Learning-Classification/assets/66542803/42cc3689-3c2d-434c-88d2-d26df9d0b157">


## Dependencies
Google Earth Engine: A platform that integrates a vast multi-petabyte catalog of satellite imagery and geospatial datasets with planetary-scale analysis capabilities at https://code.earthengine.google.com/ .
JavaScript: The scripting language used to implement algorithms on the GEE platform.

## How to Install Dependencies
Google Earth Engine: Access to GEE is provided through a web-based IDE. Users must register for an account at Google Earth Engine Sign up.
JavaScript: As a scripting language executed in the browser, it requires no additional installation for running scripts within the GEE code editor.

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your suggested changes.

## Acknowledgement
This repository was developed by Loc Nguyen under the supervision of Dr. David Daou during February - April 2024 at the United Nations University (UNU) ; Institute for Environment and Human Security (UNU-EHS). 

## Contact
For any queries or further collaboration, feel free to contact Loc Nguyen nguyenloctkp@gmail.com.

