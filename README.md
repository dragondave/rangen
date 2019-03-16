# rangen
Random generator for proceedurally generated stories.

`data["root"]` is special: it's the overarching structure of the story as a whole.

Each `data` entry is essentially a list of different chunks of text the generator might pick: some of them will have words in {squiggly brackets}. These will be replaced with a random selection of one of the text chunks from the relevant `data` entry.

`duplicates` is special: essentially, giving a potentially different random selection from another list.
