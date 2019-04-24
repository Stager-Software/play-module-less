Play LESS module
================

This module allows you to use LESS (http://www.lesscss.org) directly in your Play! project. The documentation is in /documentation.


Releases
========

Releases up to 0.9.1 are in the official Play module repository. Since that is now read-only, new releases are hosted elsewhere.

* http://lunatech.com/play-module-less/dist/play-less-0.9.2.zip (less-1.3.3)
* http://jpwesselink.github.io/play-module-less/dist/play-less-0.9.3.zip (less-1.5.0)
* http://jpwesselink.github.io/play-module-less/dist/play-less-0.9.4.zip (less-1.5.1)
* http://jpwesselink.github.io/play-module-less/dist/play-less-0.9.5.zip (less-1.6.0)
* http://jpwesselink.github.io/play-module-less/dist/play-less-0.9.6.zip (less-1.6.1)
* https://play-module-repo.s3.amazonaws.com//play-less/less-0.9.7.zip (bug fixes)


Build and publish
=================

This project uses the `ant` build tool. Make sure to have it installed.

Provide the path of the Play source directory (e.g. `/usr/local/lib/play-1.5.2/`) and build the project with:

    ant -Dplay.path=/usr/local/lib/play-1.5.2/

This puts a JAR file in: `lib/play-less.jar`

Rename this file to `less-$VERSION.zip` and publish it to a repository (e.g. `play-module-repo.s3.amazonaws.com/play-less/less-0.9.7.zip`).


License
=======

Copyright 2011-2013 Lunatech (http://www.lunatech.com).

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this project except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0.

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
 
