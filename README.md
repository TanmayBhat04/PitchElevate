# **PitchElevate** 🚀  
*PitchElevate is a dynamic platform designed for entrepreneurs, investors, and startup enthusiasts. It enables users to submit innovative business ideas, and gain visibility within the startup ecosystem. Engage with the community by getting to see works of like-minded professionals, and turning ideas into reality.*  

## **🛠 Tech Stack**  
- **Frontend:** Next.js (React Framework)  
- **Backend & CMS:** Sanity.io
- **Authentication:** NextAuth.js
- **Error Monitoring:** Sentry
- **Styling:** Tailwind CSS
- **Language:** TypeScript  

## **🌟 Features**  
✅ Submit and showcase startup ideas  
✅ Engage with a community of investors and entrepreneurs  
✅ Track trending ideas   
✅ Error tracking and monitoring with Sentry  

## **🔧 Installation**  
To set up PitchElevate locally, follow these steps:  

```bash
# Clone the repository
git clone https://github.com/TanmayBhat04/PitchElevate.git

# Navigate to the project directory
cd PitchElevate

# Install dependencies
npm install  # or yarn install

# Create an .env.local file and configure your environment variables
touch .env.local

# Your .env.local should include the following variables:
# AUTH_SECRET, AUTH_GITHUB_ID, AUTH_GITHUB_SECRET, NEXT_PUBLIC_SANITY_PROJECT_ID, NEXT_PUBLIC_SANITY_DATASET, SANITY_WRITE_TOKEN

# Create an .env.sentry-build-plugin file and store your SENTRY_AUTH_TOKEN variable inside it
touch .env.sentry-build-plugin

# Start the development server
npm run dev  # or yarn dev
```


## **📄 License**  
This project is licensed under the **MIT License** – feel free to modify and distribute it.  
