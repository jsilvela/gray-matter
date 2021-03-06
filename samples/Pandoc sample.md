% Pandoc Tests
% Philip Belesky
% 2000-01-01

## Pandoc Tests

### Inline formatting

This ~~is deleted text.~~

H~2~O is a subscript example.  2^10^ is a superscript example.

This is an [Internal Link](#intrduction).

### Footnotes

Here is a footnote reference,[^1] and another.[^longnote] TODO: square brackets and inline text should be gray here.

Here is an inline note.^[Inlines notes are easier to write, since
you don't have to pick an identifier and move down to type the
note.] TODO: square brackets and inline text should be gray here.

[^1]: Here is the footnote. TODO: square brackets and in-square text should be gray here.

[^longnote]: Here's one with multiple blocks.

    Subsequent paragraphs are indented to show that they
belong to the previous footnote.

### Citations

Blah blah [see @doe99, pp. 33-35; also @smith04, ch. 1].  TODO: square brackets and in-square text should be gray here.

Blah blah [@doe99, pp. 33-35, 38-39 and *passim*].

Blah blah [@smith04; @doe99].

@smith04 says blah.

@smith04 [p. 33] says blah.

### Line blocks

| The limerick packs laughs anatomical
| In space that is quite economical.
|    But the good ones I've seen
|    So seldom are clean
|         And the clean ones so seldom are comical

### Fancy lists

#. one
#. two

### Sequential lists

(@)  My first example will be numbered (1).
(@)  My second example will be numbered (2).

Explanation of examples.

(@)  My third example will be numbered (3).

### Tables

  Right     Left     Center     Default
-------     ------ ----------   -------
     12     12        12            12
    123     123       123          123
      1     1          1             1

Table:  Demonstration of simple table syntax.

: Sample grid table.

+---------------+---------------+--------------------+
| Fruit         | Price         | Advantages         |
+===============+===============+====================+
| Bananas       | $1.34         | - built-in wrapper |
|               |               | - bright color     |
+---------------+---------------+--------------------+
| Oranges       | $2.10         | - cures scurvy     |
|               |               | - tasty            |
+---------------+---------------+--------------------+

## End of Document



