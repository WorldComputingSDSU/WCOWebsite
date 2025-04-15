# Welcome to React Router!

A modern, production-ready template for building full-stack React applications using React Router.

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/remix-run/react-router-templates/tree/main/default)

## Features

- 🚀 Server-side rendering
- ⚡️ Hot Module Replacement (HMR)
- 📦 Asset bundling and optimization
- 🔄 Data loading and mutations
- 🔒 TypeScript by default
- 🎉 TailwindCSS for styling
- 📖 [React Router docs](https://reactrouter.com/)

## Getting Started

### Installation

Install the dependencies:

```bash
npm install
```

### Development

Start the development server with HMR:

```bash
npm run dev
```

Your application will be available at `http://localhost:5173`.

## Building for Production

Create a production build:

```bash
npm run build
```

## Deployment

### Docker Deployment

This template includes three Dockerfiles optimized for different package managers:

- `Dockerfile` - for npm
- `Dockerfile.pnpm` - for pnpm
- `Dockerfile.bun` - for bun

To build and run using Docker:

```bash
# For npm
docker build -t my-app .

# For pnpm
docker build -f Dockerfile.pnpm -t my-app .

# For bun
docker build -f Dockerfile.bun -t my-app .

# Run the container
docker run -p 3000:3000 my-app
```

The containerized application can be deployed to any platform that supports Docker, including:

- AWS ECS
- Google Cloud Run
- Azure Container Apps
- Digital Ocean App Platform
- Fly.io
- Railway

### DIY Deployment

If you're familiar with deploying Node applications, the built-in app server is production-ready.

Make sure to deploy the output of `npm run build`

```
├── package.json
├── package-lock.json (or pnpm-lock.yaml, or bun.lockb)
├── build/
│   ├── client/    # Static assets
│   └── server/    # Server-side code
```

## Styling

This template comes with [Tailwind CSS](https://tailwindcss.com/) already configured for a simple default starting experience. You can use whatever CSS framework you prefer.

---

Built with ❤️ using React Router.

# WCOWebsite - A website to display the achievements and future of The World Computing Organization

📌 World Computing Organization - Official Website

Welcome to the official repository for the World Computing Organization (WCO) website. This platform serves as the central hub for our club’s initiatives, including events, projects, sponsorships, and member-exclusive resources.

🌍 Overview

The World Computing Organization is a student-led initiative dedicated to fostering innovation, collaboration, and professional growth in the field of computing. Our mission is to create an inclusive space where students can work on cutting-edge projects, connect with industry professionals, and develop technical skills through hands-on experiences.

This website provides information about our ongoing initiatives and allows registered members to access and contribute to club projects.

🚀 Projects

Our members work on a variety of software and hardware projects, ranging from web and mobile development to AI, cybersecurity, and cloud computing.
• Members can log in to view ongoing projects and contribute.
• Some projects are open-source, while others are reserved for active club members.
• Project updates, documentation, and collaboration tools are integrated into the platform.

🎉 Events

We host hackathons, tech talks, networking sessions, and workshops throughout the year. Stay updated on:
• Upcoming events
• Guest speakers & industry panels
• Hands-on coding workshops
• Annual competitions and challenges

Check out the Events page for the latest schedule and registration details.

🤝 Sponsors

We are grateful for our sponsors, who support our mission by providing funding, mentorship, and resources. If you are interested in sponsoring our organization, please visit the Sponsors page for more details on partnership opportunities.

📢 Join Us

Want to become a member? We welcome students of all experience levels who are passionate about technology and innovation.
• Gain access to exclusive projects and resources
• Network with industry professionals
• Participate in coding challenges, competitions, and workshops

🔒 Member Portal

🔑 Login Required – Members can log in to:
• View and contribute to ongoing projects
• Access exclusive resources
• Collaborate with teams on assignments and deadlines

🎓 Board Members

Meet the leadership team behind WCO. We are dedicated to fostering a strong tech community through mentorship, hands-on projects, and collaboration.

📚 Resources

We provide members with access to valuable learning materials, tutorials, coding challenges, and development tools.

📂 Available Resources:
• Programming guides and cheat sheets
• Past event recordings & slides
• Open-source contributions
• Career & resume-building resources

Check out the Resources page to get started!

👥 Members

Our members-only section includes:
• Private project repositories
• Task management & collaboration tools
• Discussion forums for technical and career advice
• You will need to have authorized access in order to get access to this.

⚡ Contributing

Want to help improve our website? Feel free to fork this repository, submit pull requests, and report issues.

📜 License: MIT
