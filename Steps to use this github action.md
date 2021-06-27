# Steps to use this:

1. Clone this repo in your local system

2. In build_readme.py, Replace the feed URL with link 
   of the repo whose files you want. 

To test in local system :

*  Create README.md file write these 2 lines 

```bash
<!-- Projects start -->

<!-- Projects end -->
```

*  Run the python file, it will paste the title with link of the folders
   of the repo in the README.md file.

3. Now push these files in the repo in which 
you want to apply this github Acton. 

* build_readme.py,
* .github/workflows/build.yml
* requirements.txt

4. Add these 2 lines in your readme.md file where you 
want list of the external contents of repo. 

```bash
<!-- Projects start -->

<!-- Projects end -->
```
5. Wait for minute so that github actions start its work
or click on Actions to view status. 
