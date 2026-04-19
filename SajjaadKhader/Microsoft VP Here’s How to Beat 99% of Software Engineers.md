# Microsoft VP: Here’s How to Beat 99% of Software Engineers

## Video Information
- **Video URL:** https://www.youtube.com/watch?v=ekOh45Mw7EY
- **Video ID:** ekOh45Mw7EY

## Transcript

10 years ago, maybe you could just be a really good coder. Now, you're going to have to be a product manager and a good user of these AI tools, leveled out the playing field, and now it's more about is what you're producing good. You need to be thinking about and at the beginning, in fact, I would actually say you should maybe think about studying that before you even learn how to write code. >> Will AI replace software engineers? [sighs] That's a tricky one. Um, today I'm sitting down with Brendan Burns, a corporate vice president at Microsoft to talk about the future of coding, software engineering, and a super popular technology known as Kubernetes. If you're in computer science or are a beginner in tech, you need to know about Kubernetes. Nearly every big tech company you might work at uses it, and it's a skill companies actively hire for today. And lucky for you, Brendan is not only a Microsoft leader, but he's actually one of the co-creators of Kubernetes itself. So, we're getting a real insider scoop into this technology. In this video, we break down what Kubernetes actually is, how it took over the tech and AI industry and how you can use it to build real projects that will actually get you hired in tech. And as a Microsoft leader, he shares specific advice on the future of coding and software engineering in the age of AI and key skills to focus on in this shifting landscape. a lot of value to unpack in this video. So, let's get right to it. Can you actually introduce yourself to us? >> Sure. Hi, I'm Brendan. As was mentioned, I'm the corporate vice president for Azure cloud native and management platforms. Um, which basically has to do with everything modern cloud application development on Azure and a lot of open source. I've been involved in the tech industry and and open source for over 25 years at this point. uh and I guess most famously helped create was the three co-creators of the Kubernetes open source project which is now the way that people define and manage applications in the cloud. >> Yeah, absolutely. And getting into that, if I have no clue what Kubernetes is, >> how would you describe it to me as if I was like 5 years old? >> Sure. I mean, I guess one of the easiest ways to describe it is maybe tell a story from my past. Mh. >> Um, so when I was a kid, I got a model airplane kit and I spent a long time building this model airplane. If you're balsa wood airplanes, spent a very long time building this balsa wood airplane. Um, and I went to fly it and uh, it took off and it was amazing and it lasted about 10 seconds and it crashed into the ground and exploded into a million pieces. >> Okay. >> Um, and now my my kids experience of flying an airplane is they got a little quadcopter drone. They have an iPad. Yeah. >> They fly it around the house. >> Right. Right. >> Does it crash? doesn't it just it goes and I think that that's the key insight which is that the reason that that works is because when I was flying that airplane I had to control everything myself you have to control the throttle you have to control the where it goes the run all that stuff >> when my children are flying this drone around there is software in there helps keep it level that takes their intent >> I want this thing to go forward and translates that intent >> into action into a holistic package of software >> it's a piece of software that that is designed to say actually you don't care how fast the motors are spinning. You just want this thing to go forward, >> right? And Kubernetes is there to do that for your application, >> right? >> So, it's like an autopilot for your application, >> right? >> And it will do things like automatically scale it up. So, you you know, you obviously still still have to write the code, although we can talk about how AI the code more and more, but the code is written and packaged as a container. Um, which is really, you can think of it like just a runnable thingy. and you give that runnable thingy to Kubernetes and you say, I want this to be reliable and I want it to scale. >> Um because obviously if you want to be su if you want your application to be successful, it's going to have to be reliable for your users and scale out as you you get more and more users. Just like that autopilot on the drone, Kubernetes takes care of those sorts of things for your application. You need three replicas, it'll create those three replicas. Your program crashes, it will restart your program. >> Interesting. >> U so it's it's really kind of like an autopilot for your cloud applications, >> right? Really quick, we talk a lot about AI on this channel, and if you really want to take your workflow with AI to the next level, you need to use Zapier. If you're a computer science student or software engineer, you're probably using AI tools everywhere. Chat GPT for ideas, Notion for notes, Slack, email, GitHub, Google Docs. The problem is none of these tools talk to each other. So, you end up trying to put everything together instead of focusing on real engineering. This is where Zapier, the sponsor of today's video, comes in. Zapier is basically AI orchestration. Instead of just chatting with AI, you tell Zapier Copilot what you want in plain English. No code required. And it builds an actual workflow or agent for you. For example, I told Copilot when I get a new project idea, create a description with AI, save it to notion, and notify me on Slack. No scripts, no APIs. Zapier just wires it all together across thousands of apps and 8,000 plus supported integrations. This is huge for engineers because this is how real teams scale AI because now instead of doing all these steps manually, I get to just focus on the actual creative project. And then all the nitty-gritty work of building the project description, adding it to notion task, and notifying my teammates on Slack is handled by Zapier. Zapier easily saves me at least 10 hours of work per week. And I have tested tens and tens of AI tools, and I can confidently tell you Zapier is the one on top. So, if you're ready to advance your workflow with AI and build agents that actually do work for you, check out Zapier. I linked my workflow template below so you could try it yourself. Thank you to Zapier for sponsoring this video. And now, back to the interview. One uh thing that I try to think about is, for example, you know how Oreos, right? They're sent out in packages, right? Because if someone wanted an Oreo and individual cookies were sent all across the world, it would get damaged and corrupted. But putting into this kind of like packaged nice thing that's kind of synonymous with >> the heart of Kubernetes is is the container, right? Um we didn't invent the container. The container was invented by uh Docker which is a separate open source project. But yeah, that container basically to take your Oreo analogy from a consumer of Oreo's perspective, I just buy one package and I and I open it and I eat it, right? But from the store's perspective or the shipper's perspective, they have hundreds of those packages and they don't actually look inside. they just deal with the outside and they know they can, you know, put them all on the shelf. >> So that's where the Kubernetes >> Kubernetes is that thing that says like I don't actually care what's inside the package. >> But I can stack up a hundred of them on the shelf and if all you know a whole bunch of people want Oreos all at once, >> they can come into the store and they can pull all those packages off and they each individually get to have their Oreos. But as a store, all I cared about was like stacking them up and I didn't have to worry about the individual details of what's inside. So if I'm a student or beginner in tech and I want to do a project that involves Kubernetes as part of the tools, what's the project that you would recommend? >> You want to build something that's useful to you? >> Yeah. >> Well, so like I was just out doing this vibe coding thing and I was actually building a reminders app for my family so that we can have each person can have a list of their reminders for the day and they go through them. We don't have to sort of constantly be like, "Hey, have you done your homework? Hey, you know." So, I think that could be an example that's going to hopefully, you know, make the the the family life a little happier, but it's going to vary depending on the person, right? Actually, another one I wrote an app a long time ago for uh enabling everybody to turn the Christmas tree lights on and off, even if they were upstairs or in bed or whatever, >> right? Did I remember turn it off, right? Um, but you find whatever app is the thing that you are excited about because if you're excited about it and it's useful to you, you'll go deeper. If you're just kind of running through the example like click click click through the example, you sort of get something done at the end but you don't necessarily learn. >> Right. Right. >> Because you just kind of did what you were told. It's like following a recipe. >> It's like following a recipe a good meal maybe but it's not going to make you a great cook. >> Right. Right. >> Right. Um >> and getting deeper into that project. So like uh the reminders app for example. At what point do you integrate the Kubernetes? Because the reminders app I could throw up a quick Python script for. Right. >> Sure. Sure. Well, I mean, but I think it's one of those things where once I'm building it for my family, they want it to work all the time, right? And they don't want it to be like, >> "Oh, it crashed. Maybe I'll go restart it somewhere." They want it to just keep going, right? So, actually, I have a a little Kubernetes cluster that's running in my house. >> Um, probably not everybody does that, but I do. And so, I'll just deploy it there, and everybody's mobile uh or web devices can talk to that. It's got a DNS entry, and so I can So, they can access it. they can access it and I have all the monitoring that I need to understand if there's a problem or anything like that. That might not be the the default, but I would say that like once you're ready to put it out there for someone else to use, that's a good moment when it's when it's moving from your laptop into the cloud, that's a good moment. >> And I feel like people should be doing that, right? They should be pushing this stuff out, right? >> Absolutely. I think so. I mean, and if you want to get started even earlier, you know, you can run a very small Kubernetes installation in a virtual machine on your desktop or laptop and uh that's that's a good way. We've got a lot of really great integration with VS Code, right? To make it super easy for people to get started. >> Obviously, in the this like world of AI, how is AI impacting infrastructure and Kubernetes? >> Yeah, I mean, I think there's two things. One is that like literally all of the AI that you see out there, it's running on Kubernetes, right? Right. So when you use chat GPT that's running on Kubernetes and running on Azure and you know most of the AI training and serving that is done out there started with Kubernetes because these AI applications they need to bring lots of uh machines together >> and uh Kubernetes is a great interface for that and frankly the AI people they don't care about the machine management they just wanted to say hey someone else takes care of it for you. >> Right. Right. Right. >> So that's one form is it's the foundation for a lot of the the AI work that you see out there. But I also I think you know you sort of alluded to it a little bit. This technology can be kind of complicated. >> Right. >> Right. And so I think we're also seeing things like copilot being used to help people learn. >> Okay. I want to, you know, create a docker file for a node.js application, right? >> You used to have to do a bunch of research to do that. Now that's a >> the AI sets up the infrastructure >> the co-pilot, right? And it will set it up for you. Or I want to deploy this application out to a Kubernetes cluster. How's the best way for me to do that? the AI can generate you the right config files. I don't think it's intended that you stay in the using the AI forever, but it's a jump start, right? It helps you get to a place where something's working. I personally find, you know, I'm much more motivated when it's working. >> Yeah. I hate environment setups and all that, right? Just telling the >> terminal errors, >> they're like the whole thing, right? Like I don't want to do any of that, right? And so I actually end up a lot of times doing a really bad job or making like lesser technology choices cuz they're just easier. >> Right. Right. Right? Like I'm I'm totally lazy at times, right? And I found that the GitHub copilot actually helps me be better. >> It's taken a lot of the toil out of a lot of this environment. >> Yeah. All the grunt work. >> It's just the like stuff I don't want to learn about, you know? I just want it to work. >> Um, so yeah. >> Yeah. And I got to ask, as a corporate vice president at Microsoft, if I'm a beginner and I want to break into tech, what's your number one piece of advice? >> Focus on what you're excited about, >> right? because I think that you know there's a lot of learning and obviously you're all about helping people learn right and I think that if you're excited you'll learn more >> so I think sometimes people get see the the various things that are hyped or various things that are popular like AI right now is very hot right and they think wow I need to go where the hotness is right and if you're excited about that then absolutely go right right but there's jobs all over the tech industry right and if you're more excited about the operating system than you are about the AI go deep on the operating system Right? Or if you're excited about front-end development, go build a bunch of frontends or mobile apps. Go build a bunch of mobile apps, right? Because that passion and that energy is gonna take you further than worrying about, you know, the specific topic, right? >> And actually, the other thing is I would say, you know, learning how to learn about technology is kind of the same regardless of the technology. And so once you found the thing that you're excited about and you've learned how to learn, then you can go and say, "Oh, okay. Now this you know this job like AI is a big deal right and I would say actually right now learning how to use AI to build software >> you should go do that >> like that is just like that's going to be a requirement that is an expectation and I think that one of the interesting things that I'm seeing anyway is that learning how to use the AI really well if you're new to it if you're new to software development it'll spit out a ton of code >> but you need to be able to judge if it's good code >> you need to be able to tell it >> you can't just be a vibe coder without knowledge right >> be a vibe coder without a knowledge of how the software is supposed to be built, right? And so where something like software engineering >> and unit testing and all that kind of stuff might have been a third, fourth, fifth semester kind of class, a 200 levelish, 250 levelish class. I think it's now a 101 class, >> right? You need to be thinking about object modeling and testing and API design and all of the principles of good software engineering. Yeah. >> At the beginning. In fact, I would actually say you should maybe think about studying that before you even learn how to read write code >> because at this point we're at a place where knowing how to generate the code is not necessarily that important. >> Yeah. It's also not that impressive. >> Well, and that's true too, right? It's not all that impressive, right? And but knowing how to build something, remember, we're still going to be operating on Teams, >> uh, you know, software teams. >> Yeah. Yeah. Yeah. Microsoft Teams. >> Microsoft Teams, although hopefully on Microsoft Teams. [laughter] And so learning how to build code that works well with other people that multiple people can maintain that you know code lives for a really long time. >> So learning how to build maintainable testable code is is a valuable skill. Actually writing the code you know I think that's becoming less and less of the importance. >> Right. Right. It just seems kind of like a baseline you should know other than oh wow you know it. >> Yeah. And it used to be like you know I think that the volume of good code that you could write >> Yeah. was kind of a marker, especially in the early stages of your career, was kind of a marker of like how fast you were going to run, how fast you were going to go. >> But now it's like you better. >> Yeah. And at this point, I think it's much more like no, we've leveled out the playing field and now it's more about like is what you're producing good, >> right? I guess in some ways it's like going from a handsaw where like your muscle matters to a power saw where like what you do with it matters, >> right? Yeah. And I actually I want to drill into something you mentioned where learning how to use AI for software development. How does a beginner learn how to use AI for software development? >> Yeah. Have some idea of what you want to what you want to do. Find some idea just whatever occurs you. I mean a lot I go running a lot. >> Ideas occur to me when I'm out running. Yeah. >> Um and then you go home and you build them. >> Yeah. >> Right. And I think we really are at that place where you know if you're in GitHub and you're using GitHub copilot you can really just start with agent mode and say like hey I had this idea scaffold me a TypeScript app for doing this right and it will generate it out. >> So basically just start doing it >> just start doing it. Yeah, I mean I think a little bit of learning. I mean, obviously you have to learn enough to know, okay, TypeScript's a perfect language. Uh, you know, oh, here's the >> Yeah, we talked to Anders earlier, >> right? >> So, you know, there is a little bit of like learning of that, but then I think if you want to learn how to use the AI, just use it. Yeah. >> You know, um, learn what it's good at, learn what it's bad at. I think it's really good, especially early on, I found when I was teaching myself Rust, >> I found it was really good at explaining compiler errors to me, >> right? I think early on when people are using these tools sometimes you get really especially some of the open source ones you get really opaque errors >> you're like get it you're not you won't do what I want you to do >> why [laughter] >> right and actually you can in the co-pilot if you're in VS Code and you're in the terminal you can actually say hey co-pilot you know at terminal explain >> and it will look at the output of the program that's in your terminal and it will try to explain to you >> what's going wrong and how you might fix it >> right so I think that helps It helps you, right? It helps you get over those because I think when early on, especially you hit these roadblocks where you feel really stuck, >> like really frustratingly stuck, right? I don't know how to do this. Why is it not I know like I know what I want it to do, >> it won't do it. >> Right. Right. >> Right. And I think, you know, AI can help you get through that. Um, and learning how to to work with it there helps a lot. >> Okay. And now a very hot question. Will AI replace software engineers? We've been developing technology to make building software easier for 70 years at this point. From the dawn of the first forran compiler all the way through to co-pilot today, we've [music] been making it easier and more approachable, more accessible for people to build software. And the only thing that has ever happened is that we've built more software. So no, I don't think the total number I think the job changes, right? Like you know, as I said, like I think that >> So how do you see like software engineers in 2025 compared to software engineers in 2030? Like right now we're writing code, we're deploying the code. What do you think software engineers in 2030 are going to be doing? >> I think what happens is there's a lot more focus on what is the product, >> what are we actually trying to build, what's the specification, what's the validation that we're using to make sure it's working. A lot less of a focus on like what are the actual mechanics of building the software. 10 years ago, maybe you could just be a really good coder. >> Right >> now, you're going to have to be a product manager and a good user of these AI tools because you have to be able to understand what should the product look like. I think what Satya mentioned yesterday in his keynote, it's like software engineers are going to be managers of AI teams going forward. >> Yeah, a certain amount of that. And I'd like to remind people that like the machines are already generating all the code, >> right? Compilers have been generating all of the machine code for years, decades at this point, right? I think it's useful to think of AI as just being a better compiler or a higher level compiler. >> Yeah. Like who who it's more of just the abstraction of the written rather than the compile, right? Yeah. And so it's like it's allowing you to talk at higher levels, >> but you still have to know what you want to build, right? >> Right. Um, we just finished building a house and and it's not like I walked up to the architect and said, "I want a house." And then walked away and years. No, they asked me questions, right? How many kids do you have? What kind of activities do you like doing? You What are your colors do you like? Do you like the modern style or more traditional? You know, like there's a lot of decisions that I made that go into the final product and and ultimately the usefulness of that thing is is dictated by my vision and and our vision, right? And so I think that's the that's the thing that that is still essential is that we, you know, we still have to understand why, right? >> We don't just build code because we build code. We build code for a purpose. In some sense, the cheaper we make it to build software and to build reliable software, the more places we will find to put software. M yeah I I always say like uh right now if you have like one software engineer develops one feature in the future might have one software engineer developing a hundred features because they're managing the AI team to do that. >> But I will tell you from running a lot of engineering teams it's not like our backlogs lack hundreds or thousands of features that we're not that we're not doing. Yeah, tech's part of it, but also just like straight up features, right? Or somebody wants something >> and we just say, well, you know what? Like it just doesn't make it into the prior prioritized list >> of things that we're going to work on this semester, right? >> But future it will. >> Future it will, right? And I think that again makes the software better. Think about all of the work that we do on accessibility, right? >> That is work that has to be coded today and there's limits, right? I mean, we try and do a really good job on accessibility, but obviously like people find gaps. Now imagine if you you know we have 10x the amount of code that's being generated. We can customize our applications 10x more to better fit every individual in the world. Right? So I think I don't know I I'm maybe I'm too much of an optimist but I profoundly believe that there will be more work. The work changes but there will always be more work in terms of building software. >> And I also got to ask so for young people beginners in tech what do you think is the number one common mistake that you see they make? you get through school early in your career if you're in the tech industry, it is a team sport. You're supposed to ask for help, I think, especially in this days of hybrid and other stuff like that. It can be hard, right? See, people get stuck, you know, and and often I'm stuck on dumb stuff, too, right? Like honestly, I I've told people on on our teams like if you get stuck for longer than half an hour, it's probably something that we did, not something that you did, right? We probably just didn't document it right or the tool is buggy or, you know, like we have the same kind of debt and mistakes that other people do. Um and getting people over that hurdle of asking for help I think is I mean you don't want to ask [laughter] you don't always be asking for help but also you know a lot of what you're doing in the beginning is is figuring it is learning and figuring it out and often times like >> you know again documentation's out of date or we just didn't build a really good onboarding script or whatever. So like that willingness to be a little bit vulnerable ask for a little bit of help can also go a long way. Um, so yeah, that's another another thing I see people do sometimes. >> Well, that's about all I have in this video. I really hope that you guys enjoyed it and if you did, make sure to hit the like button, subscribe if you haven't already. If you're interested in my absolutely free tech newsletter, link for that will also be in the description. And if you're interested in watching the interview that I had with the CEO of Microsoft, Satya Nadella, asking him about how to get hired in tech, you might like this video right

