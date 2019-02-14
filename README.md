# BBV-Project-Intro
This repository is to host the initial discussion of the best way to build BallotBox.Vote apps for iOS and Android. The simple, easy-to-use apps will be for creating, printing and scaning paper ballots for a ranked-choice election - but only for non-government offices such as a class president or local civic association officers. The apps will always be free to use, and the entity organizing this educational effort is applying for non-profit status. The founder of this effort has no software experience. Hopefully some experienced developers will volunteer to take the technical leads on this project before too long. For more, please see the rest of this Readme and the separate PDF file of mock screenshots. 

The easiest thing may be for initial partipants here to send an email comments and programming strategies (like what languages to use) to ballotboxinfo@gmail.com, or upload text files to this repository for all to see. 


I'm propbably technically in error here, but for now, let's say the iOS and Android apps have three main pieces:
1) The ballot making section where the user can input candidate names and the number of ballots needed, and have a single PDF containing all the ballots e-mailed out. Each ballot page will have a unique serial number. 
2) The ballot scanning and tabulation section
3) Wrapping that code up into the phone apps and their user interfaces

There is a "Universal Ranked Choice Tabulator" that has been created that by the RCV comminmity of election officials. This BBV project strives to use that code to do the actual tabulation of the rounds. 

Also, below is  link to a tutorial about using OpenCV to read bubble sheets. This linked tutorial uses Python, and that might not be the optimal language to then create smart phone apps. BBV is lookikng to the GitHub community to advise on this and 99% of all technical metters. I've been told that OpenCV is the right base for the scanning. Hopefully that is right. And hoefully the Python tutorial can be translated to a better app language and to RCV from simple test scoring by someone with the right experience without too much trouble. 

https://www.pyimagesearch.com/2016/10/03/bubble-sheet-multiple-choice-scanner-and-test-grader-using-omr-python-and-opencv/

It's important to note that this app is not intended to be super-duper secure or ever be used for elections to government office. It will never communicate with official, government voter databases or any outside ID systems,or have proprietary systems like official voting machines do. If a person running an election for senior class president gives ballots out to some freshmen, and then those ballots get scanned, then that election will not be a good one. It's up to the person running each election to secure their own ballot prinrting, distribution and scanning. 

The goal is common-sense security. If a teacher downloads the app directly from a major app store, and holds an election for prom king right away, our goal is only that all of the partipants in that election will feel confident in the outcome, and not that the system might be theoretically hackable.  Also, by relying on paper ballots, any questions about the scanning and counting can be answered by hand-counting the ballots, or by scanning the same ballots with another phone that just downloaded the app from a major store. Our goal is in part security therough transparency and redundancy. 

The leaders of BallotBox.Vote are open to suggestions in security, design and other aspects.

Once the paper ballots sytems works, it would make sense to add voting by e-mail and/or by desktop computer, so long as it is still very, simple.  There are of course many different vafriants of RCV. Rhere are groups such as labor unions who hold elections electronically, adn there are a lof of rules they  ust follow. BallotBox.Vote does not see these more formal lextions as a part of its mission. BallotBox.Vote wants only to be the decision system for common-sense, basic community elections. Also, there are a variety of RCV voting mehods, but BallotBox.Vote plans only to offer the "standard" RCV as used in Maine and other jurisdictions. We want to remove all possible barriers that might stand in he way - such as complexity - to non-RCV users to giving RCV a try. 
