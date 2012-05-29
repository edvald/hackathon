Startup Iceland Hackathon - CLARA
=========

##Background
CLARA provides companies with powerful tools to help them analyze discussion within communities. Our biggest clients are video game developers and publishers looking to understand the communities surrounding their video games. To accomplish this, CLARA gathers massive amounts of online discussion data from various sources, including forums, social media and blogs. Every article or post is analyzed by CLARA’s text mining engine to extract, for example, the most prevalent phrases, topics and sentiment (whether the posts appear positive, negative or neutral). The data being processed by CLARA, largely unstructured text, is generally very noisy and challenging to work with. Natural language processing (NLP) aims to make sense of this type of data, and it is at the heart of what CLARA does.

##Our challenge
Largely the point of doing text mining is to derive actionable information from a lot of articles without having to read them all individually. Thus we turn to visualization to summarize and show at a glance highlights of the data in question. Because of the complex and noisy nature of natural language, using simple charts and graphs rarely accomplishes this, making this one of the many challenging subjects in the field of text mining.

Word clouds (or tag clouds) are a very common method of showing the most common words from a set of articles. However, they are in fact of limited value, aside from being aesthetically pleasing (sometimes, at least). This is primarily because they do not show the context of the individual words or how they relate to one another.

The challenge we present is to come up with an innovative way to display the most common words in a set of articles along with their context, in a reasonably compact format (one that will at least fit on an average computer screen). It can be dynamic or static, beautiful or pragmatic, simple or complex, just as long as it has a clear use case and helps the user to understand the underlying content. Ideally the solution would be browser based, and the use of standardized web technologies (HTML5, SVG, Javascript etc.) is encouraged over proprietary solutions like Flash or Silverlight.

##Tools & APIs
The Python NLTK (Natural Language Toolkit, http://nltk.org/) and LingPipe (http://alias-i.com/lingpipe/) are two very useful sets of tools for processing natural language, written in Python and Java, respectively. They both provide tools for rudimentary NLP tasks such as tokenization (splitting text into words), part-of-speech tagging, grammatical parsing, as well as more complex operations such as classification and clustering. The NLTK front page shows a quick example of how to tokenize text, which will be useful for the above challenge.

##Data
Various test data sets can be found online. A good start might be Reuters-21758, a set of news articles in plain text format: http://www.daviddlewis.com/resources/testcollections/reuters21578/. 