## Detailed Segments

### Segment 1 [00:00]
**Duration:** 2.6 seconds

10 years ago, maybe you could just be a

---

### Segment 2 [00:01]
**Duration:** 2.9 seconds

really good coder. Now, you're going to

---

### Segment 3 [00:02]
**Duration:** 3.5 seconds

have to be a product manager and a good

---

### Segment 4 [00:04]
**Duration:** 3.4 seconds

user of these AI tools, leveled out the

---

### Segment 5 [00:06]
**Duration:** 3.3 seconds

playing field, and now it's more about

---

### Segment 6 [00:07]
**Duration:** 3.9 seconds

is what you're producing good. You need

---

### Segment 7 [00:09]
**Duration:** 4.5 seconds

to be thinking about

---

### Segment 8 [00:11]
**Duration:** 3.6 seconds

and at the beginning, in fact, I would

---

### Segment 9 [00:13]
**Duration:** 2.7 seconds

actually say you should maybe think

---

### Segment 10 [00:15]
**Duration:** 2.5 seconds

about studying that before you even

---

### Segment 11 [00:16]
**Duration:** 3.0 seconds

learn how to write code.

---

### Segment 12 [00:17]
**Duration:** 5.4 seconds

>> Will AI replace software engineers?

---

### Segment 13 [00:19]
**Duration:** 5.2 seconds

[sighs] That's a tricky one. Um,

---

### Segment 14 [00:23]
**Duration:** 3.8 seconds

today I'm sitting down with Brendan

---

### Segment 15 [00:24]
**Duration:** 3.8 seconds

Burns, a corporate vice president at

---

### Segment 16 [00:26]
**Duration:** 3.7 seconds

Microsoft to talk about the future of

---

### Segment 17 [00:28]
**Duration:** 3.8 seconds

coding, software engineering, and a

---

### Segment 18 [00:30]
**Duration:** 3.6 seconds

super popular technology known as

---

### Segment 19 [00:32]
**Duration:** 4.3 seconds

Kubernetes. If you're in computer

---

### Segment 20 [00:34]
**Duration:** 4.3 seconds

science or are a beginner in tech, you

---

### Segment 21 [00:36]
**Duration:** 3.7 seconds

need to know about Kubernetes. Nearly

---

### Segment 22 [00:38]
**Duration:** 3.9 seconds

every big tech company you might work at

---

### Segment 23 [00:40]
**Duration:** 4.3 seconds

uses it, and it's a skill companies

---

### Segment 24 [00:42]
**Duration:** 4.4 seconds

actively hire for today. And lucky for

---

### Segment 25 [00:44]
**Duration:** 3.9 seconds

you, Brendan is not only a Microsoft

---

### Segment 26 [00:46]
**Duration:** 4.4 seconds

leader, but he's actually one of the

---

### Segment 27 [00:48]
**Duration:** 4.6 seconds

co-creators of Kubernetes itself. So,

---

### Segment 28 [00:51]
**Duration:** 3.8 seconds

we're getting a real insider scoop into

---

### Segment 29 [00:53]
**Duration:** 4.3 seconds

this technology. In this video, we break

---

### Segment 30 [00:55]
**Duration:** 4.6 seconds

down what Kubernetes actually is, how it

---

### Segment 31 [00:57]
**Duration:** 4.1 seconds

took over the tech and AI industry and

---

### Segment 32 [00:59]
**Duration:** 3.2 seconds

how you can use it to build real

---

### Segment 33 [01:01]
**Duration:** 3.1 seconds

projects that will actually get you

---

### Segment 34 [01:02]
**Duration:** 3.8 seconds

hired in tech. And as a Microsoft

---

### Segment 35 [01:04]
**Duration:** 3.2 seconds

leader, he shares specific advice on the

---

### Segment 36 [01:06]
**Duration:** 3.4 seconds

future of coding and software

---

### Segment 37 [01:08]
**Duration:** 4.1 seconds

engineering in the age of AI and key

---

