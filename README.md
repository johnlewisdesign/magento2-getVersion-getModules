# magento2-getVersion-getModules
Simple cookiecutter modules I built for getting versions and modules via the Magento REST API. \s\s
\s\s
These transpire to the following routes: \s\s
\s\s
rest/all/V1/magentoVersion \s\s
rest/all/V1/magentoExtensions (all extensions) \s\s
rest/all/V1/magentoExtensions?state=Enabled (all enabled extensions) \s\s
rest/all/V1/magentoExtensions?state=Disabled (all disabled extensions) \s\s
\s\s
getVersion uses the Object manager method of call. \s\s
getModules uses the more robust and best practice dependency injection method.\s\s
