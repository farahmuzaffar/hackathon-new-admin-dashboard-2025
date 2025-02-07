# Hackathon Figma Template

This is a Next.js project template designed for hackathons, featuring a variety of modern tools and libraries to help you build your project quickly and efficiently.

## Features

- **Next.js**: A React framework for production-grade applications.
- **Clerk**: Authentication and user management.
- **Radix UI**: A set of low-level, unstyled, and accessible UI components.
- **Tailwind CSS**: A utility-first CSS framework for rapid UI development.
- **React Hook Form**: Flexible and performant forms with easy validation.
- **Zod**: Type-safe schema validation.
- **Sanity**: Headless CMS for managing content.
- **Recharts**: A composable charting library built on React.
- **Tailwind Merge**: Utility to merge Tailwind CSS classes.
- **Tailwind CSS Animate**: Prebuilt animations for Tailwind CSS.
- **Lucide React**: Beautiful and consistent icons.
- **Sonner**: Lightweight toast notifications.
- **Styled Components**: CSS-in-JS for styling React components.

## Getting Started

### Prerequisites

- Node.js (version 20 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/hackathon-figma-template.git

   Navigate to the project directory:

cd hackathon-figma-template
Install dependencies:

npm install
or
yarn install
Running the Project
Start the development server:

npm run dev
or


yarn dev
Open your browser and navigate to http://localhost:3000.

Building the Project
Build the project for production:

npm run build
or


yarn build
Start the production server:

npm run start
or


yarn start
Linting
Run the linter to check for code issues:


npm run lint
or


yarn lint
Dependencies
Core Dependencies
Next.js: ^15.1.6

React: ^19.0.0

React DOM: ^19.0.0

Clerk: ^6.10.3

Radix UI: Various components

Tailwind CSS: ^3.4.1

React Hook Form: ^7.54.2

Zod: ^3.24.1

Sanity: ^3.70.0

Recharts: ^2.15.1

Lucide React: ^0.468.0

Sonner: ^1.7.3

Styled Components: ^6.1.14

Dev Dependencies
TypeScript: ^5

ESLint: ^8

PostCSS: ^8

Tailwind CSS: ^3.4.1

Contributing
Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or bug fixes.

License
This project is licensed under the MIT License. See the LICENSE file for details.

## Environment Variables

To run this project, you will need to set up the following environment variables:

- `NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY`: Your Clerk publishable key.
- `CLERK_SECRET_KEY`: Your Clerk secret key.
- `SANITY_PROJECT_ID`: Your Sanity project ID.
- `SANITY_DATASET`: Your Sanity dataset name.
- `SANITY_API_TOKEN`: Your Sanity API token.

Create a `.env.local` file in the root directory and add the variables above.
## Project Structure
/components # Reusable UI components
/lib # Utility functions and helpers
/pages # Next.js pages
/styles # Global styles and Tailwind configuration
/sanity # Sanity schema and queries
/public # Static assets (images, fonts, etc.)


## Deployment

This project can be deployed to any platform that supports Next.js, such as Vercel, Netlify, or AWS.

### Vercel Deployment
1. Install the Vercel CLI:
   ```bash
   npm install -g vercel
Deploy the project:
vercel

## Roadmap

- [ ] Add user authentication flows.
- [ ] Integrate more Radix UI components.
- [ ] Improve mobile responsiveness.
- [ ] Add unit and integration tests.


## Acknowledgments

- [Next.js Documentation](https://nextjs.org/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Radix UI Documentation](https://www.radix-ui.com/docs)
- [Clerk Documentation](https://clerk.com/docs)

## Support

If you encounter any issues or have questions, please open an issue on the [GitHub repository](https://github.com/your-username/hackathon-figma-template/issues).
