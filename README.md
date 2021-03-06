[![Codacy Badge](https://api.codacy.com/project/badge/Grade/fb2e5b1e69484d3c979351671a5f7225)](https://www.codacy.com/app/ravikalla/xml-compare?utm_source=github.com&utm_medium=referral&utm_content=ravikalla/xml-compare&utm_campaign=badger)
[![Build Status](https://travis-ci.org/ravikalla/xml-compare.svg?branch=master)](https://travis-ci.org/ravikalla/xml-compare)
[![Issue Count](https://codeclimate.com/github/ravikalla/xml-compare/badges/issue_count.svg)](https://codeclimate.com/github/ravikalla/xml-compare)
[![Issues](https://img.shields.io/github/issues/ravikalla/xml-compare.svg?style=flat-square)](https://github.com/ravikalla/xml-compare/issues)
[![Docker Stars](https://img.shields.io/docker/stars/ravikalla/xml-compare.svg)](https://hub.docker.com/r/ravikalla/xml-compare/)
[![Docker Pull](https://img.shields.io/docker/pulls/ravikalla/xml-compare.svg)](https://hub.docker.com/r/ravikalla/xml-compare/)
[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![Join the chat at https://gitter.im/capitalone/Hygieia](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/XML-Compare/Lobby?utm_source=share-link&utm_medium=link&utm_campaign=share-link)

# Compare two XMLs and write differences to an Excel

### Run Java code in local

    java -jar xml-compare-0.0.1-SNAPSHOT-jar-with-dependencies.jar <Input XML1 path> <Input XML1 path> <Output XLS path>
 Eg:

    java -jar xml-compare-0.0.1-SNAPSHOT-jar-with-dependencies.jar /home/ravi/Desktop/Projects/xml-compare/src/main/resources/XML1.xml /home/ravi/Desktop/Projects/xml-compare/src/main/resources/XML2.xml /home/ravi/Desktop/Projects/xml-compare/src/main/resources/Results2.xls

### Run as Docker image
    docker run -p 8084:8080 -v <local path>:/usr/src -t ravikalla/xml-compare /usr/src/<XML1 in local path> /usr/src/<XML2 in local path> /usr/src/<Results.xls in XML1 in local path>
 Eg:

    docker run -p 8084:8080 -v /home/ravi/Desktop/Projects/xml-compare/src/main/resources:/usr/src -t ravikalla/xml-compare /usr/src/XML1.xml /usr/src/XML2.xml /usr/src/Results.xls

### Input files:
![https://github.com/ravikalla/screenshots/blob/master/XMLs.png](https://github.com/ravikalla/screenshots/blob/master/XMLs.png)
### Result:
![https://github.com/ravikalla/screenshots/blob/master/ComparisonResults.png](https://github.com/ravikalla/screenshots/blob/master/ComparisonResults.png)

Javadoc in Github pages:
[Javadoc](https://ravikalla.github.io/xml-compare)
