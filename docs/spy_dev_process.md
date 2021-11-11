# The SPY Database Development Process

The [SPY Database](https://github.com/cf7/SPY) was my undergraduate thesis project and the reason I didn't eat or sleep for 12 months. I was fortunate to partner with [Safe Place for Youth](https://www.safeplaceforyouth.org/), a youth homeless services organization based in Venice, CA, to implement a database-driven web application for their staff and case managers. (You can read about the project description [here](https://github.com/cf7/SPY/blob/master/docs/Project_Proposal.md).) 

Like many young and ambitious thesis projects, it was a complete flop, but as we developers like to say, "Fail early and fail often!" The experience I gained from the project has proven invaluable.

The beauty of the project, however, lies in what happened behind the scenes. As project manager, I had already developed a working relationship with the organization when they approached me with their vision so that by the time the semester started, I was able to recruit a team of 9 classmates of various skillsets.

### Design Thinking for UX Use Cases
Crucially, we first went through the entire [Design Thinking](https://web.stanford.edu/~mshanks/MichaelShanks/files/509554.pdf) phase with SPY before writing a single line of code. We recorded interviews with staff and case managers where they told us what features they wanted in the platform. We co-designed user stories and wireframes with them, walking through each interaction with the app and its data. We toured the organization and met the clients, and we role-played how the platform would exist within the organization and its daily operations.

### Prototyping
We built a very cheap and easy prototype frontend for the platform based on this initial inquiry phase so that the staff could gain insights and provide invaluable early feedback before we spent weeks on features they neither needed nor wanted. This also helped hone the vision and helped us devise a development strategy and generate our Requirements Specifications for the project.

### Workflow Design
We divided build assignments by feature, each of which had workflows that spanned the entire pipeline of the application, front-to-back. I had the idea that we could choose one initial feature and develop it end-to-end to use as the "root of the tree," a model to inform the rest of the features. 

What better way is there to choose a feature than by following the client data on its journey through the web app?!

"Adding a client to the database," therefore, was the first feature we tackled as a team that established our pipeline. This turned out to be an excellent move since it gave us early insight into how we could structure our database table schema as well as practice our workflows. It was at this point of the process that I had to learn fullstack development on the fly AND train my team at the same time (because we were all just students).

![IMG_2242.JPG](https://github.com/cf7/cf7/blob/main/images/IMG_2242.JPG?raw=True)

### Scrum/Kanban Cycle
After an initial feature map and relational schema, it was off to the races! As part qualitative researcher, I was particularly excited about how we decided to organize ourselves. 

Each team member had two scopes of work: 

1) full stack assignments
2) specialization assignments

Each of us chose a feature we would implement end-to-end for a sprint. At the end of each vertical sprint down the pipeline, everyone would then sweep laterally and touch-up the portion of the pipeline they specialized in. This allowed us to implement a lot of featureus very quickly and with less effort so that we could test as soon as possible and present iterations to the SPY staff for feedback every step of the way. It also made the project extremely flexible so that new features and data logics could be added or removed on the fly. And in the process everyone got full stack experience while also utilizing their strengths!

![IMG_2244.JPG](https://github.com/cf7/cf7/blob/main/images/IMG_2244.JPG?raw=True)

### Deployment

Our plan was to deploy with Heroku . . . but unfortunately, we never made it to deployment. The semester ended and our department required students to spend their last semester working on a solo project, so a majority of our team's developers lost interest and left. I spent the final months of school writing a test harness for the app, converting some of its pages to ReactJS, and onboarding underclassmen and external freelancers who might be interested in carrying the project further. 

In the end, the project was never completed, but the staff at SPY were so inspired by our effort that they used our work and insights to apply for a grant for a private company to develop the system for them.


I learned a great many lessons from this project. Above all, it peaked my interest in the affects of human organizing on resulting technologies. (This is partly why I went off to get my masters degree to learn about the social realities that structure our technological infrastructure.)
