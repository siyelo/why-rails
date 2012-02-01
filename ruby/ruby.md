
!SLIDE subsection

# The Ruby Language


!SLIDE

## Code is meant to be understood by human beings


!SLIDE

# Hello World
## c

    @@@ c
    #include <stdio.h>

    int main(void) {
        printf(“Hello, World!“);
        return 0;
    }

!SLIDE

# Hello World
## Java

    @@@ java
    class HelloWorld
    {
        public static void main(String args[])
        {
            System.out.print(“Hello, World!“);
        }
    }


!SLIDE
# Hello World
## PHP

    @@@ php
    <?php
      print "Hello world!";
    ?>


!SLIDE
# Hello World
## Ruby

    @@@ ruby
    print "Hello World!"

.notes also perl/python

!SLIDE

# Ruby 

* Conservative
* Concise
* Flexible
* Good elements of Perl/Python/Smalltalk

.notes Collection of many great ideas. OO, Functional, Reflective,
uses conventions,


!SLIDE

# Conservative

    @@@ ruby
    if n < 10
      return true
    else
      return false
    end

.notes sticks to what programmers are familiar with


!SLIDE

# Concise

    @@@ruby
    print total unless total == 0


!SLIDE

## "Because there is a definite cost involved in scanning code with the human eye, programs should ideally contain no unnecessary information."
###- 'Matz'

.notes Yukihiro Matsumoto, programmers are expensive


!SLIDE

# Flexibility

* More than one way to "skin a cat"
* freely alter/patch core parts of Ruby
* even at runtime!

.notes reflective - allowing metaprogramming


!SLIDE

## "Should we outlaw rope just because people can hang themselves with it?"
###- David Hansson

.notes learning through experience


!SLIDE

# Culture of Testing #

    @@@
    $ rake stats
      ...
      Code to Test Ratio: 1:1.3

.notes rubyists care deeply about testing, I can run their tests, share with confidence


!SLIDE

## "Ruby is designed to make programmers happy" #
### - matz ##

![](simple_jack.jpg)


