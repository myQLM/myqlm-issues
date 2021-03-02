# Guidelines for reporting issues in myQLM

We are using [GitHub issues](https://github.com/myQLM/myqlm-issues/issues) for tracking bugs and issues. To report a bug, from the "New issue" tab go to  [bug report](https://github.com/myQLM/myqlm-issues/issues/new?assignees=&labels=&template=bug_report.md&title=) and submit your issue. You can also suggest us different ideas for myQLM from the tab [Feature request](https://github.com/myQLM/myqlm-issues/issues/new?assignees=&labels=&template=feature_request.md&title=) .   
For simple questions and discussion on quantum computation and myQLM you can use our [Slack](https://myqlmworkspace.slack.com/?redir=%2Fgantry%2Fclient).

# Guidelines for installing myQLM on MacOS

It’s recommended to use the official Python distribution (without virtual environment or without anaconda) on MacOS.

# Guidelines for installing myQLM magics on Windows

The wand module requires extra tools to work (like the ImageMagick library) on Windows, please go to the Install ImageMagick on Windows page to download this library.
Once you have installed this library, you can install myQLM magics:

python -m qat.magics.install
