# Make a Profile class

## The goal:

Today, we're learning about creating instances (individual versions) of classes (Types that we use as blueprints). This will unlock a lot of power for us later, but getting a class off the ground takes a lot of work.

Our end goal is to be able to create profiles for individual people, and then access and change the data we have about those people.
<br><br>

## Write an \_\_init__ method

Ultimately, we want to be able to create new profiles in our **test.py** file with lines of code that look like this:

```Python
first_profile = Profile("Nicki")
second_profile = Profile("Sarah")
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