### Segment 38 [01:10]
**Duration:** 3.9 seconds

skills to focus on in this shifting

---

### Segment 39 [01:12]
**Duration:** 3.6 seconds

landscape. a lot of value to unpack in

---

### Segment 40 [01:14]
**Duration:** 2.7 seconds

this video. So, let's get right to it.

---

### Segment 41 [01:15]
**Duration:** 1.5 seconds

Can you actually introduce yourself to

---

### Segment 42 [01:16]
**Duration:** 2.0 seconds

us?

---

### Segment 43 [01:17]
**Duration:** 3.0 seconds

>> Sure. Hi, I'm Brendan. As was mentioned,

---

### Segment 44 [01:18]
**Duration:** 2.7 seconds

I'm the corporate vice president for

---

### Segment 45 [01:20]
**Duration:** 3.1 seconds

Azure cloud native and management

---

### Segment 46 [01:21]
**Duration:** 4.4 seconds

platforms. Um, which basically has to do

---

### Segment 47 [01:23]
**Duration:** 4.7 seconds

with everything modern cloud application

---

### Segment 48 [01:26]
**Duration:** 3.8 seconds

development on Azure and a lot of open

---

### Segment 49 [01:28]
**Duration:** 4.9 seconds

source. I've been involved in the tech

---

### Segment 50 [01:29]
**Duration:** 5.4 seconds

industry and and open source for over 25

---

### Segment 51 [01:32]
**Duration:** 5.4 seconds

years at this point. uh and I guess most

---

### Segment 52 [01:35]
**Duration:** 5.2 seconds

famously helped create was the three

---

### Segment 53 [01:38]
**Duration:** 4.9 seconds

co-creators of the Kubernetes open

---

### Segment 54 [01:40]
**Duration:** 4.6 seconds

source project which is now the way that

---

### Segment 55 [01:43]
**Duration:** 2.5 seconds

people define and manage applications in

---

### Segment 56 [01:45]
**Duration:** 2.7 seconds

the cloud.

---

### Segment 57 [01:45]
**Duration:** 4.6 seconds

>> Yeah, absolutely. And getting into that,

---

### Segment 58 [01:47]
**Duration:** 4.4 seconds

if I have no clue what Kubernetes is,

---

### Segment 59 [01:50]
**Duration:** 3.3 seconds

>> how would you describe it to me as if I

---

### Segment 60 [01:52]
**Duration:** 3.0 seconds

was like 5 years old?

---

### Segment 61 [01:53]
**Duration:** 3.4 seconds

>> Sure. I mean, I guess one of the easiest

---

### Segment 62 [01:55]
**Duration:** 3.0 seconds

ways to describe it is maybe tell a

---

### Segment 63 [01:56]
**Duration:** 3.8 seconds

story from my past. Mh.

---

### Segment 64 [01:58]
**Duration:** 4.5 seconds

>> Um, so when I was a kid, I got a model

---

### Segment 65 [02:00]
**Duration:** 3.3 seconds

airplane kit and I spent a long time

---

### Segment 66 [02:02]
**Duration:** 3.2 seconds

building this model airplane. If you're

---

### Segment 67 [02:04]
**Duration:** 3.7 seconds

balsa wood airplanes, spent a very long

---

### Segment 68 [02:05]
**Duration:** 5.4 seconds

time building this balsa wood airplane.

---

### Segment 69 [02:07]
**Duration:** 5.5 seconds

Um, and I went to fly it and uh, it took

---

### Segment 70 [02:11]
**Duration:** 3.2 seconds

off and it was amazing and it lasted

---

### Segment 71 [02:13]
**Duration:** 2.7 seconds

about 10 seconds and it crashed into the

---

### Segment 72 [02:14]
**Duration:** 1.8 seconds

ground and exploded into a million

---

### Segment 73 [02:15]
**Duration:** 1.2 seconds

pieces.

---

### Segment 74 [02:16]
**Duration:** 4.3 seconds

>> Okay.

---

### Segment 75 [02:17]
**Duration:** 5.8 seconds

>> Um, and now my my kids experience of

---

### Segment 76 [02:20]
**Duration:** 4.2 seconds

flying an airplane is they got a little

---

### Segment 77 [02:22]
**Duration:** 2.2 seconds

quadcopter drone. They have an iPad.

---

### Segment 78 [02:24]
**Duration:** 1.3 seconds

Yeah.

---

### Segment 79 [02:25]
**Duration:** 1.4 seconds

>> They fly it around the house.

---

### Segment 80 [02:26]
**Duration:** 1.9 seconds

>> Right. Right.

---

### Segment 81 [02:26]
**Duration:** 3.0 seconds

>> Does it crash? doesn't it just it goes

---

### Segment 82 [02:28]
**Duration:** 3.2 seconds

and I think that that's the key insight

---

### Segment 83 [02:29]
**Duration:** 2.8 seconds

which is that the reason that that works

---

### Segment 84 [02:31]
**Duration:** 2.8 seconds

is because when I was flying that

---

### Segment 85 [02:32]
**Duration:** 3.4 seconds

airplane I had to control everything

---

### Segment 86 [02:34]
**Duration:** 3.4 seconds

myself you have to control the throttle

---

### Segment 87 [02:35]
**Duration:** 3.4 seconds

you have to control the where it goes

---

### Segment 88 [02:37]
**Duration:** 4.0 seconds

the run all that stuff

---

### Segment 89 [02:39]
**Duration:** 4.8 seconds

>> when my children are flying this drone

---

### Segment 90 [02:41]
**Duration:** 4.5 seconds

around there is software in there helps

---

### Segment 91 [02:43]
**Duration:** 3.8 seconds

keep it level that takes their intent

---

### Segment 92 [02:46]
**Duration:** 3.5 seconds

>> I want this thing to go forward and

---

### Segment 93 [02:47]
**Duration:** 5.8 seconds

translates that intent

---

### Segment 94 [02:49]
**Duration:** 4.6 seconds

>> into action into a holistic package of

---

### Segment 95 [02:53]
**Duration:** 2.0 seconds

software

---

### Segment 96 [02:54]
**Duration:** 3.1 seconds

>> it's a piece of software that that is

---

### Segment 97 [02:55]
**Duration:** 3.6 seconds

designed to say actually you don't care

---

### Segment 98 [02:57]
**Duration:** 3.8 seconds

how fast the motors are spinning. You

---

### Segment 99 [02:59]
**Duration:** 3.5 seconds

just want this thing to go forward,

---

### Segment 100 [03:01]
**Duration:** 2.8 seconds

>> right? And Kubernetes is there to do

---

### Segment 101 [03:02]
**Duration:** 1.5 seconds

that for your application,

---

### Segment 102 [03:03]
**Duration:** 2.5 seconds

>> right?

---

### Segment 103 [03:04]
**Duration:** 3.0 seconds

>> So, it's like an autopilot for your

---

### Segment 104 [03:06]
**Duration:** 1.3 seconds

application,

---

### Segment 105 [03:07]
**Duration:** 2.3 seconds

>> right?

---

### Segment 106 [03:07]
**Duration:** 3.6 seconds

>> And it will do things like automatically

---

### Segment 107 [03:09]
**Duration:** 2.9 seconds

scale it up. So, you you know, you

---

### Segment 108 [03:11]
**Duration:** 3.1 seconds

obviously still still have to write the

---

### Segment 109 [03:12]
**Duration:** 4.2 seconds

code, although we can talk about how AI

---

### Segment 110 [03:14]
**Duration:** 4.5 seconds

the code more and more, but the code is

---

### Segment 111 [03:16]
**Duration:** 3.8 seconds

written and packaged as a container. Um,

---

### Segment 112 [03:18]
**Duration:** 3.6 seconds

which is really, you can think of it

---

### Segment 113 [03:20]
**Duration:** 4.3 seconds

like just a runnable thingy. and you

---

### Segment 114 [03:22]
**Duration:** 4.8 seconds

give that runnable thingy to Kubernetes

---

### Segment 115 [03:24]
**Duration:** 3.9 seconds

and you say, I want this to be reliable

---

### Segment 116 [03:27]
**Duration:** 2.6 seconds

and I want it to scale.

---

### Segment 117 [03:28]
**Duration:** 2.4 seconds

>> Um because obviously if you want to be

---

### Segment 118 [03:29]
**Duration:** 2.6 seconds

su if you want your application to be

---

### Segment 119 [03:31]
**Duration:** 3.8 seconds

successful, it's going to have to be

---

### Segment 120 [03:32]
**Duration:** 4.5 seconds

reliable for your users and scale out as

---

### Segment 121 [03:34]
**Duration:** 3.8 seconds

you you get more and more users. Just

---

### Segment 122 [03:36]
**Duration:** 3.4 seconds

like that autopilot on the drone,

---

### Segment 123 [03:38]
**Duration:** 3.2 seconds

Kubernetes takes care of those sorts of

---

### Segment 124 [03:40]
**Duration:** 3.3 seconds

things for your application. You need

---

### Segment 125 [03:41]
**Duration:** 3.8 seconds

three replicas, it'll create those three

---

### Segment 126 [03:43]
**Duration:** 3.1 seconds

replicas. Your program crashes, it will

---

### Segment 127 [03:45]
**Duration:** 1.4 seconds

restart your program.

---

### Segment 128 [03:46]
**Duration:** 2.0 seconds

>> Interesting.

---

### Segment 129 [03:47]
**Duration:** 3.7 seconds

>> U so it's it's really kind of like an

---

### Segment 130 [03:48]
**Duration:** 3.9 seconds

autopilot for your cloud applications,

---

### Segment 131 [03:50]
**Duration:** 4.0 seconds

>> right? Really quick, we talk a lot about

---

### Segment 132 [03:52]
**Duration:** 4.2 seconds

AI on this channel, and if you really

---

### Segment 133 [03:54]
**Duration:** 4.3 seconds

want to take your workflow with AI to

---

### Segment 134 [03:56]
**Duration:** 4.1 seconds

the next level, you need to use Zapier.

---

### Segment 135 [03:59]
**Duration:** 3.7 seconds

If you're a computer science student or

---

### Segment 136 [04:00]
**Duration:** 4.8 seconds

software engineer, you're probably using

---

### Segment 137 [04:02]
**Duration:** 5.9 seconds

AI tools everywhere. Chat GPT for ideas,

---

### Segment 138 [04:05]
**Duration:** 5.3 seconds

Notion for notes, Slack, email, GitHub,

---

### Segment 139 [04:08]
**Duration:** 4.2 seconds

Google Docs. The problem is none of

---

### Segment 140 [04:10]
**Duration:** 3.9 seconds

these tools talk to each other. So, you

---

### Segment 141 [04:12]
**Duration:** 4.2 seconds

end up trying to put everything together

---

### Segment 142 [04:14]
**Duration:** 3.8 seconds

instead of focusing on real engineering.

---

### Segment 143 [04:17]
**Duration:** 3.4 seconds

This is where Zapier, the sponsor of

---

### Segment 144 [04:18]
**Duration:** 3.6 seconds

today's video, comes in. Zapier is

---

### Segment 145 [04:20]
**Duration:** 4.5 seconds

basically AI orchestration. Instead of

---

### Segment 146 [04:22]
**Duration:** 5.1 seconds

just chatting with AI, you tell Zapier

---

### Segment 147 [04:24]
**Duration:** 4.5 seconds

Copilot what you want in plain English.

---

### Segment 148 [04:27]
**Duration:** 4.4 seconds

No code required. And it builds an

---

### Segment 149 [04:29]
**Duration:** 4.9 seconds

actual workflow or agent for you. For

---

### Segment 150 [04:31]
**Duration:** 4.6 seconds

example, I told Copilot when I get a new

