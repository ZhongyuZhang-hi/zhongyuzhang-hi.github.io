---
layout: essay
type: essay
title: "AI: The Future of Programming"
# All dates must be YYYY-MM-DD format!
date: 2025-05-12
published: true
labels:
  - AI
---
## I. Introduction

AI, or artificial intelligence, with its ability to generate code, explain complex topics, and assist in debugging, has become a powerful and valuable tool in the learning process. In ICS 314, I engaged with AI tools such as ChatGPT and GitHub Copilot to support my development as a software engineer. These tools offer unique advantages, from helping me understand programming concepts to accelerating my problem-solving workflow. I believe AI can be a powerful learning tool, but only in the right hands. When used thoughtfully, it can enhance understanding, improve productivity, and foster deeper engagement with technical challenges. This essay reflects on my personal experience using AI throughout ICS 314, evaluating its role, benefits, and limitations within the course and beyond.

## II. Personal Experience with AI

Here are some examples where I have used AI when progressing ICS314.

- **Experience WODs**  
  E18–20: Functional Programming (Parts 1–3)
  With the complexity and specificity of TypeScript’s functional programming syntax, I found it necessary to use AI tools like ChatGPT. I first tried approaching each problem by browsing through the list of array functions in TypeScript (such as .map, .filter, .reduce) and selecting one I thought would be helpful. I would then describe my idea and ask ChatGPT for help refining or implementing it. For example, in E19, when I wanted to calculate the total number of awards from the UH data set, I knew I had to use .reduce(). So I asked ChatGPT:
  “Using reduce(): sum the awards of each UHData” (and included the code snippet provided in the WOD).
  ChatGPT responded with a working solution using .reduce() to iterate through the data array and sum the values. This was very helpful, not because I couldn’t understand the concept, but because the syntax was tricky and I needed a reference to get it right. It still required trial and error, but ChatGPT helped guide me in the right direction quickly.
  E49–54: Digits
  For these Experience WODs, I didn’t use AI. The instructions were detailed, and I felt I had gained enough confidence from earlier Experience and Practice WODs, especially those involving Next.js and databases. I decided not to rely on AI because I wanted to test and reinforce my understanding.
  
- **In-class Practice WODs**  
  For In-class Practice WODs, I did not use AI because I was usually working with classmates who could fill the same role as AI when it came to asking questions, brainstorming, or generating ideas. These WODs were collaborative and lower-pressure, so I saw them as valuable learning opportunities to develop my own understanding and problem-solving skills without relying on external tools. I intentionally used these sessions to practice thinking through problems and talking through solutions with others.

- **In-class WODs**  
  I used AI for almost all of the In-class WODs, except for the first couple, which were fairly straightforward. For the rest, my typical approach was to paste the entire WOD prompt into ChatGPT at the start of the session. As I worked through the WOD, I would reference ChatGPT whenever I ran into issues—whether it was a concept I didn’t fully understand or a syntax error I couldn’t figure out.

  For example, if I was trying to use .reduce() and wrote something like arr.reduce(a, b => a + b). I would type it directly to ChatGPT.
  "arr.reduce(a, b => a + b)"
  ChatGPT would recognize any errors and help by correcting or refining my syntax and showing how to apply it properly to the dataset. This made the WODs much more manageable. AI was incredibly useful in this context, it helped me move past roadblocks quickly and ensured I could complete each In-class WOD on time with a working solution.

- **Essays**     
  I used ChatGPT for every essay in ICS 314, but I always made sure the core ideas and structure came from me. At the beginning of each assignment, I would paste the entire prompt into ChatGPT to ensure it understood the expectations and context. Then, I wrote the essay section by section based on my own thoughts and analysis.

  After completing each section, I would send it to ChatGPT along with the section title and a short explanation of what was expected. Such as:
  "Essays: Describe my process of using AI to help my essays <the section here>"
  ChatGPT would then help me revise it by improving clarity, grammar, spelling, and word choice. This process made my writing cleaner and more professional.
  
  This revision step made my writing cleaner and more professional. When I got stuck, especially when I wasn’t sure how to expand a point or connect ideas, I would paste a rough paragraph into ChatGPT and ask for suggestions on how to develop it further. This approach helped me improve both the flow and depth of my essays without compromising originality.
  
- **Final project**  
  For the final project, my use of AI was fairly limited because I was able to reuse a lot of components and code from previous assignments. I mainly used ChatGPT when I needed to implement something new that I hadn’t done before.

  One example was when I wanted to add a like button to a post. I provided ChatGPT with my data model and the relevant component, and asked, “Add a like button.” It generated code that introduced new concepts I hadn’t used before, like useState, which was helpful for learning. However, the solution didn’t fully work because it didn’t handle updating the backend. I realized I needed to update the database, so I wrote a function to increment the like count and then asked ChatGPT how to use my custom function in the button logic. This back-and-forth helped me troubleshoot and finish the feature, but required my own reasoning to fully implement.

- **Learning a concept/tutorial**  
  I didn’t use AI to learn the basic concepts. When I studied the official tutorials for React, TypeScript, or HTML, I wanted to focus and learn from the source.
  I thought that if I always used AI for this, I might not fully understand the fundamentals. So I read the docs and tried things by myself.
  
