# NasaCommandCenter

https://martinezworldwide.github.io/NasaCommandCenter/


# NASA Command Center

A comprehensive dashboard application that simulates a real NASA command center environment utilizing multiple NASA APIs to provide interactive data visualization and monitoring capabilities.

## Overview

The NASA Command Center is a Next.js application that provides a realistic mission control center interface, giving users access to a wide range of NASA data, including:

- Astronomy Picture of the Day (APOD)
- Near Earth Object (NEO) tracking
- Earth imaging systems (EPIC)
- Mars Rover photos
- Space Weather monitoring
- Earth Observatory Natural Event Tracker (EONET)

## Features

- **Modern Command Center UI**: Sleek, professional interface designed to simulate a real NASA mission control environment
- **Real-time Data**: Pulls live data from NASA's official APIs
- **Interactive Controls**: User-friendly controls for exploring different datasets
- **Responsive Design**: Works on desktop and mobile devices
- **Multiple Data Streams**: Access to 6+ different NASA data sources

## NASA APIs Used

This application leverages the following NASA APIs:

1. **APOD** - Astronomy Picture of the Day
2. **NEO** - Near Earth Object Web Service
3. **EPIC** - Earth Polychromatic Imaging Camera
4. **Mars Rover Photos** - Images from Mars rovers
5. **DONKI** - Space Weather Database
6. **EONET** - Earth Observatory Natural Event Tracker
7. **Earth** - Landsat imagery of Earth

The application supports being embedded in iframes on other websites, thanks to custom Content Security Policy headers configured in the Vercel deployment.

This application can also be deployed to other hosting platforms that support Next.js applications, such as Netlify or AWS Amplify.

## Technologies Used

- **Next.js**: React framework for server-rendered applications with built-in API routes and optimized performance
- **React**: JavaScript library for building user interfaces and interactive components
- **TypeScript**: Strongly typed programming language that builds on JavaScript for improved developer experience
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development
- **Axios**: Promise-based HTTP client for API requests
- **Vercel**: Cloud platform for static sites and serverless functions, providing:
  - Continuous deployment with GitHub integration
  - Global CDN for optimal performance
  - Serverless functions for API endpoints
  - Environment variable management
  - Custom domain support
- **ESLint**: Static code analysis tool for identifying problematic patterns in JavaScript code
- **React Hooks**: Feature that allows using state and other React features without writing classes
- **SWR**: React Hooks library for data fetching, caching, and revalidation
- **NASA APIs**: Multiple public APIs providing space and Earth science data
- **CSS Grid/Flexbox**: Modern CSS layout techniques for responsive design
- **localStorage**: Browser-based storage for persisting user preferences
- **Git/GitHub**: Version control and code collaboration platform

## License

This project is licensed under the MIT License - see the LICENSE file for details.
