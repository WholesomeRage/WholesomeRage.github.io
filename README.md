# Wholesome Rage

Wholesome Rage is owned and operated by the Australian author Ross James.

It updates Wednesday with articles on subjects ranging from science, economics, politics, history and writing advice.

# Figment's Documentation

## How to post

This part's simple.

Every article to be posted to the site must include the following YAML header prior to the actual written part of the article:

```
---
layout: "post"
title: Title Of Article
date: 2017-12-13 20:12:00 -0700
author: Wholesome Rage
categories: [Writing Advice]
excerpt_separator: <!--more-->

# Contributor stuff
contributor: false
---
```
Let's break down the most important bits.

### Date

The `date` field must be formatted exactly as shown above (`YEAR-MONTH-DAY HOUR:MINUTE:SECOND TIMEZONE`). Hours are to be formatted in military time. Seconds can just be left as `00`.

### Categories

I insist that you always tag your articles with an appropriate category (even multiple appropriate categories). This is so that users won't have to dig into your site just to find an article, since they'll all be accessible from the Categories Index page. Some of the ones currently available are:

```
Writing Advice
Media
Politics
Economics
Guest Article
Audio
Anecdotes
```

Categories must be written in the YAML header as `categories: [Category1, Category2, Category3]`. Every time you add a category that isn't already written, Jekyll will *automatically* add that as a new category, so you don't have to worry about fiddling with any code. 

### Excerpt Separator

I know you used small descriptions on the former site, but on this site you need to use the excerpt separator. 

This tells Jekyll what part of the article to display on the main page, as a sort of lead in for the rest of the article. It is defined as `<!--more-->`, and functions as a cutoff. The paragraphs prior to it will be displayed on the home page, but the rest won't be. 

**If you do not put this separator in your document, the home page will render the entire thing**. I cannot stress this enough. It's important to use it. 

### Contributors

If an article is by a Guest Writer, it will need two things:

1. The `Guest Article` category
2. The `contributor` flag set to `true`

This tells Jekyll to format the article with an `About The Author` section at the bottom. It'll try and match the author to any preexisting authors listed in `_data/contributors.yml`, and display the information listed there.

If you're gonna feature a new author, please make sure their info is put inside the `contributors.yml` file in the same format as the rest of the entries. That way Jekyll knows who to display. 

### Writing the actual article

After you've taken care of business with the YAML header, you can start writing. Text must be formatted in [Markdown](https://commonmark.org/help/). You should already be familiar with it, since it's the same syntax you use on Discord. Most everything in the guide I just linked can be utilized. 

Once you've finished writing, save the Markdown file in the `_posts` folder. **Your document's filename must be in the following format: `YEAR-MONTH-DAY-name-of-post.md`**. This is crucial. If the filename is not formatted like this, Jekyll will throw up errors and you won't be able to see your article. 

## Some special things

### Images

If you want to embed multiple images on the same line, make sure you wrap those images like so:

```
<div class="images" markdown="1">
![image1](imagelink.gif)

![image2](imagelink.png)
</div>
```

By doing this, Jekyll will display the images side by side so it looks a lot nicer in the article. 

A good thing for practice, too, is that **all images should be stored in the `assets/images` location, in a folder specific to that article**. This is not for Jekyll's sake, but more for your own organization. To access those images in your documents, simply preface your image tags like so:

```
![image3](/assets/images/article_folder/image.jpg)
```

You can also use off-site hosting images by simply replacing the path in the parentheses with a URL, like

```
![image4](https:/i.imgur.com/some_image.gif)
```

### Audio

Whenever you want to upload your audio to the site, make sure the audio file is stored in `assets/audio`. Whether or not you want to put it in an article-specific folder is up to you. 

Then, when you want to use the file, simply insert `{% include audio.html name="audio_file.mp3" %}` in your document, and Jekyll will take care of the rest. **Make sure you put it in the `assets/audio` folder, because Jekyll is hardcoded to look for it there**. 

### Video

If the thing you want is on YouTube, just grab the embed code from the video's sharing options on YouTube itself. Then just copy and paste it into your article and you're done. 

## Questions/Concerns?

Just notify me (Figments) if you're having any trouble and I'll help in any way I can. You know how to reach me.
