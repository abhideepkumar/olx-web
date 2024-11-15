# S-OLX

## Project Overview

**S-OLX** is a web-based application tailored specifically for college students to buy, sell, and exchange items within their college communities. Inspired by platforms like OLX, it offers a secure and user-friendly experience by verifying users through their college email addresses. The platform enables students to list a variety of items, such as textbooks, electronics, furniture, and bikes, and also includes a community page for discussions and reviews.

## Key Features

- **Marketplace for Products**:  
  Create and browse listings for various items, including textbooks, furniture, electronics, vehicles, and more.
- **College Email Verification**:  
  Users are verified through their academic email, ensuring a safe and genuine user base.
- **Community Page**:  
  Engage with peers through a community feed. Participate in discussions, post reviews, share referrals, and connect through alumni talks.
- **Wishlist Functionality**:  
  Save products to view or discuss later.
- **Product Review System**:  
  Leave comments and feedback on listed items to help others make informed decisions.

## Target Audience

**S-OLX** is designed exclusively for college students. Whether you're buying a used textbook, selling a bike, or exchanging furniture, our platform is here to serve your needs in a trusted environment.

## Market Analysis

The current market is dominated by general platforms like OLX and Facebook Marketplace, which do not cater specifically to the needs of college students. **S-OLX** addresses this gap by leveraging the trust and familiarity of college communities. Our unique focus on security and community engagement makes us the go-to platform for student transactions.

## Unique Selling Proposition (USP)

- **Exclusive to College Students**:  
  User verification through college email ensures a safe and exclusive environment.
- **Community Engagement**:  
  The community page fosters interaction and trust, making it more than just a marketplace.

## Technological Stack

- **Front-end**: [Next.js](https://nextjs.org/) for a responsive and dynamic user interface.
- **Back-end**: [Node.js](https://nodejs.org/) with [Express.js](https://expressjs.com/) for robust server-side logic.
- **Database**: [MongoDB](https://www.mongodb.com/) for efficient data management.
- **Authentication**: [Google OAuth](https://developers.google.com/identity) for secure user authentication.
- **Hosting**: [AWS](https://aws.amazon.com/) / [Azure](https://azure.microsoft.com/) for scalable cloud hosting.
- **Media Storage**: [Cloudinary](https://cloudinary.com/) / [Amazon S3](https://aws.amazon.com/s3/) for efficient media management.

## Future Opportunities

- **Expansion to Other Institutions**:  
  Include trade schools and other educational institutions to broaden our reach.
- **Mobile Applications**:  
  Develop dedicated iOS and Android apps for seamless access.
- **Integrated Payments**:  
  Introduce secure in-platform payment options for hassle-free transactions.
- **Rentals and Services**:  
  Expand the platform to support item rentals and other student-focused services.

## Getting Started

### Prerequisites

To run this project locally, ensure you have the following installed:

- **Node.js** (v16 or higher)
- **MongoDB** (local or cloud-based instance)
- **Git**

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/S-OLX.git
   ```
2. Navigate to the project directory:
   ```bash
   cd S-OLX
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Set up environment variables:
   Create a `.env` file in the root directory and add the following:

   ```env
   PORT=8000
   MONGODB_URI=your_mongo_connection_string
   ACCESS_TOKEN_SECRET= your token
   ACCESS_TOKEN_EXPIRY=1d
   REFRESH_TOKEN_SECRET= your token
   REFRESH_TOKEN_EXPIRY=10d
   CLOUDINARY_API_NAME=
   CLOUDINARY_API_KEY=
   CLOUDINARY_API_SECRET=your api
   CLOUDINARY_DEFAULT_IMAGE=https://res.cloudinary.com/djcm8wdeu/image/upload/v1731230785/graduation_dug5zn.png
   ```

5. Start the development server:

   ```bash
   npm run dev
   ```

6. Open your browser and navigate to `http://localhost:3000`.

### Scripts

- `npm run dev`: Start the development server.
- `npm run build`: Build the project for production.
- `npm start`: Start the production server.

## Contributing

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to your branch:
   ```bash
   git push origin main
   ```
5. Open a pull request.

Let's make student life easier! 🚀