- **Answering a question in class or Discord**
  I didn’t use AI to answer questions. I felt like if I could solve the problem, I should answer it myself. Also, if someone else asked a question, they could ask AI too—so I didn’t see the        point in using it for that.
  
- **Asking or answering a smart question**
  I didn’t use AI here either. I didn’t do this very often, but when I did, I tried to rely on what I had already learned.

- **Coding examples**
  I used AI often to find simple examples, especially when I forgot the syntax.
  For example, I asked how to use a forEach loop or how to use some functional programming functions. It saved time and helped me review.
  
- **Coding examples**
  Sometimes I copied code from AI but didn’t fully understand it. So I asked ChatGPT to explain things like:

    “What does query do in a Next.js Link?”
    or
    “What happens when useEffect has an empty dependency array?”
    These answers helped me understand how data flows in React and how re-rendering works.
  
- **Writing code**
  Yes, I used AI when writing code, especially small components or logic functions.
  For example, I asked:

    “How do I create a simple modal in React-Bootstrap?”
    AI gave me a basic example, and then I changed it to match our project’s style. I always tested the code and checked it before using it.

- **Documenting code**
  I didn’t use AI to write comments. I wanted to practice explaining my logic clearly.
  In our final project, I wrote things like:
  // This function opens the modal when the edit button is clicked
  Writing my own comments helped me think more deeply about what the code was doing.

- **Quality assurance**
  This was one of the most helpful uses of AI for me. Many times, I got strange ESLint or runtime errors. I copied the error and asked ChatGPT:

    “Why am I getting 'property undefined' when accessing an image in a club object?”
    It explained that maybe the object wasn’t loaded yet, and I should check for null.
    I also asked during Prisma errors:
    “Why is my migration failing with a relation error?”
    ChatGPT helped me figure out I had a mistake in my schema file.

- **Other uses**
  I don’t remember using AI for anything else. Mostly, I used it for debugging, writing code, and learning harder parts of React.
## III. Impact on Learning and Understanding

For me, one of the biggest advantages of using AI in ICS 314 was how it helped me move forward when I got stuck. When I ran into an obstacle or didn’t fully follow a topic, I could type my thoughts into ChatGPT, and it would help me make sense of what I was trying to do or carry me into the next step. Even if I didn’t understand everything perfectly, AI often helped me keep making progress without getting completely lost.

AI was especially helpful when it came to understanding TypeScript functions. I struggled with passing functions as arguments and manipulating arrays. When I asked ChatGPT something like, “Give an example of a TypeScript function that filters an array of numbers greater than 10,” it responded with something like:

```
const filterNumbers = (arr: number[]): number[] => {
  return arr.filter(num => num > 10);
};

console.log(filterNumbers([5, 12, 8, 20])); // Output: [12, 20]
```

Seeing working examples like that made it easier for me to understand the syntax and logic behind what I was doing. And I was able to absorb the idea over a simple example, and even if I was still confused, I could ask more questions. Rather than spending too much time searching for examples on my own, AI allowed me to focus more on learning the actual concept and applying it in WODs and assignments.

In general, AI improved my comprehension and problem-solving process. It didn’t give me perfect answers every time, but it kept me from getting stuck and made it easier to build confidence in difficult topics.

## IV. Practical Applications

Outside of ICS 314, I’ve found AI to be very useful in real-world coding tasks, especially for simpler bug fixing. When dealing with logical or syntax errors, I often paste the full code into an AI like ChatGPT and ask it to help identify the issue. It saves a lot of time compared to manually combing through every line. Even if AI doesn’t always catch the error, it still helps me narrow down where to look or gives me a second opinion, which is valuable during debugging.

AI is especially helpful when I already have a good understanding of what I’m doing and just need quick guidance or confirmation. For example, during a Unity game development project, I was working on particle generation for a visual effect. The particles weren’t behaving correctly, and I wasn’t sure why. I asked ChatGPT how to randomize particle direction, and it gave me some general guidance. I was then able to apply my own knowledge of math functions, like using sin and cos for better control over direction rather than just inputting raw radian values. AI helped point me in the right direction, but I still had to combine that with my own problem-solving and understanding of Unity’s engine.

In these kinds of practical scenarios, AI works best as a support tool. It doesn’t replace real experience or deep knowledge, but it complements them well by speeding up repetitive tasks and offering ideas or reminders. It’s especially effective when I already understand the domain and just need a little push in the right direction.

## V. Challenges and Opportunities

One challenge I faced while using AI in ICS 314 was trying to transition code between different frameworks, specifically when moving from Bootstrap/HTML layouts to React-based implementations. AI often provided code that was technically valid, but it didn’t always follow the structure or style expected in a React environment. This inconsistency made it hard to stay aligned with assignment requirements, especially when React-specific approaches were expected when AI would just reuse HTML code.

