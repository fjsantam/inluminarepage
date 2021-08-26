# fjsantam.github.io

This repository is forked from [academicpages](https://github.com/academicpages/academicpages.github.io), a Github Pages template for academic personal websites, itself forked from mmistakes/minimal-mistakes. 

I have further modified some of the underlying HTML and Python code, for example: 
* edits to the [author profile](_includes/author-profile.html) portion of the website 
* generating custom [favicons](images/favicon), the small icon associated with the tab of a website in your browser
* embedding a PDF of my CV into the relevant page, rather than solely presenting a download link ([some example solutions](https://stackoverflow.com/questions/291813/recommended-way-to-embed-pdf-in-html))
* changing the "talks"-related pages and functionality (ex. talkmap) to "presentations", including \_config.yml
* modified the `talkmap.ipynb` file in "\_presentations" to have a default User-Agent application name in the Nominatim() function (see [here](https://geopy.readthedocs.io/en/stable/#nominatim) and [here](https://help.openstreetmap.org/questions/75718/what-is-or-how-to-decide-valid-http-user-agent-application-name-to-avoid-osm-blockage))

The source README file is located [here](README_source.md), with instructions on how to build your own such site.
