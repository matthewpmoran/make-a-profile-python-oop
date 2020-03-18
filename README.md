# Make a Profile class

[![Run on Repl.it](https://repl.it/badge/github/upperlinecode/make-a-profile-python-oop)](https://repl.it/github/upperlinecode/make-a-profile-python-oop)

## The goal:

Today, we're learning about creating instances (individual versions) of classes (Types that we use as blueprints). This will unlock a lot of power for us later, but getting a class off the ground takes a lot of work.

Our end goal is to be able to create profiles for individual people, and then access and change the data we have about those people.
<br><br>

## Write an \_\_init__ method

Ultimately, we want to be able to create new profiles in our **test.py** file with lines of code that look like this:

```Python
first_profile = profile_class.Profile("Nicki")
second_profile = profile_class.Profile("Sarah")
```

In order for that code to work, you'll need to write an initializer method in our **profile_class.py** file for the Profile class - otherwise, Python has no idea what to do with the string "Nicki" when you call `Profile("Nicki")`. Try to do it on your own, but if you forget, click the dropdown to see one way to do it.

<details>
  <summary>Click to see an example of an __init__ method</summary>

  ```Python
  class Profile:
    def __init__(self, name):
      self.name = name
  ```

</details>
<br>
When you think you're ready to test your code, enter the command `python test.py` in terminal.
<br><br>

## Extensions
Your user profile currently only has a name. What other traits, attributes, or information might a user have on your site?

This is a pretty open-ended lab, so if you decide your social media site is a dating app for dogs, fine - your users might have some instance variables like `breed` and `fur_color`. You might go a totally different direction and create a college-matching application, in which case users might have traits like `gpa` and `grade`. The direction you go with this is up to you, but please make it a goal to include at least one instance variable for each of these four major datatypes:
* String
* Integer
* Float
* Boolean (True or False)

Be sure to initialize at least three unique users for your site. We already have Nicki and Sarah above, but you'll need to make at least one more. 