---

### Segment 151 [04:34]
**Duration:** 4.6 seconds

project idea, create a description with

---

### Segment 152 [04:36]
**Duration:** 5.0 seconds

AI, save it to notion, and notify me on

---

### Segment 153 [04:38]
**Duration:** 4.8 seconds

Slack. No scripts, no APIs. Zapier just

---

### Segment 154 [04:41]
**Duration:** 4.6 seconds

wires it all together across thousands

---

### Segment 155 [04:43]
**Duration:** 4.6 seconds

of apps and 8,000 plus supported

---

### Segment 156 [04:46]
**Duration:** 4.9 seconds

integrations. This is huge for engineers

---

### Segment 157 [04:48]
**Duration:** 4.3 seconds

because this is how real teams scale AI

---

### Segment 158 [04:51]
**Duration:** 3.8 seconds

because now instead of doing all these

---

### Segment 159 [04:52]
**Duration:** 4.6 seconds

steps manually, I get to just focus on

---

### Segment 160 [04:54]
**Duration:** 4.2 seconds

the actual creative project. And then

---

### Segment 161 [04:57]
**Duration:** 3.5 seconds

all the nitty-gritty work of building

---

### Segment 162 [04:59]
**Duration:** 3.5 seconds

the project description, adding it to

---

### Segment 163 [05:00]
**Duration:** 4.6 seconds

notion task, and notifying my teammates

---

### Segment 164 [05:02]
**Duration:** 4.9 seconds

on Slack is handled by Zapier. Zapier

---

### Segment 165 [05:05]
**Duration:** 4.3 seconds

easily saves me at least 10 hours of

---

### Segment 166 [05:07]
**Duration:** 4.2 seconds

work per week. And I have tested tens

---

### Segment 167 [05:09]
**Duration:** 4.4 seconds

and tens of AI tools, and I can

---

### Segment 168 [05:11]
**Duration:** 3.9 seconds

confidently tell you Zapier is the one

---

### Segment 169 [05:14]
**Duration:** 3.8 seconds

on top. So, if you're ready to advance

---

### Segment 170 [05:15]
**Duration:** 4.3 seconds

your workflow with AI and build agents

---

### Segment 171 [05:17]
**Duration:** 4.2 seconds

that actually do work for you, check out

---

### Segment 172 [05:20]
**Duration:** 4.0 seconds

Zapier. I linked my workflow template

---

### Segment 173 [05:22]
**Duration:** 3.5 seconds

below so you could try it yourself.

---

### Segment 174 [05:24]
**Duration:** 3.6 seconds

Thank you to Zapier for sponsoring this

---

### Segment 175 [05:25]
**Duration:** 3.8 seconds

video. And now, back to the interview.

---

### Segment 176 [05:27]
**Duration:** 3.8 seconds

One uh thing that I try to think about

---

### Segment 177 [05:29]
**Duration:** 3.8 seconds

is, for example, you know how Oreos,

---

### Segment 178 [05:31]
**Duration:** 4.0 seconds

right? They're sent out in packages,

---

### Segment 179 [05:33]
**Duration:** 3.9 seconds

right? Because if someone wanted an Oreo

---

### Segment 180 [05:35]
**Duration:** 3.4 seconds

and individual cookies were sent all

---

### Segment 181 [05:37]
**Duration:** 3.7 seconds

across the world, it would get damaged

---

### Segment 182 [05:38]
**Duration:** 4.2 seconds

and corrupted. But putting into this

---

### Segment 183 [05:40]
**Duration:** 3.6 seconds

kind of like packaged nice thing that's

---

### Segment 184 [05:43]
**Duration:** 2.7 seconds

kind of synonymous with

---

### Segment 185 [05:44]
**Duration:** 4.4 seconds

>> the heart of Kubernetes is is the

---

### Segment 186 [05:45]
**Duration:** 4.3 seconds

container, right? Um we didn't invent

---

### Segment 187 [05:48]
**Duration:** 3.0 seconds

the container. The container was

---

### Segment 188 [05:50]
**Duration:** 3.5 seconds

invented by uh Docker which is a

---

### Segment 189 [05:51]
**Duration:** 3.5 seconds

separate open source project. But yeah,

---

### Segment 190 [05:53]
**Duration:** 4.9 seconds

that container basically to take your

---

### Segment 191 [05:55]
**Duration:** 5.5 seconds

Oreo analogy from a consumer of Oreo's

---

### Segment 192 [05:58]
**Duration:** 4.2 seconds

perspective, I just buy one package and

---

### Segment 193 [06:00]
**Duration:** 3.3 seconds

I and I open it and I eat it, right? But

---

### Segment 194 [06:02]
**Duration:** 2.9 seconds

from the store's perspective or the

---

### Segment 195 [06:04]
**Duration:** 3.1 seconds

shipper's perspective, they have

---

### Segment 196 [06:05]
**Duration:** 3.4 seconds

hundreds of those packages and they

---

### Segment 197 [06:07]
**Duration:** 3.0 seconds

don't actually look inside. they just

---

### Segment 198 [06:09]
**Duration:** 2.4 seconds

deal with the outside and they know they

---

### Segment 199 [06:10]
**Duration:** 1.4 seconds

can, you know, put them all on the

---

### Segment 200 [06:11]
**Duration:** 1.6 seconds

shelf.

---

### Segment 201 [06:11]
**Duration:** 2.6 seconds

>> So that's where the Kubernetes

---

### Segment 202 [06:13]
**Duration:** 2.6 seconds

>> Kubernetes is that thing that says like

---

### Segment 203 [06:14]
**Duration:** 2.0 seconds

I don't actually care what's inside the

---

### Segment 204 [06:15]
**Duration:** 2.3 seconds

package.

---

### Segment 205 [06:16]
**Duration:** 3.0 seconds

>> But I can stack up a hundred of them on

---

### Segment 206 [06:17]
**Duration:** 3.5 seconds

the shelf and if all you know a whole

---

### Segment 207 [06:19]
**Duration:** 3.4 seconds

bunch of people want Oreos all at once,

---

### Segment 208 [06:21]
**Duration:** 3.0 seconds

>> they can come into the store and they

---

### Segment 209 [06:22]
**Duration:** 3.0 seconds

can pull all those packages off and they

---

### Segment 210 [06:24]
**Duration:** 4.3 seconds

each individually get to have their

---

### Segment 211 [06:25]
**Duration:** 4.6 seconds

Oreos. But as a store, all I cared about

---

### Segment 212 [06:28]
**Duration:** 3.9 seconds

was like stacking them up and I didn't

---

### Segment 213 [06:30]
**Duration:** 4.1 seconds

have to worry about the individual

---

### Segment 214 [06:32]
**Duration:** 3.6 seconds

details of what's inside. So if I'm a

---

### Segment 215 [06:34]
**Duration:** 3.9 seconds

student or beginner in tech and I want

---

### Segment 216 [06:36]
**Duration:** 4.7 seconds

to do a project that involves Kubernetes

---

### Segment 217 [06:38]
**Duration:** 3.6 seconds

as part of the tools, what's the project

---

### Segment 218 [06:40]
**Duration:** 2.0 seconds

that you would recommend?

---

### Segment 219 [06:42]
**Duration:** 1.7 seconds

>> You want to build something that's

---

### Segment 220 [06:42]
**Duration:** 1.0 seconds

useful to you?

---

### Segment 221 [06:43]
**Duration:** 1.8 seconds

>> Yeah.

---

### Segment 222 [06:44]
**Duration:** 3.1 seconds

>> Well, so like I was just out doing this

---

### Segment 223 [06:45]
**Duration:** 4.5 seconds

vibe coding thing and I was actually

---

### Segment 224 [06:47]
**Duration:** 4.9 seconds

building a reminders app for my family

---

### Segment 225 [06:49]
**Duration:** 3.6 seconds

so that we can have each person can have

---

### Segment 226 [06:52]
**Duration:** 2.9 seconds

a list of their reminders for the day

---

### Segment 227 [06:53]
**Duration:** 2.8 seconds

and they go through them. We don't have

---

### Segment 228 [06:54]
**Duration:** 2.9 seconds

to sort of constantly be like, "Hey,

---

### Segment 229 [06:56]
**Duration:** 2.5 seconds

have you done your homework? Hey, you

---

### Segment 230 [06:57]
**Duration:** 2.4 seconds

know." So, I think that could be an

---

### Segment 231 [06:58]
**Duration:** 3.2 seconds

example that's going to hopefully, you

---

### Segment 232 [07:00]
**Duration:** 3.1 seconds

know, make the the the family life a

---

### Segment 233 [07:02]
**Duration:** 2.8 seconds

little happier, but it's going to vary

---

### Segment 234 [07:03]
**Duration:** 3.1 seconds

depending on the person, right?

---

### Segment 235 [07:04]
**Duration:** 3.6 seconds

Actually, another one I wrote an app a

---

### Segment 236 [07:06]
**Duration:** 3.7 seconds

long time ago for uh enabling everybody

---

### Segment 237 [07:08]
**Duration:** 3.6 seconds

to turn the Christmas tree lights on and

---

### Segment 238 [07:10]
**Duration:** 2.8 seconds

off, even if they were upstairs or in

---

### Segment 239 [07:12]
**Duration:** 3.0 seconds

bed or whatever,

---

### Segment 240 [07:12]
**Duration:** 4.3 seconds

>> right? Did I remember turn it off,

---

### Segment 241 [07:14]
**Duration:** 4.6 seconds

right? Um, but you find whatever app is

---

### Segment 242 [07:17]
**Duration:** 3.9 seconds

the thing that you are excited about

---

### Segment 243 [07:19]
**Duration:** 4.2 seconds

because if you're excited about it and

---

### Segment 244 [07:21]
**Duration:** 3.6 seconds

it's useful to you, you'll go deeper. If

---

### Segment 245 [07:23]
**Duration:** 2.5 seconds

you're just kind of running through the

---

### Segment 246 [07:24]
**Duration:** 3.3 seconds

example like click click click through

---

### Segment 247 [07:26]
**Duration:** 3.3 seconds

the example, you sort of get something

---

### Segment 248 [07:28]
**Duration:** 2.6 seconds

done at the end but you don't

---

### Segment 249 [07:29]
**Duration:** 1.7 seconds

necessarily learn.

---

### Segment 250 [07:30]
**Duration:** 1.8 seconds

>> Right. Right.

---

### Segment 251 [07:31]
**Duration:** 3.5 seconds

>> Because you just kind of did what you

---

### Segment 252 [07:32]
**Duration:** 4.6 seconds

were told. It's like following a recipe.

---

### Segment 253 [07:34]
**Duration:** 3.5 seconds

>> It's like following a recipe a good meal

---

### Segment 254 [07:36]
**Duration:** 1.8 seconds

maybe but it's not going to make you a

---

### Segment 255 [07:38]
**Duration:** 1.2 seconds

great cook.

---

### Segment 256 [07:38]
**Duration:** 1.8 seconds

>> Right. Right.

---

### Segment 257 [07:39]
**Duration:** 3.1 seconds

>> Right. Um

---

### Segment 258 [07:40]
**Duration:** 4.4 seconds

>> and getting deeper into that project. So

---

### Segment 259 [07:42]
**Duration:** 4.2 seconds

like uh the reminders app for example.

---

### Segment 260 [07:44]
**Duration:** 3.3 seconds

At what point do you integrate the

---

### Segment 261 [07:46]
**Duration:** 3.1 seconds

Kubernetes? Because the reminders app I

---

### Segment 262 [07:48]
**Duration:** 2.2 seconds

could throw up a quick Python script

---

### Segment 263 [07:49]
**Duration:** 2.2 seconds

