# Phases of SDLC and Accessibility

It's easy to get agreement that Accessibility is important, but without embedding checks in the way of working, you will unlikely see a consistant approach. The risk is that Accessibility issues will quickly slip into being dealt with in a "fire fighting" manner.

In the course of doing Accessibility audits, I find most issues could have been easily avoided, with some checks added to the SDLC (Software Development Life Cycle). These checks at each phase of design and development, and will not add much effort or time. A strong reasoning behind adding more checks to the SDLC, so that more time can be invested in covering how accessible the user experience (UX) of an app under test. 

Testing an app for Accessibility can be very time-consuming, if there are numerous minor (avoidable) issues.

## Planning Stage 

Define accessibility goals and requirements at the outset. This includes understanding legal obligations and setting clear objectives for compliance with WCAG guidelines. This is where it is worth writing a compnay Accessibility strategy, so that aims and goals are clear to all.

Assess existing systems and content for accessibility issues to identify areas needing improvement, and generate an Accessibility Statement. This can be done by requesting an audit from a third-party (generally recommended).

## Analysis

Engage with users with disabilities, to gather insights and requirements (suprisingly few do). Their insights will be invaluable, as they have real world experience with assistive software and devices. From those discussions, you can start creating personas and user stories that reflect behaviour expected from the app.

A persona in user-centered desig is a personalized fictional character created to represent a user type that might use an app in a similar way. They are based on demographic and behavioural personal information collected from users, qualitative interviews, and participant observation. 

## UI/UX Design

Apply inclusive design principles following the WCAG POUR ((Perceivable, Operable, Understandable, and Robust) principles, to create wireframes and prototypes. Ensure that design elements such as color contrast, font sizes, and navigation structures are accessible. Most design tools have these checking features. If not run a simple tool to do a pass on the design which will pick up on sizing and color contrast.

With forms, this touches on UX (user experience). Design forms, buttons, and other interactive elements to be easily usable by all users, including those relying on assistive technologies.

## Development

Use semantic UI code to ensure that content is structured in a way that is easily interpretable by screen readers and other assistive technologies. Implement ARIA roles and attributes to enhance the accessibility of dynamic content, and ensure ALL elements on screen are uniquely labelled. Ensure that all functionality is accessible via keyboard, providing logical tab order and focus indicators.

Tools like Axe, WAVE, and Lighthouse help  identify accessibility issues early in the development process.

## Testing

In testing phase, this is when the testing can be more focused on UX, focusing on user journeys through the app. Test frameworks such as Playwright, Espresso and XCUTest have plugins to run screen reader tests, and other UI checks. 

Test with assistive technologies such as screen readers (e.g., VoiceOver or NVDA), and voice recognition software. If possible, involve users with disabilities in usability testing to identify practical issues and gather feedback.

## Deployment

Provide an accessibility statement that outlines the accessibility features of the product and offers contact information for reporting issues. Monitor accessibility post-deployment to ensure ongoing compliance and address new issues as they arise.

## Maintenance

With checks integrated in your SDLC, it means that in maintenance phase, you already have all checks in places, when any changes occur. Also perform regular accessibility audits to ensure that updates and new features continue to meet accessibility standards, then update your Accessibility statement to match.  Provide channels for easy feedback from users with disabilities, to continuously improve accessibility.

## Resources

* The [Web Content Accessibility Guidelines (WCAG 2.2)](https://www.w3.org/TR/WCAG22/) provide comprehensive standards for web and mobile app accessibility.
* For mobile apps, [Apple's Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/accessibility) and [Android's Accessibility Principles](https://developer.android.com/guide/topics/ui/accessibility), should also be taken into consideration.
[Guides for developing accessible websites](https://webaim.org/articles/)

