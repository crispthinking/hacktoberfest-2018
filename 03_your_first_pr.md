# Your first Pull Request

Making your first pull request to an open source project can seem like quite a daunting task. We're here to take some of the mytery out of the process.

There's two main reasons you might want to open a pull request. Either you have found a bug in a piece of code that's affecting you directly, or you want to give back to the community and help maintain the software you love.

## Finding an Issue

The first step in opening a PR is to find an issue you want to fix. This can either be something that's already known about on the project's issue tracer, or something you've just discovered yourself. Once you know what you want to fix the next step is to write some code.

## Fix it!

The fist step in fixing a bug is to get the code. Fork the repo on GitHub and clone it to your machine. A good first step before you try to fix things is to make sure you can build it.

Each issue is different. There's no correct way to solve any given bug, but there are a few things to remember:

 * Take a look at the project's coding guidelines if there are any. Sometimes projects maintainers can be quite particular about indentation rules and naming things. A good rule here is to follow the code around the issue you're fixing.
 * Your fix doesn't have to be pristine. Pull requests are about discussing the best solution to an issue or the best way to add a new feature. If you make a start and get stuck you can still open a PR and the project maintainers or other contributers can lend a hand.

## Opening your PR

Once you've pushed your code to your fork it's time to open your first pull request. From the repositories home page click the "New pull request" button. This will open a diff of your changes and allow you to write up a good description of your changes.

Some repositories have a set of contributing guidelines and code of conduct that are linked to from this page. If this is your first time opening a PR against that repo give them a look over to make sure you've formatted your changes in the best way to help the project maintainers. Some repositories will want you to make a formal delcaration that your changes can be used under their license at this point too.

When you're writing the description of your PR try to include as much information as possible. If you've fixed a bug caused by a missing set of `{}` try to sumarise _how_ this caused an issue and how you've fixed it. If you're fixing a known issue in the repo add a line in your pull request description like `Fixes #1234` where `1234` is the GitHub issue number. This will tie your pull reuqest back to the issue and auto-close the issue for the project maintainers when your PR is merged.

## Status Checks

Some repositories will have status checks that are atuomatically run against their pull requests. These can check a range of things from making sure that the code still builds and passes uint tests to checking that you've signed the contributor license agreement or making sure that enough project maintainers have approved of the chagnes. Once you've opened your PR keep an eye on the status checks and make sure that they pass. If your code intruduces build failures you should be able to click through from the check to the failing build and work out what the problem is.

## Wait for Merge

Once your PR has passed status checks and any discussion around it with the contributors and maintainers has completed it should either be merged or abandoned. Often mainatainers will only have a small amount of time to deidcate to each of their open source projects so spending tme on making your pull request dsecription and the change simple and easy to follow will really pay off here. Remember the reasons behind contributing to open source and try not to get frustrated if this takes a little while.
