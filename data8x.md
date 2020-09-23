We will also be referring to material from the [Berkeley 2018 EdX course on
data
science](https://courses.edx.org/courses/course-v1:BerkeleyX+Data8.1x+1T2018/course).
When you click on the link above, EdX will ask you to register for a free account:

![](../file_contents/course%20files/images/data8x_register.png)

Next, the interface should ask you to "Enroll" on the course:

![](../file_contents/course%20files/images/data8x_enroll.png)

Once you have clicked on "Enroll", you should see a screen like this:

![](../file_contents/course%20files/images/data8x_initial.png)

Note that the course finished in 2018, so you are reviewing the materials from a 2018 course, that is no longer running.

Here are some notes on using the course.  **Please skip-read the rest of this
page before using the course, so you can see which errors can occur**.

## Git clone error

It's possible to run into an error like the following, when you try and run the interactive exercises:

```
git clone --depth 1 --branch master git://reposync/materials-x18
/home/jovyan/materials-x18
Cloning into '/home/jovyan/materials-x18'...
fatal: Unable to look up reposync (port 9418) (Name or service not known)
```

If you do, it will likely look like this:

![](../file_contents/course%20files/images/data8x_error.png)

To fix this, open a new tab in your web browser, and go to this link:

<https://hub.data8x.berkeley.edu/hub/user-redirect/git-pull?repo=git%3A%2F%2Fgithub.com/data-8%2Fmaterials-x18>

After a bit, you should see something like this:

![](../file_contents/course%20files/images/data8x_materials.png)

Now you should be able to go back to whichever exercise was causing the
original error, and try again, expecting it to succeed.

## Typo in Little Women "lec01" notebook

One of the very first notebooks has an error in the web address.  There is a code cell in the `lec01` notebook containing where the first line of code is:

```
little_women_url = 'https://www.inferentialthinking.com/chapters/01/3/little_women.txt'
```

In fact the URL in the first line is incorrect, and you will have to fix it, to make the code work correctly.  It should be:

```
little_women_url = 'https://www.inferentialthinking.com/data/little_women.txt'
```
