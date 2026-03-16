# <center> Chapter 1: Introduction

## Defining Software Architecture

This definition has four dimensions. The software architecture
of a system consists of an architecture style as the starting point, combined with the
architecture characteristics it must support, the logical components to implement its
behavior, and finally the architecture decisions justifying it all.

- Architecture characteristics (see Figure 1-2) define the capabilities of a system (commonly
abbreviated as “-ilities”) and the criteria for its success: in short, what the
system should do.
    - Availability, Reliability, Testability, Scalability, Security, Agility,...}

- While architectural characteristics define a system’s capabilities, logical components
define its behavior.
    - he logical components form the domains, entities, and workflows of the application.

![alt text](fig_1_4_Arch_style.png)

- architecture decisions define the rules for how a system should be constructed. For example, an
architect might make a decision that only the Business and Services layers within
a layered architecture can access the database

## Laws of Software Architecture

Everything in software architecture is a trade-off.
—First Law of Software Architecture

If you think you’ve discovered something that isn’t a trade-off, more likely you just
haven’t identified the trade-off…yet.
—Corollary 1

You can’t just do trade-off analysis once and be done with it.
—Corollary 2

Why is more important than how.
—Second Law of Software Architecture

Most architecture decisions aren’t binary but rather exist on a spectrum between
extremes.
—Third Law of Software Architecture

## Expectations of an Architect

We’ve identified eight core expectations for any software architect,
irrespective of their role, title, or job description:
• Make architecture decisions
• Continually analyze the architecture
• Keep current with latest trends
• Ensure compliance with decisions
• Understand diverse technologies, frameworks, platforms, and environments
• Know the business domain
• Lead a team and possess interpersonal skills
• Understand and navigate organizational politics