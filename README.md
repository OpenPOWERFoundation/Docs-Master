# Document Master Project for OpenPOWER Foundation Documentation
This repository hold the source for the generation of OpenPOWER
Foundation Documents using Maven and Docbook.  Included in this repository
are the master POM file to control the builds and common source
files for common document content (preface and appendix).

This project does not represent a complete document, but rather
a pre-requisite project.  To build OpenPOWER documents, one must
perform the following steps:

1. Clone this project (Docs-Master) using the following command:
    ```
    $ git clone https://github.com/OpenPOWERFoundation/Docs-Master.git
    ```
2. Clone the documentation project (my_project) using the following command:
    ```
    $ git clone https://github.com/OpenPOWERFoundation/my_project.git
    ```
3. Build the project with these commands:
    ```
    $ cd my_project
    $ mvn clean generate-sources
    ```

Note: The net result of this cloning, is that the Docs-Master and
the my_project directory must reside in the same parent directoy
for the build to complete successfully.

For more information on building OpenPOWER Foundation documents,
see the *Master Template Guide* available at \([TBD](http://openpowerfoundation.org/TBD.html\).

To contribute to the OpenPOWER Foundation document master project, contact Jeff Scheel \([scheel@us.ibm.com](mailto://scheel@us.ibm.com)\) or 
Jeff Brown \([jeffdb@us.ibm.com](mailto://jeffdb@us.ibm.com)\).
