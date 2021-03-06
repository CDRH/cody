README.md

Update Instructions
-------------------
After you update solr and pull changes from the cocoon repo, you will need to break and unbreak two files in order for changes to show up and to repupulate the search autofill. 

The files are: 

- stylesheets/xslt/tei.p5.xsl
- stylesheets/xslt/solr2json-facets.xsl

Other Instructions
------------------

This file will help you 'install' the quills project.
Note that you will (most likely) be unable to install this interface to Windows.
You will need a UNIX-like environment (anything that understands and respects
the 'ln' UNIX command).
Note: It was not deemed worth it to get this working with Windoze.

This interface is ran using Cocoon. If modifying anything,
you will likely need to read up about how Cocoon works.

You will need to create/modify the following file(s):
 - config.xsl

Some of these files is soft (symbolically) linked to the proper location. You
will need to edit each file in the **config** directory.

For each file, there is a templated version (typically with some instructions on
what needs to be edited in the file). These are (respectively):
 - config.tmpl.xsl

Directions:
Copy the above templated file to it's proper untemplated filename, then edit
each file to fit your configuration. Everything should work at this point.

Images:
If you need to see the images for work, you will also need to copy the images
from there archived location (probably the U drive, i.e. 
libstaff1a.unl.edu/commetextd).
Copy images to:
 - figures/250/*
 - figures/800/*
