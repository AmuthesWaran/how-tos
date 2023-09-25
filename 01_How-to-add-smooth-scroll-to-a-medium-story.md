# How to add smooth scroll to a medium story?

To add a smooth scroll to a medium story i.e to use hyperlink to scroll to a particular section of a blog, find the id of the section you like to scroll.

In your blog right on the section where you want scroll and select inspect to find the id of the html tag

![finding-id-of-a-section-using-devtools-medium](https://github.com/AmuthesWaran/how-tos/assets/79437368/c620e7d4-b4b6-45be-8edd-b8f5b29e975d)

In the above, image for the section Step 1: .. the id for the p tag is 0317

Now this id along with # in the front (like #0317) is suppose to be added as hyperlink as below


![adding-id-to-hyperlink-to-smooth-scroll](https://github.com/AmuthesWaran/how-tos/assets/79437368/1adb1b54-4f56-40c1-b1b4-2e95286dcfa1)


Result:

![smooth-scroll-in-a-medium-blog-using-hyperlink-with-section-id](https://github.com/AmuthesWaran/how-tos/assets/79437368/a3aff945-e3a0-4a31-bdf7-7f709e2dc777)


Note: To find the id of the section tag (in my case it is a p tag) you have to
* First post your story publically
* Find id you the section in your posted story
* And now edit your posted story and add the hyperlink of the id to the text

| Description  | Hyperlink |
|:---|:---|
| Link to a paticular section | [Step 1: VS code Extension Pack for Java](https://medium.com/@amutheswaran/java-setup-on-vs-code-windows-4747964402b7#0317) |
| Medium story link  |[Java Setup on VS Code (Windows)](https://medium.com/@amutheswaran/java-setup-on-vs-code-windows-4747964402b7) |
