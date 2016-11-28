MSBBSS11: Research Seminar
===

Exercise 5

---
This repository might contain useful information for anyone who’d like to pursue a career where reproducibility of code and results is desired. It is designed as a tutorial for the graduate students of the selective master program [**Methodology and Statistics for the Behavioural, Biomedical and Social Sciences**](http://www.uu.nl/masters/en/methodology-and-statistics-behavioural-biomedical-and-social-sciences) in the `MSBBSS11: Research Seminar` course. 

This is by no means a full overview of markdown, GitHub, reproducibility, or anything else, for that matter: the aim is to get you started and allow you to develop a workflow that rocks your boat while simultaneously allowing others to follow your train of thought by simply looking at your project’s documentation. ‘

I’d like to give you some pointers in the form of tips:

---

#### Tip 1 - Work in projects and project folders. 

Most things we (we as in statisticians) do have a representation in digital space. For example, if a client comes to me with a missing data problem I have a very distinct workflow of a) checking and editing the input data, b) designing the missing data models, c) joining these models by means of algorithms to impute the missing data and d) evaluating the joint data. I use scripting languages (such as R) and programming languages (such as C(++) or Python). The code I produce is updated and executed (run) frequently, results are produced and stored on the fly, and the state of the project at timepoint B may be very different from the state at timepoint A. Using a dedicated folder for every project makes tracking the code, the changes to the code and the states of the project over time much more convenient. 

#### Tip 2 - Don't make your projects too comprehensive. 
Simple. It's easier to manage a (giant) project if you break it up into smaller parts

#### Tip 3 - Document your code
A year from now, when looking at your code, syntax or project, you probably won't be able to remember what you did, what your code does, or why you coded something like you did. Unless you document your code and make it insightful. When coding your project, try to adhere to some coding convention: the [Google style guides](https://github.com/google/styleguide) are very useful resources and provide you with well-designed style conventions on all the major programming and scripting languages. I suggest you study at least the [R Style Guide](https://google.github.io/styleguide/Rguide.xml) as this might me the language you will use most during your thesis.

#### Tip 4 - Open a GitHub account
Its simple, free and even the paid version is free when you are a student (i.e. the fee is waived). You can apply for a student discount [here](https://education.github.com/discount_requests/new). There is also a [Student Developer Pack](https://education.github.com/pack) that helps you learn new coding languages and provides you with a comprehensive software toolkit to do so - also free. And you can host your own professional site on [GitHub Pages](https://pages.github.com). Also for free!

Why GitHub? It is a great platform to share your work/projects as open source repositories for others to use or work with. You can work with multiple collaborators on the same project repository and all version history is automatically controlled. So when sh&t hits the fan: you can simply go back in time. If you would like to keep things closed source and work alone or together in a private repository: the paid version (yes - the one that is free as a student) allows for that, too. In short; many developers work together on GitHub and there is a reason why they choose this platform. Also, there are apps for Mac and Windows and its use is extensively documented by GitHub and by the community itself. 

#### Tip 5 - Document changes to your code
With GitHub this is really easy - the framework does this for you. After all, it is a repository service build on the version control software [`Git`](https://git-scm.com), created by Linus Torvalds. See for yourself: click this `Readme.MD` file and have a look at the history of the file. If you click on a commit (a change in the document) - you can even compare the committed source to the previous source!

#### Tip 6 - Use version control software
If you use GitHub; you're done! congrats. If not, please integrate `Git` into `R-Studio`, or place your `R-Studio` projects into something that does version control, such as [Google Drive](https://www.google.com/drive/), [DropBox](https://www.dropbox.com/), [OneDrive](https://onedrive.live.com), [SurfDrive](https://www.surfdrive.nl/en) or any of the other major cloud-based file hosting platforms around.

#### Tip 7 - Learn Markdown
Use [markdown](http://daringfireball.net/projects/markdown/) or [rmarkdown](http://rmarkdown.rstudio.com) to communicate your project to the masses (or clients). It is easy, it allows for weaving your text and code into a single document and it makes the things you do much more reproducible. It exports as anything you'd like - although I would suggest HTML files as they are cross-device readable. Oh, and this `Readme.MD` file is also written in markdown - as well as directly online editable in GitHub! As are most major code files. 

#### Tip 8 - Go with the flow
Your own workflow, that is! If you have decided on a foundation for your project workflow, all that rest is a workflow itself. I like to develop all my projects according to [this nested workflow](https://github.com/gerkovink/Pooling_MI), because it results in an effortlessly archivable project folder. But choose whatever floats your boat. 

---

All the best, 

- [Gerko](https://www.gerkovink.com)



