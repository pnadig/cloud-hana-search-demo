SAP HANA Cloud Samples - HANA Search Demo
==========================================

This sample web application demonstrates how-to use native SAP HANA search (fuzzy and linguistic) in Java applications running on SAP HANA Cloud Platform.

Quick start
-----------

Read the how-to blog: http://scn.sap.com/community/developer-center/cloud-platform/blog/2013/05/23/enable-hana-search-in-your-cloud-application

Project Overview
----------------

Here is a basic description of the project. The structure is as follows:

com.sap.hana.cloud.samples.search - contains SearchDemoServlet which is used as demo
	db - classes which are used for database access
	
		
Application startup
-------------------

You can run "HANA Search Demo" application only on the Cloud.

Running on the Cloud
 - from command prompt run "mvn clean install" to build war file
 - deploy war file to the cloud
 - navigate to SearchDemoServlet URL, and try the search

Versioning
----------

For transparency and insight into our release cycle, and for striving to maintain backward compatibility, the SAP HANA Cloud - Samples project will be maintained under the Semantic Versioning guidelines as much as possible.

Releases will be numbered with the following format:

`<major>.<minor>.<patch>`

And constructed with the following guidelines:

* Breaking backward compatibility bumps the major (and resets the minor and patch)
* New additions without breaking backward compatibility bumps the minor (and resets the patch)
* Bug fixes and misc changes bumps the patch

For more information on SemVer, please visit http://semver.org/

Authors
-------

**Dimitar Tenev**

Copyright and license
---------------------

Copyright 2013 SAP AG

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

Find the project description at documents/index.html
