# Real Estate App

A modern, responsive, and feature-rich real estate application built using **React Native** for mobile and **Next.js** for web. This app allows users to browse, search, and explore real estate listings with a seamless and intuitive experience.

---

## Features

- **Cross-Platform Support**: Mobile app built with React Native and web app powered by Next.js.
- **Real-Time Listings**: Integration with backend APIs for up-to-date property information.
- **Search and Filter**: Advanced search with filters for price, location, property type, and more.
- **Interactive Map View**: Integration with map services for property location visualization.
- **User Authentication**: Secure login and registration using OAuth and JWT.
- **Favorites and Saved Searches**: Users can bookmark properties and save search preferences.
- **Multi-Language Support**: Internationalization (i18n) for broader accessibility.
- **Optimized Performance**: Leveraging server-side rendering (SSR) and code-splitting in Next.js.

---

## Technology Stack

### Frontend:
- **React Native**: For building cross-platform mobile applications.
- **Next.js**: Framework for server-side rendered React applications.
- **Tailwind CSS**: For styling and responsive design.
- **Redux Toolkit**: For state management.
- **React Query**: For data fetching and caching.

### Backend:
- **Node.js** and **Express**: Backend API server (not included in this repo but required).
- **MongoDB** or **PostgreSQL**: Database for storing listings and user data.

### Third-Party Services:
- **Mapbox** or **Google Maps**: For interactive maps.
- **Firebase**: Optional for push notifications and analytics.

---

## Installation and Setup

### Prerequisites
- Node.js v16+ and npm or yarn installed.
- React Native CLI installed for mobile development.
- Access to backend API or set up your own.

### Steps to Run

#### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/real-estate-app.git
cd real-estate-app
```

#### 2. Install Dependencies
```bash
# For mobile (React Native)
cd mobile
npm install

# For web (Next.js)
cd ../web
npm install
```

#### 3. Set Up Environment Variables
Create a `.env` file in both the `mobile` and `web` directories with the following:

```env
# Common Variables
API_URL=your-backend-api-url

# Mobile Specific (React Native)
GOOGLE_MAPS_API_KEY=your-google-maps-api-key

# Web Specific (Next.js)
NEXT_PUBLIC_GOOGLE_MAPS_API_KEY=your-google-maps-api-key
```

#### 4. Run the Applications

**Mobile:**
```bash
cd mobile
npm start
```

**Web:**
```bash
cd web
npm run dev
```

---



## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Open a pull request.

---



## Contact

For questions or support, please contact:
- Name: Maksymilian Mikolajczak
- Email: maksymilianmikolajczakcode@gmail.com

---

## Acknowledgments

Special thanks to the open-source community and the following libraries and frameworks that made this project possible:
- React Native
- Next.js
- Tailwind CSS
- Mapbox / Google Maps
