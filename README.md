# jQCloud: beautiful word clouds with jQuery

jQCloud is a jQuery plugin that builds neat and pure HTML + CSS word clouds and tag clouds that are actually shaped like a cloud (otherwise, why would we call them 'word clouds'?).

You can see a demo here: http://www.lucaongaro.eu/demos/jqcloud/

# This Fork

Adds the following:

* Support for [Zepto](http://zeptojs.com)
* Options:
  * **notVisibleOk** (boolean): allow the word to be added to non-visible divs
  * **boundToDiv** (boolean): don't add words that won't fit in their entirety within the div box
  * **scaleFont** (number): scale factor for forcing the fonts to be bigger or smaller

