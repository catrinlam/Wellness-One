# Wellness One

Wellness One is a one-page website designed to provide easy-to-understand, beginner-friendly information about mental health. The website aims to support users in recognising common mental health challenges and managing stress effectively. With a clean and calming layout, the website ensures an accessible and supportive experience for users seeking quick guidance or resources. Mindful Moments caters to individuals who want to improve their mental well-being and are looking for a starting point on their journey towards mental health awareness.

The site is built with HTML and CSS using the Bootstrap framework, ensuring a responsive and aesthetically pleasing design across all devices. The focus is on delivering a welcoming and organised interface that meets the needs of its audience.

![Responsice Mockup](assets/images/readme-images/wellness-one-mockup.png)

## Site Goals

The primary goals of Wellness One are:

1. **Educational Goal**: To educate users about mental health in a simple and approachable manner.
2. **Support Goal**: To provide practical stress management tips that users can implement immediately.
3. **Connection Goal**: To direct users to professional organisations and resources for further support.

## Design Choices

The design of Wellness One reflects its focus on calmness, simplicity, and accessibility:

- **Minimalist Layout**: A clean, single-page design ensures easy navigation without overwhelming users.
- **Colour Scheme**: Soft, muted colours (light blues, whites, and greens) evoke calmness and positivity.
- **Typography**: Sans-serif fonts are used for readability and to convey a modern, friendly tone.
- **Responsiveness**: The Bootstrap framework ensures compatibility across various devices and screen sizes.

## User Stories
The following user stories were considered to guide the design and functionality of the site:
- As a new user, I want to understand the purpose of the site quickly.
- As a new user, I want to learn about common mental health challenges in an approachable way.
- As a new user, I want to find practical tips to manage my stress immediately.
- As a new user, I want to access links to trusted resources for further help.
- As a new user, I want the site to be easy to navigate, even on my mobile device.
- As a returning user, I want to revisit specific stress management tips that worked for me.
- As a returning user, I want to share helpful content from the site with a friend or loved one.
- As a user, I want to feel supported and reassured by the tone and visuals of the site.

## Wireframes
The wireframes were designed to reflect the simple and structured layout of Wellness One, prioritising usability and accessibility:

1. **Landing Section**:
    - Features a hero image with a calming background, a concise welcome message, and navigation links.

![Landing Wireframe](assets/wireframes/landing.png)

2. **Mental Health Information Section**:
    - Divided into easy-to-read subsections covering common challenges like anxiety and depression.

![Mental Health Information Wireframe](assets/wireframes/mental-health-info.png)

3. **Stress Management Tips Section**:
  - Displays practical advice in a bullet point or list format for quick implementation.

![Stress Management Tips Wireframe](assets/wireframes/stress-management.png)

4. **Resources Section**:
  - Includes external links to trusted organisations and tools.

![Resources Wireframe](assets/wireframes/resources.png)

5. **Footer**:
  - Contains social media icons, a contact email, and any disclaimers or additional notes.

![Footer Wireframe](assets/wireframes/footer.png)

## Additional UX/UI Considerations

**Accessibility**:
  - Colour contrast and font sizes were tested to ensure readability for users with visual impairments. The chosen colour scheme, shown below, was selected to provide a calming and soothing experience:
![Colour Scheme](assets/images/readme-images/colour-scheme.png)
  - The navigation bar and buttons are large and easy to click, improving usability for individuals with motor impairments.

**User Flow**:
  - A linear, logical layout guides users seamlessly through the site from introduction to actionable resources.

**Feedback Opportunities**:
  - A contact link in the footer encourages users to share feedback for site improvement.

## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so. You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

### Existing Features

- **Navigation Bar**

  - A responsive navigation bar located at the top of the page provides links to all sections: Home, Mental Health Info, Stress Management Tips, and Resources.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button.

![Nav Bar](assets/images/readme-images/nav-bar.png)

- **The landing page image**

  - The landing section includes a soothing background image with an uplifting welcome message, introducing the site's purpose and encouraging users to explore.
  - This feature creates a positive first impression, inviting users to learn more about mental health.

![Landing Page](assets/images/readme-images/landing.png)

- **Mental Health Information Section**

  - This section outlines common mental health challenges like anxiety and depression, explained in a simple and approachable tone.
  - It provides value by educating users without overwhelming them, making mental health topics more accessible.

![Mental Health Information Section](assets/images/readme-images/mental-health-info.png)


- **Stress Management Tips Section**

  - A concise list of practical stress management techniques, such as breathing exercises and time management tips, is included here.
  - Users gain actionable advice that they can implement immediately to improve their mental well-being.

![Stress Management Tips Section](assets/images/readme-images/stress-management-tips.png)

- **Resources Section**

  - Links to trusted mental health organisations, helplines, and articles are provided in this section.
  - This feature ensures users can easily find further support if needed.

![Resources Section](assets/images/readme-images/resources.png)

- **The Footer**

  - The footer includes links to the website's social media accounts and an email contact for feedback or additional queries.
  - By encouraging users to connect, this section fosters a sense of community and support.

![Footer](assets/images/readme-images/footer.png)

### Features Left to Implement

- **Interactive Quiz**

  - A short, interactive quiz to help users identify their stress levels and receive personalised tips.

- **Newsletter Sign-Up**
  - A sign-up form to allow users to receive regular updates and mental health tips via email.

- **Theme Changing**
  - Implement a dropdown that allows users to switch between light and dark themes for a customised browsing experience.

## Testing

### Functional Testing
- Please see [TESTING.md](TESTING.md) file for all manual testing.

### Lighthouse Results
- Desktop Lighthouse Report:

  ![Desktop Report](assets/images/readme-images/desktop-lighthouse.png)

- Mobile Lighthouse Report:

  ![Mobile Report](assets/images/readme-images/mobile-lighthouse.png)

### [WCAG Accessible Web Helper](https://chromewebstore.google.com/detail/accessible-web-helper/gdnpkbipbholkoaggmlblpbmgemddbgb)

Accessible Report:

![Accessible Report](assets/images/readme-images/accessible-report.png)

### Validator Testing

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcatrin.is-a.dev%2Fwellness-one%2F)
  ![HTML Validator Report](assets/images/readme-images/html-validator.png)

- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fcatrin.is-a.dev%2Fwellness-one)
  ![CSS Validator Report](assets/images/readme-images/css-validator.png)


## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows:
  - In the GitHub repository, navigate to the Settings tab
  - From the source section drop-down menu, select the Deploy Branch
  - Once the Deploy branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found here - https://catrin.is-a.dev/wellness-one/

## Credits

### Content

- Used [Readme Template](https://github.com/Code-Institute-Solutions/readme-template) by Code Institute
- The ReadMe file was rewritten and structured using ChatGPT to ensure clarity and professionalism
- Mental health information and stress management tips adapted from [NHS](https://www.nhs.uk/mental-health/) and [Mind.org](https://www.mind.org.uk/) resources.
- The font was taken from [Google Fonts](https://fonts.google.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- Background image from [Unsplash](https://unsplash.com/) by [Kelly Sikkema](https://unsplash.com/photos/person-reaching-black-heart-cutout-paper-XX2WTbLr3r8).
