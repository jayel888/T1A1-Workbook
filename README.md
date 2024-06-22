# Jess Lee T1A1-Workbook 

## Question 1

Markup Languages (ML) are systems that utilise sets of annotations such as tags and elements in a text document making it easier for computers to interpret and manipulate the text. These rules define and govern how elements such as text or images are presented digitally. There are many different types of Markup Languages, however some of the most common for web development include HTML (Hypertext Markup Language), SGML (Standard Generalised Markup Language) and XML (Extensible Markup Language) (Ben Sadok, 2021).

A major benefit of Markup Languages is improving Search Engine Optimisation (SEO) quality. HTML utilises semantic tags which define sections on a webpage which allows browsers, search engines and other developers to read and understand the flow of content easier (Ben Sadok, 2021). There are many different semantic tags that can be used and are generally divided for either Structure ie. `<header>, <main>, <section>` etc. or Text elements ie. `<h1> to <h6>, <p>` etc. By using semantic language, it adds an additional layer of information which makes the information more comprehensible and allows search engines to pinpoint crucial information on the webpage. This effectively assists in increasing the chances of a websites content to rank higher on the results page against the relevant keywords of the search. By implementing responsive design principles, it ensures websites are optimised depending on the device they are viewed on. This not only improves user experience by changing how websites are viewed on different sized screens, but also boosts SEO as Google now priortises results that are mobile-friendly. 

Additionally, Markup Languages enhance accessibility for users with disabilities making it easier to interact with websites, and simply more user-friendly for everyone. It enables assistive technologies such as screen readers, to interpret and output the information in ways the user requires to access it. An example of this would be using Alt Text for images with meaningful descriptions which lets screenreaders comprehend the context of an image and greatly increases the browsing experience for visually impaired users. By ensuring a website is highly assessible, it allows websites to reach wider audience which can be overlooked often. The World Wide Web Consortium (W3C) have created Web Content Accessibility Guidelines (WCAG) which makes it easier for developers and designers to follow and produce an accessible website.

## Question 2

### Packets

A packet is a small unit or portion of data that is sent over a computer network. This method of splitting and sending data is known as Packet Switching. Each packet contains part of a complete message that hold important address information of the sending computer and its intended recipient, where the packets are then reordered into a single file at their destination. Packet loss occurs when one or more packets fail to reach the intended destination, resulting in information loss.

A network that facilitates packet is known as a Packet-Switching network. The worlds first Packet-Switching Network was developed in 1969 by Advanced Research Projects Agency of the U.S. Department of Defense (ARPA) named ARPANET. This invention provided the foundation in which the internet still operates today. As ARPANET evolved, it required governance which supported the invention of a new method named Transmission-Control Protocol (TCP/IP) (ScienceMediaMuseum.org, 2020).

### IP Addresses (IPv4 and IPv6)

An Internet Protocol (IP) Address is a unique indentification number that is assigned to all devices connected to the internet. It is used for computers to efficiently communicate with each other over the internet or local networks to share information to specific locations. An IP Address has two parts, one of which identifies the host and the other the network is belongs to.

There are two core versions or standards of Internet Protocol, which are IP Version 4 and Version 6. IPv4 was first launched in 1981 by the Internet Engineering Task Force (IETF) and later adopted by ARPANET in 1983. It still routes a majority of the internet traffic today and is a popular protocol for communication over the internet, however it's greatest limitation is that it can host just under 4.3 Billion possible IPv4 addresses due to 32-bit address format. This limitation is essentially solved by IPv6 as it uses a 128-bit address format which allows approximately 340 undecillion (2^128) possible IP addresses. Other improvements over IPv4 include autoconfiguration, routing and security upgrades. However, despite these improvements, the migration from IPv4 to v6 is expensive and complex, hence why most of the internet stills runs on IPv4 (geeksforgeeks.org, 2023). 

### Routers and Routing

Routing is the process of selecting the path in which the packets of information/data are transmitted across one or multiple networks (Rouse, 2023). These decisions are facilitated by devices known as routers. A router guides packets between two or more packet-switched networks. Its primary functions are to manage traffic between the networks and allowing multiple devices to utilise the same Internet Connection. Most routers today allow devices to connect to the internet wirelessly (Wifi).

### Domains and DNS

Domain Name System (DNS) is a protocol for how computers relay data over the internet. It aids in converting user-friendly names which are easy to understand into an IP address which computers then use to identify on the network (Brain et al., 2024). It was invented in 1983 by Paul Mockapetris and has been pivotal in shaping the internet as we know it today. DNS makes it easier for us as users to navigate websites with easy to remember names and eliminates the need for memorising individual IP addresses (Villanueva, 2021). Without a DNS translating the domain names to correct IP address, it would make it much more difficult to access the websites we want, especially if IP addresses were to change for whichever reason, DNS still allows us to view the page with the same domain name. 

