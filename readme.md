Templates for Jekyll
---

The goal of this project is to provide reusable templates for producing jekyll webpages for the following purposes:

*	home pages
*	course pages
*	seminar pages
*	conference pages

The fundamental design idea is to have a sane approach for which files should be modified when the page is first established. So far, we are requiring modification of:

	_config.yml : for the basic page properties
	_data/lectures.yml : for the lecture metadata
	_includes/image.html : for the title picture

### to do (and where things are at)

1.	so far, I've just started a version of the course template. the other templates are still to be done.
2.	what is the best way of generating the page itself? should there be a basic script to generate a new directory?
3.	documentation within the directory structure needs to be placed to inform the user which files (as listed above) need to be modified to complete the page.

