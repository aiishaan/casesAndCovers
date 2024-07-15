# CasesAndCovers

CasesAndCovers is an e-commerce store that allows users to create their own phone cases using custom images and purchase them. This project is built with modern web technologies to provide a seamless and engaging user experience.

## Live Demo

Check out the live site: [CasesAndCovers](https://casesandcovers.vercel.app/)

## Tech Stack

- **Frontend**: [Next.js](https://nextjs.org/)
- **Database**: [NeonDB](https://neon.tech/)
- **ORM**: [Prisma](https://www.prisma.io/)
- **Authentication**: [Kinde](https://kinde.com/)
- **Image Uploads**: [Upload Thing](https://uploadthing.com/)
- **Payments**: [Stripe](https://stripe.com/)
- **Email Confirmation**: [Resend](https://resend.com/)

## Features

- **Custom Phone Case Creation**: Users can upload their own images to create personalized phone cases.
- **Secure Authentication**: User authentication is handled with Kinde for a secure and seamless login experience.
- **Fast and Reliable Database**: NeonDB and Prisma are used for efficient data management and retrieval.
- **Image Uploads**: Upload Thing is integrated for handling custom image uploads.
- **Payment Processing**: Stripe is used to process payments securely.
- **Confirmation Email**: Resend is used to send order confirmation emails to the customers.

## Getting Started

### Prerequisites

- Node.js (v14.x or later)
- Yarn or npm
- A NeonDB account
- A Kinde account
- A Stripe account

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/casesandcovers.git
    cd casesandcovers
    ```

2. Install dependencies:

    ```bash
    yarn install
    # or
    npm install
    ```

3. Set up environment variables:

    Create a `.env.local` file in the root of the project and add the following environment variables:

    ```env
    DATABASE_URL=your_neondb_connection_string
    NEXT_PUBLIC_KIND_API_KEY=your_kinde_api_key
    NEXT_PUBLIC_STRIPE_PUBLIC_KEY=your_stripe_public_key
    STRIPE_SECRET_KEY=your_stripe_secret_key
    ```

4. Run database migrations:

    ```bash
    npx prisma migrate dev
    ```

5. Start the development server:

    ```bash
    yarn dev
    # or
    npm run dev
    ```

    The app should now be running on [http://localhost:3000](http://localhost:3000).

## Deployment

This project is deployed using Vercel. To deploy your own version:

1. Connect your repository to Vercel.
2. Set up the necessary environment variables in Vercel dashboard.
3. Deploy your application.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.

## Acknowledgements

- [Next.js](https://nextjs.org/)
- [NeonDB](https://neon.tech/)
- [Prisma](https://www.prisma.io/)
- [Kinde](https://kinde.com/)
- [Upload Thing](https://uploadthing.com/)
- [Stripe](https://stripe.com/)
- [Vercel](https://vercel.com/)

## Contact

For any inquiries or issues, please reach out to [Aishan Irfan](https://aishanirfan.netlify.app/).

---

Happy customizing and shopping at CasesAndCovers!
