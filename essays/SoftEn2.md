---
layout: essay
type: essay
title: "Lessons Beyond the Code: A Lookback at ICS314"
# All dates must be YYYY-MM-DD format!
date: 2025-05-14
published: true
labels:
  - Programming
  - Reflection
---
<img src="https://media.istockphoto.com/id/693474546/photo/iceberg-floating-in-arctic-sea.jpg?s=612x612&w=0&k=20&c=7JISfbPbqqOXzkwtqBuGJZi5hI1m4xhZTtuQH4kJLIk=">

*“The more you learn, the more you realize how much you don't know.” * – Albert Einstein.

** Throughout the Course

Throughout the ICS 314 course, I’ve gained many valuable skills and experiences in software engineering. Over the semester, we learned and worked with various coding frameworks such as HTML, CSS, Bootstrap, React, Next.js, and tools like pgAdmin and Vercel for database integration and deployment. But that’s just the tip of the iceberg, there are countless other frameworks and technologies out there waiting to be explored.

What stood out to me the most was the group project. For many of us, it was our first real experience working in a multi-person software development environment. Through it, I came to appreciate the importance of several core software engineering concepts, which I’ll explore in the following sections.

** The Final Project

Over the course of this class, we explored many software engineering concepts, but I truly had the chance to apply and test them during the final group project. It was through this experience that I learned some of the most valuable lessons. Two concepts that stood out to me the most were design patterns and coding standards. I’ve grown especially fond of these because they play a crucial role in creating a smooth and effective collaborative workflow. In a team setting, having a shared understanding of structure and style can make development more consistent, maintainable, and enjoyable for everyone involved.

What I find most valuable about design patterns is their reusability and the learning benefits that come from working with them consistently. One pattern I became very familiar with was the AddStuff pattern from the Next.js application template. During our assignments, this pattern was refined into AddContact, and I was able to further adapt it into my own version, Posting, during the group project.

The best part of using this pattern was how deeply I came to understand its structure and functionality. After working with it multiple times, making changes became almost trivial. It helped me create a simple, effective page that was easy to modify and build upon later. This consistency saved time and prevented bugs, which is exactly what design patterns are meant to do: provide tested, reliable solutions to common problems in a reusable format.

In contrast, one of my group members created a different page built mostly using AI assistance instead of following our established design patterns. Here’s a snippet from that implementation:
```
const onSubmit = (data: ClubData) => {
    startTransition(async () => {
      await onAddClub(data); // ✅ 使用传入的 prop
      handleClose();
      reset();
      router.refresh();
    });
  };
...
...

<Modal.Body>
          <Form onSubmit={handleSubmit(onSubmit)}>
            <Form.Group className="mb-2">
              <Form.Label>Creator Name</Form.Label>
              <Form.Control {...register('creator')} required />
            </Form.Group>
...

```

This approach didn’t incorporate the design patterns we had used throughout the rest of the semester, like centralized schema definitions and shared dbAction functions. As a result, all the logic was stuffed into the component files themselves, making the page harder to understand and much more difficult to maintain or modify, especially when the original author wasn’t available. This experience really emphasized to me how crucial consistent design patterns are for collaboration and maintainability in any software project.

** Possible Improvements

Although the main issue stemmed from a lack of consistent design patterns, I believe things could have still been improved if we had not neglected another important aspect: coding standards. During the project, we mostly treated coding standards as a chore, something we had to do just to make Vercel deployments work. But in hindsight, I see how much more potential coding standards had, and how we could have used them to our advantage.

One major improvement would have been to establish our own coding standard at the very start of the project, something that expanded on ESLint by including team-wide expectations. For example, we could have adopted a consistent practice of documenting each function with clear comments that describe what it does, where it is called from, and where it navigates or links to. Similarly, each component could have included detailed notes about its structure, purpose, and any dependencies. Clear separation and documentation within components would have made it much easier to cross-check files, understand unfamiliar code, and maintain a shared understanding across the team.

Additionally, had we done this, the merge process, which was quite confusing at times, could have been significantly smoother. Each team member would have been able to understand any section of code at a glance, without having to dig through unfamiliar or undocumented logic. Coding standards aren't just about clean syntax, they're about communication and collaboration, which are critical in any team-based software development environment.

** Conclusion

ICS 314 has been much more than a course on web development, it’s been a hands-on journey into the principles of software engineering. Through our final group project, I gained first-hand experience with the real-world challenges and value of concepts like design patterns and coding standards. These aren’t just academic ideas; they directly influence the quality, maintainability, and collaboration potential of any software project.

This course has laid a solid groundwork, and I feel more prepared to continue growing as a software engineer.

- ChatGPT is used to assist in writing this essay only in word choice, spelling, and grammar.

