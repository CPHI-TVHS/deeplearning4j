# Notes

## From Glenn email

The full code is here:

https://github.com/eclipse/deeplearning4j

It’s huge, and if you try to put everything in Eclipse, it may take a while. And you’ll be building stuff you will probably never use.  I recommend downloading the examples here:

https://github.com/eclipse/deeplearning4j-examples

and importing one of them (like dl4j-examples) into Eclipse for testing.  The example files seem to pull down the source when built with Maven in Java, so you can look at just the source you need that way.  It has a word2vec example there.  You can create a FastText instance using FastText.build()…parameterMethods() in place of one of the word2vec examples.
