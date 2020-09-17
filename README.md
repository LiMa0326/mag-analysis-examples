# MAG Analysis Examples
This repository contains different MAG analysis notebooks, scripts and related resources. For introduce and prerequisites of MAG and store MAG on Azure, see [MAG Subgraph Generation (PySpark)](https://github.com/LiMa0326/mag-subgraph-generation-pyspark)

## MAG Subgraph Analysis (Pandas)
For using PandasMagClass.py to read MAG streams for Pandas:
1.	Store PandasMagClass.py as same location with notebook, import class using: `from PandasMagClass import MicrosoftAcademicGraph`
2.	Set root folder like: `root = './data/'`
3.	Create new instance with root: `mag = MicrosoftAcademicGraph(root)`
4.	Get Dataframe by like:
`df_papers = mag.get_data_frame('Papers')`
`df_paper_author_affiliations = mag.get_data_frame('PaperAuthorAffiliations')`

### Resources for MAG Subgraph Analysis (Pandas)
* [AffiliationRegions.txt](https://github.com/microsoft/mag-covid19-research-examples/blob/master/src/MAG-Samples/impact-of-covid19-on-the-computer-science-research-community/AffiliationRegions.txt)

## Region Year Paper Stats (Pyspark/U-SQL)
Draw paper/citations/saliency growth comparison figures by single region and regional collaborations.

### Resources for Region Year Paper Stats (Pyspark/U-SQL)
* [ISOCodeRegion.txt](https://github.com/LiMa0326/mag-analysis-examples/blob/master/resource/ISOCodeRegion.txt)
