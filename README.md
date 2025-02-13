# Caresync 🚀

The inspiration behind Caresync was to bridge the gap between healthcare and technology. We aimed to create a platform that seamlessly connects users and hospitals, providing efficient healthcare solutions, This project was fueled by the desire to address real-time healthcare challenges using cutting-edge technology.

Caresync is a comprehensive healthcare application designed to serve both users and hospitals. Users can access personalized dashboards to manage their health information, generate medical records from our symptoms checker, chat with a healthcare bot, book appointments, and stay connected with healthcare providers. Hospitals, on the other hand, benefit from a dedicated dashboard that streamlines patient management, appointment scheduling, and overall healthcare administration.

[Live link](https://getcaresync.vercel.app)
<br/>
[API Codebase](https://gitlab.com/adedoyin-emmanuel/caresync-api)
<br/>
[API Documentation](https://documenter.getpostman.com/view/25154969/2sA3BrX9mW)
<br/>
[View our presentation slides](https://docs.google.com/presentation/d/1Uece9jYipLzy3s3BJmKlWk6Zz6TFEfjMU2ONA9g4TXI/edit?usp=sharing)
<br/>
[Watch Demo Video](https://www.youtube.com/watch?v=X4G9UJXlUKA)

For more details on how **Caresync** was built, how it works, and the overall development journey, please read this article [Click here](https://adedoyin.hashnode.dev/caresync-bridging-healthcare-with-technology)

## Video Demo 📹

[![Watch the video](/assets/banner.png)](https://www.youtube.com/watch?v=X4G9UJXlUKA)

## Getting Started

To run this app on your local machine, see the steps below

1. Clone this repository

```bash
git clone https://gitlab.com/adedoyin-emmanuel/caresync
```

2. Rename `.env.example` to `.env.local` You will need to also clone the `API` to make sure everything is connected properly. You will also need `OPEN AI'S API KEY` and `CLAUDE API KEY` to test the healthcare bot and symptoms checker. Head on to <https://platform.openai.com/account> to get your API key. Then place the API KEY to the `NEXT_PUBLIC_OPEN_AI_KEY` variable. Also, head on to <https://console.anthropic.com/settings/keys> to get your CLAUDE API KEY. You will have to create an account if you don't have one. You will also have to verify your phone number so you can get demo credits. After that, you can create an API KEY and paste it into your `.env.local` on the `NEXT_BASE_CLAUDE_AI_KEY` variable.

3. You want to install the necessary application dependencies. So you need to run this command `npm install`. I'm assuming you already have node installed on your machine. If not, head on to [Node Js Website](https://nodejs.org) and install NodeJs on your computer.

4. After installing the necessary dependencies. You will need to clone the API Repository so the backend can be connected to the frontend. So head on to [API Repository](https://gitlab.com/adedoyin-emmanuel/caresync-api)

5. After you're done with the API Repository too, you can run this command to start the app `npm run dev` this will start the app at `http://localhost:3000`

## How Caresync Was Built

Caresync was built using a stack of modern technologies. The front end is powered by React and Next.js, providing a robust user interface. To manage state and data, we adopted Redux and Redux Toolkit, which was a significant learning experience as it was the first time we used them for a large-scale project.

On the backend, we developed a Node.js server that utilizes Express to handle API requests. The core of the application's data management is handled by a combination of Axios for HTTP requests and Redux Toolkit Query for efficient data fetching and management.

During the development process, we encountered a few challenges, including initial setup hurdles with RTK Query and Next.js. However, we persevered, learned valuable lessons, and overcame these obstacles.

## Challenges we ran into

We faced some initial challenges, particularly in configuring and integrating Redux Toolkit Query (RTK Query) with Next.js. The learning curve for this powerful tool was steep, but through perseverance and dedicated problem-solving, we successfully implemented RTK Query into our project. Additionally, handling real-time data and state management in a healthcare context presented unique challenges, which we tackled by enhancing our understanding of Redux and RTK Query.

## Accomplishments that we're proud of

One of the most notable accomplishments is mastering Redux and Redux Toolkit for a significant project. This was the first time we utilized these technologies extensively, and the resulting efficient state management was a major achievement. Furthermore, we integrated a health assistant model based on GPT models into the application, offering personalized healthcare advice and information to users. This was a groundbreaking step for us, marking our first venture into this innovative field.

## What we learned

Throughout the development of Caresync, we learned invaluable lessons. Our proficiency in Redux and RTK Query improved significantly, allowing us to efficiently manage and synchronize application data. Additionally, we expanded our skills by integrating GPT-based health assistant features, opening up new opportunities in the healthcare technology sector.

Incorporating Next.js into our development stack also broadened our knowledge and empowered us to build a large-scale application with improved performance and SEO capabilities. We are proud of the expertise we gained and look forward to applying these skills in future projects.

This write-up encapsulates the journey of Caresync, highlighting the challenges we faced, the accomplishments we achieved, and the knowledge we acquired throughout the development process. We are excited to present this innovative healthcare solution and share our experiences with the world.

## What is next for Caresync?

We plan on taking Caresync to the next level by monetizing it. This way, hospitals can earn from the services they are rendering. Also, we plan on adding a feature that allows hospitals to add their staff and assign them to several appointments. That way, the user knows more about the hospital and who exactly is attending to them. Also, we can take the hospital discovery to the next level. We plan to implement **Google Map** to allow users to find hospitals that are around them in real time. The services Caresync provides can also be added to a hospital Management System, that way, the hospital has all features in one and can reach their patients through Caresync.

For more details on how **Caresync** was built, how it works, and the overall development journey, please read this article [Click here](https://adedoyin.hashnode.dev/caresync-bridging-healthcare-with-technology)
# caresync
