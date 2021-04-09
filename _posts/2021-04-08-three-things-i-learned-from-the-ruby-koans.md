---
layout: post
title: Three things I learned from The Ruby Koans
---

Here are (at least) three things I learned from [The Ruby Koans](http://rubykoans.com/):

1. The similarity and interactions amongst symbols and strings.

2. How raising errors work (i.e. NoMethodError). This included how assert_raise works. This is similar to begin/rescue/end, which I utilized in AppDevI, so I can still run the program despite the code error.

3. The similarities between Python and Ruby for object oriented programming and interactions between classes

4. You can set the default value for a hash (i.e. a =[] then **h = Hash.new(a)** then if you add an element, the default value is the array.

5. Super is a means of searching for ancestors to find something with the same name, which allows you to not use the .self method

6. Methods with ! mean it modifys what it's called on and ones with ? yield a true or false 
