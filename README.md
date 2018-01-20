# wikiMath17
Dataset of English Wikipedia Articles Containing &lt;math/>, &lt;ce/> or &lt;chem/> tags.

## Log

### 2017-07-31
* Modifi [wikifilter](https://github.com/physikerwelt/wikiFilter/commit/1cc1b1bb8656c7ecec60887896ac26a4be668798) to select acticles with ce (deprecated) or chem tags as well.
* Download [latest dump](https://dumps.wikimedia.org/enwiki/latest/enwiki-latest-pages-articles.xml.bz2) (Dump file created on Fri, 21 Jul 2017 12:07:13 GMT)
  * The permanent? dump info page is https://dumps.wikimedia.org/enwiki/20170720/. 
  * The download was saved to physikerwelt@mathosphere:/srv/reg/wikiFilter

### 2017-08-02
* Start running wikifilter script without arguments in physikerwelt@mathosphere:/srv/reg/wikiFilter

### 2017-08-03
* Filtering process completed (release v0.1)
* Discover false positives `<center` instead of `<ce`:[fix](https://github.com/physikerwelt/wikiFilter/commit/1f612080b3f85cb43a1bd5adf648a3997f9d42f0)
* restart filtering

### 2017-08-04
* Develop math tag extraction using [mathosphere](https://github.com/TU-Berlin/mathosphere/commit/df784c7e2dc9b7aca3f9db3489ea6923e42f70c9)

### 2017-08-08
* upload second version (release v0.2) processing time was <3h

### 2017-08-26
* Improve math tag extraction in mathosphere

### 2017-08-27
* Fix bugs in chemistry extraction

### 2018-01-20
* Add dataset of all formulae to (v0.3)