## Question 3

### TCP

Transmission Control Protocol (TCP) is the internet protocol establishes a connection between computers, allowing them to communicate between each other by transferring data over long distances. As the internet is a packet-switched network, the data is broken down into small packets which are sent individually through different routes (facilitated by routers) and then reassembled at the destination (BasuMallick, 2022). Since it's inception in the 1970's-80's when the internet was being built, it has been a cornerstone in the development of communication over the internet. It provides a reliable method to transmit data over the internet, ensuring data is delivered accurately in its correct order (Kurose & Ross, 2021). Its design has effectively enabled it to scale with the current growth of the internet and served as a foundation for the advancing of many internet technologies (Severance, 2015). This has been accomplished by standardising the information delivery so all hosted applications on the internet are interoperable (BasuMallick, 2022).

### HTTP and HTTPS

Hypertext Transfer Protocol (HTTP) is an application protocol that was created to facilitate the transfer of information between clients and servers, and operates on top of the TCP/IP suite. It was used alongside HTML to create the first text-based web browser and still remains the primary protocol for data transfer across the Internet today. HTTP utilises a request-response model, where the client sends a request to a server, which issues a response. The server delivers the requested data to the user in the form of HTML pages, images or videos after the request has been initiated via their browser. Hypertext Transfer Protocol Secure (HTTPS) is a more secure extension of HTTP, in which the browser and server establish a secure, encrypted connection before the commencement of data transfer. 

HTTP started off very basic, supporting only the retrieval of plain text. Over the years, its capabilities have evolved alongside the complexity of web applications as they required faster performance. It's next stage HTTP/2 improved upon data compression and allowed multiple requests/responses to be processed simultaneously. HTTP/3 further enhanced its performance by reducing latency in harsher network conditions (Make Computer Science Great Again, 2023).

### Web Browsers

Web Browsers are software applications that allow users to navigate the internet by displaying text, images or videos from the information that is retrieved from web servers. There are many different types of browsers in the market, with the most commonly used being Google Chrome and Safari making up approximately 85% of users in 2024 (similarweb, 2024). The first browser "WorldWideWeb" was invented in 1990 by Tim Berners-Lee and was the only means of accessing the web at the time. In 1992, Lynx was created but could only display text and no graphic components. This feature was later introducted by Mosaic that allowed embededd images. Microsofts Internet Explorer was debuted in 1995 while Safari was released in 2003 specifically for Macintosh computers. Google Chrome was later introducted in 2008 and quickly dominated the market with is being the most widely used browser today (Mcpeak, 2018). Web Browsers have shaped the internet today by providing an easy-to-use graphical interface to it's users to display information, with each browser enhancing browser experience by improving speed and efficiency, security and privacy, providing cross-platform compatibility and implementing extensions and plug-ins that can be contributed to by the community. 

## Question 4

Compilers (eg. C, C++) and Interpreters (eg. PHP, Ruby) are programs that take high-level language or source code, that we humans understand, and converts it into machine language; each with their own advantages and disadvantages. The main difference between the two is that, a compiler will read the entire code that is saved to a file before it is executed; whereas interpreters read source code line by line as the program is run (Ben Sassi, 2023). Compiled code generally takes longer to analyse than Interpreted as it goes through the entire code, but consequently the final program will perform faster than interpreted code that is being analysed line by line while the program is being executed. 

Compilers will display all errors after it's been compiled and interpreters will display the errors of each line individually which makes it simpler to debug. This in turn means that compilers generally consume more memory than interpreters. Another reason Compiled code is faster is due to it being optimised to the device or platform that is is run on, although this can also be a disadvantage as it means the programs may not be cross-platform compatible. Once code has been compiled, the executable file can be launched without needing any of the source code which provides some confidentiality. Interpreters always require the source code for processing but can be executed on any machine or device without compatibility issues (BasuMallick, 2023).

Both compilers and interpreters have unique applications and do not replace each other.

## Question 5

### JavaScript

JavaScript (JS) is a very widely used programming language that is popular for its versatility in creating interactive elements for a website. It was initially designed to add interactivity to static HTML pages, and has since evolved into an essential tool for web developers. It has provided the framework for other emereging technologies such as Node.js, which expands Javascripts application beyond an internet browser. As of February 2024, Javascript is used in 98.7% of websites on the internet as a client-side programming language (Raval, 2024). There are many advantages that turned this language, which was only created in ten days, into one of the a fundamental pillar of the internet. 

