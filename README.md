# EMP_impact
##estimating impact factor for EMP studies

### About

I've basically imported DOIs from the EMP manuscript table S1, and used them as queries to Google Scholar. 

The top hit from each DOI is returned, along with the year of publication and the number of citations.

Average impact factor is calculated as the number of citations divided by the number of years since
publication (considering 'now' as 2017.5. 

### Other info

This uses the [scholar.py code](https://github.com/ckreibich/scholar.py) from ckreibich on GitHub.

Portions have been adapted as new modules in the included ipynb, and original code is imported from the
unmodified scholar.py script. The original README.md file included with `scholar.py`, including the
associated license text, is included as `scholar_README.md`.  