for. Right.

---

### Segment 264 [07:50]
**Duration:** 4.2 seconds

>> Sure. Sure. Well, I mean, but I think

---

### Segment 265 [07:52]
**Duration:** 5.7 seconds

it's one of those things where once I'm

---

### Segment 266 [07:54]
**Duration:** 5.1 seconds

building it for my family, they want it

---

### Segment 267 [07:57]
**Duration:** 3.2 seconds

to work all the time, right? And they

---

### Segment 268 [07:59]
**Duration:** 3.2 seconds

don't want it to be like,

---

### Segment 269 [08:00]
**Duration:** 3.5 seconds

>> "Oh, it crashed. Maybe I'll go restart

---

### Segment 270 [08:02]
**Duration:** 3.4 seconds

it somewhere." They want it to just keep

---

### Segment 271 [08:04]
**Duration:** 3.3 seconds

going, right? So, actually, I have a a

---

### Segment 272 [08:06]
**Duration:** 2.4 seconds

little Kubernetes cluster that's running

---

### Segment 273 [08:07]
**Duration:** 2.9 seconds

in my house.

---

### Segment 274 [08:08]
**Duration:** 3.7 seconds

>> Um, probably not everybody does that,

---

### Segment 275 [08:10]
**Duration:** 4.6 seconds

but I do. And so, I'll just deploy it

---

### Segment 276 [08:12]
**Duration:** 5.1 seconds

there, and everybody's mobile uh or web

---

### Segment 277 [08:15]
**Duration:** 4.4 seconds

devices can talk to that. It's got a DNS

---

### Segment 278 [08:17]
**Duration:** 4.3 seconds

entry, and so I can So, they can access

---

### Segment 279 [08:19]
**Duration:** 3.8 seconds

it. they can access it and I have all

---

### Segment 280 [08:21]
**Duration:** 3.0 seconds

the monitoring that I need to understand

---

### Segment 281 [08:23]
**Duration:** 3.4 seconds

if there's a problem or anything like

---

### Segment 282 [08:24]
**Duration:** 3.6 seconds

that. That might not be the the default,

---

### Segment 283 [08:26]
**Duration:** 4.6 seconds

but I would say that like once you're

---

### Segment 284 [08:28]
**Duration:** 4.9 seconds

ready to put it out there for someone

---

### Segment 285 [08:31]
**Duration:** 3.9 seconds

else to use, that's a good moment when

---

### Segment 286 [08:33]
**Duration:** 4.0 seconds

it's when it's moving from your laptop

---

### Segment 287 [08:35]
**Duration:** 3.2 seconds

into the cloud, that's a good moment.

---

### Segment 288 [08:37]
**Duration:** 3.0 seconds

>> And I feel like people should be doing

---

### Segment 289 [08:38]
**Duration:** 2.4 seconds

that, right? They should be pushing this

---

### Segment 290 [08:40]
**Duration:** 2.1 seconds

stuff out, right?

---

### Segment 291 [08:40]
**Duration:** 3.0 seconds

>> Absolutely. I think so. I mean, and if

---

### Segment 292 [08:42]
**Duration:** 3.4 seconds

you want to get started even earlier,

---

### Segment 293 [08:44]
**Duration:** 3.6 seconds

you know, you can run a very small

---

### Segment 294 [08:45]
**Duration:** 4.6 seconds

Kubernetes installation in a virtual

---

### Segment 295 [08:47]
**Duration:** 4.3 seconds

machine on your desktop or laptop and uh

---

### Segment 296 [08:50]
**Duration:** 3.0 seconds

that's that's a good way. We've got a

---

### Segment 297 [08:51]
**Duration:** 3.7 seconds

lot of really great integration with VS

---

### Segment 298 [08:53]
**Duration:** 3.9 seconds

Code, right? To make it super easy for

---

### Segment 299 [08:55]
**Duration:** 4.4 seconds

people to get started.

---

### Segment 300 [08:57]
**Duration:** 4.9 seconds

>> Obviously, in the this like world of AI,

---

### Segment 301 [09:00]
**Duration:** 3.1 seconds

how is AI impacting infrastructure and

---

### Segment 302 [09:02]
**Duration:** 1.7 seconds

Kubernetes?

---

### Segment 303 [09:03]
**Duration:** 2.8 seconds

>> Yeah, I mean, I think there's two

---

### Segment 304 [09:04]
**Duration:** 3.7 seconds

things. One is that like literally all

---

### Segment 305 [09:05]
**Duration:** 3.1 seconds

of the AI that you see out there, it's

---

### Segment 306 [09:07]
**Duration:** 3.5 seconds

running on Kubernetes, right? Right. So

---

### Segment 307 [09:09]
**Duration:** 4.6 seconds

when you use chat GPT that's running on

---

### Segment 308 [09:11]
**Duration:** 4.6 seconds

Kubernetes and running on Azure and you

---

### Segment 309 [09:13]
**Duration:** 3.8 seconds

know most of the AI training and serving

---

### Segment 310 [09:15]
**Duration:** 3.8 seconds

that is done out there started with

---

### Segment 311 [09:17]
**Duration:** 5.3 seconds

Kubernetes because these AI applications

---

### Segment 312 [09:19]
**Duration:** 4.2 seconds

they need to bring lots of uh machines

---

### Segment 313 [09:22]
**Duration:** 3.0 seconds

together

---

### Segment 314 [09:23]
**Duration:** 4.2 seconds

>> and uh Kubernetes is a great interface

---

### Segment 315 [09:25]
**Duration:** 3.5 seconds

for that and frankly the AI people they

---

### Segment 316 [09:27]
**Duration:** 3.2 seconds

don't care about the machine management

---

### Segment 317 [09:29]
**Duration:** 2.6 seconds

they just wanted to say hey someone else

---

### Segment 318 [09:31]
**Duration:** 1.7 seconds

takes care of it for you.

---

### Segment 319 [09:31]
**Duration:** 2.3 seconds

>> Right. Right. Right.

---

### Segment 320 [09:32]
**Duration:** 3.8 seconds

>> So that's one form is it's the

---

### Segment 321 [09:34]
**Duration:** 3.8 seconds

foundation for a lot of the the AI work

---

### Segment 322 [09:36]
**Duration:** 2.7 seconds

that you see out there. But I also I

---

### Segment 323 [09:38]
**Duration:** 2.9 seconds

think you know you sort of alluded to it

---

### Segment 324 [09:39]
**Duration:** 2.4 seconds

a little bit. This technology can be

---

### Segment 325 [09:40]
**Duration:** 1.3 seconds

kind of complicated.

---

### Segment 326 [09:41]
**Duration:** 2.8 seconds

>> Right.

---

### Segment 327 [09:42]
**Duration:** 4.7 seconds

>> Right. And so I think we're also seeing

---

### Segment 328 [09:44]
**Duration:** 3.5 seconds

things like copilot being used to help

---

### Segment 329 [09:46]
**Duration:** 3.5 seconds

people learn.

---

### Segment 330 [09:48]
**Duration:** 5.0 seconds

>> Okay. I want to, you know, create a

---

### Segment 331 [09:50]
**Duration:** 3.1 seconds

docker file for a node.js application,

---

### Segment 332 [09:53]
**Duration:** 1.7 seconds

right?

---

### Segment 333 [09:53]
**Duration:** 3.2 seconds

>> You used to have to do a bunch of

---

### Segment 334 [09:54]
**Duration:** 3.8 seconds

research to do that. Now that's a

---

### Segment 335 [09:56]
**Duration:** 3.4 seconds

>> the AI sets up the infrastructure

---

### Segment 336 [09:58]
**Duration:** 3.4 seconds

>> the co-pilot, right? And it will set it

---

### Segment 337 [10:00]
**Duration:** 3.8 seconds

up for you. Or I want to deploy this

---

### Segment 338 [10:02]
**Duration:** 3.8 seconds

application out to a Kubernetes cluster.

---

### Segment 339 [10:03]
**Duration:** 3.9 seconds

How's the best way for me to do that?

---

### Segment 340 [10:05]
**Duration:** 3.4 seconds

the AI can generate you the right config

---

### Segment 341 [10:07]
**Duration:** 3.6 seconds

files. I don't think it's intended that

---

### Segment 342 [10:09]
**Duration:** 3.9 seconds

you stay in the using the AI forever,

---

### Segment 343 [10:11]
**Duration:** 3.4 seconds

but it's a jump start, right? It helps

---

### Segment 344 [10:13]
**Duration:** 4.0 seconds

you get to a place where something's

---

### Segment 345 [10:14]
**Duration:** 3.8 seconds

working. I personally find, you know,

---

### Segment 346 [10:17]
**Duration:** 1.7 seconds

I'm much more motivated when it's

---

### Segment 347 [10:18]
**Duration:** 2.5 seconds

working.

---

### Segment 348 [10:18]
**Duration:** 4.2 seconds

>> Yeah. I hate environment setups and all

---

### Segment 349 [10:20]
**Duration:** 3.4 seconds

that, right? Just telling the

---

### Segment 350 [10:23]
**Duration:** 2.4 seconds

>> terminal errors,

---

### Segment 351 [10:24]
**Duration:** 2.6 seconds

>> they're like the whole thing, right?

---

### Segment 352 [10:25]
**Duration:** 3.4 seconds

Like I don't want to do any of that,

---

### Segment 353 [10:26]
**Duration:** 4.6 seconds

right? And so I actually end up a lot of

---

### Segment 354 [10:28]
**Duration:** 4.9 seconds

times doing a really bad job or making

---

### Segment 355 [10:31]
**Duration:** 3.0 seconds

like lesser technology choices cuz

---

### Segment 356 [10:33]
**Duration:** 2.7 seconds

they're just easier.

---

### Segment 357 [10:34]
**Duration:** 4.0 seconds

>> Right. Right. Right? Like I'm I'm

---

### Segment 358 [10:36]
**Duration:** 3.8 seconds

totally lazy at times, right? And I

---

### Segment 359 [10:38]
**Duration:** 3.8 seconds

found that the GitHub copilot actually

---

### Segment 360 [10:40]
**Duration:** 3.9 seconds

helps me be better.

---

### Segment 361 [10:42]
**Duration:** 3.0 seconds

>> It's taken a lot of the toil out of a

---

### Segment 362 [10:44]
**Duration:** 2.6 seconds

lot of this environment.

---

### Segment 363 [10:45]
**Duration:** 3.4 seconds

>> Yeah. All the grunt work.

---

### Segment 364 [10:46]
**Duration:** 3.7 seconds

>> It's just the like stuff I don't want to

---

### Segment 365 [10:48]
**Duration:** 2.4 seconds

learn about, you know? I just want it to

---

### Segment 366 [10:50]
**Duration:** 2.2 seconds

work.

---

### Segment 367 [10:51]
**Duration:** 3.6 seconds

>> Um, so yeah.

---

### Segment 368 [10:52]
**Duration:** 4.3 seconds

>> Yeah. And I got to ask, as a corporate

---

### Segment 369 [10:54]
**Duration:** 4.3 seconds

vice president at Microsoft, if I'm a

---

### Segment 370 [10:57]
**Duration:** 3.8 seconds

beginner and I want to break into tech,

---

### Segment 371 [10:59]
**Duration:** 3.8 seconds

what's your number one piece of advice?

---

### Segment 372 [11:00]
**Duration:** 3.4 seconds

>> Focus on what you're excited about,

---

### Segment 373 [11:02]
**Duration:** 2.9 seconds

>> right? because I think that you know

---

### Segment 374 [11:04]
**Duration:** 3.4 seconds

there's a lot of learning and obviously

---

### Segment 375 [11:05]
**Duration:** 4.6 seconds

