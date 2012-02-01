!SLIDE

# Why Ruby? #

Collection of many great ideas



!SLIDE

Blocks

!SLIDE

# unless

cares enough to provide this equiv to if !...



!SLIDE

# Culture of Testing #

care deeply about testing

Code to Test Ratio: 1:1.3


!SLIDE



if i want to use other peoples code I can run their tests, and know I
didnt break something

smoothes collaboration


!SLIDE

insert users_controller code

no restrictions on spacing
dont have to squash my key=value

!SLIDE

# Powerful features #

.notes code 

!SLIDE

![](img/web_app_in_rails.jpg)

.notes it makes me happy 

!SLIDE

* concise
* succinct
* get the job done.

.notes focus on the task & forget about the magic rules of the language

!SLIDE

# "Ruby is designed to make programmers happy" #
## - matz ##


!SLIDE

# Freedoms #

* More than one way to skin a cat
* Monkey Patching

.notes contrast python philosophy
.notes dont need to recompile the language


!SLIDE code

  "octopus".pluralize          # => "octopi"
  "sheep".pluralize            # => "sheep"

.notes monkey patch to String


!SLIDE code

class Array

  def second
    self[1]
  end

  def forty_two
    self[41]
  end
  

.notes someone cared enough to want to read .second instead of [1]


!SLIDE

# Level playing field #

.notes unwashed masses
.notes doesn't patronize you or treat you like you're stupid
.notes when was the last time static typing saved your day?


!SLIDE

# "Should we outlaw rope just because people can hang themselves with
it?"

##- David Hansson 

.notes learning through experience


!SLIDE

## The very fact that it's possible to write messy programs in Perl is also what makes it possible to write programs that are cleaner in Perl than they could ever be in a language that attempts to enforce cleanliness. ##
### - Larry Wall


# 