JavaScript enhanced speed and efficiency, a benefit from its ability to executing directly on the clients or users end, which minimises its use of server resources. As users enter a website, the javascript code is executed directly from their browser which aids in loading webpages significantly faster as it is able to bypass server communication. It is also able to efficiently handle large data transfers, meaning the information is relayed with minimal delay, increasing the overall responsiveness of webpages. 
JS also has the ability to facilitate front-end and back-end tasks to be executed by a single language, making is simple and more accessible to web developers at all level. 
It is interoperable meaning it works seamlessly with other programming languages like HTML and CSS, and has amassed a large ecosystem, which contains an abundance of libraries and frameworks such as React and Angular. 

However with all of its positives, there are some drawbacks. There is a client-side security risk as its implementation varies between browsers, which makes it more difficult for developers to write code cross-browser. This can create vulnerabilities for users which hackers can exploit, enabling them to modify it with malicious code and compromise their systems. JavaScript code is visible to everyone, meaning anyone could potentially access and modify it, increasing the risk of data breaches. Additional layers of security must be implemented to combat this and protect sensitive data. JavaScript has a 'Single Inheritance Model' meaning objects or elements are limited to inheriting properties from a single parent, in comparison to other languages that can support multiple. Its dynamic nature can make debugging more challenging as some errors may only present themselves during runtime (Thakur, n.d.). 

### Python

Python is an interpreted, high-level programming language that has recently become one of the fastest growing and most popular coding languages in the world due to its versatility and beginner-friendliness. It has multi-purposed functionality meaning it can be used to design a wide array of applications like software and web development, automation or conduct data analysis. Python has a strong active community that is known for being friendly and supportive, maintaining many open-source libraries and frameworks available to the public (Gavrilova, 2023). It is embeddable meaning it can be seamlessly integrated into other languages, which allows users to utilise the benefits of Python whilst using their preferred programming language. Another advantage of Python is its high scalability being able to handle large amounts of data and computing by utilising libraries and frameworks such as Pandas or NumPy. 

Nevertheless, with all its advantages, Python does come with some drawbacks. As it is a interpreter, it is slower than compiled languages which is noticeable computing large amounts of code or performing complex calculations. It is not a native to mobile environment and is considered a fairly weak language for mobile development. Python also has high memory consumption, and comes with a process called Garbage Collection which automatically frees up memory resources that aren't use by the program, which can consequently lead to performance issues due to poor optimisation. 

## Question 6

Hi Alex,

Thank you so much for your enquiry. SAM sounds like a great museum, I'll be sure to visit soon! From the briefing you provided, I will definitely be able to assist you in the creation of your website.

I can send you a mock up of the wireframes and sitemaps which will provide you a visual on the layout for each page of the website and how the website flows. This will tell us if we're heading in the right direction of your vision. If I may ask, who is your primary target audience? This will help us decide on the most suitable design elements such as theme, colours and images etc. We ensure that all the website we design are responsive, so my team will optimise it for all devices as most people now access the internet through their phones. Additionally, we also focus on SEO optimisation, so your website ranks higher when certain keywords are searched into search engines like Google for example. This will increase traffic flow, directing more people to your website. 

Bsased on what you described, this is the current layout I have in mind for your website:
**Home Page** - On your landing page, we can keep it up-to-date with the latest and attractive exhibit you have at the time to really captivate your audience. We will design a navigation bar and footer which will make it easier for your customers to navigate to all pages of the website. 

**Exhibits / What's On Page** - We can create a separate page listing all of your exhibits and items, etc. including all past and future ones; this will help increase consumer engagement as they can see what will be coming to the museum and plan accordingly. This would be helpful for schools to plan excursions ahead of time for example. 

**Plan Your Visit / Location Page** - Another page will be dedicated to location and helping customers navigating to your museum. We can implement a Google Map that is interactive showing exactly where your museum is located, and when clicked, they will be directed to Google Maps and can plan their journey. We could also include nearest train stations or public transport options, nearest parking facilities and restaurants/cafes. We could also include a floormap of the museum which will help customers optimise their visit. This will also include a link directly to the Tickets page if applicable. Providing all this information to your customers will make it as easy as possible for them to access your museum.

**Contact Us Page** - This page will display all the contact information for the museum, including opening hours, contact number, email, address and links to all your social media. This will also include a form for customers to fill in and contact you directly from the website, which would include information such as "Name, Number, Email and Message". 

**Tickets** - If your museum requires tickets, we would be able to design a page that allows customers/members to purchase directly from your website. 

You mentioned that you do not currently sell items, however, if in future you ever decide you want to, we could add a 'Shop" page and integrate an e-commerce store.

My team will be responsible for hosting the website, managing customer information database and ongoing maintenance. We could update the website to suit your desired theme/exhibit. Once we have built the website, it will thoroughly tested to ensure everything is working as it should before finally launching it live. We strive to keep your involved in the entire process and keeping you updated on progress.

