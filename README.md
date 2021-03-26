# Welcome!

I am a junior developer ready to move onto the next level of software engineering. After graduating at the top of my class with my Bachelors in Computer Science from Loyola Marymount University, I spent three years out of state to pursue my passion of service immersion in and around homelessness in impoverished communities. During that time I was able to earn a masters degree in Social Justice and Homelessness Organizing as well as keep up my coding skills by taking graduate level computer science classes in Machine Learning and Artificial Intelligence.

However, I've finally moved back to Los Angeles and am ready to dive back into the world of software development!

What I lack in experience I make up for in learning speed. My hopes are to gain more full stack experience and do so in the service of those less fortunate by working for an organization that makes an impact. Fortunately, I already have a bit of full stack experience from my main app development project: [SPY Database](https://github.com/cf7/SPY). __(Important Note: Since I switched my email addresses linked to my github account, my contribution history insights were erased from the repo. However, manually looking through the commit history will very clearly reveal that I am the primary contributor for the project.)__

Want to learn about some nuances of my skillset? 
Check out my standards-development-reviews from my courses:
[CMSI371](https://github.com/cf7/cmsi371/blob/master/sdr-371.pdf),
[CMSI370](https://github.com/cf7/cmsi370/blob/master/sdr-370.pdf),
[CMSI284](https://github.com/cf7/cmsi284/blob/master/sdr-284.pdf)


# The SPY Database Process

The SPY Database was my undergraduate thesis project and the reason I didn't eat or sleep for 12 months. I was fortunate to partner with [Safe Place for Youth](https://www.safeplaceforyouth.org/), a youth homeless services organization based in Venice, CA, to implement a database-driven web application for their staff and case managers. (You can read about the project description [here](https://github.com/cf7/SPY/blob/master/docs/Project_Proposal.md).) 

Like many young and ambitious thesis projects, it was a complete flop, but as we developers like to say, "Fail early and fail often!" The experience I gained from the project has proven invaluable (especially working in a context where half our development team somehow got away with not doing any work whatsoever.)

The beauty of the project, however, lies in what happened behind the scenes. As project manager, I had already developed a relationship with the organization who then approached me with their vision so that by the time the semester started, I was able to recruit a team of 9 classmates of various skillsets.

### Design Thinking
Crucially, we first went through the entire [Design Thinking](https://web.stanford.edu/~mshanks/MichaelShanks/files/509554.pdf) phase with SPY before writing a single line of code. We recorded interviews with staff and case managers where they told us what they wanted to be able to do and how they wanted to use the platform. We co-designed user stories and wireframes with them. We toured the organization and met the clients, and we role-played how the platform would exist within the organization.

### Prototyping
We built a very cheap and easy prototype frontend for the platform based on this initial inquiry phase so that the staff could gain insights and provide invaluable early feedback before we spent weeks on features they neither needed nor wanted. This also helped hone the vision and helped us devise a development strategy and generate our Requirements Specifications for the project.

### Workflow Design
We chopped up the project into features, each of which had workflows that spanned the entire pipeline of the application, front-to-back. I had the idea that we could choose one initial feature and develop that end-to-end so we could use it as the "root of the tree," a model to inform the rest of the features. What better way to implement this than by following client data through the web app! Adding a client to the database, therefore, was the first feature we tackled as a team that established our pipeline. This turned out to be an excellent move because it gave us early insight into how we could structure our database table schema as well as practice for our workflows. It was at this point of the process that I had to learn fullstack development on the fly and train my team at the same time. 

![IMG_2242.JPG](https://github.com/cf7/cf7/blob/main/images/IMG_2242.JPG?raw=True)

### Scrum/Kanban Cycle
After an initial feature map and relational schema, it was off to the races! As part qualitative researcher, I was also particularly excited about how we organized ourselves. Each team member had two scopes of work: 1) full stack and 2) their specialization. Each of us chose a feature we would implement end-to-end for a sprint. At the end of each sprint vertically down the pipeline, everyone would then sweep laterally and touch-up the portion of the pipeline they specialized in. This allowed us to implement a lot of featureus very quickly and with less effort so that we could test as soon as possible and present iterations to the SPY staff for feedback every step of the way. It also made the project extremely flexible so that new features and data logics could be added or removed on the fly. And in the process everyone got full stack experience while also utilizing their strengths!

![IMG_2244.JPG](https://github.com/cf7/cf7/blob/main/images/IMG_2244.JPG?raw=True)

### Deployment

Our plan was to deploy with Heroku, but unfortunately, we never made it to deployment. The semester ended and our department required that we spend our last semester working on a solo project. I spent the final months of school writing a test harness for the app, converting some of its pages to ReactJS, and onboarding underclassmen and external freelancers who might be interested in carrying the project further.

In the end, the project was never completed, but the staff at SPY were so inspired by our effort that they used our work and insights to apply for a grant for a company to develop the system for them.


I learned a great many lessons from this project. Above all, it peaked my interest in the affects of human organizing on resulting technologies. (This is partly why I went off to get my masters degree to learn about the social realities that structure our technological infrastructure.)

