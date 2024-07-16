<hr/>
<h3>Hello & Welcome, </h3><br/>

You may view my public repositories (below) to get a feel for my progression as a developer.

My largest development to date is a full-stack web application and SaaS offering supporting a small paying customer base, housed in a private GitHub repository. You can visit the live site at [Bodyboon](https://bodyboon.com/).<br/>

Project Overview<br/>
The project includes three websites:

- Home Page: [www.bodyboon.com](https://bodyboon.com/)<br/>
- Production: [app.bodyboon.com](https://app.bodyboon.com/)<br/>
- Beta: private<br/><br/>
Production Technical Details<br/>
- Hosting and Deployment: Production and beta sites are containerized and deployed to Google Cloud Run.<br/>
- User Authentication: Built with Google's Firebase SDK, utilizing JWT token authorization middleware for all HTTP fetch requests.<br/>
- Payment Processing: Implemented with Stripe's SDK, handling JSON queries and webhook events.<br/>
- Front-End: Utilizes custom Lit (lit.dev) web components, auto-detecting state changes in the shadow DOM caused by user interaction, communicating these changes via a REST API to an Express.js back-end.<br/>
- Back-End: Stateless architecture with Express.js, interfacing with Firebase, Stripe and MongoDB to save user data in real-time.<br/>
- Core Functionality: Custom algorithms and data structures generate unique dietary recommendations based on user inputs (age, weight, height, sex, and activity levels).<br/> Features include custom recipe building by ingredient search, nutritional content analysis (covering 44 nutrients), and diet tracking to monitor daily nutrient intake against dietary goals.


(っ˘ڡ˘ς) ♨ (๑ᵔ⤙ᵔ๑)<br/>
