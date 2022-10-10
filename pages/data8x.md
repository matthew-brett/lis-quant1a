Our course uses material from the [Berkeley 2019 EdX course on data
science](https://courses.edx.org/courses/course-v1:BerkeleyX+Data8.1x+1T2019/course).
When you click on the link above, EdX will ask you to register for a free
account:

![](../file_contents/course%20files/images/data8x_register.png)

Next, the interface should ask you to "Enroll" on the course:

![](../file_contents/course%20files/images/data8x_enroll.png)

Once you have clicked on "Enroll", you should see a screen like this:

![](../file_contents/course%20files/images/data8x_initial.png)

Note that the course finished in 2019, so you are reviewing the materials from
a 2019 course, that is no longer running.

Here are some notes on using the course.  **Please skip-read the rest of this
page before using the course, so you can see which errors can occur**.

## Git clone error

If you run the interactive (notebook) exercises, you may get an error like the
following:

```
git clone --depth 1 --branch master git://reposync/materials-x18
/home/jovyan/materials-x18
Cloning into '/home/jovyan/materials-x18'...
fatal: Unable to look up reposync (port 9418) (Name or service not known)
```

It will likely look like this:

![](../file_contents/course%20files/images/data8x_error.png)

To fix the error, open a new tab in your web browser, and go to this link:

<https://hub.data8x.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com/data-8%2Fmaterials-x19>

After a bit, you should see something like this:

![](../file_contents/course%20files/images/data8x_materials.png)

Now you should be able to go back to whichever exercise was causing the
original error, and try again, expecting it to succeed.
