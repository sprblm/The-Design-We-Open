# Design for Internet Shutdowns in Taiwan
## Taxi Drivers, Satellites, and Tech: The Surprising Heroes in Taiwan's Fight Against Internet Shutdowns.

![img](https://github.com/sprblm/The-Design-We-Open/blob/main/Documenting%20Internet%20Shutdowns%20Workshop/graphics%20and%20illustrations/Large%20Splash%20Image-solution-11-28.jpg)

---

# Executive Summary

Designers have a crucial role to play in the internet freedom open-source ecosystem. This report describes the importance of designers working on technology for high-risk contexts, as explored during a hands-on workshop at COSCUP 2023 and follow-up workshop at COSCUP 2024. 

Open-source software (OSS) teams provide a crucial resource to activists in high-risk environments by offering privacy and security tools that help them organize safely. However, many users struggle with the complexity of OSS tools. They often look and feel different than "standard" big tech tools, which can make them challenging to figure out: not only are the privacy settings and security features different, there are systemic barriers making collaboration between OSS developers and designers more difficult. Design is often not considered or supported in the internet freedom OSS funding landscape. The predominant collaboration platforms are not optimized for design contributions. However, events like this one can help to bring designers and developers together, leading to tools that are both functional and intuitive.

COSCUP, a major open-source conference in Taiwan, is free to attend and run by volunteers from the Taiwanese open-source community. Since 2006, COSCUP has been a forum for community-building around internet freedom, privacy, and security, with a particular emphasis on people who are at high risk due to their political activities. Taiwan has strong free speech protections, which allows COSCUP to hold a neutral space for discussion and problem-solving. Taiwan's worldwide ranking for internet freedom is high, with a 90.7% internet penetration rate and a strong civic tech community promoting transparency. Taiwan is also an important use case for internet freedom OSS tools. Given Taiwan's geopolitical relationships and risks of natural disaster, developing tools for preparedness and resilience is at the forefront of many COSCUP workshops and hackathons.

At COSCUP 2023, Superbloom conducted a workshop on ‘Designing for Human Rights and Internet Freedom OSS,’ where participants created user personas, journey maps, and strategies to address digital restrictions. These outputs were documented, translated into Chinese, and published on GitHub for accessibility and continuity. In this report, we lead readers through the process and outputs of the workshop: the schedule, the activities, and the outputs of each team. 

However, our aim is not just to report on a single workshop, but to provide a blueprint for similar workshops connecting the dots between design and internet freedom. We supply a starter pack to encourage readers of this report to convene a similar workshop of their own. We make suggestions for the logistical aspects of workshop preparation (who to invite, what kind of space to use) as well as including activities and methods you may want to use. We hope that this documentation serves to bring people together in the name of bringing usability and accessibility to internet freedom OSS tools, in Taiwan and worldwide.

![img](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/Documenting%20Internet%20Shutdowns%20Workshop/graphics%20and%20illustrations/document%20image%20dividers/crowd-full-width.png)

_Image caption: An image of four people, smartphones, technology devices. The people are in internet browser ‘frames’ with speech bubbles symbolizing discussion. A person is holding a Taiwanese vegetable bag ‘gaji bag’ 茄芷袋 and two are wearing good luck charms._

---

Throughout this markdown text file you will find English written text only. You can also find the [English only document here](https://github.com/sprblm/The-Design-We-Open/blob/main/Documenting%20Internet%20Shutdowns%20Workshop/No%20Executive%20Summary%20-%20of%20Design%20for%20Internet%20Shutdowns%20in%20Taiwan%20-%20Report%20(en%20only).pdf). The [Mandarin only document here](https://github.com/sprblm/The-Design-We-Open/blob/main/Documenting%20Internet%20Shutdowns%20Workshop/%E9%96%8B%E6%BA%90%E8%A8%AD%E8%A8%88%E5%B7%A5%E4%BD%9C%E5%9D%8A-%E6%8D%8D%E8%A1%9B%E5%8F%B0%E7%81%A3%E7%B6%B2%E8%B7%AF%E4%B8%AD%E6%96%B7%E8%8B%B1%E9%9B%84%20-%20Report%20(cn%20only).pdf) and the [Mandarin only markdown text file here](https://github.com/sprblm/The-Design-We-Open/blob/main/Documenting%20Internet%20Shutdowns%20Workshop/%E9%96%8B%E6%BA%90%E8%A8%AD%E8%A8%88%E5%B7%A5%E4%BD%9C%E5%9D%8A-%E6%8D%8D%E8%A1%9B%E5%8F%B0%E7%81%A3%E7%B6%B2%E8%B7%AF%E4%B8%AD%E6%96%B7%E8%8B%B1%E9%9B%84-cn.md). The [English and Mandarin document is here](https://github.com/sprblm/The-Design-We-Open/blob/main/Documenting%20Internet%20Shutdowns%20Workshop/No%20executive%20summary%20-%20of%20Design%20for%20Internet%20Shutdowns%20in%20Taiwan%20-%20Report%20(en%20%26%20cn).pdf) and the [English and Mandarin markdown text file is here](https://github.com/sprblm/The-Design-We-Open/blob/main/Documenting%20Internet%20Shutdowns%20Workshop/design-for-internet-shutdowns-in-taiwan-report-en-cn.md).

# Why Design and designers are important for Internet Freedom OSS

The enthusiasm that technologists express when speaking about human rights, civic tech and privacy and security tools is admirable. They create and configure these tools, advocate for their use and their continual improvement with a passion that is frequently connected to a very real and intense life experience. Yet when you speak to the users of these tools, ordinary people, not especially technologically experienced, though experienced enough to know that they need these tools in order to stay safe, private and independent you hear the similar passion for human rights sprinkled with moderate to large amounts of frustration. 

- *“Why can’t the privacy settings be more clear and understandable?”*

- *“It’s so difficult to communicate to the people we train in digital privacy that to be safe, they have to switch VPN sometimes. It’s hard to communicate why”*

- *“Well I use these tools for my journalism reporting but, honestly I still use big techs communication tools too, even though I know it’s risky they are easier to use and my family won’t switch to secure tools.”*

Technologists notice these issues from their users as critical usability bugs in their technologies. Here is where designers and their design practices can mitigate problems for users and equalize the access and use of critical human rights and civic technologies. Designers seek to prioritize both expert and novice use of technology.

Designers and their practices bridge the experiences between tool developers and citizen users. It should never be a requirement to fully comprehend the technologies inner workings in order to use it to be safe. Here is the bridge designers and technologists in partnership build to bring users across, towards safe and secure existence and interaction with tech. Designers humanize the needs and purposes of technology in order to make it useful across a spectrum of global daily life experiences. Designers want to, by their very practice, include and make accessible. Designers, when given the opportunity to use design practice to do good, will do good.

Yet the barriers for designers and design practice to be normalized in Internet Freedom OSS technology are great. Design practice often registers as less vital than technological skills. Less budgeted for, less respected, less served by online collaboration platforms yet in design practice is where the interaction between the lived experience of the human meets technology and is humanized. Humanising technology and understanding these high risk, complex human rights defenders experiences is where we find the focus of the design events and hackathons like those hosted at COSCUP.

_“The team found that the workshop format was effective in bridging the gap between technical and non-technical participants, showing the power of design processes in building and improving technology”_ **- Sugar from Team Cake**

![img](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/Documenting%20Internet%20Shutdowns%20Workshop/graphics%20and%20illustrations/document%20image%20dividers/notebooks-full-width.png)

---

# Why COSCUP is an important event for Internet Freedom OSS

COSCUP is one of the biggest and important international open source events in Taiwan. It receives a high number of participants interested not only in tech but also design which makes it a great spot for discourse from critical perspectives of people involved in building solutions for internet freedom i.e. technologists and designers. COSCUP is also very welcoming and offers flexibility in tailoring workshops and discussions around open source and internet freedom topics. 

COSCUP, being held in Taiwan, also offers a neutral or rather a more positive space (geographically) with a freedom of speech and freedom of press to talk and spread ideas concerning sensitive topics such as the human rights especially those of the marginalized communities who are most in need of internet freedom tools and technologies to protect their privacy and security digitally. There are also other organizations and individuals in Taiwan working on complex issues of human rights  and building civic technologies. If anything, there needs to be a greater involvement among such persons. Most countries surrounding Taiwan may not offer the same level of freedom. This makes COSCUP an important event for internet freedom OSS in South East Asia and broader parts of Asia. 

The need for privacy, security and finding ways to stay connected as a community in the face of internet instability is also very real for the Taiwanese. They recognize their relationship with CCP, they understand the natural calamity can impact their infrastructure and hence believe in staying prepared. From our experience of running workshops in COSCUP, these have been key problem areas that the participants chose to design their solutions for. 

_“Speculating on a ‘war situation’ we Taiwanese think that Taiwan would go through circumstances similar to the Russo-Ukrainian War with actual military intervention...China has already employed cognitive warfare strategy, through disinformation, military intimidation, and influence operations for many years.”_ **- Biscuit from Team Cheesecake**

![image](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/Documenting%20Internet%20Shutdowns%20Workshop/photos/coscup-2023.png)

_Image caption: A photo from COSCUP 2023 showing the poster of the event and the welcome desks._

![img](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/Documenting%20Internet%20Shutdowns%20Workshop/graphics%20and%20illustrations/document%20image%20dividers/bubble-tea-full-width.png) 


---

# Taiwan's relationship to internet freedom and OSS 

*What are the threats to internet freedom in Taiwan and what do regular people and technologists think about internet freedom?*

Taiwan is widely recognized for its high level of internet freedom, ranking sixth globally and first in Asia according to Freedom House's 2023 report. With an internet penetration rate of 90.7% as of January 2024, Taiwanese citizens view internet access as a fundamental right. This freedom has fostered a vibrant civic tech community that collaborates with the government to promote transparency and openness.

However, Taiwan faces unique challenges to its internet freedom. The country is on the frontline of China's "Cognitive Warfare," which includes disinformation campaigns, military intimidation, and influence operations. These threats have put pressure on Taiwan's online information ecosystem, potentially manipulating public opinion and threatening the integrity of its digital spaces.
The open source software (OSS) community in Taiwan has responded to these challenges by developing locally-focused projects. Many of these initiatives, like the fact-checking bot Cofacts, are designed to address Taiwan-specific issues and are deeply integrated into popular local platforms. While this approach effectively serves the Taiwanese context, it can make these tools difficult to replicate in other countries.

---

# What is the purpose of this Document?

As it would be apparent from the above sections, Superbloom conducted a workshop at COSCUP in 2023 on the topic of ‘Designing for Human Rights and Internet Freedom OSS’. This workshop brought together different kinds of contributors (developers, engineers, designers and OSS enthusiasts etc.) to utilize design practices, methods and research to explore the topic of internet shutdowns and censorship in Taiwan and how OSS technology can be used and improved from their perspectives. During the workshop, the participants developed various artifacts such as -  improved personas, detailed user journey maps, discovering problems and finding solutions to prepare for internet shutdown scenarios. 

The purpose of this report/output is to preserve and present all the artifacts in a structured, translated(in Chinese) and detailed manner along with design experts’ contexts. These outputs are also published on a public GitHub repository so that there’s a continuity with future workshops as opposed to being lost and forgotten. This output includes commentary on how to run similar workshops thereby enabling other design facilitators to learn and recreate them. We hope others will iterate on these resources, reference them in future workshops and build on this work.

In summary, we hope that this will:
- Enhance accessibility and understandability of the workshop artifacts
- Increase knowledge sharing and collaboration on this topic
- Empower other design practitioners
- Increase community engagement and participation
- Lead to productive solutions that benefits people in need


![image](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/Documenting%20Internet%20Shutdowns%20Workshop/photos/design-workshop-1.jpg)

_Image caption: A photo from the workshop. 5 people around a table with large paper, sticky notes and pens write._

---

# Who should read this? 

This report is for anyone interested in human rights and internet freedom OSS design and ideation process, but it will especially benefit the following audiences:

1. **Human rights technologies and organizations:** The resources will provide valuable insights and actionable solutions related to understanding and addressing internet shutdowns, benefiting organizations working in the realm of human rights and digital freedom.
2. **Design practitioners and facilitators:** The resources offer insights into the design process, facilitating learning and inspiration for practitioners interested in employing similar methodologies in their workshops.
3. **Workshop participants and contributors:** Participants who attended the original workshop and contributed to the creation of artifacts will benefit from having their work documented and made accessible in a more structured format, enabling them to revisit and build upon their ideas.
4. **Future workshop facilitators and participants:** The resources published on a public GitHub repository will serve as a reference and guide for future workshops, ensuring continuity and enabling iterative improvements based on past experiences.

![image](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/Documenting%20Internet%20Shutdowns%20Workshop/photos/COSCUP-stage-lights-set-up.jpg)

_Image caption: A photo of the main lecture hall at COSCUP’s venue. Some people are setting up a camera and a light umbrella and most of the seats are full with audience members._

---

# Workshop Methods and processes

## Introduction and framing the workshop / 工作坊的介紹與框架

When beginning the workshop, there must be a welcoming and inviting feeling. Many designers have not experienced the Free and Open Source (FOSS or OSS) space or gained much experience with the Internet Freedom, Human rights technology or censorship circumvention technology space. The OSS and Human Rights technology space share many commonalities and the development and coding practices are familiar to each other, but design in both these spaces are rare. Ensure that workshop participants are welcome to bring their own thoughts, critique and experience as well as asking detailed and basic questions is welcome.
This workshop can be attended by designers, coders, developers, technologists and those interested in OSS or involved in OSS. It's also good for journalists, human rights defenders, civic technologists or people who work at NGOs or charities that are committed to a non-political/non-partisan, human rights inclusive approach. People involved in 'Big Tech', surveillance technology or who are politically aligned can also join these workshops, especially if they are openly accessible and available, but the framing of the workshop should be clearly communicated that we are prioritizing privacy, security and digital human rights globally with this work.

![image](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/workshop%20slides/The%20Design%20We%20Open%20Workshop%202023/COSCUP%202023%20-%20The%20Design%20We%20Open%20-%20cover.jpg)

_Image caption: An image of the title slide from the workshop. The text reads “The Design We Open Workshop - 網路中斷黑客松”. There is an image of a femme person with long dark hair and dark clothes and a masc person in a white shirt. The femme person has a laptop open and they are both looking towards a large screen with a computer UI displayed on it. The wall behind the screen has many orange, yellow and pink sticky notes on it._

---

## Facilitators

For this workshop, it is important to have some different sectors and expertise present. We recommend local design groups (e.g. IxDA, Ideo, Ladies that UX etc.), OSS designers and/or coders, developers or maintainers of those OSS projects and designers who are experts in the internet freedom, human rights and censorship circumvention technology space. Facilitation should ideally be shared between these groups and done by those who feel most comfortable and able to facilitate in an engaging and clear way towards the designers and technologists participating in the workshop.

_“In the team, most people identified as engineers, one person had some design training but was not currently in a design job role. However, they ended up playing a key facilitation role between the engineer discussions and keeping the focus on the users.”_ **- Sugar from Team Cake**

---

## Open source design experts

People who work on or have contributed to OSS generally are valuable participants of this workshop. They are able to give insight and context on OSS culture, communication and expectations across a broad selection of OSS projects. They can also typically operate and use the interfaces and processes needed to contribute to OSS more quickly and effectively than those completely new to these but also can support and teach other participants at the workshop how to use OSS processes and functions e.g. how to submit an issue, how to create a branch, how to install, run and use an OSS project/tool.

_“I was curious about open-source software and found the internet shutdown scenario. This experience has reinforced my view of GitHub as a collaborative platform where developers can gain valuable insights on their projects. I have created my own OSS project since the workshop.”_ **- Pepperoni from Team Pizza**

![image](https://github.com/sprblm/The-Design-We-Open/blob/main/Documenting%20Internet%20Shutdowns%20Workshop/photos/Group-10.png?raw=true)

_Image caption: A photo of the workshop from behind. There are many masc and femme presenting people facing towards a projector screen where the workshop facilitators are standing with a microphone. Behind the facilitators is a wall of colorful sticky notes. The room is a classroom style with white walls, gray and brown tables filled with notebooks, sticky notes, pens and laptops and there are plastic chairs._

---

## Internet freedom tool experts

These can be designers, technologists or people who have worked/volunteered in the NGO, Internet Freedom, Journalism or Civic Technology space. They offer insight into the complex and nuanced challenges faced by those institutions and individuals doing human rights advocacy and work. The areas of knowledge are broad and it's best to look for people with knowledge in a specific type of human rights depending on the focus of the workshop. For example, our workshop in 2023 focussed on experiences of journalists, researchers and protestors who are at risk of being surveilled as well as targeted with online harassment and violence when they have critical information or attendance at events that may target them as human rights defenders. Along with these types of people we also focussed on when the internet is shut down or when certain information (or access to information) is censored.

_“I appreciated the civic and social focus of the workshop, which contrasts my day job where design must always be monetized for commercial purposes. The most educational part came from the feedback provided by the designers working in Internet Freedom and those with experiences of these complex  Human Rights issues. I found it valuable to directly see how different teams approached the same topic with unique processes and solutions.”_ **- Mint from Team Mojito**

---

## Local design community experts

Local design expert community groups (e.g. IxDA, Ideo, Ladies that UX etc.) should be present at the workshop to act as experts in design processes and practices but also how these processes and practices are done in the country's local context. We should not assume that design processes are the same all around the globe.

![image](https://github.com/sprblm/The-Design-We-Open/blob/main/Documenting%20Internet%20Shutdowns%20Workshop/photos/Group-1.jpg)

_Image caption: A photo of 6 people gathered at the workshop having a discussion. One person with pink and blue hair and tattoos on their arm is speaking and the others are listening. There are femme people with long dark hair and masculine folks with short dark hair. Everyone is wearing COSCUP conference lanyards around their necks. One masc and one femme person are wearing blue t-shirts with the community logo for IxDA Taiwan - Interaction Design Association Taiwan is a community group for interaction designers in Taiwan._

---

## Clear planning and agenda in OSS contribution

It's important to enable many forms of engagement in a workshop where you are aiming to investigate open source technology and make contributions. Some participants may want to work on their own machines for privacy and security reasons and also may not be comfortable connecting to insecure internet services. We also made sure that participation via writing and using sticky notes, pens and paper was prioritized. 

These methods often allow for better collaboration, communication and also spreads the risk of who added what detail and when, across a larger group of people. Paper, when digitized carefully can be more anonymous and also can be destroyed more completely than digital files that often leave a traceable trail when interacted with.

We also ensure that setting an agenda with objectives is clear from the beginning. Ensuring that there is the ability to be flexible within these times should participants want less or more time on certain activities and processes. There doesn't need to be very strict times for each activity but allowing for a minimum and a maximum time can help with planning the overall objectives of the workshop.

**The overall objective for this iteration of the workshop were:**
- Map and understand user behaviour during internet shutdowns and crisis
- Understand and explore the OSS tools ecosystem in a Taiwan context
- Ideate how OSS tools can 'fight' internet shutdowns can be designed better for Taiwanese citizens

We advise building in time to have participants that are interested in speaking out loud to the group about progress on ideas and activities that are included in an agenda plan. Sharing ideas out loud when working in smaller groups for a larger event can allow for people to be inspired by others' findings, ideas and processes which can enrich the ideas overall.

---

## Openness and safety

Due to the sensitive nature of the subject matter of this workshop, we make sure to announce that Internet Shutdowns and Human Rights in technology is a difficult and dangerous subject and that we want participants to be safe. This means that we request participants to be careful with what they say, if they feel like it could put them at risk if shared outside this workshop. Additionally the organizers of the workshop or the participants may want to create their own threat/risk models and threat/risk analysis. This can be a simple written or verbal document that if a topic is discussed they may need to remove themselves from that subject or the entire workshop at that point or that they make sure to use an alias unconnected to their legal identity throughout the workshop. They can also opt out of topics and discussions and let others in the group know (with consent) what the impact could be to them if a certain topic was discussed.

![image](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/workshop%20slides/The%20Design%20We%20Open%20Workshop%202023/COSCUP%202023%20-%20The%20Design%20We%20Open%20-%20openness%20and%20safety.jpg)

_Image caption: A screengrab of the slide used in the workshop for openness and safety. The text reads: “Guiding principles and openness of results and anonymisation. Internet Shutdowns and human rights in technology is a difficult and dangerous subject. We want you to be as safe as possible so we encourage being careful with speaking about what we explore today. Some of these OSS tools are used to actively allow citizens to access and share information that national governments would prefer citizens not to access and share._

Some of the OSS tools are used to actively allow citizens to access and share information that certain institutions, organizations and governments would prefer citizens not to access and share. This is a critical topic to discuss in these kinds of workshops but OSS tools should only be accessed, tested and used on participants' own device if they feel comfortable and not pressured to do so by the group. Alternatively, we recommend bringing test devices with OSS tools pre-loaded on these devices to be used if possible.
We recommend participants to not share insecure contact details with each other, to be careful with disclosing any political opinions or personal details about themselves unless they are very sure that they are safe and can trust the one they're sharing with.
In the absence of experts in any area, participants who feel they have enough insight into those topics can act as experts or those questions and topics can be deferred until post workshop when answers or details can be gathered.

---

## Forming groups

There are many methods that can be used to help people form groups. We recommend that groups be no less than 3 people and no more than 6 when collaborating in a workshop environment on OSS and Internet freedom projects. It's good to encourage participants to spread out the various functions they can perform and insights they can give.
For example, you want to encourage a group to have a 2 / 2 / 2 ratio - 2 designers, 2 OSS technologists/developers and 2 Internet Freedom/NGO insights people. Some people can perform more than one of these roles (e.g. A designer might also work in an NGO or an OSS developer might also have experiences of protests) which is fine. As long as your groups have diverse experience, skills and insights and can communicate and collaborate respectfully, you have a good group.
We try to encourage people to meet new people in these workshops which can be effective in mixing up experiences, perspectives and allows for some skill sharing. We used the 'shopping list' method for mixing up teams - everyone in the room thought of an ingredient for their favorite food or drink. (e.g. 'cheese') and then 1 group leader is picked to say out loud the ingredients that makes their food of choice, out loud they will say 'I need pepperoni!' and if another person chose pepperoni they would join that team. The group leader then keeps saying ingredients for their food until they have 5-6 people and as many ingredients as they can to 'make' that food. The team's name then becomes their food type e.g. 'Team Pizza'.

![image](https://github.com/sprblm/The-Design-We-Open/blob/main/Documenting%20Internet%20Shutdowns%20Workshop/photos/Group-11.png?raw=true)

_Image caption: A photo from the workshop that shows the entire room. 5 groups of people are gathered at their own tables and are enthusiastically discussing the topic of ‘Personas’. There is a large projector screen at the front of the classroom and tall windows on the left. There are many laptops, notebooks and sticky notes on the tables._

---

## Tool landscape and tool demo

Participants attending the workshops or hackathons might not have in-depth expertise or knowledge about the kinds of tools, users or problems that the workshop hopes to tackle. This expertise is built up during the first half of the workshop from each person in the group sharing what they know with each other but also through the facilitation of the workshop. We kick off the contextual understanding of the workshop with some introductions, demos and explanations of the types of technologies and tools that can be used for the purposes of censorship circumvention and human rights activism. These don't need to be complete, comprehensive demos and you don't need to be an expert or a user of these tools (it helps if you know the basic functionality of the tools you speak about) but fundamentally, letting participants know what exists and what is technologically possible in the space already helps them to better understand the limitations and explorations of what they will investigate later.

_“I was curious about open-source software and found the internet shutdown scenario. This experience has reinforced my view of GitHub as a collaborative platform where developers can gain valuable insights on their projects. I have created my own OSS project since the workshop.”_ **- Pepperoni from Team Pizza**


## Destiny

In this workshop we covered a few different technologies, a 'magic wormhole' desktop and mobile app called Destiny (made by Least Authority) that allows users to send files using unique codes that are entered into the app to verify the receiver/sender. The file only sends and receives when both the sender and receiver have the app open on an active connection at the same time. This tool ideally means that sensitive files can be sent more privately with less traceability for people involved.

![image](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/workshop%20slides/The%20Design%20We%20Open%20Workshop%202023/COSCUP%202023%20-%20The%20Design%20We%20Open%20-%20tool%20demos%20-%20destiny%202.jpg)

_Image caption: A screengrab image of a slide from the workshop. It shows the purple and blue logo for the tool ‘Destiny’, a link to their github project page (https://github.com/LeastAuthority/destiny) and several UI screenshots from the tool showing end-to-end encryption and how devices link to each other to send files. There is a screen of Destiny that has a large button that reads ‘Select a file’ and the next screens progress through sending a file._


## Briar

The second tool we introduced is a communication, messaging and documentation tool called Briar. Briar uses bluetooth technology in short range to connect to other nearby devices that also have Briar and have been through a verification process. This tool is useful for people that need to distribute essential information to pre-approved contacts through a communication method that is harder to 'shut down' (like Wifi and mobile internet). Briar is also able to host longer articles, written text and also multiple people conversations in a 'forum' type function.

![image](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/workshop%20slides/The%20Design%20We%20Open%20Workshop%202023/COSCUP%202023%20-%20The%20Design%20We%20Open%20-%20tool%20demos%20-%20briar%202.jpg)

_Image caption: A screengrab image of a slide from the workshop detailing the tool called ‘Briar’ with the project website https://briarproject.org/ and the green logo. There is an image of a phone with an animation that cycles through the UI of Briar, including the sign in page and how a user would use messaging in Briar._


## New Node

The last tool we introduced is 'New Node' which, similar to Briar, is a peer-to-peer communication tool that is harder to censor or shutdown as it connects directly to other devices with NewNode. Similar to Briar, NewNode can help people in situations where the internet is censored or shutdown make essential communications with trusted people. We also offer a 2 page document with other common tools used in internet shutdowns that participants can investigate when they get time to explore.

![image](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/workshop%20slides/The%20Design%20We%20Open%20Workshop%202023/COSCUP%202023%20-%20The%20Design%20We%20Open%20-%20newnode%202.jpg)

_Image caption: Two images of the UI of NewNode. The images show a list of contact profile pictures in circles and the message thread previews next to them that shows the most recent message from that message history. The next UI shows a message thread with one person detailing an audio file and an image file being sent as well as fire emojis being used in chat._

Finally, the room was opened up to discuss and write down tools that participants knew of that they anticipated could be useful in internet shutdown scenarios. Even if participants are not familiar with internet shutdowns or other human rights related purposes, they begin to understand the needs and circumstances that people in these human rights situations need and what technology could be useful or fundamental in such scenarios. Participants can either call these out in the room or write their own on stickies and then place them on a common area. In addition to technology or tools it is also helpful to write what it aims to do or achieve, within the human rights context.


![image](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/workshop%20slides/The%20Design%20We%20Open%20Workshop%202023/COSCUP%202023%20-%20The%20Design%20We%20Open%20-%20other%20tools%20from%20participants%202.jpg)

_Image caption: A screengrab image of a slide from the workshop showing many virtual sticky notes with different tools that workshop participants knew about from the workshop. There is a mixture of English characters and Mandarin characters._

<p align="center">
  <img src="https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/Documenting%20Internet%20Shutdowns%20Workshop/graphics%20and%20illustrations/document%20image%20dividers/mobile-phones-divider.png" />
</p>

---

## Why design is needed in OSS and Internet Freedom tools

One of the main purposes of encouraging designers to participate in OSS and Internet Freedom tool workshops and hackathons is that commonly, these OSS tools and Internet Freedom technologies don't have dedicated design support or design contributions. Hence these tools lack the kind of usability, design and interfaces that regular people expect from technology. They can have difficult to use interfaces, unusual settings, difficult technical language and non-supportive help text or error text. These are just some of the ways in which OSS and Internet Freedom technology can be 'lacking' in terms of design than other commonly used proprietary and commercial technologies and tools.
We focus on showing and communicating the lack of consistent design support for these technologies to help the designers present in the workshop understand the impact they will be able to make on these tools even with limited time in a workshop. Design is an underserved function across OSS and the Internet Freedom space, though there are talented and dedicated designers in the space they can be supported immensely by designers volunteering at events like these workshops. One of the fantastic things about running workshops on these topics around the globe is that these technologies are able to gain perspective from multiple citizens and user perspectives. These OSS internet freedom tools can then be designed with many cultural and contextual scenarios which makes them more usable, relevant and useful world-wide.

_“Internet Freedom and OSS technology is not so easy to use. After the workshop I recognised that some technologies are trying to be implemented for the general public and reduce its relatively high technological entry barrier.”_ **- Taro from Team Hotpot**

![image](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/workshop%20slides/The%20Design%20We%20Open%20Workshop%202023/COSCUP%202023%20-%20The%20Design%20We%20Open%20-%20why%20is%20design%20in%20oss%20important.jpg)

_Image caption: A screengrab image of a slide from the workshop. The text reads: “Design in O﻿SS: Why?. Design in OSS is not new by any means! Designers and those that work on the design of OSS tools have been around since the beginning. But they might have called themselves usability experts or maybe HCI (Human computer interaction)Regardless of when designers in FL/OSS started, the trend and increase of interest for design in OSS in the last 5+ years is becoming clearer. Design is mentioned and has a presence across all technology tools in the proprietary or commercial world and more and more organizations and companies are getting on board with the design process and designers as part of technology projects._

![image](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/workshop%20slides/The%20Design%20We%20Open%20Workshop%202023/COSCUP%202023%20-%20The%20Design%20We%20Open%20-%20designers%20are%20users%20advocates.jpg)

_Image caption: A screengrab image of a slide from the workshop. The text reads: “Designers are users advocates. Designers are typically focussed on ensuring that the FLOSS's users needs are being met in the way that most works for them. This might not always be a technical answer to a problem, sometimes it's about refining, clarifying and exploring alternate pathways and 'hacks' users use. Designers are there to translate those user needs for the technology they design for. Balancing 'business wants' and stakeholder needs (among other needs and wants!) is the designer's domain._

---

## Personas

Once the tool landscape has been explored, discussed and understood, the next critical component to explore are the users, their needs, threats and experiences. These are critical in order to better understand under what conditions the OSS, Internet Freedom technology will be used. These personas exercises help anyone, designer, developer or human rights activist explore these experiences and helps when making assumptions, asking questions about the users and coming up with hypotheses for use of the technology.
In order to optimize the time in the workshop, the facilitators created 3 user personas based on our own knowledge of similar situations and country contexts. These personas were intended to “spark ideas” and were there to be remixed and edited by workshop participants. This was the first activity the attendees worked on together in their groups. The personas could be read and used by the teams at the workshop as their 'key persona' to design and consider. What we found though, was that the participants in the workshop wanted to analyze and understand these personas, written by people outside Taiwan and then re-contextualise them in a Taiwanese way. Hence, some groups used a majority of a persona’s information and then edited small details. Other groups completely re-wrote their own personas using information from all 3 examples and also information from their own experiences of internet shutdown situations.
These new personas ended up being vital to better understanding the needs and experiences from South East Asian perspectives including folks from Taiwan, Hong Kong and China. Personas, when used as a device to explore needs, threats and feelings, gives anyone reading them a look at people in certain countries with certain struggles and problems. This is how designers build understanding and empathy for users and can later match technological ideas, features and improvements to goals, needs and threats of personas and then, validate whether those features help solve those problems.

_“As a team we wanted to explore the relationship between Taiwanese citizens and local journalists. The members of this team believe there are two types of journalists. The most common journalist is someone who works to gain views. Then there's also a rarer journalist that informs the public about important social issues, and serves as a watchdog to ensure transparency and accountability while working towards societal solutions.”_ **- Biscuit from Team Cheesecake**

![image](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/Documenting%20Internet%20Shutdowns%20Workshop/photos/teams-persona.png)

_Image caption: A photo of Team Mojito’s persona. There is a simple person drawing in the top left, name and then bio details including his role and other information about his needs, threats, goals and struggles._

![image](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/workshop%20slides/The%20Design%20We%20Open%20Workshop%202023/Personas/Lara%20-%20Activits%20Journalist.png)

_Image caption: An image of one user persona document. This included a face image generated by https://this-person-does-not-exist.com/en. The document includes sections with information written on: Bio, Job role, a quote from that persona, What could hurt them, What do they need, goals and struggles._

![image](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/workshop%20slides/The%20Design%20We%20Open%20Workshop%202023/Personas/COSCUP%202023%20-%20The%20Design%20We%20Open%20-%20persona%20-%20blank.jpg)

_Image caption: A blank version of the user persona document. The document includes sections with information written on: Bio, Job role, a quote from that persona, What could hurt them, What do they need, goals and struggles._

---

## Feedback from users and broader design challenges in the internet shutdowns space

Balancing between too much and just enough research on the users, circumstances, experiences and scenarios is tough to measure for every workshop. We included anonymised data to offer deeper insight into user and OSS technology developers/maintainers pain-points and challenges. These included complaints that the OSS technologists had heard from their own user bases such as: "This process is confusing and I don't know if I can trust the people who make the tool and who shows up as my 'friends' there" and consistent challenges like designing technology when the likelihood of a device being 'seized' (taken by police, governments or institutions in order to be searched for any illegal or sensitive information). These prompts add more detail and context to the challenges of designing and developing internet freedom technology and allow the participants to keep in mind these needs.

_“Our persona already knows how to encrypt sensitive data within images (Steganography). This creates a hidden layer of information, safeguarding it from unauthorized access. She then transfers the encrypted files onto USB drives, ensuring physical possession and reducing digital tracking. The real challenge then, if getting it to the right people”_ **- Pepperoni from Team Pizza**

![image](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/workshop%20slides/The%20Design%20We%20Open%20Workshop%202023/User%20Research/UX%20challenges.jpeg)

_Image caption: A photo of a large piece of paper taped to a window. The paper has a title ‘What are common UX challenges in ‘SD’ (Shut Down’ scenarios’ and has many colorful sticky notes stuck to it in groups labeled: ‘Explanations’ ‘TMI’ ‘Sync & Status’ ‘Discovery’ ‘Trust’ ‘Devices’ ‘Risk’ and ‘Adoption’._

---

## Harmful or adversarial personas (personas non-grata)

We finish off the user research and user feedback evidence section by introducing the concept of an 'Adversarial Persona' or a 'Persona non-grata'. A list of the kinds of people, users and entities that can harm our good-faith and legitimate persona users are offered up, which includes persona types like 'Prankster' (someone who wants to play jokes on other users, divert their attention, distract or disturb their legitimate use) and 'Abuser' (either a romantic partner or other kind of abuser). These Adversarial Persona are useful to consider to explore the complex needs of users. It allows designers and technologists to understand what can harm their users completing key actions and what personal or institutional harm can happen to users on their own platforms. These harmful circumstances can then be accounted for and designed better so that less or none of the Adversarial Persona behaviour can affect users.

_“Taiwan's status as a high-tech hub contributes to its safety. However, while Taiwan's semiconductor industry is certainly advantageous for security, the 'silicon shield' against China is only one component of the strategy. It alone is insufficient to ensure national security.”_ **- Taro from Team Hotpot**

---

## User scenarios

User scenarios are an opportunity to use various personas, user feedback and design challenges that begins to tell a story of this persona's daily life, their interaction with technology and OSS tools for internet freedom purposes. These scenario statements begin to tie together details of user personas' lives and technology in a way that can lead to further exploration, isolation of a specific problem, and beginning to explore when and how technology is most and least useful.
The workshop participants are encouraged to remix and adapt these scenarios with the personas they previously chose and developed in their groups. These scenarios act as 'prompts' and ideas for the teams to consider as they build out the user and situation they want to prototype for towards the end of the workshop.

---

## Simulating a shutdown

*How well can we really design and develop technology if we haven't experienced what our users have experienced?*

If possible, designers and developers of any technology can find out what it's like to 'be the user'. Most people need to use the essential services and functions online that construct and run our interconnected global lives. However, there are many user experiences and scenarios that we as designers and developers may not have experienced. These are the unique 'stress cases' of users and people that do high-risk human rights and internet freedom work. We can learn more about those experiences by reading about those experiences, speaking with people with those experiences and exploring the thoughts, needs, threats and feelings of users through the exercises and activities like personas, scenarios and journeys. But, if you are able to simulate those experiences to better understand them in a safe and controlled environment then you can begin to experience the micro-decisions that people living under censorship and internet shutdowns experience too.
During this workshop, we interrupted the workshop participants to let them know that until they leave the venue that the internet has been 'shut down' and is inaccessible. Only workshop participants that need to be connected for care responsibility (like caring for the sick, elderly or children) or emergency reasons were 'allowed' to use the internet.
We asked the workshop participants to join us in experiencing what it's like when the internet is shut-down or censored. In reality, the wifi and mobile internet had not been shut-down, but we asked each of the workshop participants to place their devices into airplane mode or to turn off the wifi and mobile internet capabilities for the remaining time of the workshop.
With simulation exercises, simple or complex, you can build a more detailed understanding of how users navigate those circumstances.

_“Through exploring the journeys and users, the team was able to improve their understanding of how technical solutions can address social issues. Previously the connection was harder to discover”_ **- Sugar from Team Cake**

![image](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/workshop%20slides/The%20Design%20We%20Open%20Workshop%202023/COSCUP%202023%20-%20The%20Design%20We%20Open%20-%20simulating%20a%20shutdown.jpg)

_Image caption: A screengrab image of a slide from the workshop. The text reads: Simulating a shutdown. 1. Imagine the government has imposed a shutdown and there's no internet connection in the room. 2. Switch off the internet on your phones. Maybe even laptops. 3. This might be just a lightweight experience of an actual shutdown. 4. Try to live the scenario in the shoes of the persona you have chosen. You can let your personal experience right now guide what your persona might be going through. 5. We will run the simulation for the duration of the rest of the workshop._

---

## User journeys

The user journey mapping exercise is the last of the 'exploring users' exercises in this workshop plan. It typically includes conversations about the different kinds of actions and choices that can be made during a certain event, time period or meaningful interaction. For example, some groups mapped a person who had essential gathering information during a large city wide protest and some groups mapped a journalist looking to publish a story against their media outlets views. These journeys offer us a further expanded view of our user personas, finding out what they are doing when, where and how they are achieving their actions. Furthermore, how the persona is feeling and thinking during that moment can allow us better insight into how a technology experience should be designed. e.g. if a user is anxious, what can the technology do to help manage that anxiety? If a user is feeling rushed and reckless, how can technology help them make careful and well-researched decisions with their identity and information? These are the kinds of explorations that user journey mapping allows for.

During the workshop, we encouraged participants to think about the different possibilities, and to pick the route their chosen persona would most likely and logically take when faced with a user choice. There are not necessarily any incorrect routes. All routes of a user journey map are worth mapping, so that we can discover as many uses of tools as possible. It's worth understanding when facilitating a user journey mapping exercise that there are what seems to be endless possible choices users can make, both positive and negative. Ideally teams would have time to map out routes until they feel comfortable enough to progress with finding 'key moments' but it is also ok for user journey maps to have unfinished routes, decisions and questions about user behaviors. These can feed into later user research validation for technologies too.

![image](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/Documenting%20Internet%20Shutdowns%20Workshop/photos/Team-pizza-user-journey-1.jpeg)

_Image caption: A photo of a user journey written by ‘Team Pizza’ from the workshop. There are various sticky notes on a piece of large paper stuck to the wall in both English and Mandarin that describe a user's journey._

![image](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/Documenting%20Internet%20Shutdowns%20Workshop/photos/Team-hotpot-user-journey-1.JPG)

_Image caption: A photo of a user persona and a user journey written by ‘Team Hotpot’ from the workshop. There is a basic icon drawn of a person alongside various written information in Mandarin about this persona and their journey._

![image](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/Documenting%20Internet%20Shutdowns%20Workshop/photos/blank-user-journey.png)

_Image caption: An image of the blank user journey template. The template includes a section at the top ‘Purpose’, the ‘Persona’ ‘The goal of the exercise’ and the ‘Scenario’ that is being user journey mapped. The template is separated into ‘touch points’ to describe the events of a time-period and then ‘What happened?’ ‘How did you feel?’ ‘How did you think?’ ‘What or who was involved?’_

---

## Discovery moments in user journeys

After finishing user journey maps participants can be feeling overwhelmed by information and options of the specific parts of a users experience to focus on. At this stage it's important to give teams a way to focus their attention on key moments depending on the purpose and objectives of your workshop. In this workshop, we wanted to attempt to isolate the key moments in the user journeys where technology is used or relied upon for an essential purpose where it may fall short of the expectation of the user. That single moment can then be focused on for the ideation and prototyping phase in order to not spread a team's attention too thinly and explore too many options. We're looking for a small, actionable moment where designing a change could have a big effect.
In our example, we show a user journey map created around a protest in a European country. The internet starts to slow down and communication methods that previously were accessible and safe are no longer so. When looking for key moments here we discovered that people would try to message friends and family and other key contacts when the internet connection begins to fail - when messages don't send and fail the behaviour that users often do is scrolling up in a chat history - we then had an idea that we could send critical info about shutdowns and protest information before the internet goes down to then be 'found' in the history via n eye catching design/text a sort of 'You won't need this info now but you will when the internet goes out, 'proactive' moment for groups sharing information.

![image](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/Documenting%20Internet%20Shutdowns%20Workshop/photos/critical-moments-user-journey.png)

_Image caption: A photo of a ‘moment’ in a user journey. A single sticky note that reads “Wants to get the message out” is circled in pen._

---

## Ideate and design

The last activity in this workshop on design processes is ideation. After teams have identified as many key moments in their user journey and are well-informed and ready to start generating ideas, they can start with idea generation. We ask that the groups discuss the key moments and ensure they are all happy with the moment picked and then discuss the potential ideas that solve for a specific key moment for a user. These ideas can include UI, new OSS tools and technologies, and leverage existing ones. The teams are encouraged to explore more 'blue sky' thinking and less about the detailed technical feasibility and implementation. The main objective here is to explore the solutions while continually referring back to the user journeys, user scenarios and user personas to ensure that the solutions meet the needs of the users.
Participants should however, be advised to stay within the realms of technological possibility and not go into science fiction technology. The tool landscape and demos serve the purpose for grounding the reality of the technological space. During ideation teams should have a 'storyboard' layout for their idea that they think, when looking back at the user insight, solves their problems. These storyboards often communicate both the human action and the technology/device action in them. The critical element that this workshop has brought is the lived experiences of the citizens participating in the workshop.

_“Our team had the goal in mind first, then worked backwards through the user journey. The goal of the journalist is to deliver necessary information to the public in the midst of a communication shutdown.”_ **- Biscuit from Team Cheesecake**

![image](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/Documenting%20Internet%20Shutdowns%20Workshop/photos/team-japanese-curry-4.JPG)

_Image caption: A solution prototype from Team Japanese Curry that shows simple illustrations of a taxi driver couriering information and people to a safe place from a dangerous place and receiving messages via the taxi communications._

![image](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/Documenting%20Internet%20Shutdowns%20Workshop/photos/team-hotpot-prototype.jpeg)

_Image caption: A solution prototype from Team Hotpot that shows a series of mobile app screens where a user can ping a remote location that will find a connection when it can as well as logging any injuries or details on group members._

![image](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/Documenting%20Internet%20Shutdowns%20Workshop/photos/Team-mojito-4.JPG)

_Image caption: A solution prototype from Team Mojito that shows illustrations of using a USB and wifi (before a shutdown) to record data and information about critical news events or organising details. This USB then asks users to install an app to view a sandbox in order to view the information. To get the USB this would be passed between people using a passphrase._

---

## Documentation

Finally, at the end of the workshop after everyone has had a chance to talk about their proposed solutions to their user journey key moments, we encourage the participants to document the ideas and conversations on a platform of their choice. If the host event has documentation platforms they'd like you to use or if the participants have their own platforms they'd like to use then those platforms should take priority. Documentation is communicated as an important exercise to designers and human rights activists that are not familiar with OSS practices. Documentation that is privacy respecting while being as open as possible is how this work and these ideas live on past the workshop day.
The outcomes of these kinds of workshops are far-reaching for OSS for internet freedom and human rights. There's plenty that can be learned from participants who have their own lived experience and relationships to the subject matter.

![image](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/workshop%20slides/The%20Design%20We%20Open%20Workshop%202023/COSCUP%202023%20-%20The%20Design%20We%20Open%20-%20documentation.jpg)

_Image caption: A screengrab image of a slide from the workshop. The text reads: Wrap up﻿ and Documentation An important part of this workshop was engaging with the topic 'What if the internet was not available in a critical moment for these users?' and explore their journeys . Your work and insight can now be used to improve tools during internet shutdowns and crises. We'd like each group to speak about their persona, journey map and ideas they came up with - We'll be documenting them in the HackMD notes and you can also add details. We'll move these ideas to Github anonymously._

---

## Running a workshop for designers and technologists on OSS Internet Freedom technology

If you find yourself inspired to run a workshop for designers, OSS maintainers, technologists and Internet Freedom activists after reading this we have resources available in an Open Github repository: https://github.com/sprblm/The-Design-We-Open/tree/main. You can also find an open virtual whiteboard https://bit.ly/DesignatCOSCUP  (We use Miro.com for our workshop plans and resources). We make sure to build workshop content that is inclusive of people new to design processes in open source. The intersection of design, open source software and internet freedom technology is small but growing and we make content that is accessible and helps grow understanding of each other.

We encourage you to use whatever resources and structures work for you and your communities. If you’d like support or advice on how to plan and run a workshop then you can contact us on the following email hi@superbloom.design. Superbloom staff have planned and facilitated design and OSS contribution workshops internationally and are particularly interested in how we bring more designers and design practices into the open source software community and the internet freedom and human rights technology space. 

![image](https://github.com/sprblm/The-Design-We-Open/blob/main/Documenting%20Internet%20Shutdowns%20Workshop/photos/Group-5.jpg?raw=true)

_Image caption: A photo from the workshop. In a classroom setting, Superbloom staff respond to a team’s ideas in an entire workshop discussion section. There were many people sitting in chairs or standing and listening._

![img](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/Documenting%20Internet%20Shutdowns%20Workshop/graphics%20and%20illustrations/document%20image%20dividers/food-full-width.png)

---

# Workshop team solutions and designer analysis

This next chapter covers each team's process and contributions to the workshop, along with insight from the designers at Superbloom who have knowledge in design, Internet Freedom technology and Open Source Software.

![img](https://github.com/sprblm/The-Design-We-Open/blob/main/Documenting%20Internet%20Shutdowns%20Workshop/graphics%20and%20illustrations/team%20foods/team%20Food%20Name-solution-11-28.png?raw=true)

---

# Team Mojito Overview

<p align="left">
  <img src="https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/Documenting%20Internet%20Shutdowns%20Workshop/graphics%20and%20illustrations/team%20foods/mojito.png" height=100 width=80 />
</p>

A. **Scenario:** A Chinese computer engineer and civic journalist, whose investigative paper has drawn government scrutiny, faces imminent arrest. He must escape to another country to ensure his safety and that of his family.

B. **Persona:** An academic user persona - Computer Engineer and Civic Journalist. Team Mojito chose this persona because they read about a similar case in the news. The familiarity helped them relate to the person's situation better.

C. **Context:** The journalist's paper exposed sensitive government information which has caused protests and unrest. He must try to escape the country safely, securing travel documents, and arranging safe passage for himself and his loved ones. Since he cannot use regular and common means of transport, he needs to find a way to cross the border via land. Through his journey he is unable to access the internet and must be cautious to maintain privacy, keep his whereabouts and identity hidden.

D. **Goal:** To escape and secure a safe and discreet exit from the country for himself and his family.

E. **Solution finding:** The team explored and evaluated the need for multiple tech solutions to bring this persona to succeed. He would need a method to communicate with his trusted sources and contacts. He would need some safe houses or checkpoints to break his journey. And he would need to be out of sight of authorities and the army.
 
Since this case is not a common occurrence, building specific technologies for this persona may not be feasible, hence he needs to use already existing tools, technologies and methods to plan his escape. As a result of the user journey mapping and brainstorming, the team Mojito came up with the following ideas:

_Offline connectivity in Taiwan:_ Establish a local network using devices connected via a Wi-Fi router. When the internet is cut off, the network automatically switches to mesh mode, enabling continued communication and connectivity among devices.

_Escape documentation and safety navigation:_ In an escape situation, use a hiking app in offline mode that has radar functionality. This app allows users to request updates from others about safe locations verified by NGOs(more neutral entities), helping navigate to secure areas. 

_Virtual message box system:_ Use a secure virtual message box where both parties agree on a long code. To communicate, each person places a message in the box, which can only be accessed and read by entering the agreed code. 
While these are all great ways to think about the solution, this needs further development in terms of how to stay connected in remote areas i.e. how does the mesh network enable connectivity when there are lesser devices available in the region. The solution also raised questions about who the team considered to be the ideal authority to ensure the security of the messages? Responses from the team members varied, while some suggested politicians they trust, others recommended NGOs for their credibility. 

We were curious about what types of information might be the most sensitive. Mint noted that in a scenario of government repression, individuals employed by the government would likely be the primary targets. The focus is not on the specific information being monitored but on how certain professions naturally increase the risk of being targeted.

![img](https://github.com/sprblm/The-Design-We-Open/blob/main/Documenting%20Internet%20Shutdowns%20Workshop/graphics%20and%20illustrations/solution%20illustrations/team-mojito-solution-11-28.png?raw=true)

---

# Team Hotpot Overview

<p align="left">
  <img src="https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/Documenting%20Internet%20Shutdowns%20Workshop/graphics%20and%20illustrations/team%20foods/hotpot.png" height=90 width=120 />
</p>

A. **Scenario:** This team was focused on emergency communication tools in disaster scenarios where the internet is failing due to environmental destruction or heavy weather conditions. This scenario was chosen as it is a common occurrence in Taiwan due to the prevalence of Typhoons, landslides and other weather related crises as well as mountain climbing being a common activity.

B. **User persona:** The persona they focused on was a professional adult, climbing hobbyist who, until this disaster scenario, had not thought or prepared for a lack of communication. In this exploration the general critical user type is explored, the unprepared, regular citizen who by circumstance has been ‘pushed’ into communication cut off and is struggling with what to do.

C. **Context:** The team members found that this was a user persona as well as a scenario where they could explore the topics of restricted communication, harm to people around them and decision making around what to communicate, when and to what best effect for more than one person. The topic of war-like or an international or national 'internet shutdown' was discussed in this team, but the safer option that explored similar themes was the natural disaster scenario and allowed the team to speak freely, unburdened by sensitive politics.

D. **Goal:** To use available technology when in a remote/rural location with limited internet connectivity, to contact or 'send a signal' (primarily location data) in order to coordinate rescue and/or sending new location information to those without connectivity.

E. **Solution finding:** The team discussed the use of hiking apps, Bluetooth, mesh networks and a known tool called Sigfox for maintaining connectivity in remote, mountain areas and also for potential urban, city settings. It isn’t common for teams exploring design ideas to come with an established idea of what technology to use as part of the scenario solution, these technologies were often brought into the team discussions by those who self-described as engineers or coders. In itself, mentioning or suggesting technologies doesn’t ‘pollute’ the design exploration at large, as the users, journeys and needs for technology solutions are still maintained in the process, but early suggestions can affect and bias the decisions the teams make. Here though, the purpose of mentioning this tech was that it was being investigated in the local tech communities in Taiwan. The ideal scenario for the teams solution was that, through a combination of a ‘back-up weak connection (either via bluetooth mesh or Sigfox) that a hiking mobile app (possibly connected to LINE, with information inputted in offline) could ‘ping’ a location of the climbers in order to either then receive or send a ‘packet’ of information of their location and status.

This led the team to discuss the importance of localizing technology to fit specific user interface expectations and needs, such as integrating with popular apps like Line, and chat functions in Taiwan. The team considers the challenges of privacy and trust in government-created technology, and the role of citizen awareness and localized solutions in ensuring the effectiveness of these tools. The trust in government administered and maintained technologies relied heavily on what government department undertook that responsibility, given that some departments were trusted more than others. Examples of this shaky trust surfaced in conversations about potential overseas surveillance cameras being bought from a Chinese owned manufacturing company as well as the digital Taiwanese citizenship cards that were resisted against.

The biggest discovery this team made as they developed their persona was around the importance of accessible and well designed training and usable technology for regular citizens. Citing that most tools that facilitate communication not using the standard internet are difficult, confusing and require a considered training approach for regular citizens.

_“Generally Taiwanese citizens trust government-issued apps. Taiwan's V-Watch during the COVID-19 pandemic was an example. It integrated with the popular messaging app LINE, to collect vaccination data and connect the government with the local population. In emergency response situations, trust between the Taiwanese government and the public remains relatively high. However, on the topic of surveillance technology, the team were concerned with who manufactures it. If it’s made in China, there is a risk that these cameras could be used for surveillance.”_ **- Taro from Team Hotpot**

![img](https://github.com/sprblm/The-Design-We-Open/blob/main/Documenting%20Internet%20Shutdowns%20Workshop/graphics%20and%20illustrations/solution%20illustrations/team-hotpot-solution-11-28.png?raw=true)

---

# Team Cake Overview

<p align="left">
  <img src="https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/Documenting%20Internet%20Shutdowns%20Workshop/graphics%20and%20illustrations/team%20foods/cake.png" height=90 width=120 />
</p>

A. **Scenario:** There's been a protest that the government is attempting to stop.

B. **Persona:** Journalist/Citizen journalism

C. **Context:** This team focused on events similar to the Umbrella Movement. At the beginning of the protest scenario, our journalist/citizen journalist arrives at the scene, ready to report on the unfolding events. The atmosphere is tense as demonstrators gather, with the government threatening to shut down internet access to quell the protest. As our protagonist prepares to document the situation, they're suddenly faced with a communication blackout as the internet goes out. They need to be able to collect and share information without  being tracked.

D. **Goal:** Successfully communicate with each other to gather for protest in the midst of internet shutdown. The journalist needs to be able to collect accurate information and inform as many people as possible.

E. **Solution finding:** Team started their design journey by picking a protest scenario first, followed by selecting the journalist/citizen journalist persona. In the middle of the chaos of protest, our journalist must quickly adapt to this new challenge. They realize the critical need to share vital information such as media files, contacts, messages along with information about protest meeting locations and police movements, but traditional communication channels are no longer available. This is where they begin to explore alternative methods of information sharing, tapping into technologies like FireChat, NFC, Bluetooth, and fingerprint authentication. NFC and bluetooth are tech developments that a person naturally gravitates towards when considering no internet scenarios. But also the team structure had more engineers over designers which also indicates why the solution is tech-first. A vital moment in the journey of the user when they need to use this solution the most is when the police arrive to break apart the protest and people need to find a way to evade them so they share information such as the police location, safe protest places or any other information in their phone etc… Therefore, this team considered a solution where they could bump their phone against another person thereby transferring a packet of information. While it is an interesting idea because of the ease of use in a crowded setting and ensuring they send the information to the specific trusted person, it still raises questions about what if the phone is bumped into the wrong person in a chaotic setting or concerns of ensuring that there’s no spread of misinformation. This led to discussions about finding the right, trusted authority who would be the source of the information. The journalist works with fellow protesters to establish a decentralized network, allowing them to pass verified information securely without relying on internet connectivity.

In a different line of thought to make their solution reach more people, the team would have preferred if there was a way to use existing lines of communication such as the Line app itself for such a scenario and purpose. If Line app could introduce offline capabilities, that would make it easier because people are already used to the app. 

During solutions thinking it is often easy to go in various directions, sometimes unproductively and so it is important to keep the user and their journey in mind at all times. Sugar recounted the same happening in their group where she being the only one related to the design field used the design journey to align the group and their solution around the user. 

_“As a team we wanted to understand how existing technologies (FireChat, NFC, Bluetooth, Fingerprint authentication) could be developed into solutions for the Internet Freedom scenarios and what needed improving.”_ **- Sugar from Team Cake**

![img](https://github.com/sprblm/The-Design-We-Open/blob/main/Documenting%20Internet%20Shutdowns%20Workshop/graphics%20and%20illustrations/solution%20illustrations/team-cake-solution-11-29.png?raw=true)

---

# Team Cheesecake Overview

<p align="left">
  <img src="https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/Documenting%20Internet%20Shutdowns%20Workshop/graphics%20and%20illustrations/team%20foods/cheesecake.png" height=90 width=120 />
</p>

A. **Scenario:** War-like situation in Taiwan. This team chose this situation because of the topic of the workshop and the tense political relations with CCP and the constant looming threat Taiwanese face about such a possibility of being attacked by CCP.

B. **Persona:** Journalist. The team thought they could understand and relate to the journalist more and it would be harder to imagine what the activist would need. This does highlight the basic approach of design thinking which is to be able to empathize with the users.

C. **Context:** CCP deploys military aircraft over Taiwan disrupting the internet and communications by destroying the infrastructure or blocking the signals, leaving citizens without access to news updates. Our journalist wakes up to the sound of military aircraft flying overhead. Turning on the TV, they learn that the CCP has deployed military aircraft over Taiwan, causing widespread panic. As the journalist tries to check online news sources, they realize that internet connectivity is becoming increasingly unstable. Feeling a mix of confusion and determination, they head to the news agency's office and on the way notice people on the streets looking anxious and confused, many frantically trying to use their smartphones without success. At the office, the journalist and their colleagues face a grim reality: the internet is completely down, and traditional communication channels are disrupted. They realize they need to find alternative ways to gather and disseminate crucial information to the public.

D. **Goal:** The journalist would want to send the correct information for the public to follow. The message is about the CCP attacking Taiwan and because the communication was shut down, there is no way to know. The other goal is to enable people to communicate with each other in a war-like scenario.

E. **Solution finding:** Since people are always connected to the internet at all times, disruption even for a little while can cause people to panic. Team Cheesecake thought about a similar situation where people who might be on their way somewhere in metros etc… would want to know what happened to the internet. With traditional methods unavailable, the team came up with the following solutions to leverage existing infrastructure and local community networks:

1. District leaders: Each district in Taiwan also has people(sort of a district leader) who are related to the government and take care of the common matters for the public. People could reach out to the district leader to get the right information. These district leaders are a part of many team’s solutions because they are an important and prominent part of the social structure. This also makes the solution localized to the Taiwanese region. The journalists will also go to the district leaders to get the information and relay it to the public. Since there is no internet, there needs to be an additional reliance on physical locations for the solutions. 

2. Kiosk machines: Convenience stores become hubs of information, with people gathering to read the latest updates on the bulletin boards.

3. Line app: Everyone in Taiwan has the Line app and there’s a news section(Line Today) on the app. There could be a possibility to collaborate with them to make that feature offline, or users could be allowed to receive updates by scanning QR codes at convenience store kiosks. This is where this team found interesting intersections in their ideas in an attempt to make the solutions robust.

4. Youbike: While thinking of other prevalent systems in Taiwan the team also thought of using the youbike screens to flash short important messages to the public. Since there are several youbike spots across Taiwan, it can be an innovative use of city infrastructure under dire need.

The team considers journalists to be a trusted source of information and act as a bridge for the public to understand the complex social issues. Journalists offer insights on the important things that the public should care about hence they play a crucial role in informing people about the latest happenings thereby making them a critical part of their solution. 

_“We explored leveraging LINE app's potential offline functionality. LINE is the dominant messaging app in Taiwan. LINE already has a news page called LINE Today. We wanted to utilize existing features and make important news available in critical locations, then release it through the convenience store kiosk machine for people to scan the QR code to gain the most updated information. (This function is not currently available at the convenience store nor in the LINE app). We also wanted to address the importance of authenticity in news sources. Particularly, the credibility of news sources in times of chaos.”_ **- Biscuit from Team Cheesecake**

![img](https://github.com/sprblm/The-Design-We-Open/blob/main/Documenting%20Internet%20Shutdowns%20Workshop/graphics%20and%20illustrations/solution%20illustrations/team-cheesecake-solution-11-29.png?raw=true)

---

# Team Japanese Curry Overview

<p align="left">
  <img src="https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/Documenting%20Internet%20Shutdowns%20Workshop/graphics%20and%20illustrations/team%20foods/japanese-curry.png" height=90 width=120 />
</p>

A. **Scenario:** This team focussed initially on the aspect of internet shutdown sparked by a 'war' like conflict scenario, as a location based phenomena. Meaning that, as well as starting with a persona type, they also focused on the fact that when an internet shutdown occurs, what goes missing is the ability to communicate across significant physical distances. The internet enables us to, with a stable connection, speak to anyone that we have a method of contact for, anywhere that they may be provided they have connection and at any time provided they are able to check their devices/communication methods.

B. **Persona:** Wangxiaming a taxi driver in his late 50s without too much tech knowledge in the face of war.

C. **Context:** As the team focused their explorations on access and mobility potential and the behaviors associated with transit/taxi drivers they then began to explore the social motivations, communication patterns/access, preparation work and finally, the difficult subject of trust and verification. This surfaced from inquiry around critical information being moved by individuals that might have their own agendas or views on the social issue causing the internet shutdown.

D. **Goal:** There are certain people that have local, non-internet connections and communications and city-wide mobility (e.g. Taxi drivers and truck drivers). How can these methods be leveraged in an internet shutdown scenario.

E. **Solution finding:** The focus of their explorations therefore became centred on the need of mobility and consistent movement throughout a location (city or district) and what kinds of people do this activity already surfaced the critical user persona of a transit driver or a taxi driver. These citizens also can have access to alternative methods of communication that do not always rely on internet connectivity, such as closed networks of  walkie-talkies and radio communications.

The team had a number of areas they could have focused an OSS technology intervention on, including:
- How do we recognise critical citizens before a crisis that leads to an internet shutdown (e.g. taxi drivers) and prepare them ahead of that crisis to locate, verify and disseminate information.
- How do people verify and trust information, what are their methods of critical deduction when it comes to information that preserves lives. 
- Similarly, how does information spread both naturally and when more engineered? How can this make its way to people that are not as technologically adept. 
- Once correctly informed and safe, what do citizens then do? What are the next steps in safety, returning to normal life or what are the likely next steps for citizens post crisis.

There was also a concern that taxi drivers may be generous enough to move messages around in limited circumstances or times they care about the issues but ultimately they are sacrificing income to do a messenger role and perhaps they would need some payment for this.
A large general realization among the designers and technologists participating was that in an internet shutdown, typical technology that most people are comfortable using no longer functions at all or as intended. They quickly realized that technology that doesn’t rely on internet connectivity might be older, more complicated to set up and use and less instant. Which led to a shift in users that are not ordinarily the focus of. 

Upon further discussion with the team members, we discovered that there are many detailed and nuanced aspects that only get lightly mentioned in a 1 day workshop around internet shutdown technologies. One topic was whether or not there are topics that the demographic user of ‘transit/taxi driver’ would refuse to spread, such as issues more connected to younger people like feminist issues, women’s rights and political beliefs and alignment. A potential solution to this though was ‘locked’ information so the drivers did not know the contents of the message. This was also risky for them though given concern over ‘illegal’ information.

From Superbloom’s design expert perspective this group discovered a user persona that is underserved in the OSS internet shutdowns prevention technology. Personas which do not automatically self-align with technology and/or information or news spreading are rare in this sector. The focus on the pre-crisis phase, sometimes described as the ‘training phase’ also tends to underserved these kinds of citizens and typically it is hard to engage those not technologically curious in prevention and resilience technology. The use of technologies such as bluetooth (for sharing information/files), walkie talkie applications, radios and paper based couriered messages while astute also reveals that more can be done to help designers and understand the capabilities for technology in these scenarios. The presence of technologists helped this greatly as many shared their own knowledge of tools and technologies beyond that of Superbloom’s examples, especially technologies that were incubated in Taiwan. 

However, like many prototypes are, they’re only the first step in a potential avenue for improvement in technology. The benefits of this team’s insight are in focusing on the margins where under represented groups, scenarios and circumstances rise. These are the aspects that OSS censorship circumvention and internet shutdown technologies can learn from generally. How to communicate these insights though, reveals the gap between design practice and OSS technology. Methods for designers who create outputs like this sorely need clearer avenues to signal to relevant technologies and stakeholders.

_“The team emphasized the importance of this multi-faceted approach: In a crisis like flooding or other natural disasters, we need to ensure that everyone, regardless of their access to technology, can receive and understand life-saving information. High-risk information, such as content related to war, political issues, or rumors, is particularly sensitive. People are often hesitant to share this kind of information because of the varying political stances and interpretations that can lead to conflicts. Many individuals are unwilling to support or deliver any message that could be perceived as a political agenda.”_ **- Pepper from Team Japanese Curry**

![img](https://github.com/sprblm/The-Design-We-Open/blob/main/Documenting%20Internet%20Shutdowns%20Workshop/graphics%20and%20illustrations/solution%20illustrations/team-japanese-curry-solution-11-28.png?raw=true)

---

# Team Pizza Overview

<p align="left">
  <img src="https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/Documenting%20Internet%20Shutdowns%20Workshop/graphics%20and%20illustrations/team%20foods/pizza.png" height=70 width=120 />
</p>

A. **Scenario:** The user persona has critical information that they want to report, yet the act of reporting is repressed by a media outlet that could be worried about national or international governmental backlash. Along with this systemic worry there is the possible social pressure from citizens, organizations and entities aligned with the perpetrator and not the victim.

B. **Persona:** Journalist/Citizen journalist. This team focussed on the user persona that has gained critical information about an important, national or international issue and wants to make sure that both citizens and appropriate people in power have access to this information. The team explored the ways that journalists and citizen journalist personas might face challenges like misinformation and disinformation campaigns as well as malicious entities that look to discredit or erase the information and evidence from existence. In our experience as designers working on many projects that face censorship and shutdowns, these personas face targeted attacks and, if an issue is suitably volatile enough, a government or other entity can look to shutdown or throttle internet services or perform targeted censorship. This persona has a high intensity existence once they have obtained information they wish to make public and it becomes important quickly to move away from ordinary, yet insecure internet and communications practices towards privacy and security preserving ones.

C. **Context:** The journey that the user persona went on is not necessarily an obvious internet shutdown scenario e.g. war, disaster, malicious entity removing connectivity. It surfaces as more social and technological censorship and intimidation. To publish is to make a target of one's self and this journey encapsulates the experience of an individual who's media outlet does not train or support their safety and that meets this risk not in a hypothetical scenario first, but a real scenario.

D. **Goal:** To share essential news and information in a way that cannot be traced back to a specific individual through any kind of tracking.

E. **Solution finding:** The team identify a number of points in a journey where technology can intervene:

- Helping the journalist persona to find out who is likely to be monitoring/surveilling them.
- Supporting the journalist persona to still use certain words and terms online and offline without raising alarm or risk further monitoring.
- Helping the journalist persona camouflage or hide critical information on their story ‘in plain sight’ and transfer that through safe, secure online methods that do not require use of compromised internet or internet connection altogether.

Plenty of exploration was done by the group to find physical locations for information to spread as well as how that information can be trusted, verified and obfuscated by ‘passing through many hands’. Here is where the designers encountered the critical aspects of privacy and security alongside an internet shutdown scenario.

The final prototype made was a USB device that could contain vital news, articles and information related to a topic that is possible to have a recognisable logo on. The USB, once opened, would access a ‘proxy’ or ‘sandbox’ to open the relevant files for individuals to read. This ‘sandbox’ was prototyped to work both online and offline. There are still many questions related to trust of devices like USB drives and the risk of malware and viruses on these devices. These in depth topics though would require more user research, exploration and prototype iterations beyond a single day workshop. 

Interestingly, the members of this team we spoke to were interested because of the focus on OSS, privacy, security and internet shutdown issues and attended in order to explore those ideas in a group setting. They commented further that if you’re not a privacy and security engineer or specialist, speaking about and having input or thoughts on these topics felt ‘inaccessible’ without that knowledge and authority. Notably, a member of this team went on to change their study major to engineering and started their own OSS project shortly after the workshop.

_“To disseminate the information anonymously, we wanted to recruit individuals to distribute the USB drives to strangers. This creates a chain of anonymous transmission, making it difficult to trace the original source. As the information spreads, individuals can add details or context, further obscuring the origin. But how do people trust each other enough to share the USB and know what to do with it?”_ **- Pepperoni from Team Pizza**

![img](https://github.com/sprblm/The-Design-We-Open/blob/main/Documenting%20Internet%20Shutdowns%20Workshop/graphics%20and%20illustrations/solution%20illustrations/team-pizza-solution-11-28.png?raw=true)

![img](https://github.com/sprblm/The-Design-We-Open/blob/main/Documenting%20Internet%20Shutdowns%20Workshop/graphics%20and%20illustrations/document%20image%20dividers/gaji-bag-full-width.png?raw=true)

---

# Looking ahead: Post Workshop Feedback and Improving workshops

During workshops at [COSCUP 2023](https://coscup.org/2023/en/) (and in [COSCUP 2024](https://coscup.org/2024/en/)) we received actionable feedback from participants. We’ve turned these into recommendations for future workshops.

## Recommendation #1 - Grounding Design exploration in reality

Design exploration activities are useful for those that know those practices (Designers typically) and those that don’t (Activists and OSS Technologists). These are activities like User Persona ([Resource 1](https://superbloom.design/resources/persona-template-tech.pdf) and [Resource 2](https://superbloom.design/resources/superbloom-threat-modeling-template.pdf)), User Scenario and Journey Mapping ([Resource 1](https://superbloom.design/resources/superbloom-user-journey-mapping-template.pdf)) and Ideation activities ([Resource 1](https://www.designkit.org/methods/rapid-prototyping.html) and [Resource 2](https://www.designkit.org/methods/storyboard.html)). However, when you explore design without a clear grounding in the realities of the software and tool landscape people become prone to ‘blue sky thinking’ ideas that are beyond current or possible technical realities. Time spent focusing on short but clear tool demos and landscapes in the workshop allows participants to apply design explorations to existing technology tools/OSS. 


## Recommendation #2 - Including OSS maintainers in workshops

OSS is typically open and accessible to anyone for contributions; designers and coders don’t need permission to submit improvements but it often feels like you need to ask before offering design. When you involve OSS maintainers and OSS founders in a workshop they are able to communicate any vision or goals they have for the OSS, as well as communicating any user needs they may know. Additionally, the designers get the opportunity to see the OSS in action if the maintainers can do demos. 

## Recommendation #3 - Including activists in workshops

The presence of people with lived experience of human rights abuses and internet censorship/shutdowns is important to designers, technologists and OSS developers alike. When workshop participants get ‘stuck’ on a particular point, question or circumstance they can look to the person with experiences to offer perspective and their own account. As an informational resource people with lived experience can quickly feel exploited and vulnerable when offering information and therefore we recommend the safest ways to involve these people possible be it remotely, funded in-person attendance and anonymous representation or representative information. We encourage offering access and further value to the activists or communities in the form of involvement in the OSS.

## Recommendation #4 - Design confidence, feedback and designing within systems of oppression

Participants found significance in the processes of feedback between designers. Many designers at the workshop, and in OSS generally, do not get to work closely with other designers (groups of designers are even rarer!) so found the support and feedback process invigorating and valuable to their careers beyond the workshop. The second implicit effect feedback has, is to build confidence and capability in tackling OSS and Internet Freedom topics by designers which can benefit both OSS and Internet Freedom and proprietary, commercial and for-profit spaces, enabling them to design within systems of oppression.

## Recommendation #5 - 2 day workshops with specific focuses 
Participants of the 2023 workshop that also attended the 2024 workshop noted that they felt like these were two halves of a single workshop spread out a year apart. They value the day of design thinking exercises at 2023’s workshop and the more practical ‘make a contribution’ focus of 2024’s workshop (Read more here on our blog). We recommend that workshops are a minimum of 2 days, one day to focus on design and user exploration and the second to ensure a tangible contribution is made. These days don’t need to both be in person or close together but should ideally happen between 2 weeks and 1 month of each other.

## Recommendation #6 - Design legitimacy and further learning in OSS
Designers are more commonly working in sectors that don't understand open source software contributions as valuable work experience and how some designers choose to advance their design skills. The designers in attendance wanted certification/a certificate for being involved in the workshop, and also expressed wanting a curriculum or educational course they could follow from OSS design experts in order to become more proficient in design for OSS and internet freedom.

## Recommendation #7 - Small-scale support for prototypes
The technologists and coders in the workshop wanted to be able to spend time building or coding the solutions prototyped in the workshop and test whether or not they solved the problems they intended to. Offering small scale funding to build and test a prototype technology can help to build infrastructure for on-going involvement in developing OSS Internet Freedom technology, design in OSS Internet Freedom technology and supporting the post workshop enthusiasm beyond the moment.

<p align="center">
  <img src="https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/Documenting%20Internet%20Shutdowns%20Workshop/graphics%20and%20illustrations/document%20image%20dividers/crowd-full-width.png"/>
</p>

---

# Positionality statements

Codenames for the researchers are: Nutmeg, Soybean, Cocoa and Basil.

## What are your beliefs about Taiwan, OSS and Internet Freedom?

**Nutmeg:** My beliefs about Taiwan before these workshops was that, as a country, Taiwan was under threat from China in social, political and societal ways. I believed that Taiwan was in a disadvantageous position when it came to fighting or resisting these threats and while the potential risks are complex, Taiwan is incredibly capable, strong and advanced in Internet Freedom Technologies. 

**Soybean:** I believe Taiwan is part of the human world, and the internet serves as a tool for us to communicate and connect as individuals. The internet is an important infrastructure in our network history, akin to highways, railways, and air routes today. Although maintaining these infrastructures comes at a cost, as humans who thrive through collaboration, ensuring the free and open access to the internet is crucial for uniting people. This relies on the collective efforts of individuals across different nations. Open-source software is one of the means to promote internet freedom by developing tools and sharing solutions that ensure everyone has the opportunity to participate in collaboration and technological advancement. Since humans make mistakes, self-correcting mechanisms are essential in every context, and open-source software is one form of self-correction in technology.

**Cocoa:** I have learnt a lot more about Taiwan and its Internet Freedom and OSS space during the workshops than before. My impressions of the country have mainly been about its strong semiconductor industry, progressive policies and threat from ROC. I have come to learn more about Taiwan’s complex need for Internet Freedom tech for various political and geographical reasons. I have come to learn of the resilience of its people, their capabilities and the ecosystem it offers to voice and develop innovative solutions.

**Basil:** Taiwan currently enjoys a high degree of internet freedom. Unlike some countries, Taiwan does not impose strict regulations on online speech, and people have the freedom to choose how they use the internet. Additionally, internet penetration is very high across the country. Regarding open-source software (OSS), based on my observations, most people are still more accustomed to using paid software or operating systems. This may be due to the school environment, where students typically grow up using Microsoft software, and assignments are often submitted in formats like doc or xls.

## What history or personal interaction do you have with Taiwan, OSS and Internet Freedom?

**Nutmeg:** As a British citizen, before doing these workshops, I distantly understood Taiwan within the context of historical British colonialism. My first direct experiences with Taiwan were directly related to open source software and an inclusive attitude towards design as part of how open source software is made better for users.

**Soybean:** Honestly, I don’t know how to code, but with my social science background, I understand that the birth of technology relies on human collaboration, and designing technology requires the involvement of many people to meet the needs of different groups. When I first joined the g0v community, my favorite thing was observing how people used technology. This also influenced my choice to pursue a design career. The people here are generous, always willing to share how they use technology, along with data and source code, and they are also open to feedback on what they share. I love this spirit of openness and open source.

**Cocoa:** While I have experience in OSS and design, I am relatively new to the Internet Freedom space in Taiwan. I approached this workshop as an opportunity to offer my design skills and design experience while learning more about Internet Freedom. I had already worked on a few open source projects mainly targeted for the South Asian context, at the time of joining the workshop. 

**Basil:** In high school, I participated in a translation project for open-source software (OSS). Additionally, I have some experience using OSS and have recently been deeply involved in related workshops.


## What is your connection to workshop participants? Do you share any commonalities, identities, or experiences with workshop participants?

**Nutmeg:** I planned, applied and facilitated workshops around design in open source software and then internet freedom both in Taiwan for this work and also elsewhere through my career. I share and connect to the dedication that Taiwanese people involved in civic tech and OSS have in regards to open access and freedoms. With the workshop participants I share and remember my earlier days of my design career and how community collaboration events shaped my growth and community connection.

**Soybean:** Many participants, like me, are designers, but they come from diverse backgrounds. Some are also friends from the g0v community. One similarity is that we all enjoy observing human behavior, providing emotional value, and making others feel comfortable and relaxed. In terms of self-identity, I think we all share a desire for everyone to lead a happy life.

**Cocoa:** I share commonalities of experiences with the workshop participants in a broader Asian context. There are a few common cultural and behavioral commonalities such as the work ethics driven by Indian and Taiwanese economies, cuisine etc... Apart from that I shared a common interest for Open Source and Design in tech, with many participants. 

**Basil:** I personally believe in the importance of internet freedom, but I also think such freedom needs appropriate management. Taking Taiwan's current situation as an example, the lack of regulation may allow malicious actors to manipulate online discourse. Furthermore, even if the government does not impose internet restrictions, businesses might compromise internet freedom in pursuit of profit. I hope to promote internet freedom more deeply in Taiwan and help people understand that there are viable solutions available when facing internet restrictions.

## What are your hopes for Taiwan, OSS and Internet Freedom?

**Nutmeg:** I hope that Taiwanese citizen’s interest and access to open source software and openness continues to grow and gradually becomes more inclusive of design practices in a sustainable way. I also hope that Taiwan never suffers under censorship or shutdown but I believe there is the resilience and knowledge to prepare and mitigate these circumstances should they come to pass.

**Soybean:** I hope Taiwan continues to maintain an open, diverse, and free social environment, allowing creativity, ideas, and technology to thrive. I also hope open-source software becomes a daily tool for more people, embedding the spirit of sharing technology into everyone’s lives and enabling collaboration. As for internet freedom, I hope we can continue to promote open access, allowing more people to freely access information, express their ideas, and use the power of the internet for effective collaboration. This way, we can support each other and face global challenges together. 

**Cocoa:** I hope that Taiwan continues to be a relatively safer space for activists and people in general to fight on the right side of Internet freedom. I hope that the culture of design in tech and open source grows stronger and that there are more diverse communities participating in conferences such as COSCUP.

**Basil:** I hope that people in Taiwan can embrace open-source software (OSS) with greater openness, instead of relying solely on commercial software due to a reluctance to learn. As for internet freedom, I hope that while defending it, people can also enhance their ability to discern misinformation and cherish the hard-earned freedom they enjoy.

![img](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/Documenting%20Internet%20Shutdowns%20Workshop/graphics%20and%20illustrations/document%20image%20dividers/bubble-tea-full-width.png)

---

# OSS and documentations process

This workshop’s (and the 2024 workshop) resources, content and illustrations have been uploaded to a Github Repository https://github.com/sprblm/The-Design-We-Open/tree/main. There you will find the content under a [CC0 1.0 Universal license](https://github.com/sprblm/The-Design-We-Open/blob/main/LICENSE). This license details under what circumstances people can modify or use this content.
[Superbloom Design](https://superbloom.design/) maintains open source repositories on an adhoc basis after publishing. If you want to contribute we suggest [creating/participating in issues](https://github.com/sprblm/The-Design-We-Open/issues), [creating/participating in discussions](https://github.com/sprblm/The-Design-We-Open/discussions) or making a [pull request](https://github.com/sprblm/The-Design-We-Open/pulls).

Find our design documentation in our repository: https://github.com/sprblm/The-Design-We-Open/blob/main/Documenting%20Internet%20Shutdowns%20Workshop/graphics%20and%20illustrations/visuals-and-graphics.md 

# Thank you

Thank you to [COSCUP](https://coscup.org/) for hosting and being a supporter and advocate for design in their OSS event.
Thank you to [Least Authority:Destiny](https://leastauthority.com/community-matters/destiny/), [Briar](https://briarproject.org/) and [NewNode](https://www.newnode.com/) for being open source software project examples in our internet shutdowns workshop.

Thank you to the attendees, volunteers and supporters involved in these workshops.

![img](https://raw.githubusercontent.com/sprblm/The-Design-We-Open/refs/heads/main/Documenting%20Internet%20Shutdowns%20Workshop/graphics%20and%20illustrations/document%20image%20dividers/notebooks-full-width.png)

