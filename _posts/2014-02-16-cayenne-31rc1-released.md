---
layout: post
title:  Cayenne 3.1 Release Candidate is Available
date:   2014-2-16
---

We are glad to announce a release candidate of Cayenne 3.1. Apache Cayenne is one of the leading open source Java ORMs with a simple learning curve and many unique features like generic objects, remote object persistence, etc. It's been a while since the last beta, giving us an opportunity to collect feedback from the community, fix bugs and improve the documentation. Still 3.1 has remained very stable, and the new RC1 is really a drop-in replacement for the previous beta version. The next 3.1 release will likely be a "final" (aka "GA"). Most of the remaining work will focus on user documentation. 

Cayenne can be downloaded from [here](/download.html). Give it a try and give us feedback!

A full list of changes in this release:

* CAY-1813 Missing ObjEntity Attribute Validation with Duplicate DbEntity Columns
* CAY-1822 Make DataMap editor fields wider 

Bug fixes in this release:

* CAY-1736 IllegalArgumentException when synchronizing entities in the Modeler
* CAY-1794 Duplicate attributes in discriminator columns of PersistentDescriptor
* CAY-1797 NPE importing DataMap
* CAY-1799 ROP: Server can't deserialize LIKE expression with pattern already compiled
* CAY-1804 Serialisation of long[] type was not working correctly. 
* CAY-1806 Error importing eomodel 
* CAY-1809 Remove 'final' modifier from Cayenne, HessianUtil, PropertyComparator, ConversionUtil, and LinkedDeque
* CAY-1818 Fix copyright year in the Modeler "about" panel
* CAY-1827 EhCache region corresponding to a cache group loses its settings after 'removeGroup'
* CAY-1845 Upgrade javadoc plugin to 2.9.1 
* CAY-1854 driver.xsd schema shouldn't be in 3.1 - it is no longer applicable 
* CAY-1856 Expression.expWithParameters does not work when parameters are placed in the inline collection 
* CAY-1866 Change in General Modeler Preferences reverts old settings to default value
* CAY-1868 Select contention with multiple contexts 
* CAY-1874 DB2 Procedure action ignores the first result set
* CAY-1880 objectStore snapshots never cleared from RefreshQuery when "use shared cache" unchecked
* CAY-1881 CayenneModeler (Mac version) doesn't work with Java 7
* CAY-1885 Null value in subclass's field.