Please let me know what you think. If there is anything else you would like to add or change, please don't hesitate to contact me. If you're happy with the above, I can begin on creating a quote and providing you with estimated timeframes. I look forward to hearing back from you.


Kind Regards,

Jess Lee

Project Manager
Coder Academy

## Question 7

I have only had one previous software engineering project, which was creating my Website Portfolio for Coder Academy. The scenario I will be reflecting upon specifically is when I was trying to create the a page showcasing all my Blogs and the Blog Article layout page itself. For this self-reflection, I will be adopting Gibbs' Reflective Cycle 1988, which explored six stages of the experience: description, feelings, evaluation, analysis, conclusion and action plan. I believe this reflection model covers many bases and offers a solid framework for examining many aspects of the experience (University of Edinburgh, n.d.).

### Description

I explicitly remember the difficulty I had designing these two pages. After I had spent hours designing my header and footer and having everything the way I liked, I moved onto designing the main blogs page and the blog article page with placeholder text. I was attempting to utilise CSS Grid as I was previously working with CSS Flexbox and wanted to try to achieve the design I wanted with a different method. I wanted to create interactive and responsive tiles for each blog, centering them in the middle of the page. And for the individual blogs layout, I had decided to go with a generic article layout with the heading at the top, image on the right, and text wrapping around the image. Due to creating my wireframes and planning the layout beforehand, I knew exactly how I wanted those pages to look, the journey however, just wasn't what I expected. But I suppose that can be said about coding in general. I had allocated myself 3 hours after work to complete these pages, which I believed would be a generous amount of time after completing the Header and Footer over the last few days, so I had gained a bit of experience.

### Feeling

Going into the task, I had felt hopeful, as I managed to complete other areas of the website fairly smoothly, however for this specific task, I went through an entire array of emotions. The strongest and most frequent emotion I felt was frustration. Whenever I tried to place an element where I had imagined, it would throw everything else out of position. It was even worse when you felt like the code you had written would fix it, only to check liveshare and it look even worse than before. However all this frustration was followed with slight feelings of accomplishment after finally managing to do what you wanted. It was shortlived as you would start on a new element and the cycle would continue again. Reflecting on this now, I am proud of myself for persevering through that and not letting it overwhelm me completely. 

### Evaluation

The positives I can take away from this experience is that in the end, I did manage to complete it and have it working as planned. Designing the Blog Article page was much smoother than the main page, and I didn't encounter nearly as much trouble. Once I was able to get the image and heading how I wanted, it was very easy to have the text wrap around it. The most common thing that went wrong was having my main and footer not staying in position, or it affect the responsive design whilst I was trying to add the tiles. I did not manage to complete the task within the 3 hours I had initially given myself, however I did still finish it that night. The entire process for this task took just under 5 hours. A majority of that time spent on debugging or scrapping initial code and starting from scratch.

### Analysis

I believe the main reason things didn't go as well as they could have, was due to my code not being as optimised as it could have been. There were lines of code that affected the body in my index.css file that would affect the blog pages. It definitely helped planning the wireframes so I had clear direction in what I wanted to achieve, rather than just attempting different things and seeing what would work or look best as I went. A lot of the issues I faced was also due to lack of knowledge as I had zero coding experience beforehand, except for the classes, so stepping into this project was very daunting and took a lot of mental energy/fortitude. I spent a lot of time trying different things with CSS Grid, but I could not get it working the way I wanted, and switched to CSS Flexbox half way through. I decided this would be best as I had a stronger understanding of Flexbox and was able to debug more efficiently, rather than spending more time attempting to get Grid to work. Although I can't say it's by any means a strength, it was definitely comparatively stronger than my knowledge of grid. 

### Conclusion

There were many things I was able to take away from this experience. It helped me understand and become more comfortable being uncomfortable when things weren't going my way. This helped for the remainder of the project as I would inevitably be put into similar situations, which I would be able to navigate more efficiently. Although I didn't accomplish what I wanted using the method I originally planned, I still managed to achieve my end goal with a different path. I think this could have been a more positive experience had I researched a bit more, because for the specific design I was aiming for, it would have been been easier using Flexbox for the responsive design. I was unable to keep the grid the same when I was viewing it on different sized devices, and all the elements would wrap into ridiculous sizes. Wheras Flexbox kept the tiles the same and wrapped them exactly how I needed. As this was an indivudal project, I rarely asked questions in the support chat that Coder Academy offers. I felt that if I kept asking questions, I didn't want to annoy anyone or seem bothersome. I also partially felt some embarrassment as I thought what I wanted to achieve was an very simple thing to do, but I was having so much difficulty. I understand now having reflected on it, that I shouldn't let those things stop me from reaching out and asking for help when needed.

