

# WanderNest

![WanderNest Logo](./public/images/logo2.png) <!-- If you have a logo, replace the link -->

WanderNest  allows users to discover, book, and list unique accommodations around the world. Whether you're a traveler looking for a cozy home away from home or a host looking to share your space, WanderNest has you covered.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)


## Demo

Below is a video showing website features take a look yourself- [Demo video](https://www.youtube.com/watch?v=lJRM428MdTU) <!-- Replace with a link to your demo -->

## Features

The key features of my project:

- User authentication and registration(with google and github)
- Search and filter properties based on various criteria(location,type,time )
- Property listing with detailed information and photos
- Booking and reservation management
- trips page to see your past and upcoming trips
- reservtion page to cancel and see reservation
- lisintgs page to see your listed houses you can remove them
- full responsiveness
- image upload using cloudinary
- Guest and owner reservatin cancellation
- favourites system
- fetch data in server react components by directly accessing database

## Getting Started

Provide instructions on how to set up and run your project locally. Include any prerequisites and installation steps.

### Prerequisites

List any software or libraries that users need to have installed before they can use your project.

- Next.js
- MongoDB
- prisma, cloudinary to store photos.


### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/suyash-29/WanderNest
   ```

2. Change to the project directory:

   ```bash
   cd WanderNest
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Set up environment variables by creating a `.env` file and adding the necessary configurations (database URL, API keys, etc.):

   ```plaintext
   DATABASE_URL=
   GOOGLE_CLIENT_ID=
   GOOGLE_CLIENT_SECRET=
   GITHUB_ID=
   GITHUB_SECRET=
   NEXTAUTH_SECRET=
   ```

5. Start the application:

   ```bash
   npm run dev
   ```

6. Open your web browser and navigate to `http://localhost:3000` to access WanderNest.






