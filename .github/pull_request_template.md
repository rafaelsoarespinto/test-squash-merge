<type>(<scope>): <subject>

<!--

First line cannot be longer than 70 characters, second line is always blank and other lines should 
be wrapped at 80 characters. The type and scope should always be lowercase as shown below.

Allowed <type> values:
  - feat (new feature for the user, not a new feature for build script)
  - fix (bug fix for the user, not a fix to a build script)
  - docs (changes to the documentation)
  - style (formatting, missing semi colons, etc; no production code change)
  - refactor (refactoring production code, eg. renaming a variable)
  - test (adding missing tests, refactoring tests; no production code change)
  - chore (updating grunt tasks etc; no production code change)

Example <scope> values:
  - init
  - runner
  - watcher
  - config
  - web-server
  - proxy
  - etc.
-->
  
<body>
  
<!--
Message body
  - Uses the imperative, present tense: “change” not “changed” nor “changes”
  - Includes motivation for the change and contrasts with previous behavior
For more info about message body, see:

http://365git.tumblr.com/post/3308646748/writing-git-commit-messages
http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html
-->

<footer>
  
<!--
Referencing issues
Closed issues should be listed on a separate line in the footer prefixed with "Closes" keyword like this:

Closes #234
or in case of multiple issues:

Closes #123, #245, #992
Breaking changes
All breaking changes have to be mentioned in footer with the description of the change, justification and migration notes.

BREAKING CHANGE:

`port-runner` command line option has changed to `runner-port`, so that it is
consistent with the configuration file syntax.

To migrate your project, change all the commands, where you use `--port-runner`
to `--runner-port`.
-->