### Action Plan

If I were to work on a similar project and find myself in a similar position, the greatest take away for me would be to not hestitate and reach out to the support networks that I am offered. This would have saved me lots of time and effort as the educators could assess and tell me why it things weren't working as expected, rather than me having to go through all my different files of code to find the issue. I would research which would be the most efficient or optimised methods for what I would want to achieve, rather than attempting it blindly and forcing it to work, as most of the time there will be a better solution. I learned that planning is a crucial step and in future, I will spend more time in my planning phase. 


## Question 8

### Action Plan for Career Growth in IT

Hack.Melbourne hold numerous events throughout the year, with the annual **Melbourne Hack upcoming on 30/08 - 01/09/24**. This opportunity lets participants connect with industry-leading companies, meet other peers and learn. 
**CISSA X MAC | StartHack 24/06/2024** hosted by Monash Association of Coding and Computing and Information Systems Students Association from University of Melbourne
Melbourne Business Network Monthly Networking and Catchup Event 18/7/24
Programmable 2025, 2024 has passed
Tech Skills that Matter: Pair programming with TDD


### SMART Goals

1. Meet and introduce myself to at least 5 people per event to expand my network within the next 12 months.
2. 

### Tasks

### Timeline

### Resources

### Monitor Progress



https://hack.melbourne/upcoming/calendar
find events for networking

## Question 9

With the recent improvements in Language-Learning Model technologies such as ChatGPT, artifical intelligence (AI) has had both positive and negative impact on how we live and work. It is incredibly easy to use with its access being open to everyone and free. It has become increasing mainstream in many different industries. Being compared to virtual-assistant technology, it is able to intake queries and produce human-like interactions from the complex language models it learns from. 

In software development, ChatGPT is able auto-generate code in seconds in various common programming languages like Python, Java and C#. It is currently unable to produce complex software from scratch and it prone to making mistakes (Olsen, 2023). However through it's short lifespan, frequent updates to ChatGPT demonstrate it's increasing maturity. Whether or not is will completely replace developers in the future is up for debate, but as of now, it is a very powerful tool that can be used as a catalyst for creativity and significantly improve the quality of life for a software developer. It is able to produce a solid working foundation or template of code, or automate repetitive code which will free up valuable time for Developers to use for more complex tasks. This could protentially make Software Development as an industry more accessible to the public by allowing people without prior knowledge to start writing using human language (Olsen, 2023). Additionally, it is able to assist in debugging by quickly scanning through thousands of lines of code and identifying errors, as well as recommending solutions for the errors. It can be utilised to efficiently gather information and research which can save us from scouring the web for multiple resources. The same principles also apply to other tasks like reporting writing or idea generation.

In summary, there are many uses for language-learning model technologies, but ultimately it allows us more freedom to spend time on tasks that cannot yet be automated. 

## Question 10

One of the many controversies surrounding language-learning model technologies is copyright infringement and plagiarism, as results generated are bits of information from its training data stitched together somewhat coherently (Glukhovskyy, 2023), which may infringe on others intellectual property. At this time, it has not been defined on who owns the rights to ChatGPT's outputs, and as they are not always unique per conversation, it could cause potential legal issues if information is commercially used by multiple users (Ryan, 2023). In relation to report writing, the use of these technologies without proper citation or attribution has been considered a form of plagiarism as the generated content is not original source work and should be referenced as so (Jarrah et al., 2023). However some debate that if the content is "crucially evaluated, rephrased, and properly cited, its use in academic writing can be acceptable and does not constitute plagiarism (Perkins, 2023)."

Another potential issue that arises with language-learning model technologies is Data Privacy. For example, OpenAI (Owner of ChatGPT) has acknowledged that the information from conversations executed is used and stored to train ChatGPT for future interactions, which can include personal data (O’Flaherty, 2024). To exhibit a more human-like interaction, it can use information about individuals in its responses. Although users can manually disable chat history and request to delete previous conversations, some argue that it is difficult for individuals to exercise their General Data Protection Rights against language learning models as it can manipulate data without reason, and once data has been entered, can be almost impossible to have it erased from their systems (O’Flaherty, 2024).

Although it can effectively be used to boost productivity, it will only be as good as the data is learned from. This can affect the results output to contain biases or be simply incorrect as it may not have thorough understanding of the world and its workings. Some of its responses could potentially contain discriminatory or inaccurate information. This can have major impacts if the information produced by ChatGPT is published and proves inaccurate, for example reputational damage. 

## Question 11

### Hard Skills

