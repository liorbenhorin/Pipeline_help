####Pipeline folder structure framework

Every pipeline project is made of Branches.

Each branch contains a hierarchy of folders and components.

Components contain the maya files:

1. component master file
2. component version files
3. component master archived files

***The pipeline framework is designed to handle most of the common CGI workflows,<br>
from small commercial, to short film, to tv series.***<br><br>

!!! note
    Every pipeline project is essentially a maya project.<br>
    pipeline will use json files to map the projects directory structure.

!!! warning

    * Do not to alter the directory structure of a pipeline project manually.
    * Do not delete any json file from the project directories.
    * Doing so will result in pipeline unable to read the project.
