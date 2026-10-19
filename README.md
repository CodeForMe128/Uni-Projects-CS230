# Uni-Projects-CS230

The Gaming Room: Draw It or Lose It - Software Design Document

Summarize the client and software requirements: The client, The Gaming Room, wanted to basically scale their current Android app, "Draw It or Lose It", to create a cross platform app via the web. The client needed a solution that could handle many users and many instances at once with strict requirements on real time rendering (images rendered within 30 seconds out of a 1 minute round).

What did you do particularly well? I was able to assess all of the hardware and software constraints to various platforms (Mac, Linux, Windows, Mobile) and also provided very specific and scalable suggestions like Linux based servers, AWS S3 for data storage, and object pooling for fast memory allocations.

How did working through a design document help? This process made me identify all constraints (like network delays, memory constraints, etc.) before even coding. By planning out Singleton and Iterator design patterns in the domain model stage, we can save ourselves from an expensive architecture redesign during the project implementation phase.

What would you revise and improve? If there was anything that I would have revised about the design, it is the Domain Model I would say. It should incorporate detailed UML sequence diagrams that trace the interactions between the WebSocket, since server to client interaction in real time is the most challenging component of this distributed app.

How did you interpret and implement user needs? This requirement of providing the best experience while playing and being fast led to designing of a web app where heavy storage (1.6 GB of HD images) is placed in the cloud servers rather than the user's own device. Understanding the user needs is pretty important because any frustration with lag or large amounts of download will lead to some sort of rejection of the mobile/web game.

How did you approach designing software and future strategies? In this case, Object Oriented Programming was used to implement the idea along with resource management (memory vs. storage). In the future, I will continue with this approach of using cloud based infrastructure evaluations along with UML diagrams.
