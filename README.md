# Word_Recognition_using_deep_CNN

Training a deep CNN model that can help in recognizing a word, i.e. given a word-image(image with a word present in it) as input, the model yields a representation that can help in recognising the word from a set of possible words (termed as 'lexicon' of words).<br>

There are two representations for a word:<br>
i)<b> Alpha representation:</b> This is based on the claim that a word can be represented in terms of occurences of characters in various segments of image<br>
ii)<b> Omega representation:</b> This is based on the claim that a word can be represented in terms of count of 11 primitve shapes present in various segments of image. The 11 shapes are: ascender, descender, left small semi-circle, right small semi-circle, left large semi-circle, right large semi-circle, circle, vertical line, diagonal line, diagonal line at a slope of 135 degrees, and horizontal line. <br>

We are gonna comapre these 2 representations and come to a conclusion which one perfoms better for our model both for recognizing words from the given 'lexicon' of words and for new words which the model hasn't seen yet.