you're all about helping people learn

---

### Segment 376 [11:07]
**Duration:** 4.1 seconds

right and I think that if you're excited

---

### Segment 377 [11:10]
**Duration:** 3.0 seconds

you'll learn more

---

### Segment 378 [11:11]
**Duration:** 3.3 seconds

>> so I think sometimes people get see the

---

### Segment 379 [11:13]
**Duration:** 3.0 seconds

the various things that are hyped or

---

### Segment 380 [11:15]
**Duration:** 3.5 seconds

various things that are popular like AI

---

### Segment 381 [11:16]
**Duration:** 4.7 seconds

right now is very hot right and they

---

### Segment 382 [11:18]
**Duration:** 4.2 seconds

think wow I need to go where the hotness

---

### Segment 383 [11:21]
**Duration:** 3.9 seconds

is right and if you're excited about

---

### Segment 384 [11:22]
**Duration:** 4.1 seconds

that then absolutely go right right but

---

### Segment 385 [11:25]
**Duration:** 3.5 seconds

there's jobs all over the tech industry

---

### Segment 386 [11:26]
**Duration:** 3.4 seconds

right and if you're more excited about

---

### Segment 387 [11:28]
**Duration:** 4.1 seconds

the operating system than you are about

---

### Segment 388 [11:30]
**Duration:** 3.8 seconds

the AI go deep on the operating system

---

### Segment 389 [11:32]
**Duration:** 3.0 seconds

Right? Or if you're excited about

---

### Segment 390 [11:34]
**Duration:** 3.4 seconds

front-end development, go build a bunch

---

### Segment 391 [11:35]
**Duration:** 3.1 seconds

of frontends or mobile apps. Go build a

---

### Segment 392 [11:37]
**Duration:** 4.2 seconds

bunch of mobile apps, right? Because

---

### Segment 393 [11:38]
**Duration:** 5.9 seconds

that passion and that energy is gonna

---

### Segment 394 [11:41]
**Duration:** 5.6 seconds

take you further than worrying about,

---

### Segment 395 [11:44]
**Duration:** 3.9 seconds

you know, the specific topic, right?

---

### Segment 396 [11:47]
**Duration:** 3.4 seconds

>> And actually, the other thing is I would

---

### Segment 397 [11:48]
**Duration:** 4.1 seconds

say, you know, learning how to learn

---

### Segment 398 [11:50]
**Duration:** 4.0 seconds

about technology is kind of the same

---

### Segment 399 [11:52]
**Duration:** 3.0 seconds

regardless of the technology. And so

---

### Segment 400 [11:54]
**Duration:** 2.9 seconds

once you found the thing that you're

---

### Segment 401 [11:55]
**Duration:** 3.5 seconds

excited about and you've learned how to

---

### Segment 402 [11:57]
**Duration:** 3.7 seconds

learn, then you can go and say, "Oh,

---

### Segment 403 [11:59]
**Duration:** 3.8 seconds

okay. Now this you know this job like AI

---

### Segment 404 [12:01]
**Duration:** 4.5 seconds

is a big deal right and I would say

---

### Segment 405 [12:03]
**Duration:** 4.7 seconds

actually right now learning how to use

---

### Segment 406 [12:05]
**Duration:** 3.4 seconds

AI to build software

---

### Segment 407 [12:07]
**Duration:** 2.6 seconds

>> you should go do that

---

### Segment 408 [12:09]
**Duration:** 3.4 seconds

>> like that is just like that's going to

---

### Segment 409 [12:10]
**Duration:** 3.4 seconds

be a requirement that is an expectation

---

### Segment 410 [12:12]
**Duration:** 3.3 seconds

and I think that one of the interesting

---

### Segment 411 [12:13]
**Duration:** 3.8 seconds

things that I'm seeing anyway is that

---

### Segment 412 [12:15]
**Duration:** 3.3 seconds

learning how to use the AI really well

---

### Segment 413 [12:17]
**Duration:** 3.3 seconds

if you're new to it if you're new to

---

### Segment 414 [12:19]
**Duration:** 2.6 seconds

software development it'll spit out a

---

### Segment 415 [12:20]
**Duration:** 2.3 seconds

ton of code

---

### Segment 416 [12:21]
**Duration:** 2.6 seconds

>> but you need to be able to judge if it's

---

### Segment 417 [12:23]
**Duration:** 2.5 seconds

good code

---

### Segment 418 [12:24]
**Duration:** 2.7 seconds

>> you need to be able to tell it

---

### Segment 419 [12:25]
**Duration:** 2.5 seconds

>> you can't just be a vibe coder without

---

### Segment 420 [12:27]
**Duration:** 2.6 seconds

knowledge right

---

### Segment 421 [12:28]
**Duration:** 2.8 seconds

>> be a vibe coder without a knowledge of

---

### Segment 422 [12:29]
**Duration:** 3.3 seconds

how the software is supposed to be

---

### Segment 423 [12:30]
**Duration:** 3.8 seconds

built, right? And so where something

---

### Segment 424 [12:32]
**Duration:** 3.4 seconds

like software engineering

---

### Segment 425 [12:34]
**Duration:** 3.7 seconds

>> and unit testing and all that kind of

---

### Segment 426 [12:36]
**Duration:** 4.7 seconds

stuff might have been a third, fourth,

---

### Segment 427 [12:38]
**Duration:** 5.5 seconds

fifth semester kind of class, a 200

---

### Segment 428 [12:41]
**Duration:** 4.8 seconds

levelish, 250 levelish class. I think

---

### Segment 429 [12:43]
**Duration:** 3.7 seconds

it's now a 101 class,

---

### Segment 430 [12:45]
**Duration:** 4.9 seconds

>> right? You need to be thinking about

---

### Segment 431 [12:47]
**Duration:** 6.0 seconds

object modeling and testing and API

---

### Segment 432 [12:50]
**Duration:** 4.3 seconds

design and all of the principles of good

---

### Segment 433 [12:53]
**Duration:** 3.0 seconds

software engineering. Yeah.

---

### Segment 434 [12:55]
**Duration:** 3.6 seconds

>> At the beginning. In fact, I would

---

### Segment 435 [12:56]
**Duration:** 3.6 seconds

actually say you should maybe think

---

### Segment 436 [12:58]
**Duration:** 3.8 seconds

about studying that before you even

---

### Segment 437 [13:00]
**Duration:** 4.4 seconds

learn how to read write code

---

### Segment 438 [13:02]
**Duration:** 5.4 seconds

>> because at this point we're at a place

---

### Segment 439 [13:04]
**Duration:** 5.4 seconds

where knowing how to generate the code

---

### Segment 440 [13:07]
**Duration:** 3.6 seconds

is not necessarily that important.

---

### Segment 441 [13:09]
**Duration:** 3.2 seconds

>> Yeah. It's also not that impressive.

---

### Segment 442 [13:11]
**Duration:** 3.2 seconds

>> Well, and that's true too, right? It's

---

### Segment 443 [13:13]
**Duration:** 3.0 seconds

not all that impressive, right? And but

---

### Segment 444 [13:14]
**Duration:** 2.2 seconds

knowing how to build something,

---

### Segment 445 [13:16]
**Duration:** 2.3 seconds

remember, we're still going to be

---

### Segment 446 [13:16]
**Duration:** 2.8 seconds

operating on Teams,

---

### Segment 447 [13:18]
**Duration:** 2.8 seconds

>> uh, you know, software teams.

---

### Segment 448 [13:19]
**Duration:** 2.9 seconds

>> Yeah. Yeah. Yeah. Microsoft Teams.

---

### Segment 449 [13:21]
**Duration:** 2.7 seconds

>> Microsoft Teams, although hopefully on

---

### Segment 450 [13:22]
**Duration:** 3.0 seconds

Microsoft Teams. [laughter] And so

---

### Segment 451 [13:23]
**Duration:** 3.2 seconds

learning how to build code that works

---

### Segment 452 [13:25]
**Duration:** 4.2 seconds

well with other people that multiple

---

### Segment 453 [13:27]
**Duration:** 4.3 seconds

people can maintain that you know code

---

### Segment 454 [13:29]
**Duration:** 3.4 seconds

lives for a really long time.

---

### Segment 455 [13:31]
**Duration:** 4.2 seconds

>> So learning how to build maintainable

---

### Segment 456 [13:33]
**Duration:** 4.8 seconds

testable code is is a valuable skill.

---

### Segment 457 [13:35]
**Duration:** 4.1 seconds

Actually writing the code you know I

---

### Segment 458 [13:37]
**Duration:** 2.9 seconds

think that's becoming less and less of

---

### Segment 459 [13:39]
**Duration:** 2.5 seconds

the importance.

---

### Segment 460 [13:40]
**Duration:** 4.0 seconds

>> Right. Right. It just seems kind of like

---

### Segment 461 [13:42]
**Duration:** 3.4 seconds

a baseline you should know other than oh

---

### Segment 462 [13:44]
**Duration:** 2.6 seconds

wow you know it.

---

### Segment 463 [13:45]
**Duration:** 3.9 seconds

>> Yeah. And it used to be like you know I

---

### Segment 464 [13:47]
**Duration:** 2.9 seconds

think that the volume of good code that

---

### Segment 465 [13:49]
**Duration:** 2.2 seconds

you could write

---

### Segment 466 [13:50]
**Duration:** 3.0 seconds

>> Yeah. was kind of a marker, especially

---

### Segment 467 [13:51]
**Duration:** 4.0 seconds

in the early stages of your career, was

---

### Segment 468 [13:53]
**Duration:** 3.8 seconds

kind of a marker of like how fast you

---

### Segment 469 [13:55]
**Duration:** 1.6 seconds

were going to run, how fast you were

---

### Segment 470 [13:57]
**Duration:** 1.4 seconds

going to go.

---

### Segment 471 [13:57]
**Duration:** 2.3 seconds

>> But now it's like you better.

---

### Segment 472 [13:58]
**Duration:** 2.6 seconds

>> Yeah. And at this point, I think it's

---

### Segment 473 [13:59]
**Duration:** 3.0 seconds

much more like no, we've leveled out the

---

### Segment 474 [14:01]
**Duration:** 3.8 seconds

playing field and now it's more about

---

### Segment 475 [14:02]
**Duration:** 3.8 seconds

like is what you're producing good,

---

### Segment 476 [14:04]
**Duration:** 3.4 seconds

>> right? I guess in some ways it's like

---

### Segment 477 [14:06]
**Duration:** 4.3 seconds

going from a handsaw where like your

---

### Segment 478 [14:08]
**Duration:** 4.2 seconds

muscle matters to a power saw where like

---

### Segment 479 [14:10]
**Duration:** 3.8 seconds

what you do with it matters,

---

### Segment 480 [14:12]
**Duration:** 4.4 seconds

>> right? Yeah. And I actually I want to

---

### Segment 481 [14:14]
**Duration:** 5.0 seconds

drill into something you mentioned where

---

### Segment 482 [14:16]
**Duration:** 5.1 seconds

learning how to use AI for software

---

### Segment 483 [14:19]
**Duration:** 3.8 seconds

development. How does a beginner learn

---

### Segment 484 [14:22]
**Duration:** 3.2 seconds

how to use AI for software development?

---

### Segment 485 [14:23]
**Duration:** 3.4 seconds

>> Yeah. Have some idea of what you want to

---

### Segment 486 [14:25]
**Duration:** 3.0 seconds

what you want to do. Find some idea just

---

### Segment 487 [14:26]
**Duration:** 2.3 seconds

whatever occurs you. I mean a lot I go

---

### Segment 488 [14:28]
**Duration:** 2.7 seconds

running a lot.

---

