# Getting Started / Class Workflow

## Github setup and general use

- Signup for a github account if you don't have one!
- Fork this repo
- Clone the forked repo on your computer
- Add a branch for your personal dev work
  - `git checkout -b` _your_branch_name_ (-b means add a new branch)
- Add the upstream location:
  - `git remote add upstream https://github.com/aaronsherwood/artintel.git`
- Check remote locations to confirm upstream location added:
  - `git remote -v`
- Merge new examples I might add during the semester to your master branch:
  - `git fetch upstream`
  - `git checkout master`
  - `git merge upstream/master`
- Do all your work on your personal branch, not master:
  - `git checkout` _your_branch_name_ 
- Push your work to github:
  - `git add -A`
  - `git commit -m "your commit message"`
  - `git pull origin` _your_branch_name_ (not absolutely necessary but safer and a good habit to get into to avoid merge conflicts)
  - `git push origin` _your_branch_name_

## Assignment Documentation
### Posting Assignments
Add links every week for your reading responses and documentation for production assignments by editing the _studentwork_spring2018.md_ in your master branch. 
- _IMPORTANT:_ Before adding links to that file, merge from upstream to master to avoid merge conflicts:
  - `git fetch upstream`
  - `git checkout master`
  - `git merge upstream/master`
- Then, include your link(s) in the _studentwork_spring2018.md_ file (make sure you're on master). It might be easier to do this step online, rather then locally.
- Make a pull request to me (on your master branch) via github.com, to add your links into the original mark down file on my github. 
- Pull from your master branch online to your local master:
  - `git pull origin master`
  
The link(s) each week included on the main studentwork page should be just one master link per assignment/reading/etc. The page the master link leads to should contain all your descriptions/audio/video/pictures/responses/links/etc.

All code you've worked on should be in your personal dev branch. You can include links to code from your dev branch in you documentation post when you feel it is appropriate. All media files should be hosted on appropriate websites (examples: vimeo for video, soundcloud for audio, etc.). The page that contains your weekly documentation (as mentioned above) could be on your own website, or tumblr, or wordpress, etc.   

### Notes about Documentation/Responses
**You are expected to document all your work.** The purpose of this is twofold. First, it is a valuable way for you to communicate to me that you are keeping up with the work in the class. I read the site to see how you are doing. At a minimum, reference to your work is expected, as well as reference to the readings, and thorough documentation of any research. Secondly, this is a way to document your work for your own use and that of others.

You must update this weekly with the work you have done for class.

Document your projects thoroughly as you go; don’t put it off until the end.  Photos, video, drawings, schematics, and notes are all valuable forms of documentation. Explain the project at the beginning of your documentation, so that people who come to your site from outside this class can understand your work quickly.

Use pictures, drawings, and videos liberally to explain your work.

Don’t overload your notes with code. Link to the code in your dev branch. When you base your code on someone else’s code, cite the original author and link to their code, just as you would when quoting another author in a paper. If you only changed one part of an existing program, post only the part you changed, and link to the original. Make sure any code you post is well-commented, so you and others can understand what it does.

Always cite the sources of your code, the places you learned techniques from, and the inspirations of your ideas. Copying code or techniques without attribution is plagiarism.  Few ideas come out of the blue, and your readers can learn a lot from the sources from which you learned and by which you were were inspired. So be generous in sharing your sources.

Good documentation should include a description and sometimes even an illustration of your project. You should include what it looks like, what it does, what the user or participant does in response. When it’s interactive, mention and show what the user does. Your explanation should give enough information that someone who’s never seen the project can  understand it.

You should also include a section describing how the project works, aimed at a more informed reader (your instructor, or next year’s classmates). Include a system diagram to make clear what the major components of the system are and how they communicate.

You should use this as an opportunity to write clear, concise thoughts or questions based on the weekly topics. The writing is expected to be well reasoned, grammatically correct, and written as if it were a paper being turned in. You should link to any relevant sources, and provide as much context as you can using images, video, audio, or other forms of expression. 
