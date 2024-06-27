# Report for Assignment 1

## Project chosen

Name: gallery_dl

URL: https://github.com/TheBosnianHooper/SEP-group18-gallery-dl-fork.git

Number of lines of code and the tool used to count it: 62kloc lizard

Programming language: python

## Coverage measurement

### Existing tool

coverage.py was used for branch coverage for the tests

screenshots provided in google doc due to issues inputting images

https://docs.google.com/document/d/1uaWXOiuq792Gg7jwYl5rFXUqrEW7WOBVCVFZTzvl0Bo/edit

### Your own coverage tool

<The following is supposed to be repeated for each group member>

Abdulelah Sibai

remove_html in text.py
initialize in config.py

https://github.com/TheBosnianHooper/SEP-group18-gallery-dl-fork/commit/f5658c8d8a9372895093b8e515c3b1567ae5041c

<Provide a screenshot of the coverage results output by the instrumentation>

<Function 2 name>

<Provide the same kind of information provided for Function 1>

## Coverage improvement

### Individual tests

<The following is supposed to be repeated for each group member>

<Group member name>

<Test 1>

<Show a patch (diff) or a link to a commit made in your forked repository that shows the new/enhanced test>

<Provide a screenshot of the old coverage results (the same as you already showed above)>

<Provide a screenshot of the new coverage results>

<State the coverage improvement with a number and elaborate on why the coverage is improved>

<Test 2>

<Provide the same kind of information provided for Test 1>

### Overall

<Provide a screenshot of the old coverage results by running an existing tool (the same as you already showed above)>

<Provide a screenshot of the new coverage results by running the existing tool using all test modifications made by the group>

## Statement of individual contributions

<Write what each group member did>

Pedro

<Function 1 name> import_module

link to commit:

https://github.com/TheBosnianHooper/SEP-group18-gallery-dl-fork/commit/3423da2bdbdf11b3c15a07317fa369cc0d36dcd1

<Function 1 name> parse_retries

https://github.com/TheBosnianHooper/SEP-group18-gallery-dl-fork/commit/3423da2bdbdf11b3c15a07317fa369cc0d36dcd1

<Test 1>

link to commit:
https://github.com/TheBosnianHooper/SEP-group18-gallery-dl-fork/commit/3423da2bdbdf11b3c15a07317fa369cc0d36dcd1

improvement:

0% -> 100%
The new test cases have covered the branches for checking infinite retries (inf, infinite) and converting retries to integers. The additional assertions ensure that each branch is hit, resulting in an improved overall branch coverage from 0% to 100%.

<Test 2>

link to commit:
https://github.com/TheBosnianHooper/SEP-group18-gallery-dl-fork/commit/3423da2bdbdf11b3c15a07317fa369cc0d36dcd1

improvement:

0% -> 100%

The new tests cover the branches for importing the default yt_dlp module, falling back to youtube_dl, and importing a specified module with hyphens replaced by underscores. These additions ensure all branches are hit, improving the overall branch coverage from 0% to 100%.