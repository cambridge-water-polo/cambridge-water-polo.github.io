---
layout: page
title: Posts
date: 2018-05-28
permalink: "/posts/"
---

A quick guide on how to make a blog post on CWP's website via [Github](https://github.com/cambridge-water-polo/cambridge-water-polo.github.io)...

<br>

### Step 1
Go to [Posts](https://github.com/cambridge-water-polo/cambridge-water-polo.github.io/tree/master/_posts) and make sure you are signed in to Github if you aren't already.
- Username: cwpolo
- Password: Check your email or [ask Tyler](mailto:tlee753@gatech.edu)

<br>

### Step 2
Click on `Create New File` in the right corner.

<br>

![Create New File Demo](/assets/images/posts/create-new-file-demo.png)

<br>

### Step 3
Name the file using the text input box at the top of the page using the following format:

<br>
`YYYY-MM-DD-lowercase-short-title.md`
<br><br>

where `YYYY` is the four digit year, `MM` is the full month, `DD` is the full day, and `lowercase-short-title` is a simple, short, all lowercase title for the post. This title won't appear on the site, its just a file name.

<br>

![Naming File Demo](/assets/images/posts/naming-file-demo.png)

<br>

![Example of Other Posts](/assets/images/posts/example-of-other-posts.png)

Here are some examples of other post names for reference...

<br>

### Step 4
Copy and paste the following header into the main text input box:

<br>
```YAML
---
layout: post
title: TITLE YOU WANT TO APPEAR ON THE WEBSITE
date: 20YY-MM-DD
category: Game / Announcements / Awards
author: YOUR NAME
---
```
<br>

![Pasting Header Demo](/assets/images/posts/pasting-header-demo.png)

<br>

Now fix the capatilized text to match what you want the post to say and choose a category. You can create your own but eventually posts will be sortable by categories so these simple few are better, message [Tyler](mailto:tlee753@gatech.edu) if you think there should be more. Also remember you are already adding the date so time is not relevant in categorization.

<br>

![Fixing Header Demo](/assets/images/posts/fixing-header-demo.png)

<br>

### Step 5
Using the markdown language, create your article. The basics elements of markdown you will need are headers, text, breaks, links, and images. Remember that the title, date, and author are automatically added so you don't need to add those items. You can create the basic elements using the following syntax:

<br>

`### 3 pound symbols makes a header`
### 3 pounds symbols makes a header

<br>

`For text you don't need any special syntax, just type.`
<br>
For text you don't need any special syntax, just type.

<br>

`<br>`
<br>
Breaks create spacing between elements...
<br>
...like this.

<br>

`[Link to Google](https://google.com)`
<br>
[Link to Google](https://google.com)
<br>
For a link just create brackets of what you want the link to say (Typically a "Click here" where here is linked) followed by parenthesis with the actually link URL. This keeps long URL's from being seen on the website.

<br>

`![CWP Logo](/assets/images/logo.png)`
<br>
<img src="/assets/images/logo.png" width="30" height="30" alt="CWP Logo">
<br>
Images are exactly the same as links except they begin with an exclamation point. For images that aren't on the internet already (basically any picture you take) you will need to read step 6 for uploading images to the site.

<br>

### Step 6
To add your own images, you must first upload them to Github, then you can link to them as usual. Add images to your post via the [images folder](https://github.com/cambridge-water-polo/cambridge-water-polo.github.io/tree/master/assets/images) and clicking on `Upload files`

<br>

![Upload Files Link Demo](/assets/images/posts/upload-files-link-demo.png)

<br>

![Upload Files Demo](/assets/images/posts/upload-files-demo.png)

<br>

### Step 7
To view the result, fist click `Commit new file` at the bottom of the page.

<br>

![Commit Change Demo](/assets/images/posts/commit-changes-demo.png)

<br>

The post will now appear on the site after a few minutes. Go to the Cambridge Water Polo [News Page](http://cambridgewaterpolo.com/news/) and click on your new post. To edit the post, go back to the [posts page](https://github.com/cambridge-water-polo/cambridge-water-polo.github.io/tree/master/_posts) on Github, clicking your post, and clicking the `Edit This File` option in the right corner. Don't forget to commit your post at the bottom of the page once your done editing.

<br>

![Edit This File Demo](/assets/images/posts/edit-this-file-demo.png)