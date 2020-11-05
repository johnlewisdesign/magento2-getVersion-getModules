# magento2-getVersion-getModules
Simple cookiecutter modules I built for getting versions and modules via the Magento REST API. 


These transpire to the following routes:


rest/all/V1/magentoVersion


rest/all/V1/magentoExtensions (all extensions)

rest/all/V1/magentoExtensions?state=Enabled (all enabled extensions) 

rest/all/V1/magentoExtensions?state=Disabled (all disabled extensions) 


getVersion uses the Object manager method of call.

getModules uses the more robust and best practice dependency injection method.

