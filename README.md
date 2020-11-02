# Hosting Resume On GitHub Page
Ever tired of uploading your resume PDF file for each and every job application ?  This README will help you solve your problem by giving you a full instruction how to create your own resume-website on GitHub Pages using GitHub Desktop, for free, without having to code. Moreover, while showing you simple steps of hosting a resume on GitHub, we will discuss about some fundamental concepts to create a great documentation base on Etter's popular book *Modern Technical Writing*. In summary, you will learn
1. Create a beautiful resume-website
2. Learn about fundemental methods for a good documentation

## Audience
This README is intended for Computer Science student, who have no or some experience in Markdown and GitHub.

## Quick Links:
* [Basic](#Basic)
  * [Benefit of static site](#Benefit-of-static-site)
  * [Prerequisites](#Prerequisites)
* [Install Markdown and setup GitHub](#Install-Markdown-and-setup-GitHub)
* [Uploading your file on GitHub](Uploading-your-file-on-GitHub)
* [Customize your resume](##Customize-your-resume)
* [See the Resume on GitHub page](#See-your-Resume-on-Github-Page)
* [Some tips for README](Some-tips-for-README)
* [Resources](#Resources)
* [Authors](#Authors)
* [Acknowledgement](#Acknowledgement)
* [FAQ](#FAQ)

## Basic
It make sense for people in tech upload their resume online. Github Page is a simple and nice looking URL, which is a perfect location for people to put their tech resume.
### Benefit of static site
Base on Etter's book *Modern Technical Writing*, the keys for good documentation are:
* Knowing your audience
* Knowing your topic
* Having verify contents
* Update your contents regurlar

Etter mentioned in his book, to achieve the top 3 methods, people need a long learning curve, such as research about their topics and audience, testing their contents, etc. Writers can not assume anything while writing, thus, every contents in the documentation need be base on some evidence which make the contents more persuade and trustful.

However, the last key to create a good documentation require working by time, wrtiters need to update their content everytime they made a change in it. It's hard to update contents through PDF file since it download on hardware, writers alway have to upload new file every time they want to change something in their documentation. Therefore, host a website for your documentation come in as a resolution. Static website allow writers to host contents on a website, which give them a power to modify inaccurate information in their contents and sync it to exist documentation, which keep their contents in sync without go through all the unecessary troubles. By hosting a resume online, we can avoid the hassles of upload multiple PDF file when we need to make a change in our resume, such as adding more information, changing in contact, etc.
### Prerequisites
Before starting, you need to have a general ideas about [Markdown](https://www.markdownguide.org) and [GitHub](https://github.com).


## Install Markdown and setup GitHub
This is a very first guideline to help you install Markdown, setup your own Github page
* **Markdown**
  * Install your favourite text editor. I reccommend [Atom](https://atom.io), this is a beginer-friendly text editor with multiple helpful packages such as word-count, grammar-check, etc.
  * Have your resume written in [Markdown](https://www.markdownguide.org) and save it as *index.md*.
* **Github**
  * Create an account on [Github](https://github.com).
  * *Note: most of university in Canada support student for Github account. Therefore, if you use your student email to sign up for Github, you will have a free access to Github.*
* **Create a reposity on Github**
  * Login to [Github](https://github.com)
  * Look on the left right corner of the page, when you see repositories, click on ```<new>``` button as show <img width="67" alt="image" src="https://user-images.githubusercontent.com/42950390/67733058-3981dc80-f9cb-11e9-8a25-7e89d769637f.png">
  * Set your repository public and initilize it README. In Etter's book, he encourage people to publish their documentation, so that people can visit your documentation and help you contribute it better. Similar to repository, by publishing your repository, you encourage people to visit your page, and help you contribute your contents.
  * *Note: In case you don't want to public your repository, you can assign to github pro account and set your reposity private*
  * Click on ```<Create repository>``` to create your own Github repository
  * Name the repository as ```<user name>.github.io```

  [](some gif picture)


## Uploading your file on GitHub
  Now you have your Github repository, the next step in the instruction will help you understand how to clone your repository using [Github Desktop](https://desktop.github.com) and upload your resume on Github page
  * **Clone repository on Github Desktop**
    * Download [Github Desktop](https://desktop.github.com)
    * Login to [Github Desktop](https://desktop.github.com) by your github account
    * Click on ```Clone the repository from Internet``` on the left side to clone the respository from your github account <img width="425" alt="image" src="https://user-images.githubusercontent.com/42950390/97900685-a297e080-1d00-11eb-96c5-dea55a975018.png">
    * Choose the repository that you will host your resume on ```<user name>.github.io```
    * You are sucessful clone your repository from github desktop
* **Upload your resume on Github Page**
    * Go to finder <img width="34" alt="image" src="https://user-images.githubusercontent.com/42950390/97902794-af6a0380-1d03-11eb-82c5-29d30a6d0f2a.png">
    * Copy the your resume file which name as *index.md*
    * Click on documents on the left side
    * Click on Github folder, go to the folder that have ```<user name>.github.io```
    * Past the file
    * Go back to Github Desktop
    * Type in ```Summary``` and ```Description``` in the bottom left hand side
    * Click ```Commit to Master``` button on the left hand side
    * You are successful uploaded the resume on github page

[](some gif)


## Customize your resume
Now you have your resume file uploaded on Github, the next step in the instruction will help you to create a theme for your resume using Jekyll theme setting in Github
  * **Choose Jekyll theme for resume**
    * Go to [Github](https://github.com) and click to the repository that you uploaded your resume to ```<user name>.github.io```
    * click on ```<setting>``` on the top page, as show <img width="827" alt="image" src="https://user-images.githubusercontent.com/42950390/67772301-d8d4bd00-fa27-11e9-8c9c-74bcaee3e7b2.png">
    * Scroll down to the very bottom of the page, click on the button ```<change theme>```<img width="747" alt="image" src="https://user-images.githubusercontent.com/42950390/97904158-b7c33e00-1d05-11eb-89a9-9e4a2d4d5176.png">
    * Choose the theme that you like from the categories<img width="1113" alt="image" src="https://user-images.githubusercontent.com/42950390/67772995-01a98200-fa29-11e9-932a-937bd820e654.png">

  * **Change title for Jekyll file**
    * Go back to your repository
    * Go to ```_congig.yml```, edit the file by add ```title: <your name/ some titles you want>```
    * Then click on ```<commit change>``` to finish


## See your Resume on Github Page
You now have your resume host online on Github page. In order to see your site, you need to open your browser and go on ```https://<username>.github.io```


## Some tips for README
Now you know how to host a resume online. However, your repository is missing README, which is an important documentation to show your professional in hosting a static website. Therefore, there are tips from Etter that he give out in *Modern Technical Writing*  might help you complete the work:
* have a quick summary about your project
* have a instruction how to build your documentation
* have a instruction how other can contribute in your documentation


## Resources
Visit:
* [Atom](https://atom.io)
* [Markdown cheetsheet](https://www.markdownguide.org/cheat-sheet/)
* [GitHub](https://github.com)
* [Jekyll theme matter](https://jekyllrb.com)

## Authors
* **Emily Nguyen** - initial work

## Acknowledgement
* GitHub Pages tutorial
* Markdown guideline
*  jekyll-theme-midnight [author](https://github.com/pages-themes/midnight)
*  Modern Technical Writing - Andrew Etter


## FAQ
* **Why I cannot see my Github page on the browswer ?**
  * There are 3 cases that might occurs for this problem
    * First case, your resume/document file name is not index.md
    * Second case, your Github page might need extra time to active
    * You don't have Github pro account and set your repository as private
* **Why do I have to use Jekyll theme on Github setting ?**
  * You don't have to use Jekyll that Github offer, you can build your own Jekyll them if you have knowledge about HTML and CSS. However, Jekyll theme setting in Github is the easiest way to change theme for your Github without code.
