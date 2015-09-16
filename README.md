# osgi-xmlcommons-full
Supporting all xml-apis within OSGi attached with their default implementations.

SecuritySupport classes are overridden to have the following result:

 - Thread Context ClassLoader is always ignored
 - Factories search implementations within this bundle
 
 For more information what is embedded, see the [xml-commons][1] website.

[1]: http://xerces.apache.org/xml-commons/

