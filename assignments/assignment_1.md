## Assignment 1
### Computational project cookie cutter
**due at 12 noon on 2015-10-27** via email to ttimbers@quest.ca

## Instructions

Write a Shell script which will create a directory structure and documentation files
for a computational project. Advice and guidelines for project organization can be found
in [Noble, 2009](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1000424)
and many other places on the web. 

* The Shell script should make critical directories required for any computational project.
* Each directory should contain a documentation file, named `README.md`, which describes 
the purpose/role/function of each directory in your project. 
* The project's root directory should also contain an empty file named `LICENSE.md`.
* The Shell script should work when run from any directory, on any computer.
* The Shell script should contain explicit documentation on how to use it.
* Shell script code should be well documented with comments.

## Grading rubric

<table>
  <tr>
    <th></td>
    <th>Poor/Unacceptable 0% – 59%</td> 
    <th>Limited 60% – 69%</td> 
    <th>Fair/Adequate 70% – 79%</td> 
    <th>Good 80% – 89%</td> 
    <th>Exceptional 90% – 100%</td> 
  </tr>
  <tr>
    <th>Planning & Documentation (40%)</td>
    <td>No documentation exists.</td> 
    <td>Documentation about the usage or purpose of the script exists, but a a user may still have questions. Script commands are uncommented.</td> 
    <td>Documentation exists, but a user may have questions about the usage or purpose of the script. Not script commands are commented.</td> 
    <td>Not all script commands are commented, but a user would have no questions about the usage or purpose of the script.</td> 
    <td>Script usage and function is clearly documented, and commands within the script are well commented. Directory README files make directory purpose clear. A user would have no questions about the usage or purpose of the script.</td> 
  </tr>
  <tr>
    <th>Accuracy (20%)</td>
    <td>No directories or files are created.</td> 
    <td>The Shell script code creates a project directory structure, but there are no documentation files.</td> 
    <td>The Shell script code creates a project directory structure with empty documentation files.</td> 
    <td>The Shell script code creates a project directory structure with documentation files which describes the purpose/role/function of each directory in the project.</td> 
    <td>The Shell script code creates a project directory structure with documentation files which describes the purpose/role/function of each directory in the project. A an empty LICENSE.md file is also created in the projects root directory.</td> 
  </tr>
  <tr>
    <th>Reusability (20%)</td>
    <td>The Shell script can be run only on the student's computer from a specific directory.</td> 
    <td>The Shell script can be run on any computer, but only from a specific directory.</td> 
    <td>The Shell script runs when run from any directory, on any computer.</td> 
    <td>The Shell script runs when run from any directory, on any computer. The directories are useful for only the student's computational project.</td> 
    <td>The Shell script runs when run from any directory, on any computer. The directories are useful for any computational project from any discipline.</td> 
  </tr>
  <tr>
    <th>Readability (20%)</td>
    <td>It is unclear to anyone what the script does.</td> 
    <td>Only an expert familiar with this assignment could read the script and accurately predict what it does.</td> 
    <td>A person familiar with this assignment could read the script and accurately predict what it does.</td> 
    <td>A person unfamiliar with this assignment could read the script and generally predict what it does.</td> 
    <td>A person unfamiliar with this assignment could read the script and accurately predict what it does.</td> 
  </tr>
</table>