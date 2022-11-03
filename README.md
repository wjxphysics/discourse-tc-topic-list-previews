just to test modified some code:
1. remove transform when hover over topic in topic list
	modified: common/common.scss
2. remove preventdefaut from click event to enable clickable
	modified: javascripts/discourse/components/tlp-featured-topic.js.es6

# discourse-tc-topic-list-previews

Theme Component which allows you to customise the layout for many of the Topic Lists across Discourse, fundamentally adding thumbnail previews and excerpts from Topics, a featured topics images banner and a user portfolio (aka user wall).

Add to the functionality by also installing the sidecar at: https://github.com/paviliondev/discourse-topic-previews-sidecar

[See more at:](https://meta.discourse.org/t/topic-list-previews-theme-component/209973?u=merefield)

Known Issue:

- Because of the way I've opted to render a masonry style tiles display (it's very efficient), on Chromium based browsers there will be a limit to how far you can scroll until the layout messes up.  It is fixed in Chrome Beta (Version 96) so should soon not be an issue for most users.
