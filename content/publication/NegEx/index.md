+++
title = "Removal of normal and negative phrases from endoscopic semi-structured text for accurate automated endoscopic audit"
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
publication = "In *United European Gastroenterology Journal 2018; 6 (Supplement 1)*"
#publication_short = "In *ICMEW*"

# Abstract and optional shortened version.
abstract = "Introduction: Most electronically stored endoscopic reports consist of semi-structured free text. containing a significant amount of auditable information. However, the unstandardised text requires cleaning prior to audit so that the data is standardised across patients. One major obstruction to the automated auditing of free text is phrases that mention an absence of a pathology such as ‘No hiatus hernia is seen.’ or ‘There is no malignancy.’ Methods: The current study aims to determine the complexity of semi-structured free text endoscopy reports and determine the simplest function in the globally most popular data analytics language ‘R’, to remove negative phrases from endoscopic text and to validate the performance of this algorithm against manual extraction. Five hundred endoscopic reports were randomly selected for any procedure between Jan 1 2007 to Jan 1 2017. The low average text complexity (measured using the package ‘readability’ in R based on sentence structure rather than terminology) was equivalent to age 14–15 years (Readability scores: Flesch KinCaid=9.8, Gunning_Fog Index=13.3, Coleman_Liau=10.0) meaning that the text could be analysed using less processor intensive pattern recognition defined as ‘regular expressions ‘rather than using machine learning. Negative phrases were extracted from the first 100 reports as a training set, using the ‘lexicon’ package in R by cross referencing each sentence in an endoscopy report with a list of known negators to create generic regular expressions that could detect all negative phrases and incorporated into a script in R. A endoscopist blinded to the automated results was required to remove all negative phrases whether in mixed or non-mixed sentences for the same 400 endoscopy reports. Automated and manually extracted phrases were then statistically compared to generate a sensitivity, specificity and accuracy measurement of automated extraction. The difference in audit outcome was also estimated when a comparison was made between simple keyword searches to populate the audit versus the use of negative removal as implemented using our technique. Results: The training set resulted in 12 regular expressions, compiled into a single runnable function, thought capable of detecting most negative phrases. This resulted in a sensitivity for the detection of negative phrases of 97.2%, specificity 74.61%, positive prediction value of 65.4% and a negative prediction value of 98.01%. When the regular expression function was run against a simple keyword search for certain phrases, certain terms demonstrated a significant difference in their detection when keyword searches were used before and after the negator removal function was used.The term CLO for example was detected 12.25% without negator removal and 7.25% with the function. Conclusions: Given the simple sentence structure of the endoscopy reports across multiple endoscopists, a simple processor-nonintensive approach to the removal of negative or normal findings is feasible. Although there is room to improve the specificity further, it is preferable to have false positives in the output result which may require minimal work to remove in the final data cleaning stage. The removal of negators is likely to have more or less of an impact based on the phrase being searched for." 
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
url_source = "https://www.ueg.eu/education/document/automated-extraction-of-endoscopic-adenoma-detection-rates-from-endoscopic-pathological-data-is-as-sensitive-and-specific-as-manual-extraction/181995/"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
#doi = "http://dx.doi.org/10.1136/gutjnl-2018-BSGAbstracts.522"

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


