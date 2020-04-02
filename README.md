README
================

This **README** file gives a detailed description fo the contents of
this folder/repo, and things to do to enable a smooth workflow.
Endeavour to read this.

| No | Item               | Description                                                                      |
| -- | ------------------ | -------------------------------------------------------------------------------- |
| 1  | *Date*             | 2/04/2020                                                                        |
| 2  | *Title*            | COVID-19 Visualization                                                           |
| 3  | *Associated files* | README.md,                                                                       |
| 4  | *Summary*          | A shiny dashboard on visualization of COVID-19                                   |
| 5  | *Keywords*         | COVID-19                                                                         |
| 6  | *People involved*  | **Owokotomo Olajumoke Evangelina (OOE)** **<br> Olusoji Oluwafemi Daniel (DOO)** |
| 7  | *Data Source*      | <https://epistat.wiv-isp.be/Covid/>                                              |
| 8  | *Data format*      | **CSV files from the website above**                                             |

## Steps

1.  Get this repo by running `git pull
    https://github.com/OlajumokeEvangelina/CoronaVirusUpdate` in git
    bash or simply click on the `clone` option in the `Repository` tab,
    if you use Git GUI.

2.  Double click on COVID19Update.Rproj in the repo. This should open up
    RStudio with the COVID19Survey project.

3.  Create your own branch within the repo by running `git checkout -b
    your_branch_name_here` in the RStudio Terminal (the tab for this is
    besides the Console tab).

4.  Do your thing in the `masterFile.Rmd` file. Remember to create a
    section for your analysis. Step 3 makes sure that you are not
    editing the original file directly, rather you edit a copy in your
    branch.

5.  After every analysis or at the end of a day’s job:
    
    1.  add changes made to your branch by running `git add .`
    
    2.  commit changes to your branch by running `git commit -m "a short
        descritptive message of what you did here"`
    
    3.  push changes made to your branch by running `git push origin
        your_branch_name_here`
    
    4.  create a pull request for your changes to be added to the master
        file by clicking on the `pull requests`, and `new pull request
        tab` tab on Github.

6.  Your pull request will be merged later and this updates the original
    `masterFile.Rmd`.

## Note

It is safer for each of us to create branches and work with our
individual branches. After finishing any analysis, you can create a pull
request for it to be merged with the master. Doing this allows easy
tracing of errors.
