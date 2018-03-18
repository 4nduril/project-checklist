# Checklist for projects which try to hire me

## Non-Technical

* How many people are in the team (devs, designer, tester)?
 * If more than 10: __alert__ How is work coordinated, are there sub- or super-structures?
 * If 10 or less: What is the concrete focus of the team, what are its responsibilities?
* Is diversity something that is considered in hiring processes? 
* How many of the team members are non-male?
* If there is more than one team: How are the teams working together on global or cross-team tasks?
* Are there regular developer meetings where current topics are discussed?
* What agile methodology is followed? How is this reflected in daily processes?
* Are there retrospectives on a regular basis? If not: __alert__
* Is there an agile coach or scrummaster? If not: __alert__ Was there ever one? When?
* Who decides what the team should do? How is the process for bringing tasks into the team?
* Who decides about technologies or technical questions?
* Does the project have a defined due date *and* a fixed feature set? If yes: __alert__
* In which phase is the project currently? If shortly before expected/guaranteed shipping date: __alert__
* Is remote working possible? If yes: Under what conditions (VPN/repository access, communication)?
* Are there explicit UX-people involved in the design process?
* How is the interaction between design and implemention?
 * If design is "ready" (__alert__), were people involved who are implementation experts (developers)?

## Technical

* Is the product responsively designed?
 * If not: __alert__ Why?
 * If yes: What does this mean, device-based breakpoints, design- / element-dependent breakpoints …?
* Which JavaScript framework is used? And why was it chosen?
 * If Angular: Which version? If <2: __alert__
 * If React:
  * Which state-management is used (React, Redux, MobX …) and why?
  * Is there a separation between presentational and logical components? If not: __alert__
* Is SSR deployed/planned? (Not "Some HTML is somehow rendered" but real Server-Side-Rendering in JavaScript on request) If not: __alert__
* Is the overall coding style more object-oriented or more functional?
* Is there mandatory unit testing? If not: __alert__
* Is there test coverage measurement? 
 * If yes: How is the coverage? Are there certain exclusions from the coverage?
 * If not: Why?
* Are third-party dependencies updated on a regular basis?
* How is CSS managed? Less/Sass, CSS-in-JS (which one) …
* Are there certain accessibility standards followed (WCAG) or, if not, is accessibility a present topic in the project?
* Is there a living style-guide? If not __alert__ , if yes:
 * Third-party or self-made?
 * Is it the Single Source of Truth for all elements? If not: __alert__
* Is there a continuous integration server?
 * Which operating system?
 * Does it build separately on every repo change?
 * Are there feature-branches which the developers can push and then get built? If not: __alert__
 * Is it uncritical to push a failing feature-branch? If not: __alert__
* Is there a system for code reviews (Github, GitLab, Upsource)?
* Are there performance measurements (rendering time, loading time, memory usage …)?
