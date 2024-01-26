# Pest and Disease Damage Image Database

## About the Pest and Disease Damage Image Database
The [Pest and Disease Damage Image Database](https://habs.rad.naro.go.jp/damage/#!index.md) is a collection of free and open pest damage images collected in the project "Development of pest diagnostic technology using AI" supported the Ministry of Agriculture, Forestry and Fisheries.

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
 - 画像撮影機関：農研機構野菜花き研究部門、岩手県農業研究センター、茨城県農業総合センター、新潟県農業総合研究所、岐阜県農業技術センター、広島県立総合技術研究所農業技術センター、農研機構九州沖縄農業研究センター
2. Strawbery
 - 画像撮影機関：農研機構野菜花き研究部門、宮城県農業・園芸総合研究所、栃木県農業試験場、静岡県農林技術研究所、兵庫県立農林水産技術総合センター、香川県農業試験場、長崎県農林技術開発センター
3. Cucumber
 - 画像撮影機関：農研機構中央農業研究センター、福島県農業総合センター、埼玉県農業技術研究センター、長野県野菜花き試験場、愛知県農業総合試験場、高知県農業技術センター、宮崎県総合農業試験場
4. Eggplant
 - 画像撮影機関：農研機構中央農業研究センター、群馬県農業技術センター、富山県農林水産総合技術センター、山梨県総合農業技術センター、三重県、京都府農林水産技術センター、鹿児島県農業開発総合センター

### Target pests and diseases, and parts of the crop
The pests and diseases to be photographed, as well as the parts of the crop to be photographed, vary depending on the type of crop.”

### Stracture of database
- This database is constructed as static HTML.
    - The structure is organized as "Target Crop" → "Part to be Photographed" → "Pests and Diseases to be Photographed" for each crop.
- Structure of file name
    - The file names are in the format "036512_20181205100511_01.JPG". In this format, the first two digits represent the code for the testing institution, followed by a four-digit test ID. The string after the underscore indicates the time the photo was taken, and the last two digits are a serial number assigned when there are multiple photos taken at the same time.