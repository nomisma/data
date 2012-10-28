Repo for http://nomisma.org/ ids.

Nomisma is a project to establish stable URIs for concepts in the field of numismatics. It is hosted by the American Numismatic Society.

The files in the id directory are xml "snippets". To be properly processed as RDFa, they need the following wrapper:



'<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML+RDFa 1.1//EN" "http://www.w3.org/MarkUp/DTD/xhtml-rdfa-2.dtd">
<html xml:lang="en" xmlns="http://www.w3.org/1999/xhtml"
prefix="nm: http://nomisma.org/id/
   dcterms: http://purl.org/dc/terms/
   foaf: http://xmlns.com/foaf/0.1/
   gml:  http://www.opengis.net/gml/
   owl:  http://www.w3.org/2002/07/owl#
   rdfs: http://www.w3.org/2000/01/rdf-schema#
   rdfa: http://www.w3.org/ns/rdfa#
   rdf:  http://www.w3.org/1999/02/22-rdf-syntax-ns#
   skos: http://www.w3.org/2004/02/skos/core#"
   vocab="http://nomisma.org/id/"
 >
<head></head>
<body>

<!-- put snippet here -->

</body>
</html>'
