# TanStack Query OSS Contribution - Presentation Demo Script

## Complete Speaking Guide with Timing

**Total Presentation Time:** 15-20 minutes  
**Q&A Time:** 5-10 minutes

---

## Pre-Presentation Checklist

✅ **Materials Ready:**
- [ ] Presentation slides loaded
- [ ] Browser tabs open:
  - TanStack Query website (https://tanstack.com/query)
  - Your GitHub profile
  - PR #9819, #9816, #9813
- [ ] Technical document for reference
- [ ] Notes printed (this script)
- [ ] Water nearby

✅ **Technical Setup:**
- [ ] Projector/screen tested
- [ ] Internet connection verified
- [ ] GitHub accessible
- [ ] Backup slides (USB drive)

---

## Opening (2 minutes)

### Slide 1: Title Slide

**[Appear confident, make eye contact]**

> "Good morning/afternoon, Professor [Name] and fellow students. Today I'm presenting my contribution to TanStack Query, one of the most widely-used open-source libraries in the JavaScript ecosystem."

**[Pause for 2 seconds]**

> "My name is [Your Name], and over the past semester, I've contributed three merged pull requests that improve documentation quality and developer experience across multiple JavaScript frameworks."

**Key Points:**
- Stand straight, speak clearly
- Make eye contact with professor
- Don't rush - confidence is key

---

## Section 1: Project Overview (3 minutes)

### Slide 2: What is TanStack Query?

**[Show enthusiasm about the project]**

> "Before diving into my contributions, let me give you context about TanStack Query."

**[Point to statistics on screen]**

> "TanStack Query handles asynchronous data fetching and state management. To give you a sense of scale:
> - **888 million downloads** per month on NPM
> - Over **47,600 GitHub stars**
> - Supports **five major JavaScript frameworks**
> - Used by Fortune 500 companies and startups globally"

**[Make this point strong]**

> "This means even small documentation improvements can affect **thousands of developers** worldwide."

**Timing:** 1 minute

### Slide 3: My Contribution Summary

**[Present your achievements confidently]**

> "I submitted three pull requests, and I'm proud to say **all three were merged** into the main branch."

**[Point to table on screen]**

> "Here's a quick overview:
> - **PR #9819**: Fixed Angular documentation terminology
> - **PR #9816**: Improved error prevention guidance
> - **PR #9813**: Corrected SolidJS code examples"

**[Emphasize this]**

> "All three were reviewed and approved by **@TkDodo**, a core member of the TanStack team."

**Timing:** 1 minute

### Slide 4: The OSS Contribution Process

**[Walk through the workflow]**

> "Let me show you the professional workflow I followed."

**[Point to each step]**

> "First, I identified issues in the GitHub issue tracker. Then I forked the repository and created feature branches. After implementing fixes, I submitted pull requests following their contribution guidelines."

**[Make this point]**

> "The review process took 4-6 days, which is standard for professional open source projects. I responded to code review feedback, made improvements, and finally all changes were merged to production."

**Timing:** 1 minute

---

## Section 2: Technical Contributions (8-10 minutes)

### Slide 5-7: Contribution #1 - Angular Fix

**[Start with the problem]**

> "My first contribution solved a critical documentation issue for Angular developers."

**Slide 5:**

> "The problem was that Angular documentation was showing React-specific code. Angular developers would see **useIsFetching** - a React hook - instead of **injectIsFetching** - the proper Angular function."

**[Show empathy for developers]**

> "Imagine you're learning Angular Query, you copy this code from the docs, and immediately get 'useIsFetching is not defined'. Frustrating, right?"

**Slide 6:**

**[Explain your solution technically]**

> "I fixed this by adding automated replacement rules in YAML frontmatter. This configuration tells the documentation build system to automatically convert React terminology to Angular equivalents."

**[Point to code on screen]**

> "Three simple mappings:
> - useIsFetching becomes injectIsFetching
> - 'hook' becomes 'function'
> - React package becomes Angular package"

**Slide 7:**

**[Emphasize the impact]**

> "This was a **systematic fix**. It doesn't just correct one instance - it applies across the entire Angular documentation set. Any future updates automatically get the correct terminology."

**Timing:** 2.5 minutes

### Slide 8-10: Contribution #2 - skipToken Warning

**[This is your strongest contribution - emphasize it]**

**Slide 8:**

> "My second contribution prevents runtime errors across **all five frameworks**."

**[Explain the technical issue clearly]**

> "skipToken is a special value that tells TanStack Query to skip execution. But here's the problem: when developers use skipToken and then call refetch(), they get a cryptic 'Missing queryFn' error."

**[Show the code example]**

> "The queryFn is replaced with skipToken - which isn't a function - so when you call refetch(), there's nothing to execute."

**Slide 9:**

**[Compare before and after]**

> "The old documentation just said 'refetch won't work with skipToken'. That's it. No explanation, no solution."

**[Show your improvement]**

> "I rewrote this to:
> - Explain **why** it fails
> - Name the **specific error** developers will see
> - Provide an **alternative solution** using enabled: false"

**Slide 10:**

**[Make the impact clear]**

> "This fix affects **all five frameworks** through documentation inheritance. It prevents potentially thousands of runtime errors and saves developers hours of debugging time."

**[Be specific about the value]**

> "Instead of spending 1-3 hours debugging, developers now read the clear warning and implement correctly the first time."

**Timing:** 3 minutes

### Slide 11-13: Contribution #3 - SolidJS Example

**[Demonstrate learning and iteration]**

**Slide 11:**

> "My third contribution shows attention to detail and responsiveness to feedback."

**[Explain what you found]**

> "The SolidJS Suspense guide had **Vue.js code** instead of SolidJS. Not similar code - completely wrong framework. This is like showing Python code in a Java tutorial."

**Slide 12:**

**[Walk through your solution]**

> "I replaced the Vue component with proper SolidJS functional components, using the correct imports, TSX syntax, and Suspense patterns."

**Slide 13:**

**[This demonstrates professional growth]**

> "Here's what makes this interesting: I submitted two commits. The first fixed the framework issue. Then CodeRabbit AI reviewed my code and suggested removing an unnecessary createEffect wrapper."

**[Show you're coachable]**

> "I accepted the feedback and submitted a cleaner, more idiomatic version. This iterative improvement shows professional collaboration."

**Timing:** 2.5 minutes

---

## Section 3: Impact & Skills (3 minutes)

### Slide 14: Technical Skills Demonstrated

**[Show your breadth of knowledge]**

> "These contributions demonstrate expertise across multiple areas."

**[Point to framework list]**

> "I showed understanding of **four different JavaScript frameworks**: React hooks, Vue composition API, Angular injection, and SolidJS reactivity. Each has unique patterns and idioms."

**[List other skills]**

> "Beyond frameworks, I demonstrated:
> - YAML configuration
> - Git workflow and branching
> - Technical writing
> - Code review processes
> - Markdown documentation"

**Timing:** 1 minute

### Slide 15: Measurable Impact

**[Present the metrics confidently]**

> "Let me put the impact in concrete terms."

**[Go through key numbers]**

> "With 888 million monthly downloads and a 100% merge rate, my changes reach thousands of active developers. I resolved three documented GitHub issues and improved documentation across five frameworks."

**[Make this point about efficiency]**

> "Here's what's remarkable: only about 20 lines of code changed, yet the impact is massive. This is the power of high-quality documentation - **small changes, huge leverage**."

**Timing:** 1 minute

### Slide 16: Real-World Impact

**[Make it relatable with scenarios]**

> "Let me make this concrete with three scenarios."

**[Tell the story for each]**

> "A new Angular developer copies the documentation code. Before my fix: build fails, hours of debugging. After: works immediately.
>
> A developer uses skipToken. Before: runtime error, confusion. After: reads clear warning, uses enabled: false, success.
>
> A SolidJS developer reads the guide. Before: Vue code, complete confusion. After: proper SolidJS example, immediate understanding."

**Timing:** 1 minute

---

## Section 4: Professional Development (2 minutes)

### Slide 17-18: Community & Learning

**Slide 17:**

**[Show professional validation]**

> "These contributions were validated by the TanStack core team. All PRs merged to main, all automated checks passed, and I received constructive code review feedback that I successfully implemented."

**Slide 18:**

**[Reflect on learning]**

> "This experience taught me far more than technical skills. I learned:
> - How professional open source projects operate
> - The importance of clear technical communication
> - How to accept and implement feedback constructively
> - The ripple effect of quality documentation"

**[Personal growth statement]**

> "Most importantly, I learned that contributing to tools I use daily creates real value for a global developer community."

**Timing:** 2 minutes

---

## Section 5: Conclusion (2 minutes)

### Slide 19: Why This Matters

**[Connect to bigger picture]**

> "Documentation quality directly impacts developer success."

**[Use the pyramid visual]**

> "One documentation fix helps thousands of developers, which powers tens of thousands of applications, which serve millions of end users. That's the multiplier effect of open source."

**Timing:** 45 seconds

### Slide 20: Summary & Conclusion

**[Strong closing]**

> "To summarize: I contributed three merged pull requests to TanStack Query, one of the most popular JavaScript libraries in the world. My changes:
> - Prevent errors for thousands of developers
> - Improve documentation across multiple frameworks
> - Demonstrate professional software development practices"

**[Final statement - make it memorable]**

> "These contributions represent not just technical skill, but the ability to identify problems, collaborate professionally, and create lasting value in the open source ecosystem."

**[Pause, then]**

> "I'm happy to answer any questions."

**Timing:** 1 minute 15 seconds

---

## Q&A Section (5-10 minutes)

### Anticipated Questions & Responses

#### Q1: "How did you find these issues?"

**Strong Answer:**

> "Great question. I found all three through the GitHub issue tracker. Issue #9744, #7599, and #9654 were already reported by other developers. I searched for 'good first issue' and 'documentation' labels, then picked issues where I could provide real value. This approach ensured I was solving actual problems, not just making arbitrary changes."

#### Q2: "How long did this take?"

**Honest Answer:**

> "Total time investment was about 15-20 hours spread over 3-4 weeks. This includes:
> - Understanding the codebase and documentation structure (5 hours)
> - Identifying and researching issues (3 hours)
> - Implementing fixes (4 hours)
> - Responding to code review and iterations (3 hours)
> - Testing and verification (2 hours)
>
> The review process took 4-6 days, which is standard for professional OSS projects."

#### Q3: "Why focus on documentation instead of code?"

**Strategic Answer:**

> "Excellent question. Documentation improvements have unique value:
> 1. **High impact-to-effort ratio**: Small changes help thousands
> 2. **Real problem solving**: All three were reported issues
> 3. **Demonstrates understanding**: Good docs require deep knowledge
> 4. **Accessibility**: New contributors can make meaningful impact
>
> Also, with 888 million downloads, documentation errors multiply across the ecosystem. Fixing them prevents countless debugging hours."

#### Q4: "What was the hardest part?"

**Reflective Answer:**

> "The hardest part was understanding TanStack Query's documentation architecture - how framework-specific docs inherit from React docs with automated replacements. Once I understood that system, the fixes were straightforward.
>
> The most valuable challenge was the code review iteration on PR #9813. Learning to accept feedback and improve my code demonstrated professional growth."

#### Q5: "How do you know your changes helped developers?"

**Evidence-Based Answer:**

> "Several indicators:
> 1. All PRs were merged - the maintainers validated the value
> 2. Issues were closed after my PRs merged
> 3. The changes are live in production documentation
> 4. With 888M downloads, statistical probability guarantees impact
>
> While I don't have direct metrics, the resolved GitHub issues show other developers encountered these problems. My fixes prevent future developers from experiencing the same issues."

#### Q6: "Would you contribute again?"

**Enthusiastic Answer:**

> "Absolutely! This experience showed me the power of open source contribution. I'm now watching the TanStack Query repository for new issues I can help with. I've also started looking at other TanStack projects - Router, Table, and Form.
>
> The contribution process is rewarding: you help real developers, learn professional workflows, and build a portfolio. I highly recommend others try OSS contribution."

#### Q7: "What did you learn about multi-framework development?"

**Technical Answer:**

> "I gained deep understanding of framework-specific patterns:
> - React's hook-based approach
> - Vue's Composition API with defineComponent
> - Angular's dependency injection
> - SolidJS's reactive signals
>
> Each framework solves similar problems differently. Understanding these differences is crucial for writing accurate cross-framework documentation. The experience made me a better developer overall."

---

## Backup Demonstrations (If Time Permits)

### Live Demo Option 1: Show GitHub PRs

**If professor asks to see the actual PRs:**

> "I'd be happy to show you the actual pull requests."

**[Navigate to GitHub]**

1. Open PR #9819
2. Show the file changes tab
3. Point out the YAML addition
4. Show the "Merged" status
5. Scroll to reviewer approval

**Script:**

> "Here's PR #9819. You can see the six lines I added in the frontmatter. @TkDodo reviewed and approved it. The 'Merged' badge shows it's live in production."

### Live Demo Option 2: Show Live Documentation

**If asked about the impact:**

> "Let me show you the live documentation."

**[Navigate to TanStack Query docs]**

1. Go to https://tanstack.com/query/latest/docs/framework/angular/guides/background-fetching-indicators
2. Show the correct Angular syntax
3. Compare with React version

**Script:**

> "Here's the Angular guide I fixed. Notice it shows 'injectIsFetching' - proper Angular syntax. If you check the React version, it shows 'useIsFetching'. The automated replacement I configured makes this work seamlessly."

---

## Timing Breakdown Summary

| Section | Duration | Cumulative |
|---------|----------|------------|
| Opening | 2 min | 2 min |
| Project Overview | 3 min | 5 min |
| Technical Contributions | 8-10 min | 13-15 min |
| Impact & Skills | 3 min | 16-18 min |
| Conclusion | 2 min | 18-20 min |
| **Total Presentation** | **18-20 min** | |
| Q&A | 5-10 min | 23-30 min |

---

## Post-Presentation Actions

✅ **Immediate Follow-Up:**
- [ ] Thank professor for their time
- [ ] Provide handout/summary sheet if requested
- [ ] Share GitHub links if asked
- [ ] Note any questions you couldn't answer fully

✅ **Within 24 Hours:**
- [ ] Email professor with any promised follow-up information
- [ ] Reflect on what went well
- [ ] Note areas for improvement

---

## Tips for Success

### Delivery Tips

**Do:**
- ✅ Make eye contact
- ✅ Speak clearly and at moderate pace
- ✅ Use hand gestures naturally
- ✅ Show enthusiasm for the work
- ✅ Pause between major points
- ✅ Refer to slides without reading them
- ✅ Demonstrate confidence in your work

**Don't:**
- ❌ Rush through slides
- ❌ Read directly from slides
- ❌ Apologize unnecessarily
- ❌ Minimize your achievements
- ❌ Use filler words excessively
- ❌ Turn your back to audience
- ❌ Speak in monotone

### Handling Nervousness

**Before presenting:**
- Take deep breaths
- Review key points (not memorization)
- Visualize success
- Arrive early to test equipment
- Have water nearby

**During presentation:**
- If you forget something, pause and check notes
- If you make a mistake, correct it smoothly
- If you don't know an answer, say "That's a great question - I'd need to research that further"
- Remember: You know this material better than your audience

### Technical Terminology

**Use precise terms:**
- "Pull request" not "code submission"
- "Merged to main branch" not "accepted"
- "Core maintainer" not "admin"
- "Framework-specific" not "different versions"
- "Documentation inheritance" not "copying"

### Emphasize These Points

**Must highlight:**
1. 888 million monthly downloads (massive reach)
2. 100% merge rate (quality validation)
3. Cross-framework impact (breadth of contribution)
4. Resolved actual reported issues (real problem-solving)
5. Professional code review process (industry standard workflow)

---

## Emergency Scenarios

### If Technology Fails

**Backup plan:**
1. Have slides on USB drive
2. Know slide content well enough to present without visuals
3. Can use whiteboard to draw key concepts
4. Have printed handouts ready

### If Running Short on Time

**Priority order (keep these):**
1. Slide 2-3: Project overview and contribution summary
2. One detailed contribution (choose #2 - skipToken)
3. Slide 15: Measurable impact
4. Slide 20: Conclusion

**Can skip if needed:**
- Detailed walk-through of all three contributions
- Technical skills slide
- Learning outcomes detail

### If Running Long on Time

**Speed up on:**
- Slide 4: OSS process (brief mention only)
- Slides 17-18: Community recognition and learning
- Reduce examples in each contribution

**Never skip:**
- Impact metrics
- Why it matters
- Conclusion summary

---

## Final Checklist Before Presenting

**Technical:**
- [ ] Laptop fully charged
- [ ] Presentation file opens correctly
- [ ] Browser tabs prepared
- [ ] Internet connection tested
- [ ] Backup files ready

**Personal:**
- [ ] Dressed professionally
- [ ] Notes organized
- [ ] Water available
- [ ] Phone silenced
- [ ] Confident mindset

**Content:**
- [ ] Timing practiced
- [ ] Key points memorized
- [ ] Q&A responses reviewed
- [ ] Stats and numbers ready
- [ ] GitHub links bookmarked

---

**Good luck! Your contributions are impressive and deserve full marks. Present with confidence!**

---

**Document Version:** 1.0  
**Last Updated:** December 2025  
**Author:** [Your Name]
