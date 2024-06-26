# Pest and Disease Damage Image Database

## About the Pest and Disease Damage Image Database
The [Pest and Disease Damage Image Database](https://habs-rad-naro-go-jp.translate.goog/damage/image_db/index.html?_x_tr_sl=ja&_x_tr_tl=en&_x_tr_hl=ja&_x_tr_pto=wapp) is a collection of free and open pest damage images collected in the project "Development of pest diagnostic technology using AI" supported the Ministry of Agriculture, Forestry and Fisheries.

## License and Disclaimer
### License
This database and the images provided are licensed under the Creative Commons Attribution 4.0 International: https://creativecommons.org/licenses/by/4.0/legalcode.en. For more information about the license, please see the link.

### Disclaimer of Warranties and Limitation of Liability.
**The provider makes no representations or warranties as to the completeness, accuracy, comprehensiveness, safety, or fitness for any particular purpose of the content. The provider is not liable for any damages, losses, costs, or expenses, whether direct, indirect, incidental, consequential, punitive, or otherwise, arising from the use of this content, including any actions taken or decisions made by the user based on the content.**

The following is a quote from [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/legalcode.en), **Section 5 – Disclaimer of Warranties and Limitation of Liability.**.

>**a.Unless otherwise separately undertaken by the Licensor, to the extent possible, the Licensor offers the Licensed Material as-is and as-available, and makes no representations or warranties of any kind concerning the Licensed Material, whether express, implied, statutory, or other. This includes, without limitation, warranties of title, merchantability, fitness for a particular purpose, non-infringement, absence of latent or other defects, accuracy, or the presence or absence of errors, whether or not known or discoverable. Where disclaimers of warranties are not allowed in full or in part, this disclaimer may not apply to You.**  
> 
>**b.To the extent possible, in no event will the Licensor be liable to You on any legal theory (including, without limitation, negligence) or otherwise for any direct, special, indirect, incidental, consequential, punitive, exemplary, or other losses, costs, expenses, or damages arising out of this Public License or use of the Licensed Material, even if the Licensor has been advised of the possibility of such losses, costs, expenses, or damages. Where a limitation of liability is not allowed in full or in part, this limitation may not apply to You.**  
> 
>c.The disclaimer of warranties and limitation of liability provided above shall be interpreted in a manner that, to the extent possible, most closely approximates an absolute disclaimer and waiver of all liability.

The database was built with the utmost care, but errors may still exist. If you find any problems, please report them to the following github issue.

https://github.com/ai-pest/image_db_open

## Overview
An overview of the Pest and Disease Damage Image Database is follows.

### Image Photgraphed Method
In capturing the images, we have isolated and identified the pests and diseases, and conducted inoculation tests. For the individuals affected, we attempt to capture images over time, from the early to the late stages of the disease or pest damage.

### Target Crops and Testing Institutions
We are collecting damage images for the following four crops. The copyright for each damage image is held by the testing institutions and is provided under [the Creative Commons Attribution 4.0 International License.](https://creativecommons.org/licenses/by/4.0/legalcode.en)

1. Tomato
 - Image Capturing Organization：Image Capturing Organization、Iwate Agricultural Research Center、Ibaraki Agricultural Center、Niigata Agricultural Research Institute、Gifu Prefecture Agricultural Technology Center、Hiroshima Prefectural Technology Research Institute Agriculture Research Center、Kyushu Okinawa Agricultural Research Center, NARO
2. Strawbery
 - Image Capturing Organization：Image Capturing Organization、Iwate Agricultural Research Center、Miyagi Prefectural Institute of Agriculture and Horticulture、Tochigi Prefecture Agricultural Experiment Station、Shizuoka Prefectural Research Institute of Agriculture and Forestry Research、Hyogo Prefectural Technology Center for Agriculture, Forestry and Fisheries、Kagawa Prefecture Agricultural Experiment Station、 Nagasaki Agricultural and Forestry Technical Development Center.
3. Cucumber
 - Image Capturing Organization：Central Region Agricultural Research Center, NARO、Fukushima Agricultural Technology Center、Saitama Prefectural Agriculture and Forestry Research Center、Nagano Vegetable and Ornamental Crops Experiment Station、Aichi Agricultural Research Center、Kochi Agricultural Research Center、Miyazaki Agricultural Experiment Station
4. Eggplant
 - Image Capturing Organization：Central Region Agricultural Research Center, NARO、Gunma Prefectural Agricultural Technology Center、Toyama Prefectural Agricultural, Forestry ＆ Fisheries Research Center、Yamanashi Prefectural Agricultural Technology Center、Mie Prefecture、Kyoto Prefectural Agriculture, Forestry and Fisheries Technology Center、Kagoshima Prefectural Institute for Agricultural Development

### Target pests and diseases, and parts of the crop
The pests and diseases to be photographed, as well as the parts of the crop to be photographed, vary depending on the type of crop.”

### Stracture of database
- This database is constructed as static HTML.
    - The structure is organized as "Target Crop" → "Part to be Photographed" → "Pests and Diseases to be Photographed" for each crop.
- Structure of file name
    - The file names are in the format "036512_20181205100511_01.JPG". In this format, the first two digits represent the code for the testing institution, followed by a four-digit test ID. The string after the underscore indicates the time the photo was taken, and the last two digits are a serial number assigned when there are multiple photos taken at the same time.
