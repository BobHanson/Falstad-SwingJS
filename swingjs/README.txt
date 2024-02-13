The swingjs directory contains the current transpiler (j2s.core.jar) 
and the run-time core site files (SwingJS-site.zip)

Remove the sf.net.j2s.*.jar files from the Eclipse dropins directory.

Place the j2s.core.jar into the Eclipse dropins directory.
Run build-1-site.xml to unzip SwingJS-site.zip into the site/ directory.

Delete the site/ directory if it exists in your project. 

Restart Eclipse and do a CLEAN BUILD (Project...clean). 