Hard Skills refer to techincal skills that can be learned through education, specific training or experience. They are skills that can be easily quantified and demonstrated through qualifications, portfolios or test results (Long, n.d.). These are required to successfully perform techincal task of a job, like building a website. The requirements of these skills is dependent on the job or role. Certain professions will require specific hard skills; for example becoming a Doctor or Lawyer absolutely requires specific qualifications to be practiced, in comparison to Software Engineering where qualifications may be desirable to an employer, the knowledge can be self-taught and does not necessarily require a degree. 

Some examples of Hard Skills and their importance in software development include:

- **Programming Language Knowledge** (eg. Python, JavaScript, HTML, CSS etc.) is crucial to work as a software developer. Through these languages, it enables the developer to create code for the computer to execute. The programming language used will depend on the project. It is not expected to be proficient in every language, however it is desirable to be an expert in at least one. 
- **Database Management** skills can offer many benefits to a software development workspace. It is the practice of collating, organising and protecting all the companies data that could be used for important business decisions and optimise business operations by reducing costs and increasing revenue and profits. This is required to handle sensitive data of staff and clients. 
- Strong **Typing skills** are generally not a hard skill required for many employers, however for software development it is highly impactful to increase efficiency. It allows coders to simply output more code in a shorter amount of time, which utilises company resources more effectively, and it important when working on projects tight deadlines. 


### Soft Skills

Soft Skills refer to personal traits or abilities of individual and speaks on 'how' and 'why' you do certain things, and what you're drivers are. These skills contribute to creating a functional and strong work environment (Indeed Editorial Team, 2024). Soft skills are not as easily quantified or measured, but hold significant value to the workplace. The soft skills required also are job/role dependeng, for example Contact Centre workers will need strong verbal communication skills are they are client facing and must relay information as clear and concise as possible.

Some examples of Soft Skills and their importance in software development include:

- **Problem Solving** is the process of defining or identifying a problem, determining the cause and creating effective solutions or plans to resolve the problem. This skill is required in all aspects of work It is crucial in software development as you will inevitably experience errors whilst coding, and it is important to know how to navigate these errors and debug efficiently. 

- **Ability to work in a team** is important as you will need to co-ordinate with team members to optimise efficiency. This comes hand-in-hand with another soft skill, **communication**. This can be as important as the code that is written, as it can prevent misunderstandings from occuring, affect deadlines and the output of the final product. It is important to leave clear messages or notes for teammates if they were to continue from your code so they have a clear grasp on the current progress.

- The **ability to work under pressure** is being able to perform at a high-standard with time or deadline constraints. This requires strong **Time Management** skills and planning so that all objectives are promptly being met. This is important in many roles, especailly software development as there will be deadlines for different goals that need to be met, and being able to remain focused under these pressures will ensure a higher quality of work being produced. 


## Question 12

Below are a few examples and descriptions of the many different roles you can find in software development company. 

### Software Developer

Software Developers specialise in the creation and design software or applications, by writing code in different coding languages (Open University Australia, 2022). This can range from coding the software, creating large networks/systems that manage devices or control networks, building systems to increase business operations which consumers may never see, or computer applications/apps for consumers. They work closely with Project Managers or clients to update progress, and review for possible improvements or suggestions (Kim, 2024). Some of the skills required to become a Software Developer include problem solving, strong attention to detail, Coding Language knowledge and interpersonal skills. 

### Project Manager

Project Managers oversee the entire project through its entire lifecycle, whilst managing the team toward their objective. They are in charge of defining goals, communication with stakeholders, effectively communicating between departments, all while focusing on budgets and schedules. They essentially act as the backbone of the project, ensuring the entire team operates smoothly and cohesively to meet deadlines. This position can be found in almost every company and industry. Project Managers will spend lots of time on research and analysis in the intial stages and plan all the stages required to complete their goal. 

Some competencies required include:
- Being proactive, being observant to make adjustments when needed and prevent problems before they arise.
- Conflict Management can be a major part of a project managers role. Having strong communication skills will benefit them as they can manage the team, build relationships with team members and stakeholders on all levels and keep moral high.
- Organisational skills are vital as they must delegate tasks appropriately, keep everyone on track with schedules and work seamlessly between departments. 

### QA Engineer

Quality Assurance Engineers are responsible for creating and running tests to identify any issues with the software, ensuring the product meets all quality requirements before its launch. Their duties generally include monitoring every stage of developement, identifying and analysing any bugs or errors, documenting and reviewing. They are also expected to create plans for correction, improvements or optimisations (Whitfield, 2022). These improvement plans can either be done manually or design automated software to test the products. 

### UI/UX Designers

UX/UI Designers are responsible for enhancing usability and user experience of a product. They  gather and evaluate data on user requirements to ensure the product or services meets the desired outcome (Pavlou, 2017). This includes how users interact with the product, eg. Websites, and designing the graphical elements like menus and widgets, and the overall layout. This is accomplished by generating mockups or prototypes (such as wireframes) to clearly demonstrate how the product will function and how it looks. They work closely with Product Managers and stakeholders to ensure their target goal is being met. 

