# About

This is a meta-project containing TextMate bundles as submodules.

It serves as an index and easy way to checkout a lot of “recommended” bundles.

# Using This Project

To checkout this project and all bundles it links to:

	git clone git://github.com/textmate/bundles.git
	cd bundles
	git submodule init
	git submodule sync

# Getting Bundles Listed

If you have a bundle and think it should be included then fork this project and run:

	git submodule add «your bundle url» «name».tmbundle
	git commit

In the commit message make the first line (summary) a short description of the purpose of your bundle. In the listing of bundles that line will be shown after your bundle so do not put in e.g. “Bundle for Java” if you add a Java bundle.

Things worth mentioning in the summary are if the bundle is for a programming language, build system, markup language, framework (javascript), database system, related to web development, etc.

After committing your change you can push to GitHub and send us a pull request.
