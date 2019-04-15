+++
title = "Automated extraction of endoscopic adenoma detection rates from endoscopic-pathological data is as sensitive and specific as manual extraction"
date = 2013-07-01T00:00:00
draft = false
  
# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Sebastian Zeki"]
  
  
# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]
  
# Publication name and optional abbreviated version.
publication = "In *Journal of Open Source Software, 3(24), 701.*"
#publication_short = "In *ICMEW*"
  
# Abstract and optional shortened version.
abstract = "Medical data is increasingly moving into electronic formats. Endoscopic data in the UK is almost exclusively electronic. Pathology reporting of specimens taken at endoscopy is also electronic.Although the data is digitalized much of it is captured in natural language, semi-structured formats. Furthermore pathology datasets are often stored separately to endoscopic datasets so that the merging a pathology report to a specific patients endoscopy date can be difficult. As a result, the data for one of the best validated indicators of endoscopic quality, the adenoma detection rate (ADR), is often done manually, and often inaccurately extrapolated from the endoscopy report only.Automated extraction from text has become simplified using natural language tools. EndoMineR (LINK) is an open source software package written in R and is specifically designed to automate the process of extracting  data from endoscopic and pathology datasets. Furthermore the package merges endoscopic and pathologic datasets by patient and (fuzzy) date and allows downstream analyses that depend on the merge between both datasets, such as the adenoma detection rate. Aim: To determine the sensitivity and specificity of adenoma detection rates when using an automated process  (EndoMineR) when compared to manual extraction.Method: For the manual extraction, the endoscopy reporting database was used to extract reports of all colonoscopic examinations carried out between July 1st 2017 and January 1st 2018 at St Thomas’ Hospital.  If the report mentioned a polypectomy having been performed, the pathology report for that endoscopy was accessed via the electronic patient record to determine whether it was an adenoma. The per endoscopist ADR was the calculated.For the automated extraction, all pathology reports between the dates above were downloaded for all patients who underwent endoscopic examinations between the two dates. EndoMineR managed the merging of pathology and endoscopic reports for each patient at each time point. EndoMineR also extracted all adenomas, including the exclusion of reports mentioning the absence of adenomas, and calculated the per endocopist ADR.Results:Between  July 31st 2017 and Jan 1st 2018 2588 colonoscopies were performed. Endoscopic reports were available for all the endoscopies. Of the 1388 endoscopies where tissue was sent to histopathology, all the pathology reports were available. Manual extraction detected 499 endoscopies where an adenoma was detected and confirmed with histopathology. EndoMineR detected 501. Further examination of the dataset revealed that manual extraction had missed two cases such that the sensitivity and specificity of EndoMineR for this dataset was 100% and 100%. Manual extraction took 4.5 hours. The automated extraction took 5.3 seconds.Conclusion:Automated adenoma detection rates can be calculated from semi-structured text reports accurately using merged endoscopic-pathology records. This technique should also be applicable to the detection of other pathologies detected at endoscopy and therefore has the potential to allow further metric development to assess endoscopic quality." 
  abstract_short = ""
  
# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects = ["internal-project"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
# url_pdf = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
# url_preprint = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
# url_code = "#"
# url_dataset = "#"
# url_project = ""
# url_slides = "#"
# url_video = "#"
# url_poster = "#"
#url_source = "https://onlinelibrary.wiley.com/doi/full/10.1111/cea.13279"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = "http://dx.doi.org/10.1136/gutjnl-2018-BSGAbstracts.522"

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
# Caption (optional)
caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"

# Focal point (optional)
# Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
focal_point = ""
+++