Some skills to become a UI/UX include knowledge with design programs such as Adobe Photoshop/Illustrator and Wireframe tools; and Critial thinking/Problem solving, as are responsible for creating ways to optimise the overall user experience. Research and Analysis skills also play a part in determining how to improve user experience based on the information and data gathered.


### Software Architect

Software Architects are responsible for determining which processes and technologies are to be implemented by the development team, by dictacting software coding standards and selecting the optimal tools (Medushevska, 2022). They assist in the translation of ideas into technical tasks that are distributed to the allocated teams. They are often delegated critical tasks that can range from designing to engineering. There are many different types of Software Architects such as Enterprise Architects, who focus on the development and growth of IT systems in an enterprise or organisation; Data Architects who handle the collection, storage and distribution of data; and Solutions Architects whom specialise in analysing business requirements and creating/implementing solutions or products to meet those requirements. The hard skills are dependent on the job and company, however generally require sound understanding of technology environments, proficiency of coding languages and knowledge of cloud software, domains and databases. 

### Full-Stack Developer

A Full-Stack is a term to define individuals who are able to operate and have expertise in both front-end and back-end development (Coursera Staff, 2021). Although the term is generally used for web development, it can apply to all types of software development. Front-end refers to elements the users see and interact with, and back-end referring to server-side, databases, etc. all the things users can't see. 



## References

A short history of the internet. (n.d.). National Science and Media Museum. Retrieved June 17, 2024, from https://www.scienceandmediamuseum.org.uk/objects-and-stories/short-history-internet

BasuMallick, C. (2022, April 5). TCP definition, model layers, and best practices. Spiceworks Inc; Spiceworks. https://www.spiceworks.com/tech/networking/articles/what-is-tcp/

BasuMallick, C. (2023, June 16). Compiler and interpreter critical differences - spiceworks. Spiceworks Inc; Spiceworks. https://www.spiceworks.com/tech/tech-general/articles/compiler-vs-interpreter-12-critical-differences-to-know/

Ben Sadok, S. (2021, October 18). What is markup language? Examples, types & definition. Semrush Blog; Semrush. https://www.semrush.com/blog/markup-language/

Ben Sassi, R. (2023, April 24). Compiler vs. Interpreter in programming. Built In. https://builtin.com/software-engineering-perspectives/compiler-vs-interpreter

Brain, M., Chandler, N., & Crawford, S. (2024, March 7). How domain name servers (DNS) work. HowStuffWorks. https://computer.howstuffworks.com/dns.htm

Coursera Staff. (2021, December 9). What is a full-stack developer? Coursera. https://www.coursera.org/articles/full-stack-developer

Coursera Staff. (2023, August 24). What is TCP/IP? Coursera. https://www.coursera.org/articles/tcp-ip

Differences between IPv4 and IPv6. (2018, November 5). GeeksforGeeks. https://www.geeksforgeeks.org/differences-between-ipv4-and-ipv6/

Gavrilova, Y. (2023, October 31). Pros and cons of Python programming language. Pros and Cons of Python; Serokell. https://serokell.io/blog/python-pros-and-cons

Glukhovskyy, A. (2023, July 7). Is ChatGPT plagiarism? No, but it’s close. Growthtribe.Io. https://growthtribe.io/blog/is-chatgpt-plagiarism

Guinness, H. (2023, November 2). What is a router? It’s like your WiFi’s post office. Popular Science. https://www.popsci.com/technology/what-is-a-router/

Hamid, N. (2023, November 9). Future of Chat GPT and its impact on society. Linkedin.com. https://www.linkedin.com/pulse/future-chat-gpt-its-impact-society-neha-hamid-qxzpc/

Hanenko, K. (2024, April 22). Software development team roles and responsibilities. Altamira; Altamira Softworks, s. r. o. https://www.altamira.ai/blog/software-development-team-roles-and-responsibilities/

Indeed Editorial Team. (2024, May 31). Hard Skills vs Soft Skills: Understanding the Difference. Indeed.com. https://au.indeed.com/career-advice/resumes-cover-letters/hard-skills-vs-soft-skills

Indiana University. (2023, September 22). What is the difference between a compiled and an interpreted program? Kb.iu.edu. https://kb.iu.edu/d/agsz

Jarrah, A. M., Wardat, Y., & Fidalgo, P. (2023). Using ChatGPT in academic writing is (not) a form of plagiarism: What does the literature say?

Jonna, V. (2024, March 28). Advantages and disadvantages of JavaScript - ellow.Io. Ellow Talent. https://ellow.io/advantages-and-disadvantages-of-javascript/

