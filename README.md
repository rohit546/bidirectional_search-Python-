# bidirectional_search-Python-

graph = {html: [head, body],
head: [title],
body: [h4, ul],
title: [text],
h4: [text],
ul:[li],
li: [a],
a: [text] }
In web crawling, depth-limited search can be applied to explore web pages and
build an index while limiting the depth of the crawl to avoid excessive resource
consumption. Use depth limited search in this task to do web crawling to search for
the text. Create graph using dictionary.
Also find out the time complexity and space complexity of this problem. Display
the complete path upon reaching a goal state. Here goal is the “text”. Take input of
the graph using file handling.