### Segment 489 [14:29]
**Duration:** 2.0 seconds

>> Ideas occur to me when I'm out running.

---

### Segment 490 [14:30]
**Duration:** 1.9 seconds

Yeah.

---

### Segment 491 [14:31]
**Duration:** 2.0 seconds

>> Um and then you go home and you build

---

### Segment 492 [14:32]
**Duration:** 0.6 seconds

them.

---

### Segment 493 [14:33]
**Duration:** 2.1 seconds

>> Yeah.

---

### Segment 494 [14:33]
**Duration:** 4.2 seconds

>> Right. And I think we really are at that

---

### Segment 495 [14:35]
**Duration:** 4.6 seconds

place where you know if you're in GitHub

---

### Segment 496 [14:37]
**Duration:** 3.4 seconds

and you're using GitHub copilot you can

---

### Segment 497 [14:39]
**Duration:** 3.6 seconds

really just start with agent mode and

---

### Segment 498 [14:41]
**Duration:** 5.6 seconds

say like hey I had this idea scaffold me

---

### Segment 499 [14:43]
**Duration:** 4.8 seconds

a TypeScript app for doing this right

---

### Segment 500 [14:46]
**Duration:** 2.7 seconds

and it will generate it out.

---

### Segment 501 [14:48]
**Duration:** 2.8 seconds

>> So basically just start doing it

---

### Segment 502 [14:49]
**Duration:** 2.4 seconds

>> just start doing it. Yeah, I mean I

---

### Segment 503 [14:51]
**Duration:** 1.8 seconds

think a little bit of learning. I mean,

---

### Segment 504 [14:51]
**Duration:** 2.1 seconds

obviously you have to learn enough to

---

### Segment 505 [14:52]
**Duration:** 3.8 seconds

know, okay, TypeScript's a perfect

---

### Segment 506 [14:54]
**Duration:** 4.6 seconds

language. Uh, you know, oh, here's the

---

### Segment 507 [14:56]
**Duration:** 2.2 seconds

>> Yeah, we talked to Anders earlier,

---

### Segment 508 [14:58]
**Duration:** 1.5 seconds

>> right?

---

### Segment 509 [14:58]
**Duration:** 2.9 seconds

>> So, you know, there is a little bit of

---

### Segment 510 [15:00]
**Duration:** 3.7 seconds

like learning of that, but then I think

---

### Segment 511 [15:01]
**Duration:** 3.0 seconds

if you want to learn how to use the AI,

---

### Segment 512 [15:03]
**Duration:** 2.6 seconds

just use it. Yeah.

---

### Segment 513 [15:04]
**Duration:** 3.2 seconds

>> You know, um, learn what it's good at,

---

### Segment 514 [15:06]
**Duration:** 3.4 seconds

learn what it's bad at. I think it's

---

### Segment 515 [15:07]
**Duration:** 3.8 seconds

really good, especially early on, I

---

### Segment 516 [15:09]
**Duration:** 3.8 seconds

found when I was teaching myself Rust,

---

### Segment 517 [15:11]
**Duration:** 3.5 seconds

>> I found it was really good at explaining

---

### Segment 518 [15:13]
**Duration:** 3.5 seconds

compiler errors to me,

---

### Segment 519 [15:15]
**Duration:** 3.2 seconds

>> right? I think early on when people are

---

### Segment 520 [15:17]
**Duration:** 2.6 seconds

using these tools sometimes you get

---

### Segment 521 [15:18]
**Duration:** 3.8 seconds

really especially some of the open

---

### Segment 522 [15:19]
**Duration:** 5.0 seconds

source ones you get really opaque errors

---

### Segment 523 [15:22]
**Duration:** 4.3 seconds

>> you're like get it you're not you won't

---

### Segment 524 [15:24]
**Duration:** 3.1 seconds

do what I want you to do

---

### Segment 525 [15:26]
**Duration:** 3.4 seconds

>> why [laughter]

---

### Segment 526 [15:27]
**Duration:** 3.8 seconds

>> right and actually you can in the

---

### Segment 527 [15:29]
**Duration:** 3.3 seconds

co-pilot if you're in VS Code and you're

---

### Segment 528 [15:31]
**Duration:** 4.6 seconds

in the terminal you can actually say hey

---

### Segment 529 [15:33]
**Duration:** 4.5 seconds

co-pilot you know at terminal explain

---

### Segment 530 [15:36]
**Duration:** 3.3 seconds

>> and it will look at the output of the

---

### Segment 531 [15:37]
**Duration:** 3.6 seconds

program that's in your terminal and it

---

### Segment 532 [15:39]
**Duration:** 3.8 seconds

will try to explain to you

---

### Segment 533 [15:41]
**Duration:** 2.2 seconds

>> what's going wrong and how you might fix

---

### Segment 534 [15:43]
**Duration:** 2.4 seconds

it

---

### Segment 535 [15:43]
**Duration:** 3.4 seconds

>> right so I think that helps It helps

---

### Segment 536 [15:45]
**Duration:** 3.0 seconds

you, right? It helps you get over those

---

### Segment 537 [15:46]
**Duration:** 3.5 seconds

because I think when early on,

---

### Segment 538 [15:48]
**Duration:** 3.9 seconds

especially you hit these roadblocks

---

### Segment 539 [15:50]
**Duration:** 3.9 seconds

where you feel really stuck,

---

### Segment 540 [15:52]
**Duration:** 3.2 seconds

>> like really frustratingly stuck, right?

---

### Segment 541 [15:54]
**Duration:** 3.5 seconds

I don't know how to do this. Why is it

---

### Segment 542 [15:55]
**Duration:** 3.0 seconds

not I know like I know what I want it to

---

### Segment 543 [15:57]
**Duration:** 1.8 seconds

do,

---

### Segment 544 [15:58]
**Duration:** 1.8 seconds

>> it won't do it.

---

### Segment 545 [15:59]
**Duration:** 2.6 seconds

>> Right. Right.

---

### Segment 546 [16:00]
**Duration:** 3.4 seconds

>> Right. And I think, you know, AI can

---

### Segment 547 [16:02]
**Duration:** 3.4 seconds

help you get through that. Um, and

---

### Segment 548 [16:03]
**Duration:** 2.8 seconds

learning how to to work with it there

---

### Segment 549 [16:05]
**Duration:** 3.1 seconds

helps a lot.

---

### Segment 550 [16:06]
**Duration:** 4.2 seconds

>> Okay. And now a very hot question. Will

---

### Segment 551 [16:08]
**Duration:** 3.4 seconds

AI replace software engineers? We've

---

### Segment 552 [16:10]
**Duration:** 4.5 seconds

been developing technology to make

---

### Segment 553 [16:12]
**Duration:** 4.4 seconds

building software easier for 70 years at

---

### Segment 554 [16:15]
**Duration:** 3.5 seconds

this point. From the dawn of the first

---

### Segment 555 [16:16]
**Duration:** 3.5 seconds

forran compiler all the way through to

---

### Segment 556 [16:18]
**Duration:** 3.1 seconds

co-pilot today, we've [music] been

---

### Segment 557 [16:20]
**Duration:** 3.1 seconds

making it easier and more approachable,

---

### Segment 558 [16:21]
**Duration:** 2.8 seconds

more accessible for people to build

---

### Segment 559 [16:23]
**Duration:** 3.0 seconds

software. And the only thing that has

---

### Segment 560 [16:24]
**Duration:** 3.5 seconds

ever happened is that we've built more

---

### Segment 561 [16:26]
**Duration:** 4.0 seconds

software. So no, I don't think the total

---

### Segment 562 [16:28]
**Duration:** 3.5 seconds

number I think the job changes, right?

---

### Segment 563 [16:30]
**Duration:** 1.9 seconds

Like you know, as I said, like I think

---

### Segment 564 [16:31]
**Duration:** 1.8 seconds

that

---

### Segment 565 [16:32]
**Duration:** 3.4 seconds

>> So how do you see like software

---

### Segment 566 [16:33]
**Duration:** 4.2 seconds

engineers in 2025 compared to software

---

### Segment 567 [16:35]
**Duration:** 4.4 seconds

engineers in 2030? Like right now we're

---

### Segment 568 [16:37]
**Duration:** 3.6 seconds

writing code, we're deploying the code.

---

### Segment 569 [16:40]
**Duration:** 2.6 seconds

What do you think software engineers in

---

### Segment 570 [16:41]
**Duration:** 3.0 seconds

2030 are going to be doing?

---

### Segment 571 [16:42]
**Duration:** 4.1 seconds

>> I think what happens is there's a lot

---

### Segment 572 [16:44]
**Duration:** 3.6 seconds

more focus on what is the product,

---

### Segment 573 [16:46]
**Duration:** 3.1 seconds

>> what are we actually trying to build,

---

### Segment 574 [16:47]
**Duration:** 3.4 seconds

what's the specification, what's the

---

### Segment 575 [16:49]
**Duration:** 3.6 seconds

validation that we're using to make sure

---

### Segment 576 [16:51]
**Duration:** 4.0 seconds

it's working. A lot less of a focus on

---

### Segment 577 [16:53]
**Duration:** 3.7 seconds

like what are the actual mechanics of

---

### Segment 578 [16:55]
**Duration:** 2.8 seconds

building the software. 10 years ago,

---

### Segment 579 [16:57]
**Duration:** 1.5 seconds

maybe you could just be a really good

---

### Segment 580 [16:58]
**Duration:** 0.9 seconds

coder.

---

### Segment 581 [16:58]
**Duration:** 1.6 seconds

>> Right

---

### Segment 582 [16:58]
**Duration:** 3.4 seconds

>> now, you're going to have to be a

---

### Segment 583 [17:00]
**Duration:** 3.9 seconds

product manager and a good user of these

---

### Segment 584 [17:02]
**Duration:** 3.0 seconds

AI tools because you have to be able to

---

### Segment 585 [17:04]
**Duration:** 3.1 seconds

understand what should the product look

---

### Segment 586 [17:05]
**Duration:** 3.6 seconds

like. I think what Satya mentioned

---

### Segment 587 [17:07]
**Duration:** 3.2 seconds

yesterday in his keynote, it's like

---

### Segment 588 [17:09]
**Duration:** 3.8 seconds

software engineers are going to be

---

### Segment 589 [17:10]
**Duration:** 4.2 seconds

managers of AI teams going forward.

---

### Segment 590 [17:12]
**Duration:** 3.2 seconds

>> Yeah, a certain amount of that. And I'd

---

### Segment 591 [17:14]
**Duration:** 3.0 seconds

like to remind people that like the

---

### Segment 592 [17:16]
**Duration:** 2.2 seconds

machines are already generating all the

---

### Segment 593 [17:17]
**Duration:** 3.1 seconds

code,

---

### Segment 594 [17:18]
**Duration:** 4.2 seconds

>> right? Compilers have been generating

---

### Segment 595 [17:20]
**Duration:** 3.6 seconds

all of the machine code for years,

---

### Segment 596 [17:22]
**Duration:** 4.2 seconds

decades at this point, right? I think

---

### Segment 597 [17:24]
**Duration:** 4.7 seconds

it's useful to think of AI as just being

---

### Segment 598 [17:26]
**Duration:** 3.1 seconds

a better compiler or a higher level

---

### Segment 599 [17:29]
**Duration:** 2.7 seconds

compiler.

---

### Segment 600 [17:29]
**Duration:** 3.4 seconds

>> Yeah. Like who who it's more of just the

---

### Segment 601 [17:31]
**Duration:** 3.1 seconds

abstraction of the written rather than

---

### Segment 602 [17:33]
**Duration:** 3.3 seconds

the compile, right? Yeah. And so it's

---

