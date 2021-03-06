# Changelog 

## Beta Changelog 2020-07-13
 
- Added tip for indenting Python in chapter 12
- Divided instructions on how to create and activate a Conda environment in chapter 15
- Updated the comment about the number of installed packages in chapter 16
- Add instructions about how to create the `projects` directory from command-line in chapter 16
- On Windows, create the `projects` directory in the User's Home insteadof `C:\` to avoid permission errors on non-Administrator users in chapter 16
- Added the windows `dir` command on explanation about how to list files and folders from the command-line in chapter 16
- Added a note about where is located the User's Home directory on Windows, Linux, and Mac and related environment variables in chapter 16 
- On Windows, use `\` character as the path separator in `pip install` sample on chapter 18
- Added a note about how to open the GUI file manager from the terminal/command-line on Windows, Linux and Mac in chapter 16
- Replaced `createdb` by `pg_isready` to verify if PostgreSQL is running in chapter 18
- Added a warning to remember to activate the everycheese conda environment in chapter 18
- Added missing reminder in chapter 18
- Reduced the commit message size to prevent text leaking out of the margin of the book in chapter 20
- Included instructions on how to get VS Code to "Auto Save" in chapter 23
- Made ending paragraph about migrations more clear in chapter 23 
- Rewrite the 'description' string value in the `shell_plus` sample to prevent the text from leaking out of the book margin in chapter 28
- Updated the '94% coverage' image in chapter 29
- Updated the cheese create tests to use a regular user and `client.force_login()` in chapter 53
- In Chapter 54, the pytest fixture is now the second fixture 
- Refactor multiple tests of update views in chapter 56

## Beta Changelog 2020-06-23

- Updated the python packages installation logs in chapter 1 and 16
- Improved the Mac PostgreSQL installation tutorial in chapter in chapter 1
- Updated cookiecutter install sample in chapter 16
- Change title bar to be dark in the django-crash-starter project to match screen captures
- Moved the changelog entirely to this file in this repo
- Updated the python packages installation logs in chapter 1 and 16
- Improved the Mac PostgreSQL installation tutorial in chapter in chapter 1
- Updated cookiecutter install sample in chapter 16
- Change title bar to be dark in theuy django-crash-starter project to match screen captures
- Remove call to `CheeseFactory` in all chapters `test_good_cheese_create_view()` is defined
- Added footer with link to issue tracker on all pages
- Include BitWarden and KeePass as open source password managers in chapters 6, 22, and 31
- Installing Conda on Linux now instructs to say "yes" to "init" in chapter 1
- Explain why we are installing Python 3.7 conda in a Python 3.8 book in chapter 1
- Remove unnecessary first header in chapter 3
- Have readers check that Django was installed correctly in chapter 3
- Included explanation for creating and running migrations in chapter 22
- Added 'Explaining "|linebreaksbr"' section to chapter 24
- Add description of how template tags work in chapter 36
- Added Stracchino to cheese list to have countries specified in chapter 45
- Remove unnecessary `(object)` from `MyMixin` declaration in chapter 48
- `test__str__()` in chapter 52 now matches what existed in previous chapters, replacing missing assertion in `test_models.py`
- Added ongoing count of tests so people know they are on track in chapters 53, 54, 55, and 56
 
## Beta Changelog 2020-06-05

- Grammar fixes
- Added explanation of HTTP methods to chapter 33
- Remove `object` as super class in example mixin in chapter 33
- Explain differences between HTTP methods in chapter 33
- Explain that request.GET and request.POST are dictionary-like objects in chapter 33
- Provide clearer description for usage of django-braces in chapter 33

## Beta Changelog 2020-05-28

- Close all `{% endblock %}` tags consistently across the book 
- Properly donate code blocks across the book that were missing code hilighting
- Remove internal cruft from across the book
- Added a pagebreak between Part I intro and Chapter 2
- Added short intro to chapter 5 
- Remove unnecessary `{sample}` tag in chapter 16
- Be more explicit for windows users when running Cookiecutter in chapter 16

## Beta Changelog 2020-05-23

- Added link to code at https://github.com/feldroy/django-crash-course/tree/master/code in introduction
- More easily understood git config instructions in chapter 1
- Added missing import to code example in chapter 33
- Fixed code highlighting in chapters 12, 13, 16, 17, and 24

## Beta Changelog 2020-05-09

- Windows users are now on sqlite in Chapter 1 and 16
- Removed TODO for using VS Code to set up SSH keys in Chapter i1
- Linked to other authored books in chapter 57

## Beta Changelog 2020-05-04

- Grammar and spelling review in Chapter 1
- Changed "Installing Git on Windows" tutorial to use CMD instead Anaconda Prompt to check if git was successfully installed in Chapter 1
- Updated the short link of the vscode quick install script in Chapter 1
- Updated the short link of the PostgreSQL 12 quick install script in Chapter 1
- Revised PostgreSQL setup for Windows in Chapter 1
- Added Two Scoops of Django to Chapter 59

## Beta Changelog 2020-04-14

- Made clarifications to the windows VS Code installation instructions in the Ultimate Django Setup Chapter
- Made clarifications to the Mac VS Code installation instructions in the Ultimate Django Setup Chapter
- Provided a warning to users of Safari on Mac and finding downloaded files in the Ultimate Django Setup Chapter
- Removed TODO from the Ultimate Django Setup Chapter
- Broke up Git installation instructions for Windows and Mac in the Ultimate Django Setup Chapter
- Added global Git configuration to the Ultimate Django Setup Chapter 
- Improved the Conda instructions in the Ultimate Django Setup Chapter 
- New Linux content!
    - Added Git installation instructions for Linux to the Ultimate Django Setup Chapter
    - Added Linux VS Code installation instructions to the Ultimate Django Setup Chapter
    - Added PostgreSQL instructions for Linux to the  Ultimate Django Setup Chapter 
- Remove backticks from first commit message in chapter 20
- Added `UserDetailView` comments to `django-crash-starter` to match what we show in chapter 22
- Tiny grammar fix in chapter 45 
- Fixed spelling in the changelog

## Beta Changelog 2020-04-08

- Tweaked the Kindle/Mobi render so it should work in all devices
- Various small grammar edits
- Improved installation git instructions in Chapter 1
- Added Configuring git section in Chapter 1
- Improve installation of vscode on Mac instructions in Chapter 1
- Closed parenthesis in the description of tests in chapter 42

## Beta Changelog 2020-03-25

- Changed links and references from **roygreenfeld** to **feldroy** per https://www.feldroy.com/blogs/news/were-now-a-little-company-called-feldroy.
- Description improvements across the book
- Fixed two more code overuns
- Explained why we add `__init__.py` to our `cheeses/tests/` directory in chapter 29


## Beta Changelog 2020-03-22

- Working `kindle/mobi` version thanks to Carlos Johnson!

## Beta Changelog 2020-03-19

- Small grammar improvements across the book
- Switched to Latin Modern font in kindle/epub to increase accessibility of code examples across the book
- Reordered the installation instructions in chapter 1
- Removed reference to `test.txt` in chapter 18
- Corrected template tag ending in chapter 55

## Beta Changelog 2020-03-13

- Reordered the installation steps on chapter 1
- Explained views a little more in chapter 10
- Reordered some of the text in chapter 5 and removed a duplicate senter in chapter 25
- Explain Django model Choices and how they are based on Python enums in chapter 27 
- Specify better where the cheeses path include should go in chapter 35
- Explain where `get_firmness_display` comes from in chapter 38
- Add missing code block around output of test results in chapter 42
- Fixed flawed URL in chapter 46
- Re-explained basic foreign principles in chapter 49
- Removed unnecessary import of `assertRedirect` in chapter 53

## Beta Changelog 2020-03-10

- Simplified add/update page titles using view properties rather than the harder-to-test-in-templates `HttpRequest` approach in chapter 55

## Beta Changelog 2020-03-06

- Made all chapters except the introduction have a number, this is to make referencing code examples easier
- Added Fabio as a tech reviewer
- Warning box for password managers had the word "names" corrected to "passwords"
- Accepted PR that fixed django-crash-starter
- Revised Postgres.app installation instructions in chapter 1
- Rename `README.rst` to `README.md` in chapter 17
- Replace the reference to `cookiecutter-django` to `django-crash-starter` in chapter 17
- Refer back to basic url routing in chapter 22
- Explained `app_name` and `path name` in chapter 34
- Add mention and links to Factory Boy in chapters 40 and 41
- Use correct fontface for `country_of_origin` in chapter 44
- Included missing `app_name` in chapter 46
- Made `INSTALLED_APPS` a list rather than a tuple in chapter 48
- Added troubleshooting chapter 58 and began moving troubleshooting instructions there

## Beta Changelog 2020-03-03 

- Give Christian and Enrique formal credit as tech reviewers
- Grammar and spelling corrections, including some embarressingly large ones
- Test `str()` built-in function result in chapters 28 and 41
- Fixed location of figure 54 in chapter 47
- Removed unnecessary usage of Stracchino in chapter 51. Up for debate is if there ever an unnecessary usage of cheese
- Corrected markdown error in chapter 53
- Used even more flexible approach in chapter 54 to account for form changes
- Added typesetting to acknowledgements

## Beta Changelog 2020-02-26 

- Minor grammar and spelling corrections
- Replaced old summary with chapter 16 with 16.2 paragraphs
- Combine end text for chapter 16 with start text in chapter 17 to be new start text of chapter 17
- Put **verify your email** image into correct place within chapter 22
- Explained source of `cheese_list` in chapter 35
- Properly use cheese firmness in chapter 41
- Use **f-strings** instead of `format()` in chapter 41
- Correct git message in chapter 41
- Added tipbox in chapter 52 explaining that `assertContains` includes an HTTP status check

## Beta Changelog 2020-02-22 

- Minor grammar and spelling corrections
- Added the cover back to the PDF version
- Fixed epub metadata so Audrey shows up as author
- Made some explanations more concise per the classic `Two Scoops of Django` style
- Added explanation for `as_view()` method in Chapter 9

## Beta Changelog 2020-02-21 

- Code examples are now at 70% scale, meaning code overlaps should be a thing of the past
- The PDF now uses Source Code Pro as the code font
- Added section in introduction titled **Why Learn Django?**
- Linux instructions for installing Conda in the Ultimate Django Setup, authored by Enrique Matías Sánchez
- Added unidecode to django-crash-starter to deal with future unicode issues like `Κεφαλοτύρι`
- Added another troubleshooting link for Conda on Mac in the Ultimate Setup Chapter.
- Added troubleshooting instructions for GCC failures on the Mac in chapter 17
- Windows users now have troubleshooting instructions for MS Visual Studio code failures in chapter 17
- Put figures (images) into their right places in chapters 22 and 23
- Chapter 24 test run example now lists the correct number of tests
- Troubleshooting non-ASCII characters added to chapter 45
- Rewrote chapter 56, next steps

## Beta Changelog 2020-02-19 

- Pronoun corrections across the book
- Specific Django version in the introduction
- Various grammar fixes
- Removed `vendor.js` from `django-crash-starter`
- Corrected Spanish in chapter 8
- Now using `django-crash-starter` as a name consistently
- Added missing exit from psql in chapter 17
- Accepted PR that patched the totally borked `django-crash-starter`
- For repo creation in chapter 19, corrected text and image
- Made HTML in chapter 35 match what exists in `django-crash-starter`
- Added missing closing backtick in chapter 35
- Fixed broken test in chapter 41

## Alpha Changelog 2020-02-14 

- Imported more art!
- New tip and warning icons
- More pronoun corrections
- Removed mention of `UnitTest` from several chapters
- Note in Ultimate Django Setup about using alternatives to conda
- In Ultimate Django Setup added instruction for CLI tools for Mac
- Finished fixing chapter 11 `context['my_statement']` dialogue to say 'Nice to see you!'
- Chapter 15 updates: `django-crash-starter` Cookiecutter prompts updated to match current template, and fix escaping and margins
- More clear description of allauth source code in chapter 21
- Now calling Cheese firmness the correct way in chapter 27, 40, and 41
- Wrote literal definition of Cheese Factory to chapter 39
- Added chapters 51, 52, 53, 54, and 55! All chapters are in! Hooray!

## Alpha Changelog 2020-02-11 

- Described Django settings as constants
- Converted chapter 26 to use Django 3-style enums
- Pronoun corrections in numerous chapters
- Image size optimizations to reduce filesize
- Added calling `code` command from shell for Mac in Ultimate Django Setup chapter
- Added summary to chapter 6
- Fixed chapter 11 `context['my_statement']` result to say 'Nice to see you!'
- Added chapter 50: Updating the cheese factory


## Alpha Changelog 2020-02-07 

- ePub TOC now only lists chapter level items
- Removed `avatar_tags` template tag reference
- Fixed pytest segments
- upgraded from legacy `django.core.urlresolvers.reverse` to modern `django.urls.reverse`
- Foreign keys now have `on_delete` arguments set
- Minor grammar corrections
- Better description faker material so it's more obvious what's going on
- Describe git commit messages to better reflect the content of their chapters
- Cleanup on chapters 37 to 49. Next up, getting more chapters into the book!
- Added how to give feedback to the next steps chapter


## Alpha Changelog 2020-02-05 

- Fix for digits at the end of some PDF links
- Make lowercase code segments like `#!/Usr/Bin/Env Python` and `__Str__` caused by an overzealous titlecase script
- Added strong password and good storage practices reminder to Django superuser creation
- Replaced link to image to the actual image
- Corrected index links to projects
- Removed broken link markup 
- Replaced old mentions of GitLab with GitHub
- Use lists instead of tuples to avoid missing-comma tuple confusion
- Updated PyPI link to https://pypi.org/project/
- Better description for hard forks of open source projects
- Added troubleshooting for Conda on Mac
- Cleanup on chapter 35
- Cleanup on chapter 36

## Alpha Changelog 2020-02-04 

- Added acknowledgements and changelog sections
- Fixed conda setup for hellodjango project
- grammar and spelling fixes
- URL path corrections 
- Removed `:` suffix from `cookiecutter` command

## Alpha Changelog 2020-02-03 

- Release of the alpha!

