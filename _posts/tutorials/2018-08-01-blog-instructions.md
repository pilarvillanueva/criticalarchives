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
You'll need to create an author ID for the website so that your review can be attributed properly. To do this, follow these steps:

1. Log in to GitHub and navigate to:  
[https://github.com/halperta/criticalarchives/blob/gh-pages/_data/authors.yml](https://github.com/halperta/criticalarchives/blob/gh-pages/_data/authors.yml)
2. **Important:** Make sure the branch has been changed from `master` to `gh-pages`. To do this, find the drop-down menu that says "branch" near the top of the page, and select `gh-pages.`
3. Open the file for editing by selecting the pen icon in the upper right corner of the screen. 
4. Create a biographical entry by copying someone else's and pasting it at the bottom of the document, replacing their information with your own info. At the very least, you should add a single-word author id, as well as your name. If you want to have a photograph of yourself to link to the page, enter the file name of the image, including the extension, under "avatar." It should look something like this:  

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

6. **Merge your changes:** Select "Create Pull Request" to propose your changes. The admin will approve your changes before the site goes live.

*7. (Optional): If you want to include an author photo, please email it to Hannah for uploading!*

## Step 3: Upload your review 
1. **Log in to GitHub** and navigate to: [https://github.com/halperta/criticalarchives/tree/gh-pages/_posts/blog](https://github.com/halperta/criticalarchives/tree/gh-pages/_posts/blog)  
2. Make sure that you are in the `gh-pages` branch (upper left corner).
3. In the upper right corner, click on the button that reads `create new file`.
4. **Name your file** using the current date. The name should be `YYYY-MM-DD-short-title.md` . For example, this review is named `2018-08-01-blog-instructions.md`
5. **Copy and paste** the text of your review into the text box. Use the `preview` tab (just to the right of the `edit new file` tab) to see what your post will look like.
6. **Save** the text of your review on GitHub by "proposing a file":
	1. At the bottom of the page, in the text block where it says "Create filename.md," enter a brief description of your proposed change. It should be something like: "Posting review by Hannah Alpert-Abrams." 
	2. Click "propose file change."
7. **Continue editing:** this can be a bit complicated, so follow these constructions if you want to go back to your post later.
	1. Navigate to your GitHub profile.
	2. Open the `repositories` tab.
	3. You should see a list of repositories, including one that is called "Critical Archives." The description should say that it was forked from halperta/criticalarchives 
	4. Open that repository and navigate to /posts/blog/
	5. Change the branch to "patch-1" using the drop-down menu, and you should see your file.
	6. To make changes, open the file, then use the edit button (the pencil) in the upper-right-hand corner. 
	7. Once you have made your changes, you can "commit the changes" using the form at the bottom of the page. Write a brief message describing your changes (for example: `fixed broken link.`)

## Step 4: Request a review
1. Email your reviewer to alert them that your post is ready to review. Include the URL to the GitHub page where the post is located. (i.e. `https://github.com/username/criticalarchives/blob/patch-1/_posts/blog/testblog1.md`)
2. **Revise your review:** Once you have received comments from your reviewer, you can make revisions to your original file... if you know where it is. It can be a little tricky to find, so follow these instructions:
	1. Navigate to your GitHub profile.
	2. Open your repositories
	3. You should see a list of repositories, including one that is called "Critical Archives." The description should say that it was forked from halperta/criticalarchives 
	4. Open that repository and navigate to /posts/blog/
	5. Change the branch to "patch-1" and you should see your file.
	6. To make changes, open the file, then use the edit button (the pencil) in the upper right hand corner. 
	7. Once you have made your changes, you can "commit the changes" using the form at the bottom of the page. Write a brief message describing your changes (for example: "began copyediting review," "reformatted headings," or "completed copyediting").
 
## Step 5: Merge your changes
1. Navigate to your forked repository. You can do this by navigating to your profile, opening the `repositories` tab, and then selecting the `critical archives` repository. You can also follow the URL directly: it should be something like `https://github.com/username/criticalarchives`
2. At the top of the page, you should see a highlighted alert showing your `recently pushed branches.` Click the green tab that says `Compare & Pull Request.`
3. **Open a pull request:** Make sure that the *base fork* is `halperta/criticalarchives`, the *base* is `gh-pages`, the *head fork* is `yourusername/criticalarchives`, and *compare* is `patch 1`.
4. In the comment box, write: `submitting review for publication by Your Name`
5. Click `Create Pull Request`.



