# Git-Flow Maven Plugin
 
  The Maven plugin that supports various Git workflows, including Vincent Driessen's [successful Git branching model](http://nvie.com/posts/a-successful-git-branching-model/) and [GitHub Flow](https://guides.github.com/introduction/flow/).

  Currently a Java implementation of Git version control system [JGit](https://github.com/eclipse/jgit) doesn't support [`.gitattributes`](http://git-scm.com/book/en/Customizing-Git-Git-Attributes).

  This plugin runs Git and Maven commands from the command line ensuring that all Git features work properly.

  Supports Eclipse Plugin projects build with [Tycho](https://eclipse.org/tycho/).

# Fork

  To further improve the [Maven CI friendly versioning](https://maven.apache.org/maven-ci-friendly.html) support, the project got forked from [aleksandr-m/gitflow-maven-plugin](https://github.com/aleksandr-m/gitflow-maven-plugin).

  Once the changes/additions are successfully integrated in the upstream repository, the fork will be irrelevant again.

# Usage

  If you feel like the plugin is missing a feature or has a defect, create a [new issue](https://github.com/mmusenbr/gitflow-maven-plugin/issues/new) submit a [Pull Request](https://github.com/mmusenbr/gitflow-maven-plugin/pulls).
  Pull Requests not related to the Maven CI friendly versioning, should be opened as [upstream Pull Request](https://github.com/aleksandr-m/gitflow-maven-plugin/pulls).
  When creating a new issue, please provide a comprehensive description of your
  concern. Especially for fixing bugs it is crucial that the developers can reproduce your problem. For this reason,
  entire debug logs, POMs or most preferably little demo projects attached to the issue are very much appreciated.
  Of course, patches are welcome, too. Contributors can check out the project from the
  [source repository](https://github.com/mmusenbr/gitflow-maven-plugin)|[source repository (upstream)](https://github.com/aleksandr-m/gitflow-maven-plugin) and will find supplementary information in the
  [guide to helping with Maven](http://maven.apache.org/guides/development/guide-helping.html).
