# MAG Analysis Examples (Pandas)
For using this:
1.	Store same location with notebook, import class using: `from PandasMagClass import MicrosoftAcademicGraph`
2.	Set root folder like: `root = './data/'`
3.	Create new instance with root: `mag = MicrosoftAcademicGraph(root)`
4.	Get Dataframe by like:
`df_papers = mag.get_data_frame('Papers')`
`df_paper_author_affiliations = mag.get_data_frame('PaperAuthorAffiliations')`
