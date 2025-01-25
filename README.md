## NBSD

NBSD：分别从中医和西医维度对中药进行“以靶找药”和“以药找靶”的新型中药网络药理学

- [安装](#安装)

- [使用](#使用)

- [Requirements](#requirements)

- [Auxiliary Code](#auxiliary-code)
  - [pubmed的xml的爬虫、解压及处理](#pubmed_downloadpy)
  - [TCMSSD数据库的各种爬虫](#TCMSSD_Formula&TCMSSD_HERB)
  - [清洗各类数据](#wash_formula&wash_zh)
  - [uniport上各种数据的下载](#crawler_uniportpy)

- [致谢](#致谢)

### 安装

暂时还未上传，未来将设计可通过pip下载

### 使用

### Requirements

- pandas
- pyecharts
- numpy
- tqdm
- requests
- os

### Auxiliary Code

#### crawler_uniport.py

#### pubmed_download.py

#### TCMSSD_Formula&TCMSSD_HERB

#### wash_formula&wash_zh

### 致谢

- 感谢HerbiV项目负责人[老王哥Wesady](https://github.com/Wesady)作为交叉学科领路人的指点！

- [HerbiV](https://github.com/MLi-lab-Bioinformatics-NJUCM/HerbiV)也是我参与的中药网络药理学领域一个伟大的项目！欢迎star！

- 感谢上海中医药大学/中科院上药所[张豪教授](https://iiimr.shutcm.edu.cn/2024/1223/c4069a164183/page.htm)开发的[OTTM](https://pmc.ncbi.nlm.nih.gov/articles/PMC10516341/)激发的思路！