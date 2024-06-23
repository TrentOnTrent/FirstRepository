## T1A1 Workbook

Q1. ***Identify*** and ***explain*** common and important components and concepts of web development markup languages.

A: Web development markup languages (such as HTML, Markdown and XML, with others available) are utilised to define how the layout and presentation of elements of a page should appear on a website. HTML specifically refers to meaning and structure of web content [according to Mozilla](https://developer.mozilla.org/en-US/docs/Web/HTML). Markup languages are different from programming languages in that they focus primarily on the presentation and structure of content, rather than being utilised to create functional and dynamic web applications. 

Source: https://developer.mozilla.org/en-US/docs/Web/HTML

Q2. **Define** the features of the following technologies that are essential in terms of the development of the internet:
 - packets 
 - IP addresses (IPv4 and IPv6) 
 - routers and routing 
 - domains and DNS 

A: Packets are small containers of data sent through a network. As described by [Cisco in their Networking Basics article](https://www.cisco.com/c/en/us/solutions/small-business/resource-center/networking/networking-basics.html#~switches), upon reception by the recipient, these packets are collected, placed in the correct order, and then assembled into the original file, such as an image (referenced from Cisco's Networking Basics).

Source: https://www.cisco.com/c/en/us/solutions/small-business/resource-center/networking/networking-basics.html#~switches

According to the American Registry for Internet Numbers (ARIN), IP addresses are a unique numerical identifier for every network or device that connects to the internet. These work as a way to identify where data is to be 
sent (in packets) and allows two devices to communicate with each other. Typically, they are expressed either in IPv4 or IPv6 format. The main difference between the two is the use of 32-bit for IPv4 and 128-bit for IPv6, allowing more options availble than the 4.3 billion IP addresses available only under IPv4.  

Source: https://www.arin.net/resources/guide/resourceguide.pdf

As described by TechTarget in their [routers definition](https://www.techtarget.com/searchnetworking/definition/router), routers are devices that allow multiple devices to interact with each other, utilising an IP address in order to collect data sent to the IP address. Routing is the actual process of how data and packets travel from their origin to their destination, as the routers decides which network and which routers to travel data through.  

Source: https://www.techtarget.com/searchnetworking/definition/router

The International Corporation for Assigned Names and Numbers describes a domain name as a string of text that corresponds to a certain IP address, typically used in order to load a website/data from a server. DNS is Domain Name System, which is the system that is utilised that turns an IP address into a website name/domain name and vice versa. 

Source: https://www.icann.org/resources/pages/dns-2022-09-13-en#:~:text=The%20DNS%20connects%20the%20IP,address%20book%20of%20the%20Internet.

**Explain** how each technology has contributed to the development of the internet.

A: Each technology above has been utilised in order to create a network and allow data to be sent easily from one device to another through packets, as well as the process being simple to utilise as an end user. 

Q3. **Define** the features of the following technologies that are essential in terms of the development of the internet:
 - TCP
 - HTTP and HTTPS
 - web browsers (requests, rendering and developer tools)

 A: TCP (Transmission Control Protocol) is the standard that allows programs and devices to exchange packets and messages over a network. TCP establishes a connection between the origin and destination of data and ensures that the connection remains while it begins breaking down large amounts of data into smaller packets, ensuring data integrity. This results in a reliable, connection-orientated, byte-streamed protocol, according to [Cisco's Understanding TCP/IP article](https://www.cisco.com/E-Learning/bulk/public/tac/cim/cib/using_cisco_ios_software/linked/tcpip.htm#:~:text=applications%20is%20redundant.-,Transmission%20Control%20Protocol,oriented%2C%20byte%2Dstream%20protocol.)

 Source: https://www.cisco.com/E-Learning/bulk/public/tac/cim/cib/using_cisco_ios_software/linked/tcpip.htm#:~:text=applications%20is%20redundant.-,Transmission%20Control%20Protocol,oriented%2C%20byte%2Dstream%20protocol.

 Mozilla's [MDN documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP) describes HTTP (Hypertext Transfer Protocol) as a set of rules that is utilised when visiting a website. When visiting a website, the web server hosting that website will send different types of HTTP responses in the forms of three-digit numerical codes, which allow the website to confirm or inform the browser whether the request for data has been completed. HTTPS is similar, but creates an encrypted connection between the host and the browser before transferring data.

 Source: https://developer.mozilla.org/en-US/docs/Web/HTTP

Browsers are, ultimately, the programs that are utilised in order to handle web requests, sending and receiving (getting) HTTP requests and turning packets into user-friendly websites and data. Web browsers also offer developer tools, which are easily viewable tools that show to the user how content is visualised and how this is being handled by the browser itself.

 **Explain** how each technology has contributed to the development of client and server communication over the internet.

 A: These technologies have ensured that there is a common and well-structured method that is utilised between client and servers over the internet to access data. TCP allows the data to be broken down succesfully into smaller packets when being sent to the client. HTTP allows the client to send codes to the client indicating whether or not a request was successfully made (or what is further required from the user). Web browsers and their tools allows the end user to determine whether there were issues regarding the data transfer, and also allows the developer of a website or web application to determine if data has been transferred correctly.

 Q4. **Describe** the features of interpreters and compilers and how they are different.

 A: Interpreters and compilers both turn a high-level coding language into machine code. As computers cannot natively translate human-readable code into a set of instructions, compilers and interpreters are created in order to convert human-readable code into instructions for a computer. A compiler translates code before the code is run, compiling the entire code into machine code. An interpreter, however, does this on a line by line basis, and turns the code into machine code as the program is running, not beforehand. 

 Source: https://builtin.com/software-engineering-perspectives/compiler-vs-interpreter

 Q5. **Identify** TWO commonly used programming languages and **explain** the benefits and drawbacks of each.

 A: Two commonly used programming languages that are utilised are Python and C. Python is a high-level object-orientated programming language, whereas C is a low-level programming language and is not considered natively object-orientated. Due to C being a compiled language and the more specific memory management required, this can result in C programs being able to be executed faster, as they do not require a level of interpretation being run. However, as C does not have garbage collection (freeing of memory utilised by the program), this does require extra care being taken to the use of memory that the program utilises. On the other hand, Python is a object-orientated language natively, and does contain native garbage collection. As well, Python has a large collection of libraries, which are a range of modules and packages that allow easily-installable code to be utilised within functions. 

 Q6. A hypothetical client has sent you an email (shown in the **Q6 Email** section), asking for you to build them a website. Write an appropriate, professional email response that shows your understanding of the client’s needs for the website, as well as an understanding of appropriate technologies or tools needed to build the website yourself.

 A: Hi Alex!

 Thank you for very much for reaching out for this project! My name is Trenton Dunstan and I would be thrilled to help out creating a website for the Super Awesome Museum (SAM).

 Based on your requirements, I would anticipate creating a user-friendly website that not only highlights SAM's fascinating exhibits but also provides essential information for the museum.

 To achieve this, I propose utilizing modern web development technologies and tools such as HTML, CSS, and JavaScript for the frontend to ensure a visually appealing and responsive design.

 Thank you once again for reaching out to myself for this project. I look forward to the opportunity to collaborate with you and contribute to the success of the Super Awesome Museum.

Best Regards,

Trenton Dunstan

 Q7. Think back to a scenario or situation in your own software development projects or work.
Explain how you would do things differently if you had a chance to go through that scenario again, using an appropriate reflective cycle or reflection technique.

A: A software development project I am involved in professionally is maintaining an extensive and feature-rich Word template written in VBA. In order to better facilitate the development of the template, I would create a kanban board in order to organise different tasks and prioritise which features/bugs are required to be worked on, and in order to keep track of what features have been created during certain times.  

Q8. A large part of career growth as an information technology professional happens through networking and workshops, often found at online or in-person events or workshops. 

Create an action plan that identifies several relevant networking opportunities for you to participate in or attend, and add some information about what you expect to gain or grow through each item in the action plan.

A: The first item in the action plan would be to join/attend software development-related meetup events occuring, such as [Brisbane Coder Club](https://www.meetup.com/en-AU/brisbane-coder-club/) and [Brisbane Full Stack User Group](https://www.meetup.com/brisbane-full-stack-user-group/). In meetups such as these, I would anticipate to gain knowledge about various professional organisations and practices that are commonly used in the industry. As well, being active on social media like LinkedIn and Twitter/X will be a strong way of socialising and connecting with fellow developers and a way of developing skills industry-ready skills.

Source: https://www.meetup.com/en-AU/brisbane-coder-club/; https://www.meetup.com/brisbane-full-stack-user-group/

Q9. Explain the uses of language-learning model technologies (such as ChatGPT) on written and technical works, such as reports and software projects.

A: Large language models (such as ChatGPT) are AI models that have been trained on vast amounts of data. [OpenAI](https://www.openai.com/about/) describes that they can be used for generative AI, which produces data and content based on prompts made by users. This ability to create content means that large language models can create written and technical documents very quickly, and can replace requiring manually writing reports and written documents.

Source: https://www.openai.com/about/

Q10. Explain the legal and ethical impacts of the usage of language-learning model technologies (such as ChatGPT) in written and technical works, such as reports and software projects.

A: Large language models learn from a vast amount of data, and have been known to utilise copyrighted material (such as articles, online content and written works). As such, this leaves the potential for large language models to produce text based on a copyrighted source. As well, large language models have been trained on a large and potentially unknown set of data, which can then produce unexpected results without careful tailored inputs and prompts. 

Source: https://www.eff.org/issues/ai

Q11. Explain multiple skills from each of the categories below, and how they’re useful to a software development workplace.

* soft skills
* hard skills

A: Soft skills are typically personality traits and personal qualities that allow interdepartmental communication and teamwork to thrive in an company. In a software development workplace, this would include strong communication skills between departments, collaborative qualities to ensure team work and morale is upheld, and leadership qualities in those who may become a team leader or product manager.

Source: https://www.hays.com.au/it/career-advice/it-upskilling-soft-skills

Hard skills are more technical skills which are job-specific and is knowledge that is required to facilitate the execution of the job. In a software development workplace, this may include strong programming skills in multiple languages, knowledge of best practices, usage of version control software, and well-established knowledge in data structures and algorithms. 

Source: https://www.investopedia.com/terms/h/hard-skills.asp

Q12. Explain multiple roles or job positions that would be found in a medium-sized software development company.

A: Multiple roles that can be expected to be found in a medium-size software development company include full-stack developers/software developers (both junior and senior roles), testing analysts and test leads, product managers and product owners, UX/UI designers, business analysts, engineering managers and scrum master (if utilising Agile methodologies)

Source: https://www.seek.com.au/career-advice/article/what-are-the-different-careers-in-it