# Working on your thesis

## Meetings

We will meet once per week for an hour to discuss your progress. To make the meeting time useful, for each session have some questions and results ready and prepare notes for the meeting on Github on which we can build during the meeting.

The more concrete examples of code and results (which may not be final) you present in the meeting, the more feedback we will be able to give you.

In addition to these meetings you will also be attending a class on research methods and thesis writing. The class normally has a fee deadlines where you have to present a research plan and partial results, and finally deadlines for submission and defences. As supervisors are not taking part in this class, do keep about the deadlines and activities in the class so that we can plan our work in line with those.



## Set-up a git repository

For all the work we will use a git repository. This includes:

  - the code you will write in the `code` folder
  - the data and other resources you will create in the `data` folder
  - notes about our discussion, experiments, results, diagrams and charts in the `notes` folder
  - a reading list, preferably a BibTeX file with a list of the relevant papers in the `literature` folder
  
Create a new private Github repository and share it with us. It is important that the repository is private as we will use it as a working repository with our particular results that we may not want to publish yet to the world.

When communicating with use always send information by committing it to this repo rather than including it in emails. The folder `notes` should be particularly handy which can be used as a wiki for analysis of partial results as you produce them. This way, we will always have information in one place and will be helpful to have an overview over the experiments and a thesis plan as well as in the final stages when you will start writing up the text. We will also send our comments back on GitHub.

Larger files like pdf papers, datasets and models do not fit on Github. For this we should use a shared folder.

Here are some useful tips if you are using our instance of nextcloud. You can work directly with the web interface which can be accessed using a link like `https://SERVERNAME/s/UNIQUE-SHARING-KEY` and sometimes a password `PASSWORD`. It is also possible to use the files using file-transferring apps such as _FileZilla_, _Cyberduck_ and _rclone_ and in most operating systems you can also mount the folder as a drive directly using the webdav/davfs protocol/file system. In that case the link becomes https://SERVERNAME/public.php/webdav where you put `UNIQUE-SHARING-KEY` as username and `PASSWORD` as a password. Note that if you are using the folder directly in a script with lots of reads and writes (i.e. if you are using it for training data in a script) it may be much slower than a local drive as it is over the network.

It is important that you carefully document your research progress by saving results in notes and commenting them, and also saving the datasets and models that were used in each experiment, per experiment. The reason for this is that it will be easier to write up your thesis in the end when you will have all the available information at hand (even if it was a negative result) but also because we should aim for _replicable research_. This means that we should eventually publish all code and models that we produced in a way that someone else could easily replicate and verify our results. We will do this at the end, by selecting from the code and the models we previously save and clean them up so that they will be interpretable by others.



## Planning your submission date

To set date for your defence we plan backward from the date you would like to defend. Normally, it works like this:

  - T: time of the defence
  - T-2 weeks: submit the thesis to the examiner and the opponent
  - T-4 weeks: final draft for the supervisors and time for final corrections, supervisor requests a defence time from Yvonne
  - T-8 weeks: all the coding is done and you have results for most of the experiments; start writing only

The last point depends mostly on you how fast you can work and how much time you have available but the first three points depend on the process and the time in which a defence can be reasonably organised.


Revised on: 2023-04-19 