Kim, A. (2024, April 2). Indeed.com. https://www.indeed.com/career-advice/careers/what-does-a-software-developer-do

Kurose, J., & Ross, K. (2021). Computer networking: A top-down approach, global edition (8th ed.). Pearson Education.

Long, B. (n.d.). Hard Skills vs Soft Skills. What are they? Insightglobal.com. Retrieved June 21, 2024, from https://insightglobal.com/blog/hard-skills-vs-soft-skills/

Make Computer Science Great Again. (2023, November 1). A deep dive into HTTP: The backbone of the World Wide Web. Medium. https://medium.com/@MakeComputerScienceGreatAgain/a-deep-dive-into-http-the-backbone-of-the-world-wide-web-423bb0218a51

Mcpeak, A. (2018, January 24). A brief history of web browsers and how they work. Smartbear.com. https://smartbear.com/blog/history-of-web-browsers/

Medushevska, M. (2022, July 20). The role, skills, and duties of a software architect. Syndicode - Custom Software Development Company. https://syndicode.com/blog/the-role-skills-and-duties-of-a-software-architect/

O’Flaherty, K. (2024, May 17). ChatGPT-4o is wildly capable, but it could be A privacy nightmare. Forbes. https://www.forbes.com/sites/kateoflahertyuk/2024/05/17/chatgpt-4o-is-wildly-capable-but-it-could-be-a-privacy-nightmare/

Olsen, T. (2023, April 4). Chat GPT: Should software developers be worried? Linkedin.com. https://www.linkedin.com/pulse/chat-gpt-should-software-developers-worried-tim-olsen/

Open University Australia. (2022, October 6). What is a software developer and what do they do? Edu.au. https://www.open.edu.au/advice/insights/what-is-a-software-developer-and-what-do-they-do

Pavlou, C. (2017, August 31). UI/UX Designer job description. Recruiting Resources: How to Recruit and Hire Better; Workable. https://resources.workable.com/ui-ux-designer-job-description

Perkins, M. (2023). Academic Integrity considerations of AI large language models in the post-pandemic era: ChatGPT and beyond. Journal of University Teaching & Learning Practice, 20(2).

Petrova, B. (2023, May 30). DNS history. When and why was DNS created? ClouDNS Blog. https://www.cloudns.net/blog/dns-history-creation-first/

Raval, N. (2024, February 29). JavaScript Statistics: Latest usage insights and trends 2024. Radixweb. https://radixweb.com/blog/top-javascript-usage-statistics

Rich, S. (2023, February 22). Why ChatGPT AI is controversial. Linkedin.com. https://www.linkedin.com/pulse/why-chatgpt-ai-controversial-steven-rich-mba/

Ryan, E. (2023, June 15). What Are the Legal Implications of ChatGPT? Scribbr.com. https://www.scribbr.com/ai-tools/legal-implications-chatgpt/

Seibert, L. (2023, March 20). Understanding the importance of web accessibility. Forbes. https://www.forbes.com/sites/forbesbusinesscouncil/2023/03/20/understanding-the-importance-of-web-accessibility/

Severance, C. (2015). Introduction to Networking: How the Internet Works.

Software Developer. (n.d.). SEEK. Retrieved June 19, 2024, from https://www.seek.com.au/career-advice/role/software-developer

Thakur, S. (n.d.). Unstop - competitions, quizzes, hackathons, scholarships and internships for students and corporates. Unstop.com. Retrieved June 22, 2024, from https://unstop.com/blog/advantages-and-disadvantages-of-javascript

Understanding markup languages: Examples, types & definitions. (n.d.). Ranked.Ai. Retrieved June 17, 2024, from https://www.ranked.ai/post/understanding-markup-languages

University of Edinburgh. (n.d.). Gibbs’ reflective cycle. The University of Edinburgh. Retrieved June 19, 2024, from https://www.ed.ac.uk/reflection/reflectors-toolkit/reflecting-on-experience/gibbs-reflective-cycle

Villanueva, M. S. (2021, November 26). What is DNS, and Why is it Important? Itsasap.com. https://www.itsasap.com/blog/what-is-dns

What is an IP Address? How it works? How to Locate it? (n.d.). Fortinet. Retrieved June 17, 2024, from https://www.fortinet.com/resources/cyberglossary/what-is-ip-address

What is Hypertext Transfer Protocol (HTTP)? (n.d.). F5, Inc. Retrieved June 22, 2024, from https://www.f5.com/glossary/hypertext-transfer-protocol-http

Whitfield, B. (2022, May 2). What is a QA engineer? How to become one, salary, skills. Builtin.com; Built In. https://builtin.com/learn/careers/qa-engineer

(N.d.). Similarweb.com. Retrieved June 22, 2024, from https://www.similarweb.com/browsers/