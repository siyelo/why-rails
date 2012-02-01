
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
## Ruby / Perl / Python

    @@@ ruby
    print "Hello World!"



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
    n < 10 ? true : false


!SLIDE

## "Because there is a definite cost involved in scanning code with the human eye, programs should ideally contain no unnecessary information."
###- 'Matz'

.notes Yukihiro Matsumoto, programmers are expensive


!SLIDE code

    @@@ruby
    print total unless total == 0


!SLIDE code

    @@@ruby
    3.times { print "ho " }   # => ho ho ho

.notes even simple data types, power, flexibility



!SLIDE

# Flexibility

## More than one way to skin a cat

.notes freely alter / redefine / aka monkeypatch


!SLIDE code

    > ["a","b"].second
      NoMethodError: undefined method `second'...
    
    >  class Array
         def second
           self[1]
         end
       end

    > ["a","b"].second    # => "b" 
    > ["a","b"][1]        # => "b"

.notes doesn't patronize you or force you to do things a certain way


!SLIDE code

    "octopus".pluralize          # => "octopi"
    "sheep".pluralize            # => "sheep"

.notes monkey patch the CORE String class


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




