LMG Front-End Development Guidelines
====================================

LMG aims to build responsive, modular, semantic, accessible, and maintainable projects that exceed client expectations and stand up over time.

Developers should strive for consistency, valid and well-tested files, and conform to generally accepted best practices.

Responsive
----------

All projects should be responsive in nature, and centered on mobile first styling, and progressive enhancement. Projects should scale from mobile devices up to extra large monitors unless otherwise specified.

Modular
-------

Styling, markup and scripts should be modular in nature, allowing for maximum reuse across the project. We use Brad Frost’s Atomic Design and Microformats (Person, Product, etc.) to guide our markup.

Semantic
--------

Optimal HTML tags should be selected to maximize the semantic meaning of content. This starts with using heading, paragraph, list, and figure tags instead of generic divs. Additionally, Microformat standards also apply for improving the semantic nature.

Accessible
----------

Code should be composed in a way that is inherently accessible, working across devices and readable by assistive technologies. ARIA roles are the preferred method of designating the role of sections in markup when its use may be ambiguous.

Progressive Enhancement should be utilized and driven with feature detection. Specific device or browser version targeting should not be used.

Maintainable
------------

Decisions should be made in favor of long-term maintainability. Developers should reduce external dependencies, and avoid browser or device “hacks”. Additionally, all files must remain under version control, properly documented, and correctly separated into presentation, content, and behavior components.

Tooling
-------

LMG utilizes both Grunt and Gulp for task running, and uses Sass (SCSS) solely for CSS preprocessing. Modules/plugins to these vary on a per-project basis. Generally separate source files should be maintained, and each file should be uncompressed and formatted for readability. Production files should be processed with the available tooling to combined and minified.

Resources/References
--------------------

* Brad Frost: Atomic Design - [http://bradfrost.com/blog/post/atomic-web-design/](http://bradfrost.com/blog/post/atomic-web-design/)
* Pattern Lab: Atomic Design System Tool - [http://patternlab.io](http://patternlab.io)
* Microformats - [http://microformats.org/wiki/Main_Page](http://microformats.org/wiki/Main_Page)
* W3C: Using Semantic Elements… - [http://www.w3.org/TR/WCAG20-TECHS/G115.html](http://www.w3.org/TR/WCAG20-TECHS/G115.html)
* Schema.org - [http://www.schema.org](http://www.schema.org)
* WebPlatform: Element Reference - [https://docs.webplatform.org/wiki/html/elements](https://docs.webplatform.org/wiki/html/elements)
* WebAIM: Intro to Web Accessibility - [http://webaim.org/intro/](http://webaim.org/intro/)
* W3C: Web Content Accessibility Guidelines - [http://www.w3.org/TR/WCAG20/](http://www.w3.org/TR/WCAG20/)
* USA Section 508 - [http://www.section508.gov](http://www.section508.gov)
* Grunt – [http://gruntjs.com](http://gruntjs.com)
* Gulp – [http://gulpjs.com](http://gulpjs.com)
* Sass - [http://sass-lang.com](http://sass-lang.com)