### Segment 603 [17:34]
**Duration:** 2.4 seconds

like it's allowing you to talk at higher

---

### Segment 604 [17:36]
**Duration:** 2.7 seconds

levels,

---

### Segment 605 [17:37]
**Duration:** 3.0 seconds

>> but you still have to know what you want

---

### Segment 606 [17:39]
**Duration:** 3.5 seconds

to build, right?

---

### Segment 607 [17:40]
**Duration:** 4.2 seconds

>> Right. Um, we just finished building a

---

### Segment 608 [17:42]
**Duration:** 3.0 seconds

house and and it's not like I walked up

---

### Segment 609 [17:44]
**Duration:** 2.9 seconds

to the architect and said, "I want a

---

### Segment 610 [17:45]
**Duration:** 3.4 seconds

house." And then walked away and years.

---

### Segment 611 [17:47]
**Duration:** 3.4 seconds

No, they asked me questions, right? How

---

### Segment 612 [17:49]
**Duration:** 3.3 seconds

many kids do you have? What kind of

---

### Segment 613 [17:50]
**Duration:** 3.1 seconds

activities do you like doing? You What

---

### Segment 614 [17:52]
**Duration:** 3.3 seconds

are your colors do you like? Do you like

---

### Segment 615 [17:53]
**Duration:** 3.1 seconds

the modern style or more traditional?

---

### Segment 616 [17:55]
**Duration:** 3.6 seconds

You know, like there's a lot of

---

### Segment 617 [17:56]
**Duration:** 4.6 seconds

decisions that I made that go into the

---

### Segment 618 [17:59]
**Duration:** 4.0 seconds

final product and and ultimately the

---

### Segment 619 [18:01]
**Duration:** 4.2 seconds

usefulness of that thing is is dictated

---

### Segment 620 [18:03]
**Duration:** 4.3 seconds

by my vision and and our vision, right?

---

### Segment 621 [18:05]
**Duration:** 4.4 seconds

And so I think that's the that's the

---

### Segment 622 [18:07]
**Duration:** 4.0 seconds

thing that that is still essential is

---

### Segment 623 [18:10]
**Duration:** 2.8 seconds

that we, you know, we still have to

---

### Segment 624 [18:11]
**Duration:** 2.4 seconds

understand why, right?

---

### Segment 625 [18:12]
**Duration:** 3.4 seconds

>> We don't just build code because we

---

### Segment 626 [18:14]
**Duration:** 3.8 seconds

build code. We build code for a purpose.

---

### Segment 627 [18:16]
**Duration:** 3.2 seconds

In some sense, the cheaper we make it to

---

### Segment 628 [18:17]
**Duration:** 3.6 seconds

build software and to build reliable

---

### Segment 629 [18:19]
**Duration:** 4.4 seconds

software, the more places we will find

---

### Segment 630 [18:21]
**Duration:** 5.0 seconds

to put software. M yeah I I always say

---

### Segment 631 [18:23]
**Duration:** 4.3 seconds

like uh right now if you have like one

---

### Segment 632 [18:26]
**Duration:** 3.1 seconds

software engineer develops one feature

---

### Segment 633 [18:28]
**Duration:** 3.4 seconds

in the future might have one software

---

### Segment 634 [18:29]
**Duration:** 3.6 seconds

engineer developing a hundred features

---

### Segment 635 [18:31]
**Duration:** 2.0 seconds

because they're managing the AI team to

---

### Segment 636 [18:33]
**Duration:** 2.1 seconds

do that.

---

### Segment 637 [18:33]
**Duration:** 3.6 seconds

>> But I will tell you from running a lot

---

### Segment 638 [18:35]
**Duration:** 5.0 seconds

of engineering teams it's not like our

---

### Segment 639 [18:37]
**Duration:** 4.6 seconds

backlogs lack hundreds or thousands of

---

### Segment 640 [18:40]
**Duration:** 4.0 seconds

features that we're not that we're not

---

### Segment 641 [18:41]
**Duration:** 4.3 seconds

doing. Yeah, tech's part of it, but also

---

### Segment 642 [18:44]
**Duration:** 3.5 seconds

just like straight up features, right?

---

### Segment 643 [18:46]
**Duration:** 3.5 seconds

Or somebody wants something

---

### Segment 644 [18:47]
**Duration:** 3.3 seconds

>> and we just say, well, you know what?

---

### Segment 645 [18:49]
**Duration:** 3.3 seconds

Like it just doesn't make it into the

---

### Segment 646 [18:51]
**Duration:** 3.0 seconds

prior prioritized list

---

### Segment 647 [18:52]
**Duration:** 2.2 seconds

>> of things that we're going to work on

---

### Segment 648 [18:54]
**Duration:** 1.9 seconds

this semester, right?

---

### Segment 649 [18:55]
**Duration:** 2.5 seconds

>> But future it will.

---

### Segment 650 [18:56]
**Duration:** 3.4 seconds

>> Future it will, right? And I think that

---

### Segment 651 [18:57]
**Duration:** 3.9 seconds

again makes the software better. Think

---

### Segment 652 [18:59]
**Duration:** 4.2 seconds

about all of the work that we do on

---

### Segment 653 [19:01]
**Duration:** 4.6 seconds

accessibility, right?

---

### Segment 654 [19:03]
**Duration:** 4.1 seconds

>> That is work that has to be coded today

---

### Segment 655 [19:06]
**Duration:** 2.8 seconds

and there's limits, right? I mean, we

---

### Segment 656 [19:07]
**Duration:** 3.1 seconds

try and do a really good job on

---

### Segment 657 [19:08]
**Duration:** 4.4 seconds

accessibility, but obviously like people

---

### Segment 658 [19:10]
**Duration:** 4.8 seconds

find gaps. Now imagine if you you know

---

### Segment 659 [19:13]
**Duration:** 4.3 seconds

we have 10x the amount of code that's

---

### Segment 660 [19:15]
**Duration:** 4.8 seconds

being generated. We can customize our

---

### Segment 661 [19:17]
**Duration:** 4.7 seconds

applications 10x more to better fit

---

### Segment 662 [19:20]
**Duration:** 3.8 seconds

every individual in the world. Right? So

---

### Segment 663 [19:22]
**Duration:** 3.4 seconds

I think I don't know I I'm maybe I'm too

---

### Segment 664 [19:24]
**Duration:** 3.1 seconds

much of an optimist but I profoundly

---

### Segment 665 [19:25]
**Duration:** 3.4 seconds

believe that there will be more work.

---

### Segment 666 [19:27]
**Duration:** 3.6 seconds

The work changes but there will always

---

### Segment 667 [19:29]
**Duration:** 2.4 seconds

be more work in terms of building

---

### Segment 668 [19:30]
**Duration:** 3.2 seconds

software.

---

### Segment 669 [19:31]
**Duration:** 4.2 seconds

>> And I also got to ask so for young

---

### Segment 670 [19:34]
**Duration:** 3.7 seconds

people beginners in tech what do you

---

### Segment 671 [19:35]
**Duration:** 3.5 seconds

think is the number one common mistake

---

### Segment 672 [19:37]
**Duration:** 3.6 seconds

that you see they make? you get through

---

### Segment 673 [19:39]
**Duration:** 4.0 seconds

school early in your career if you're in

---

### Segment 674 [19:41]
**Duration:** 3.5 seconds

the tech industry, it is a team sport.

---

### Segment 675 [19:43]
**Duration:** 3.1 seconds

You're supposed to ask for help, I

---

### Segment 676 [19:44]
**Duration:** 3.0 seconds

think, especially in this days of hybrid

---

### Segment 677 [19:46]
**Duration:** 3.4 seconds

and other stuff like that. It can be

---

### Segment 678 [19:47]
**Duration:** 4.0 seconds

hard, right? See, people get stuck, you

---

### Segment 679 [19:49]
**Duration:** 4.3 seconds

know, and and often I'm stuck on dumb

---

### Segment 680 [19:51]
**Duration:** 4.1 seconds

stuff, too, right? Like honestly, I I've

---

### Segment 681 [19:54]
**Duration:** 3.4 seconds

told people on on our teams like if you

---

### Segment 682 [19:55]
**Duration:** 3.8 seconds

get stuck for longer than half an hour,

---

### Segment 683 [19:57]
**Duration:** 3.6 seconds

it's probably something that we did, not

---

### Segment 684 [19:59]
**Duration:** 3.0 seconds

something that you did, right? We

---

### Segment 685 [20:01]
**Duration:** 3.9 seconds

probably just didn't document it right

---

### Segment 686 [20:02]
**Duration:** 4.0 seconds

or the tool is buggy or, you know, like

---

### Segment 687 [20:05]
**Duration:** 4.1 seconds

we have the same kind of debt and

---

### Segment 688 [20:06]
**Duration:** 4.4 seconds

mistakes that other people do. Um and

---

### Segment 689 [20:09]
**Duration:** 3.5 seconds

getting people over that hurdle of

---

### Segment 690 [20:11]
**Duration:** 4.6 seconds

asking for help I think is I mean you

---

### Segment 691 [20:12]
**Duration:** 3.0 seconds

don't want to ask [laughter]

---

### Segment 692 [20:16]
**Duration:** 4.0 seconds

you don't always be asking for help but

---

### Segment 693 [20:18]
**Duration:** 3.9 seconds

also you know a lot of what you're doing

---

### Segment 694 [20:20]
**Duration:** 3.1 seconds

in the beginning is is figuring it is

---

### Segment 695 [20:21]
**Duration:** 2.7 seconds

learning and figuring it out and often

---

### Segment 696 [20:23]
**Duration:** 3.4 seconds

times like

---

### Segment 697 [20:24]
**Duration:** 3.8 seconds

>> you know again documentation's out of

---

### Segment 698 [20:26]
**Duration:** 3.1 seconds

date or we just didn't build a really

---

### Segment 699 [20:28]
**Duration:** 3.8 seconds

good onboarding script or whatever. So

---

### Segment 700 [20:29]
**Duration:** 4.0 seconds

like that willingness to be a little bit

---

### Segment 701 [20:32]
**Duration:** 4.3 seconds

vulnerable ask for a little bit of help

---

### Segment 702 [20:33]
**Duration:** 3.8 seconds

can also go a long way. Um, so yeah,

---

### Segment 703 [20:36]
**Duration:** 2.0 seconds

that's another another thing I see

---

### Segment 704 [20:37]
**Duration:** 1.9 seconds

people do sometimes.

---

### Segment 705 [20:38]
**Duration:** 2.3 seconds

>> Well, that's about all I have in this

---

### Segment 706 [20:39]
**Duration:** 2.6 seconds

video. I really hope that you guys

---

### Segment 707 [20:40]
**Duration:** 2.8 seconds

enjoyed it and if you did, make sure to

---

### Segment 708 [20:42]
**Duration:** 2.9 seconds

hit the like button, subscribe if you

---

### Segment 709 [20:43]
**Duration:** 3.7 seconds

haven't already. If you're interested in

---

### Segment 710 [20:45]
**Duration:** 3.6 seconds

my absolutely free tech newsletter, link

---

### Segment 711 [20:47]
**Duration:** 3.1 seconds

for that will also be in the

---

### Segment 712 [20:48]
**Duration:** 3.6 seconds

description. And if you're interested in

---

### Segment 713 [20:50]
**Duration:** 4.5 seconds

watching the interview that I had with

---

### Segment 714 [20:52]
**Duration:** 4.3 seconds

the CEO of Microsoft, Satya Nadella,

---

### Segment 715 [20:54]
**Duration:** 5.7 seconds

asking him about how to get hired in

---

### Segment 716 [20:56]
**Duration:** 3.9 seconds

tech, you might like this video right

---

