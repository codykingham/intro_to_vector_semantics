# Keyword in Context (KWIC) Example with "War of the Worlds"

This directory contains code used to produce a KWIC example for the Lorentz 2020 slideshow. You can reproduce this example if you have `ptx` installed on your machine.

## Prequisites

Check that you have `ptx` by entering `which ptx` from command line. If you see "ptx not found", you will need to install it somehow. 

If you are on a Mac system, you can use homebrew to install ptx by entering:
`brew install coreutils`. See the discussion [here](https://gist.github.com/skyzyx/3438280b18e4f7c490db8a2a2ca0b9da) for background on this.

## Producing KWIC examples

1. Download the text of War of the Worlds by HG Wells (or other text you want to search): [http://www.gutenberg.org/files/36/36-0.txt](http://www.gutenberg.org/files/36/36-0.txt)
2. Place the file in this directory with the title "war_of_worlds.txt"
3. Run the "kwic.sh" script by typing into command line: `sh kwic.sh`
4. Browse the .txt results

## Change search terms

Modify the file `get_words` to choose which words to find. Each word should be on its own line.

## Further reading

See the [ptx documentation](https://www.gnu.org/software/coreutils/manual/html_node/ptx-invocation.html#ptx-invocation) for more.
