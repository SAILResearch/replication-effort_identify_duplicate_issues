# Replication Package for "Studying the needed effort for identifying duplicate issues"

Mohamed Sami Rakha, Weiyi Shang, and Ahmed E. Hassan  
**Empirical Software Engineering Journal**

Abstract: Many recent software engineering papers have examined duplicate issue reports. Thus far, duplicate reports have been considered a hindrance to developers and a drain on their resources. As a result, prior research in this area focuses on proposing automated approaches to accurately identify duplicate reports. However, there exists no studies that attempt to quantify the actual effort that is spent on identifying duplicate issues. In this paper, we performed an empirical study to examine the effort that is needed for manually identifying duplicate reports in four open source projects, i.e., Firefox, SeaMonkey, Bugzilla and Eclipse-Platform. Our results show that: (i) More than 50% of the duplicate reports are identified within half a day. Most of the duplicate reports are identified without any discussion and with the involvement of very few people; (ii) A classification model built using a set of factors extracted from duplicate issue reports classifies duplicates according to the effort that is needed to identify them with a precision of 0.60 to 0.77, a recall of 0.23 to 0.96, and an ROC area of 0.68 to 0.80; and (iii) Factors that capture the developer awareness of the duplicate issue’s peers (i.e., other duplicates of that issue) and textual similarity of a new report to prior reports are the most influential factors in our models. Our findings highlight the need for effort-aware evaluation of approaches that identify duplicate issue reports, since the identification of a considerable amount of duplicate reports (over 50%) appear to be a relatively trivial task for developers. To better assist developers, research on identifying duplicate issue reports should focus more on assisting developers in identifying effort-consuming duplicate issues.

## How to cite us?

```bibtex
@article{Rakha:2016:SNE:2992358.2992448,
 author = {Rakha, Mohamed Sami and Shang, Weiyi and Hassan, Ahmed E.},
 title = {Studying the Needed Effort for Identifying Duplicate Issues},
 journal = {Empirical Softw. Engg.},
 issue_date = {October   2016},
 volume = {21},
 number = {5},
 month = oct,
 year = {2016},
 issn = {1382-3256},
 pages = {1960--1989},
 numpages = {30},
 url = {http://dx.doi.org/10.1007/s10664-015-9404-6},
 doi = {10.1007/s10664-015-9404-6},
 acmid = {2992448},
 publisher = {Kluwer Academic Publishers},
 address = {Hingham, MA, USA},
 keywords = {Automated detection of duplicate issues, Duplicate bug reports, Effort based analysis, Mining software repositories, Software issue reports},
}
```

## Data and Scripts

You can find the latest version [here](https://github.com/SAILResearch/replication-effort_identify_duplicate_issues/releases/latest)
