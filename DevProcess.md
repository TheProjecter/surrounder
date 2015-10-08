# Introduction #

This plugin uses private classes of IntelliJ IDEA not in the OpenAPI.
To use it, you must add the jar "idea.jar" in your IntelliJ IDEA SDK.

Alternative method is to add the "idea.jar" as a library of the project, but be aware that it must be not deployed by IDEA, otherwise the plugin won't works.
To solve this problem just create a empty "idea.jar" read-only file into "IDEA\_CONF\_HOME/system/plugins-sandbox/surrounder/lib".