# magento2-getVersion-getModules
Simple cookiecutter modules I built for getting versions and modules via the Magento REST API. \n
\n
These transpire to the following routes: \n
\n
rest/all/V1/magentoVersion \n
rest/all/V1/magentoExtensions (all extensions) \n
rest/all/V1/magentoExtensions?state=Enabled (all enabled extensions) \n
rest/all/V1/magentoExtensions?state=Disabled (all disabled extensions) \n
\n
getVersion uses the Object manager method of call.\n
getModules uses the more robust and best practice dependency injection method.\n
