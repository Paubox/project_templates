# Project Templates #
This project includes sensible templates for git and github, based on various
best-practices gleaned from years of experience and refinement in other projects.

Feel free to fork this repo and change whatever you like to serve your own or
your team's personal preferences.


## Usage: #

#### Git Commit Message Template #
Copy `.gitmessage` to your home folder (`~/`) and then add the following lines to `~/.gitconfig`

```
[commit]
  template = ~/.gitmessage
```

#### Github Issue Templates #
Copy the contents of `./.github` to your projects root folder

__Note - Writing up Feature Requests with Cucumber and Gherkin:__

Gherkin is a syntax used in BDD to create features... it is plain enough to convey ideas from the business team about requested features, and robust enough to base feature tests around... each line in a gherkin feature definition can be translated to a Cucumber feature test step. For example:

```gherkin
Feature: PAPP (Pen-Pineapple-Apple-Pen)

  Scenario: Creating an Apple-Pen
    Given I have a Pen
    And I have an apple
    When I go 'UH!'
    I should have an apple-pen

  Scenario: Creating a Pineapple-Pen
    Given I have a Pen
    And I have a Pineapple
    When I go 'UH!'
    I should have a pineapple-pen

  Scenario: Creating a Pen-Pineapple-Apple-Pen
    Given I have an Apple-Pen
    And I have a Pineapple-Pen
    When I put them together
    I should have a Pen-Pineapple-Apple-Pen
```

### REFERENCES: #
1. [Better commit messages with a gitmessage template](https://thoughtbot.com/blog/better-commit-messages-with-a-gitmessage-template) - Matt Sumner
2. [5 useful tips for a better commit message](https://thoughtbot.com/blog/5-useful-tips-for-a-better-commit-message) - Caleb Hearth
3. [A note about commit messages](https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html) - Tim Pope
4. [Linus' thoughts on commit messages](https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html) - Linus Torvalds
5. [Semantic commit messages](https://seesparkbox.com/foundry/semantic_commit_messages) - Jeremy Mack
6. [Github Flavored Markdown Spec](https://github.github.com/gfm/)
7. [Angular Commit Guidelines](https://github.com/angular/angular.js/blob/master/DEVELOPERS.md#-git-commit-guidelines)
8. [Creating Github Issue Templates](https://help.github.com/en/github/building-a-strong-community/configuring-issue-templates-for-your-repository#creating-issue-templates)
9. [Gherkin language guide](https://cucumber.io/)
10. [PAPP](https://www.youtube.com/watch?v=Ct6BUPvE2sM)
