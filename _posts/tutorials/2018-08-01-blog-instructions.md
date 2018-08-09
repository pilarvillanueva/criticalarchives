---
layout: post
title: "Publishing a Digital Review"
modified:
categories: tutorial
excerpt: In this course, you will be invited to share a critical reflection with the public on this course website.  
tags: []
author: halperta
image:
  feature:
---
In this course, you will be asked to write and publish a critical review of a digital collection, using this course website as a platform ([more info](../../assignments)). 

You can write your post in a text editor or directly on GitHub. For instructions, open the tutorial for writing in markdown.

To publish your post, you will need to learn how to:
* Create a GitHub account
* Create an author ID
* Make a pull request (to push your changes to the website)
* Request a review

## Step 1: Creating a GitHub account
1. GitHub is an online platform for creating and sharing code. It is owned by Microsoft. You can create a GitHub account here:  
[https://github.com/](https://github.com/)  
2. After you create an account, you'll need to verify your email before moving on to the next step.  

## Step 2: Create an author ID.
You'll need to create an author ID for the website so that your review can be attributed properly. To do this, follow these steps [[video](https://youtu.be/_qW6x1Uetxw)]:

1. Log in to GitHub and navigate to:  
[https://github.com/halperta/criticalarchives/blob/gh-pages/_data/authors.yml](https://github.com/halperta/criticalarchives/blob/gh-pages/_data/authors.yml)
2. **Important:** Make sure the branch has been changed from `master` to `gh-pages`. To do this, find the drop-down menu that says "branch" near the top left of the page, and select `gh-pages.`
3. **Open the file for editing**: click on the pen icon in the upper right corner of the screen. 
4. **Create a biographical entry:** copy someone else's entry and paste it at the bottom of the document, replacing their information with your own info. At the very least, you should add a single-word author id, as well as your name. If you want to have a photograph of yourself to link to the page, enter the file name of the image, including the extension, under "avatar." It should look something like this:  

    authorid: oneword  
       name: Enter Name Here  
       email: email@utexas.edu  
       bio:  
       avatar:  image.jpg  
       twitter:  handle
       google:  
         plus:  

5. **Commit your changes:** Once you've added your own author entry to the file, "propose the file change."  
	1. At the bottom of the page, in the text block where it says "Update authors.yml," enter a brief description of your proposed change. It should be something like: `Added author: Hannah Alpert-Abrams.`  
	2. Click "propose file change."

6. **Merge your changes:** Select "Create Pull Request" to propose your changes. We'll check and approve your changes before the modification goes live.

*7. (Optional): If you want to include an author photo, please email it to Hannah for uploading!*

## Step 3: Upload your review 
1. **Log in to GitHub** and navigate to: [https://github.com/halperta/criticalarchives/tree/gh-pages/_posts/blog](https://github.com/halperta/criticalarchives/tree/gh-pages/_posts/blog)  
2. **Confirm location**: Make sure that you are in the `gh-pages` branch (upper left corner).
3. **Create file**: In the upper right corner, click on the button that reads `create new file`.
4. **Name your file** using the current date. The name should be `YYYY-MM-DD-short-title.md` . For example, this tutorial is named `2018-08-01-blog-instructions.md`
5. **Copy and paste** the text of your review into the text box. Use the `preview` tab (just to the right of the `edit new file` tab) to see what your post will look like. (*Note: If you feel comfortable on GitHub, you can write your review directly into this text editor.*)
6. **Save** the text of your review on GitHub by "proposing a file":
	1. At the bottom of the page, in the text block where it says "Create filename.md," enter a brief description of your proposed change. It should be something like: "Posting review by Hannah Alpert-Abrams." 
	2. Click "propose file change." This will create what's known as a fork (basically a copy) of the website in your own GitHub account. When you're ready to publish, you'll merge your fork back into the website.
7. **Continue editing:** this can be a bit complicated, so follow these constructions if you want to go back to your post later.
	1. Navigate to github.com
	2. On the left of the screen you'll see a list of repositories. (note: there are other ways to find your repositories, they all work.)
	3. One of the repositories should be called something like . This is your "fork" of the course website.
	4. Open the `yourusername/criticalarchives` repository and open the `_posts/blog` directory. At this point you should see the posts that are currently on the course website.
	5. Using the drop-down menu in the upper left corner, change the branch from "master" to "patch-1". (Note: if you've made more than one fork, you may see more than one patch: pick the highest number.)
	6. You should now see the file you created. You can click on that file to open it, and then use the edit button (the pen) to make changes. 
	7. Once you have made your changes, save the changes by using the "commit changes" form at the bottom of the page. Write a brief message describing your changes (for example: `fixed broken link.`)

## Step 4: Request a review
1. Email your reviewer to alert them that your post is ready to review. Include the URL to the GitHub page where the post is located. (i.e. `https://github.com/username/criticalarchives/blob/patch-1/_posts/blog/testblog1.md`)
2. **Revise your review:** Once you have received comments from your reviewer, you can make revisions to your original file, following the same steps you used to edit the file previously:
	1. Navigate to github.com
	2. On the left of the screen you'll see a list of repositories. (note: there are other ways to find your repositories, they all work.)
	3. One of the repositories should be called something like . This is your "fork" of the course website.
	4. Open the `yourusername/criticalarchives` repository and open the `_posts/blog` directory. At this point you should see the posts that are currently on the course website.
	5. Using the drop-down menu in the upper left corner, change the branch from "master" to "patch-1". (Note: if you've made more than one fork, you may see more than one patch: pick the highest number.)
	6. You should now see the file you created. You can click on that file to open it, and then use the edit button (the pen) to make changes. 
	7. Once you have made your changes, you can "commit the changes" using the form at the bottom of the page. Write a brief message describing your changes (for example: "began copyediting review," "reformatted headings," or "completed copyediting").
 
## Step 5: Merge your changes
1. Navigate to your forked repository. You can do this by navigating to your profile, opening the `repositories` tab, and then selecting the `critical archives` repository. You can also follow the URL directly: it should be something like `https://github.com/username/criticalarchives`.
2. At the top of the page, you should see a highlighted alert showing your `recently pushed branches.` Click the green tab that says `Compare & Pull Request.`
3. **Open a pull request:** Make sure that the *base fork* is `halperta/criticalarchives`, the *base* is `gh-pages`, the *head fork* is `yourusername/criticalarchives`, and *compare* is `patch 1`.
4. In the comment box, write: `submitting review for publication by Your Name`
5. Click `Create Pull Request`.



