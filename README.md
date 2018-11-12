spatialanalysis.github.io
===========================================================

This repository holds the source code for the Spatial Analysis website developed by the [Center for Spatial Data Science](https://spatial.uchicago.edu) at the University of Chicago. It is built using the R package [`blogdown`](https://bookdown.org/yihui/blogdown/).

## About 
This website was developed through the efforts of Luc Anselin, Grant Morrison, and Angela Li. Questions and feedback can be directed to us by [filing an issue](https://github.com/spatialanalysis/spatialanalysis.github.io/issues) in this repository.

### About the Center for Spatial Data Science
A joint initiative of the [Division of Social Sciences](https://socialsciences.uchicago.edu) and the [Computation Institute](https://www.ci.uchicago.edu), the Center for Spatial Data Science (CSDS) develops state-of-the-art methods for geospatial analysis, spatial econometrics, and geo-visualization; implements them through open source software tools; applies them to policy-relevant research in the social sciences; and disseminates them through training and support to a growing worldwide community of over 200,000 spatial analysts. As of July 1, 2016, CSDS succeeds the GeoDa Center for Geospatial Analysis and Computation at Arizona State University. 

### About the University of Chicago
[The University of Chicago](https://www.uchicago.edu/) is a private, nondenominational, culturally rich and ethnically diverse coeducational research university located in Hyde Park, Chicago. The University of Chicago is an urban research university that has driven new ways of thinking since 1890. Our commitment to free and open inquiry draws inspired scholars to our global campuses, where ideas are born that challenge and change the world.

## Website Notes
### References
Thanks to [Chris Prener](https://github.com/slu-dss/slu-dss.github.io) and [Mine Centinkaya-Rundel](https://github.com/Sta199-S18/website) for providing ideas for the structure of this blogdown website, as well as the [Earth Lab](https://www.earthdatascience.org) at University of Colorado for inspiring development of this site.

### Quick Tips for Updating This Site

After making changes on the `hugo` branch, committing, and pushing them, run 
```
bash setup.sh
```
to update the site. There's a nasty combination of Github subtrees and branches underlying this site, because Hugo doesn't work super well with Github pages.

- When in doubt, edit `config.toml` first, for sitewide settings like the website title, headers, and footers. Edit the `config.toml` file rather than the `config.yaml` file.
- To update page content, add to the `content` folder. 
- To update page formatting, go to the `layouts` folder. You can copy and modify the original HTML layout files from `themes/hugo-smorg/layouts`.
- **Don't touch the `public` folder!** (The stuff in there is automatically generated from the files in `content`.) 
- Images for pages and posts as well as logo files are stored in the `static` folder. Use the RStudio `blogdown` addin to insert images easily.