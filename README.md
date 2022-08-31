# Twelve Days Coding Exercise

In this exercise, you will create a ruby class and method that outputs the lyrics to the traditional English Christmas carol ["The Twelve Days of Christmas"](https://en.wikipedia.org/wiki/The_Twelve_Days_of_Christmas_(song)) (complete lyrics below).

In this song, each verse is built on top of the previous verses in a repeating pattern. Can you use Ruby to build up the repeated lyrics programmatically?

```text
On the first day of Christmas my true love gave to me: a Partridge in a Pear Tree.

On the second day of Christmas my true love gave to me: two Turtle Doves, and a Partridge in a Pear Tree.

On the third day of Christmas my true love gave to me: three French Hens, two Turtle Doves, and a Partridge in a Pear Tree.

On the fourth day of Christmas my true love gave to me: four Calling Birds, three French Hens, two Turtle Doves, and a Partridge in a Pear Tree.

On the fifth day of Christmas my true love gave to me: five Gold Rings, four Calling Birds, three French Hens, two Turtle Doves, and a Partridge in a Pear Tree.

On the sixth day of Christmas my true love gave to me: six Geese-a-Laying, five Gold Rings, four Calling Birds, three French Hens, two Turtle Doves, and a Partridge in a Pear Tree.

On the seventh day of Christmas my true love gave to me: seven Swans-a-Swimming, six Geese-a-Laying, five Gold Rings, four Calling Birds, three French Hens, two Turtle Doves, and a Partridge in a Pear Tree.

On the eighth day of Christmas my true love gave to me: eight Maids-a-Milking, seven Swans-a-Swimming, six Geese-a-Laying, five Gold Rings, four Calling Birds, three French Hens, two Turtle Doves, and a Partridge in a Pear Tree.

On the ninth day of Christmas my true love gave to me: nine Ladies Dancing, eight Maids-a-Milking, seven Swans-a-Swimming, six Geese-a-Laying, five Gold Rings, four Calling Birds, three French Hens, two Turtle Doves, and a Partridge in a Pear Tree.

On the tenth day of Christmas my true love gave to me: ten Lords-a-Leaping, nine Ladies Dancing, eight Maids-a-Milking, seven Swans-a-Swimming, six Geese-a-Laying, five Gold Rings, four Calling Birds, three French Hens, two Turtle Doves, and a Partridge in a Pear Tree.

On the eleventh day of Christmas my true love gave to me: eleven Pipers Piping, ten Lords-a-Leaping, nine Ladies Dancing, eight Maids-a-Milking, seven Swans-a-Swimming, six Geese-a-Laying, five Gold Rings, four Calling Birds, three French Hens, two Turtle Doves, and a Partridge in a Pear Tree.

On the twelfth day of Christmas my true love gave to me: twelve Drummers Drumming, eleven Pipers Piping, ten Lords-a-Leaping, nine Ladies Dancing, eight Maids-a-Milking, seven Swans-a-Swimming, six Geese-a-Laying, five Gold Rings, four Calling Birds, three French Hens, two Turtle Doves, and a Partridge in a Pear Tree.
```

A note on testing: This exercise does not include an extensive set of test cases. Instead, there is a single "acceptance" test to make sure that the final output is correct. A file called `song.txt` is included with the exercise, but this file is only to be used for the acceptance test to validate the solution, not as part of the solution itself. Do not simply import the song.txt into your `twelve_days.rb` file and export it again to get the test to pass. While we do think that is a clever and quick solution, that is not the goal of this exercise. We want to see you demonstrate your problem solving and coding skills!

* * * *

You will need `ruby` installed on your machine to do this exercise. The current ruby-version set for this exercise is `3.0.3`, but you can change the version in `.ruby-version` if you need to.

For running the tests provided, you will need the Minitest gem. Open a
terminal window and run the following command to install minitest:

    gem install minitest

Run the tests from the exercise directory using the following command:

    ruby twelve_days_test.rb

You should see the test output in the console.

Good luck!

## Source

Wikipedia [http://en.wikipedia.org/wiki/The_Twelve_Days_of_Christmas_(song)](http://en.wikipedia.org/wiki/The_Twelve_Days_of_Christmas_(song))
