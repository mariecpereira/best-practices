
# Best Practices for Reproducible Computational Research

A research is called reproducible when one can acquire the same results presented in the paper. To do so, several habits can help researchers to ensure that their results are reproducible. According to Krzystof in [A practical guide for improving transparency and reproducibility in neuroimaging research](http://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1002506), the pillars of Open Science are: data, code, and papers. 

- Dealing with data: acessibility, organization and storage

- Dealing with code: environment, version control and management, and documentation 

- Dealing with papers: connecting textual statements to results and sharing 


Some of the main elements for a successful reproducible research are: 

## 1. Version Control: 

It helps to keep tracking of the development of your research, so if you have any issue with a new version of your code or if you update a library and your code is not working as it was, you still have the last version. It also helps team members to understand the research pipeline. Below are listed some version control platforms that I have worked at: 


###  Bitbucket: 

Bitbucket is a web-based hosting service that is owned by Atlassian, used for source code and development projects that use either Mercurial or Git revision control systems. Bitbucket offers both commercial plans and free accounts. It offers free accounts with an unlimited number of private repositories, which can have up to five users in the case of free accounts. 


- Experience:

Bitbucket is easier to organize a project than GitHub depending of what you are working with. The layout helps beginners to understand someone's project or their own, pointing out which sections are the most important.  It also has the advantage of making your repository private for free accounts. Which is important when you cannot publish your results yet. 


References: [Bitbucket Guide](https://bitbucket.org/product), [Git Cheat Sheet](https://blog.bitbucket.org/2016/06/22/download-git-cheat-sheet/)




###  GitHub: 


Git is a distributed version control system written by the creator of Linux. Git is similar to other version control systems such as subversion or CVS, but it's distributed. What this means is that if you clone a git project, you have the entire project history. You can commit, branch and tag all on your local machine without interacting with a server at all. 


- Experience:

GitHub is widely used either for version control or for sharing projects. Git is also a platform to interact with people and their work. You can follow their profiles and see what they have done lately, which can be very helpful and inspiring. A great drawback is the publicity police, where you cannot create private repositories using a free account. 


References: [GitHub Guide](https://guides.github.com/activities/hello-world/), [GitHub Cheat Sheet](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf)

## 2. Data Sharing: 

Data always requires more precaution, specially in reproducible research. First of all, make sure if you can publish your data and not violate ethical policies. If it is not the case, pay attention and search for a good storage service, as you would like to keep your data safe and ready to be downloaded. Some practices might help researchers while developing their papers, such as always storing the raw data before manipulating it. It is important to take notes and explain randomness process with your data and also to avoid manual manipulation, which can be a problem during the reproducibility practice. Below are listed some data sharing platforms: 

###  Dropbox: 

Dropbox is a file hosting service that offers cloud storage, file synchronization, personal cloud, and client software. Dropbox was founded in 2007, by MIT students Drew Houston and Arash Ferdowsi. Dropbox Paper was officially announced in October 2015, and launched in January 2017. It offers a web application, as well as mobile apps for Android and iOS.

- Experience:

Dropbox is well known as a data sharing platform. It is easier to upload files, generate links and share your data. A major drawback is the limited space of 5GB for free accounts. Dropbox launched a new feature recently, Dropbox Paper. The new feature promises a better solution for collaborative work than the rival Google Docs, it is possible to upload videos, audios, texts and links creating a collaborative workspace with real time chat. 


References: [Dropbox Guide](https://www.dropbox.com/guide), [Dropbox Paper Guide](https://paper.dropbox.com/), [Dropbox Cheat Sheet](https://www.takecontrolbooks.com/resources/0150/TCoDropbox-CheatSheet.pdf)


###  Google Drive: 

Google Drive is a file storage and synchronization service developed by Google. Launched on April 24, 2012, Google Drive allows users to store files in the cloud, synchronize files across devices, and share files. 


- Experience:

Google Drive is a platform for data sharing and it gives you 15GB of space for free accounts. There you can upload photos, documents, music, videos and share with anyone. A great feature of Google Drive is Google Docs, where you can create and edit documents or sheets working collaboratively with a team. It is easier as almost everyone has a Google account. 

References: [Drive Guide](https://www.google.com/drive/using-drive/), [Drive Cheat Sheet](https://gsuite.google.com/learning-center/products/drive/cheat-sheet/drive-cheat-sheet.pdf)

###  LONI-IDA: 

The Image & Data Archive (IDA) provides tools and resources for de-identifying, integrating, searching, visualizing and sharing a diverse range of neuroscience data, helping facilitate collaborations between scientists worldwide.


- Experience:

LONI IDA platform helps researchers finding data for their projects as well as managing their own. One can request an account and once it is set up, can search and download the vast dataset available. It also shares the featured studies section, showing the studies using the IDA dataset. I had some issues while trying to download data from ADNI available through LONI IDA, it provides two types of formats for download. I was downloading the metadata file and only getting txt files containing the information about the dataset, the correct file to download is the zip file. This file contains the data you asked for and you can choose NIFTI, MINC or analyse formats. Another helpful tool is the data collection section, as the dataset available is enormous, you can search through the dataset filtering information about the patients as age, genre, disease, type of MR image, and save whatever you want into your collections. It makes easier to come back and create/save different portions of the same dataset without the need of going through a new search.



Reference: [LONI IDA Guide](https://ida.loni.usc.edu/login.jsp)

## 3. Literate Computing: 

A literate computing platform can be used for both coding and writing. Jupyter Notebook has been the most used one and its users has grown significantly in the past few years. A good point while choosing a literate computing is the number of users, developed versions and tools. You do not want to start a complex and important project in a platform that can disappear quickly or that anyone knows about. That is why Jupyter is our recommended choice! Some helpful practices are: clean code (write comments, choose wisely the variable and notebook's names) and keep notes about the exact versions of all external libraries and programs used.

###  Jupyter Notebook: 

Project Jupyter is an open source project was born out of the IPython Project in 2014 as it evolved to support interactive data science and scientific computing across all programming languages. The Jupyter Notebook is an interactive computing environment that enables users to author notebook documents that include: live code, interactive widgets, plots, narrative text, equations, images and video. These documents provide a complete and self-contained record of a computation that can be converted to various formats and shared with others using email, Dropbox, version control systems (like git/GitHub) or nbviewer.


- Experience:

My experience using this literate computing platform has been good so far. Although I am new into the Python world, it has a good documentation, help assistance and the number of users has increased significantly lately. 


References: [Jupyter Guide](http://jupyter.org/install.html), [Markdown Cheat Seet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet), [Jupyter Tips](https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/)

###  Sage: 

SageMath is a mathematical software with features covering many aspects of mathematics, including algebra, combinatorics, numerical mathematics, number theory, and calculus.


- Experience:

Sage seems to be a great tool for mathematical problems developed for mathematicians or professors. I had some issues while trying to install Sage on my Mac and I found out more users complaining about the same problems. It has a good documentation, but at the same time it is difficult to find exactly what you are looking for. Another drawback is the fact that almost all documentation is provided by the developers, which casts double the number of users. 


References: [SageMath Guide](http://www.sagemath.org/tour.html), [Sage Cheat Sheet by me](https://cocalc.com/projects/f66b5f6a-6e55-4d2e-ac07-5e736ad99258/files/SageDoc2.md)

## 4. Workflow: 

Workflow is essential for reproducible research. It helps to understand the project's main idea from the input, through the following process, to the output. Some very complex projects may require not only a workflow but a workflow management, which goes beyond the idea of a simple diagram and can in fact manage the whole process. A diagram is enough for simple projects and it can be easily done using [Draw.io](https://www.draw.io/). Make sure to rewrite all your process as a workflow, using the same pattern to the same informations, such as input data, notebooks, functions, and output data. If your project contains several notebooks and dependences, but it is not too complex for a workflow management, it is advisable to have two different workflows: one explaining the main idea of the project and another one explaining the steps for the reproducibility. Below is listed a workflow management tool:


###  LONI Pipeline: 

The LONI Pipeline is a free distributed system for designing, executing, monitoring and sharing scientific workflows on grid computing architectures. Pipeline allows users to connect and run any number of different software tools, and conveniently visualize and download the results. Unlike other workflow processing environments, Pipeline does not require new tools and services to include or be built against the core Pipeline libraries.


- Experience:

It is necessary to request an account in order to access the pipeline server to run workflows or drafts. I sent a request through their website and never got an answer. 

Reference: [LONI Pipeline Guide](http://pipeline.loni.usc.edu/get-started/)


## 5. Environment control:

###  Docker: 

Docker is the world’s leading software container platform. Developers use Docker to eliminate “works on my machine” problems when collaborating on code with co-workers. Operators use Docker to run and manage apps side-by-side in isolated containers to get better compute density. Enterprises use Docker to build agile software delivery pipelines to ship new features faster, more securely and with confidence for both Linux and Windows Server apps. 


- Experience:

Following an advice from a friend, I created a Docker account and downloaded an image already configured with Jupyter Notebook. Then I installed the necessary libraries to run my code. This way you will not need to create an image from the beginning and anyone can reproduce your paper by only cloning your git repository and downloading/running your Docker image. 

##### Creating your Docker Image from another: 
All the following codes were used on Mac iOS 10.10.5

- `sudo docker exec -it <docker image address> bash`
   - for example: `sudo docker exec -it dataquestio/python2-starter bash`
- install the libraries you need, for example: `pip install nibabel`
- from another terminal, get the full ID of the image in order to save it
   - `sudo docker ps -q --no-trunc | grep <docker image address> `
   - it will show you the full ID, copy it for the next step
- saving your image: `sudo docker commit <full id> <your docker client name>/<image tag> `
   - for example: docker commit < full id> mecp/ia369z
- it is necessary to stop the other image to start running yours
   - `sudo docker ps` it will show all the running images, get the image ID
   - `sudo docker stop <image ID>`
- `sudo docker run -p 8888:8888 -v <your folder path>:/home/ds/notebooks mecp/ia369z`
- `sudo docker login --username=mecp --email=<email you used for your Docker account>`
- `sudo docker push mecp/ia369z`


References: [Docker Guide](https://www.docker.com/what-docker), [Docker&Anaconda](https://www.continuum.io/blog/developer-blog/anaconda-and-docker-better-together-reproducible-data-science), [Docker Getting Start](http://blog.kaggle.com/2016/02/05/how-to-get-started-with-data-science-in-containers/), [Docker Image Creation](https://github.com/ecalio07/enron-paper/blob/master/environment/BEST_PRACTICES.md)

## 6. Final Paper:

Last but not least, the final paper. The main key here is to connect all the pieces together with the text, explaining the whole process while facilitating as much as possible the reproducibility. LateX is the first thought for scientific writing and some platforms, such as Overleaf, facilitate the portability and the collaborative work using LateX. 


###  LaTeX: 

LaTeX, which is pronounced «Lay-tech», is a document preparation system for high-quality typesetting. It is most often used for medium-to-large technical or scientific documents but it can be used for almost any form of publishing.

###  Overleaf: 

Overleaf is a collaborative writing and publishing system that makes the whole process of producing academic papers much quicker for both authors and publishers. Overleaf is a free service that lets you create, edit and share your scientific ideas easily online using LaTeX, a comprehensive and powerful tool for scientific writing.

- Experience:

I have used LateX for years, and it definetely is great! I cannot think about using Microsoft Word or any other similar platform. A drawback to me was always the template, but since I started using Overleaf, my problems were solved. Overleaf facilitates LateX usability, it is portable, and it is a collaborative space. There are other tools trying to link LaTeX/Overleaf with Jupyter Notebook in order to facilitate reproducible research, although it has some layout issues to be solved. 

References: [LaTeX Guide](https://www.latex-project.org/), [LaTeX Cheat Sheet](https://users.dickinson.edu/~richesod/latex/latexcheatsheet.pdf), [Overleaf Guide](https://www.overleaf.com/about)
