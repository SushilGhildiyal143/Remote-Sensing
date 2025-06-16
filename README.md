# PLA4MS: Curated Georeferenced Dataset for Cloud Removal in Remote Sensing

The PLA4MS dataset comprises pairs of cloud and cloud-free images. GeoTIFF images captured by the Planetscope satellite, each capturing identical geographical locations on the same date, with one image depicting cloud-covered conditions and its counterpart showcasing a cloud-free scene. Fig. 4 shows the distribution of cloudy and cloud-free pairs based on cloud-cover percentage. These image pairs provide valuable data for research and development in the field of satellite image processing, particularly in addressing challenges associated with cloud cover. The dataset size is nearly 64 GB, emphasizing the substantial volume of data available within the PLA4MS. Fig. 5 provides an overview of ROIs and offers complete insights into the dataset. 



![Fig_5](https://github.com/user-attachments/assets/29f27ace-5f35-49e1-b778-e80c2352fac6)


1) Final Dataset Structure: This research uses satellite imagery acquired from the Planetscope constellation, accessible through the platform planet.com. The images were collected across multiple years, from 2018 to 2023, allowing for a comprehensive analysis of temporal changes in the study area. Each image in the dataset initially had a resolution of 11,461 × 9942 pixels. This implies that, due to a spatial resolution of 3 m, it translates to a length of 34,383 × 29,826 m for the ROI. These images were subsequently divided into smaller tiles, each measuring 256 × 256 pixels, to enhance processing efficiency and facilitate detailed analysis. This division translates to a spatial coverage of approximately 1.5 × 1.5 sq km per tile. This dataset structure enables more organized and standardized data for analysis. It provides a valuable resource for studying land cover dynamics, environmental changes, crop growth monitoring, and assessing the impact of cloud cover on satellite observations over the specified region. The dataset and file naming convention is structured as PLA4MS.XXX.tif, where PLA signifies Planetscope, indicating that the images originate from the Planetscope satellite. The numeral 4 denotes the presence of four channels (red, green, blue, and NIR), while MS refers to MS images. The variable XXX functions as the unique image identifier within this naming scheme. This standardized format ensures clarity and provides essential metadata related to the PlanetScope satellite images, facilitating effective organization and identification of data in the research community. Fig. 6 shows the paired examples from the PLA4MS dataset.


![Fig_6](https://github.com/user-attachments/assets/b423d254-9a1e-46cf-ad51-a1b44af27f86)


2) Dataset Availability: The PLA4MS dataset (sample dataset) can be downloaded from a stable link managed by the Indian Institute of Technology Ropar: PLA4MS dataset link (https://drive.google.com/drive/folders/1eiQ0N7qoogs9e1-EOFB2st7PLrHf-zd9). Proper citation of this article is required when utilizing the dataset for research purposes.