Another significant limitation came during the final project when working with the Vercel database and dynamic page generation. While I personally had a good understanding of databases from the practice we did earlier in the course, some of my team members struggled. When they asked AI to help them build pages that integrated with Vercel or the backend, the results were often messy or incomplete. AI could generate code, but it wasn’t always clean, nor did it reflect best practices we were taught in class. This led to inconsistencies in our project and difficulties when trying to implement new features or troubleshoot bugs.

I believe AI has major potential in software engineering education. Rather than just being a tool to generate code, AI can be taught and used as a learning partner. Students could benefit from learning how to use AI effectively: how to ask the right questions, how to critically evaluate its responses, and how to incorporate their own thinking, design choices, and debugging strategies. By treating AI as a collaborative assistant rather than a crutch, students can enhance both their technical skills and problem-solving confidence in a way that reflects real-world software development.

## VI. Comparative Analysis

Traditional Learning:
In traditional learning, there's often a lot of theoretical knowledge and dull, rote memorization involved. A lot of time is spent digesting abstract concepts and basic examples before moving on to more complex topics. While this provides a solid foundation, it can feel overwhelming due to the sheer amount of information and the slow pace of progressing from simple examples to real-world applications. This often leaves students feeling bogged down in detail before they can see practical results.

AI-Enhanced Approaches:
AI, on the other hand, offers a more hands-on, trial-and-error learning experience. It functions almost like a mentor, guiding you through problems and helping you get immediate feedback. This feels less like memorizing static information and more like a dynamic, interactive learning process. With AI, you can experiment and refine your approach in real time, which can lead to a deeper, more practical understanding. It’s like having a personalized tutor that helps you move past initial hurdles quickly, allowing you to focus more on applying concepts rather than getting stuck on fundamentals.

In difficult or complex scenarios, AI can provide prompts and suggestions that help you generate a basic understanding before diving deeper into the problem, making learning more efficient. The ability to ask AI specific questions or get code examples instantly speeds up the learning process, allowing you to make progress without the prolonged struggle typical of traditional methods.

Ultimately, AI enhances learning by giving students a more interactive, hands-on approach while reducing the time spent stuck on basic concepts. It allows for a faster, more practical application of software engineering principles, which contrasts with traditional learning methods where you often have to slog through theory and memorization before reaching the hands-on experience.

## VII. Future Considerations

AI's Future Role in Software Engineering Education:
As AI continues to improve, I believe it will play a major role in software engineering education. AI tools can generate code quickly, offer real-time feedback, and assist with debugging. For students who are skilled at leveraging AI, it can essentially act as an advanced assistant, enabling them to excel in other areas of software engineering. Mastery of using AI effectively will become a valuable skill in itself, as it allows for a deeper understanding and more efficient problem-solving.

Challenges:
However, there are challenges to this integration. One concern is that AI’s ability to provide instant solutions can make simple problems feel trivial, potentially preventing students from going through the critical learning process of trial and error. If AI is too good at solving basic problems, students may lean too heavily on it and miss out on developing problem-solving skills themselves. Not every course can easily incorporate AI, as some might struggle with the balance of encouraging independent thinking while offering AI assistance. There’s a fine line between using AI as a tool to enhance learning and relying on it so much that it becomes a crutch.

Areas for Improvement:
An important area of improvement is how AI is incorporated into educational curriculums. In many classes I've taken, the integration of AI has been either not done at all or poorly executed. Some instructors encourage the use of AI as a problem-solving tool, while others emphasize memorization, which seems less relevant in a world where AI can handle much of the basic work. There needs to be a major update to course materials that recognizes AI as a part of the learning process, not something to be avoided or simply used to “solve” problems. The focus should shift from memorization to understanding how to use AI to solve real-world problems while developing critical thinking and design skills.

In the future, software engineering education will need to evolve to incorporate AI in a way that complements and enhances traditional learning methods, ensuring that students are equipped with the tools and skills needed to succeed in an increasingly AI-driven industry.

## VIII. Conclusion

Reflecting on my use of AI in this Software Engineering course, I find that it has been both a helpful and sometimes essential tool for advancing my understanding, particularly when I encountered obstacles. While I made efforts to solve problems independently through research, trial and error, and effort, AI became a valuable resource when those methods didn’t yield results. I believe that early assignments in the course could have been designed with more guided support, allowing students to feel confident in replicating and advancing on what they learned. Without that foundation, many students, myself included, turned to AI when they felt lost, which can become a habit if not addressed.

For future courses, I recommend incorporating AI more intentionally. Each module could include two types of assignments: one that offers more guided support to build confidence and understanding, and another that simulates real-life scenarios where students are encouraged to use AI to find solutions. While not every course can fully integrate AI in this way, I believe there’s potential, especially in areas like database management and pgAdmin, where more AI-focused, real-world assignments could deepen understanding.

In writing this essay, I, too, used AI extensively, from basic spelling and grammar checks to refining sentence structures for clarity and coherence. AI helped me expand on initial ideas, guiding me through the process of exploring and developing my thoughts further. This process highlighted the versatility of AI not only as a tool for coding but also as a way to enhance critical thinking and expression in academic work.

In conclusion, AI has proven to be a powerful asset in software engineering education, but its integration needs to be balanced with opportunities for students to engage deeply with material, learn from mistakes, and develop independent problem-solving skills.
