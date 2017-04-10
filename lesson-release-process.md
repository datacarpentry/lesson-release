## *This is a draft*

Author: Francois Michonneau

The Data Carpentry lessons have 2 active version:

- stable (are moved to branches at the date of release)
- development (takes place in the master branch)


% Maybe the branches are 

% - 'master/gh-pages' as stable
% - feature branches for bigger development

% For releases, we create a release, tag and archive it, so don't have them as branches. Then below we would replace 'development' with 'stable'.

Materials in the 'stable' or master branch should always be OK to teach, so any commits to stable should pass tests for things like spelling, that the exercises work and that the formatting works. 

PRs to stable would include new features, updates to or new exercises or moving around content. There is a one month freeze period during which pull requests leading to modifications of the content of the lessons (anything other than fixing typos and bugs) will not be merged. This allows for the content of the lessons to not change too much and leave time for instructors to be familiar with them before they need to teach it.

Features that require a longer conversation, significant changes or new tools or areas of focus should be developed in a 'feature' branch and be developed and discussed there before moving to master.
 
All teaching should be done from the "release" lessons. Lessons are released every 3 months. Fixing typos and bugs can be done for the active stable version. We strive to go through a comprehensive review process of the lesson before they are released to limit the need for fixing things once a lesson is released. Release versions are named `vYYYYMM.x` where YYYY represents the 4-digit year, MM the 2-digit month, and x the minor version number (e.g., `v201702.0` for the initial version of the lesson released in February 2017).

![Overview of the lesson development and release process](http://i.imgur.com/u14l6Gb.png)

The release version of the lesson is hosted at xxxx.

The stable version of the lesson is served by GitHub.

Checklist of tasks to complete before release:
- [ ] check that the learning objectives reflect the content of the lessons
- [ ] check for typos
- [ ] check that the live coding examples work as expected
- [ ] check that challenges and their solutions work as expected
- [ ] check that the challenges test skills that have been seen
- [ ] check that the setup instructions are up to date (e.g., update version numbers as needed)
- [ ] check that the data is available and that mentions of the data in the lessons are accurate
- [ ] check that the instructor guide is up to date with the content of the lessons
- [ ] check that all the links within the lessons work (this should be automated)
- [ ] make sure that the formatting of the code in the lesson looks good (e.g., no weird line breaks)
- [ ] update README as needed
- [ ] update the release notes (NEWS)
- [ ] tag release on GitHub
- [ ] create DOIs