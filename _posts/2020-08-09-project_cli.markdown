---
layout: post
title:      "Project CLI   "
date:       2020-08-09 21:07:06 +0000
permalink:  project_cli
---


#### Welcome to my blog. I'll be discussing my process of creating my very first Command Line Interface Application with Ruby and external API's. I wish I could say this project was a piece of cake but it continued to be an ongoing challenge for me. Toward the end of the project everything I learned in my lessons began to make sense. I thought many times "if only I knew this when I first started the project I could have saved so much time!" But hey, better late than never. 

#### My project name is Business Learner CLI. This project consisted of building a Ruby Gem that provides a CLI to external data. The external API I chose is Newsapi. I had many ideas of possible projects but after starting and restarting I thought I should stick to what I know before jumping in the deep end of complexity. Business Learner CLI is built to help business owners or managers to stay up-to-date with the latest top headline news. I think it's important to know at least a little about several subjects to broaden your perspectives. 

#### After brainstorming and jotting ideas, I began my project by bundling my gem file in my local environment terminal - VS Code (bundle gem business_learner), then creating a repository in Github then cloning it to my local environment terminal. The next process is to create my executable files inside my bin folder. I ran a few tests to ensure everything was working. 

#### I then created the following files and folders:

bin
     start
config
     environment.rb
lib
  business_learner (folder)
     article.rb
     cli.rb
     source.rb
  Service (folder)
APIService.rb 

#### These folders and I became very acquainted throughout this project. Here is more details on how I navigated through each:

1. **Inside  bin -> start file**: I included my requirement to my environment.rb file as well as my start command to run my program's code.
 
2. **Inside config -> environment file**: I included all my requirements/required relatives. This means that all the remaining folders listed above were required under this file. I found creating an environment file helped me to be more organized. 

3. **Inside lib -> .rb files**: I included my CLI file and the model files in this place. The CLI laid the structure of my program and how it interacts with the users while the model files (source/article) included the attributes I would like to be included in my program. 

4. **Inside Service -> APIService file**: I included all the requests I made from the API URI that I would like to be included in the program. For instance, I would like to request to have the Newsapi top news headlines included in the program. **

#### After all the files are created and code is included the program will run with a greeting and a list of news topics to choose to learn more information about. Once the user chooses the topic more in dept information will be displayed. 

#### Some of the things I learned from this project I don't think I could have learned in a lesson. This was definitely great hands on experience. It included a lot of research, "figuring things out", and "oh well, let's try this" in order to overcome the challenges. It was not easy but it was definitely worth the experience! 


  

