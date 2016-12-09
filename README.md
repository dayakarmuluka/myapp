
This readme file provides a brief overview of the file and folder structure
included in the default MontageJS project directory.

>IMPORTANT: Be sure to replace the contents of this readme file with information
about the final application before deploying the application or passing it on to
a client.

Project Directory
============

The default project directory includes the following files and folders:

* assets/  -  Contains global stylesheets and images for the application.
* index.html  -  Is the entry-point document for the application.
* node_modules/  -  Contains the code dependencies required in development.

    Includes Montage, the core framework, and Digit, a mobile-optimized user
    interface widget set by default. Since MontageJS uses the CommonJS module
    system, you can leverage the npm ecosystem for additional modules. To add
    dependencies (e.g., foo), use `npm install foo` in the project directory.

    NOTE: All packages in this directory must be included as dependencies
    in package.json.

* package.json  -  Describes the application and the dependencies included in
            the node_modules directory.
* README.md  -  The default readme file.
* run-tests.html  -  Is a page to run Jasmine tests manually in the browser.
* test/  -  Contains tests for the application.

    By default, this directory includes all.js, a module that points the test runner
    to all jasmine specs.

* ui/  -  Contains the application user interface components.

    By default, this directory contains one component: main.reel (the Main
    user interface component)

In development, you can expand this project directory as necessary; for example,
depending on the project you may want to add the following folders:

* locale/  -  For localized content.
* scripts/  -  For JS libraries that do not support the CommonJS exports object
           and, therefore, have to be loaded using a `<script>` tag.





