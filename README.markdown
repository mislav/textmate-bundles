# About

This is a meta-project containing TextMate bundles as submodules.

It serves as an index and easy way to checkout a lot of “recommended” bundles.

# Using This Project

To checkout this project and all bundles it links to:

	git clone git://github.com/textmate/bundles.git
	cd bundles
	git submodule update --init

# Getting Your Bundle Added

If you have a bundle and think it should be included then fork this project and run:

	git submodule add «public url» «name».tmbundle
	git commit

In the commit message make the first line (summary) a short description of your bundle. In the list it will be shown after your bundle so make it as descriptive as possible.

Things worth mentioning in the summary are if the bundle is for a programming language, build system, markup language, (javascript) framework, database system, related to web development, etc.

After committing your change you can push to GitHub and send us a pull request.
