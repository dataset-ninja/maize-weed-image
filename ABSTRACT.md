The **Maize-Weed Image** dataset contains 46336 images capturing 5764 labeled objects categorized into 2 classes: *maize* and *weed*. These high-resolution images were taken during weed surveys in both ***wet_season*** and ***dry_season*** using a digital camera and annotated using Labelmg suite. The dataset is a result of fieldwork across 18 farm locations in North Central Nigeria, part of ongoing research efforts for maize-weed identification in agricultural landscapes.

<i> Please note that this is the second version of the dataset, with an increased number of original images.</i>

## Objective

The dataset was acquired locally in Niger State, North Central Nigeria, covering four local government areas. The goal is to localize the dataset in order to meet the urgent demands of the local farmers. Due to the varying types of soil and land in those places, the authors found that different agricultural practices were implemented in the various local government districts that were visited. In addition, a review of literature in [paper sources](https://www.sciencedirect.com/science/article/pii/S2352340923001488) indicated that data of this nature were not widely available; therefore, the authors had to curate a dataset for the public and save it in the public domain for use.

## Data Description

This dataset contains images of maize plants and weed species. The dataset contains 36,874 images in total and is stored in four folders: Annotated Maize-Weed Images, Data Description and Questionnaire, Dry Season Maize Weed Images, and Wet Season Maize Weed Images.

The Dry Season contains 18,187 images captured during the dry season farm survey. The Wet Season contains 18,187 images captured during the wet season farm survey, and the Annotated contains 500 annotated images selected from the Dry Season survey saved in JSON, XML, and txt format. The images of the raw wet and dry seasons were captured using a highresolution digital camera during the Maize-Weed survey carried out on 18 farm locations in the North Central part of Nigeria. In contrast, the annotation of the images was achieved using the Labelmg suite, an open-source annotation tool.

## Experimental Design, Materials and Methods

Several farms in four (Bosso, Gbako, Katcha, and Lapai) different Local Government Areas (LGAs) in Niger State, Nigeria were visited. The details of the farms visited and their geographic information are shown in Table 2. A total of 18 farms were visited with the lowest elevation of 76 metres above sea level(masl) and the highest elevation of 225 metres above sea level (masl). Primary data were collected from the respondents during the field visits (survey) with use of structured questionnaire. 

Maize-based cropping system farms were surveyed in Bosso, Gbako, Katcha and Lapai LGAs between February and March 2022. A handheld Global Positioning System machine (GPS4300; Ethrex 10 Garmin, Taiwan) was used to record the coordinates of each location, and the data were used to map the surveyed locations. 

| Local Government Area | Location           | Latitude (⁰N) | Longitude ( ⁰E) | Altitude (m) |
|-----------------------|--------------------|---------------|----------------|--------------|
| Bosso                 | Anguwan-Shaba_01   | 9.53589       | 6.58369        | 225          |
| Bosso                 | Anguwan-Shaba_02   | 9.53562       | 6.58379        | 214          |
| Gbako                 | Sabon-Gida_01      | 9.24997       | 6.16158        | 97           |
| Gbako                 | Sabon-Gida_02      | 9.24835       | 6.16103        | 95           |
| Gbako                 | Sabon-Gida_03      | 9.24729       | 6.16051        | 94           |
| Gbako                 | Sabon-Gida_04      | 9.24357       | 6.1626         | 76           |
| Gbako                 | Sabon-Gida_05      | 9.2445        | 6.16134        | 93           |
| Gbako                 | Sabon-Gida_06      | 9.25229       | 6.16061        | 90           |
| Gbako                 | Sabon-Gida_07      | 9.25239       | 6.15988        | 96           |
| Katcha                | Katcha_01          | 9.25146       | 6.16168        | 99           |
| Katcha                | Katcha_02          | 9.25192       | 6.16192        | 100          |
| Katcha                | Katcha_03          | 9.25264       | 6.16187        | 96           |
| Katcha                | Katcha_04          | 9.25264       | 6.16187        | 158          |
| Katcha                | Katcha_05          | 9.25212       | 6.15733        | 95           |
| Katcha                | Katcha_06          | 9.24982       | 6.16652        | 85           |
| Katcha                | Katcha_07          | 9.25062       | 6.16691        | 79           |
| Lapai                 | Lapai GGSS-Day_01  | 9.02059       | 6.57805        | 140          |
| Lapai                 | Lapai GGSS-Day_02  | 9.01243       | 6.58276        | 146          |

<span style="font-size: smaller; font-style: italic;">Details of farms visited.</span>


The dataset contains images of maize crops and their accompanying weeds that alongside farm. These images were taken on field trips to 18 different maize farmlands within four Local Government Areas of Niger State, Nigeria, West Africa. The data were collected from irrigated maize fields under traditional maize cultivation practices. Raw data of maize and weeds were captured in situ using a 24.3 MP digital picture camera (Sony A6000). The images and video frames were taken one foot away from the crop, with the camera held at a constant height. The images were acquired in a ’handheld’ manner. This implies that the photographer moved through the farmland while manually holding the camera. This manual data acquisition process was required because the terrain of the farmland and the spacing of the ridges did not allow for the use of a vehicle in which the camera could be mounted. The images were checked individually to ensure they were in focus and the blurry images removed from the dataset. Direct interviews and open discussion with the maize farmers were carried out on the status, perception of weed infestation and methods of weed control, and the need for a technology that can detect weeds and apply herbicide in their fields. This information was obtained from the maize farmers using a guided questionnaire during the survey.

<img width="721" alt="maize_preview_1" src="https://github.com/dataset-ninja/maize-weed-image/assets/123257559/34f1c5f6-06ac-4d82-acc2-a0d5e3cccfd4">

<span style="font-size: smaller; font-style: italic;">Image description.</span>

After data acquisition, the data were filtered to remove noise and outliers from the images. The filtered images were stored in the ‘JPEG’ format, the same as the acquired images to preserve data integrity. Furthermore, the data was annotated with the open-source annotation tool ’LabelImg’ and saved as XML and JSON formats.
