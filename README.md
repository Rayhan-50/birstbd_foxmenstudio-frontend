# BIRSTBD Frontend - Bangladesh Institute for Research and Statistical Training

**Live Website:** [https://www.birstbd.com/](https://www.birstbd.com/)

Welcome to the frontend repository of the **Bangladesh Institute for Research and Statistical Training (BIRSTBD)**. This platform is designed to empower research and statistical skills in Bangladesh by offering expert mentorship, AI-powered tools, and career readiness training for students and professionals.

## 🚀 Features

- **Modern & Interactive UI/UX:** Stunning and responsive user interface built with Tailwind CSS, Framer Motion, and GSAP animations.
- **Comprehensive Course Management:** Explore, view details, and securely purchase training courses (integrated with Stripe payment gateway).
- **Authentication & Security:** Secure login and registration using Firebase Authentication.
- **Research & Publications:** Dedicated sections for research guidance, knowledge center, and publications.
- **Dynamic Content & Content Management:** News & events, blog, and gallery to keep users updated and engaged.
- **AI Tools Integration:** Built-in AI tools support to assist in statistical analysis and research work.
- **Form validation:** Complex form validation and management handled efficiently via React Hook Form.

## 🛠️ Technology Stack

- **Framework:** [React 19](https://react.dev/) with [Vite](https://vitejs.dev/)
- **Routing:** [React Router v7](https://reactrouter.com/)
- **Styling:** [Tailwind CSS v4](https://tailwindcss.com/)
- **Animations:** [Framer Motion](https://www.framer.com/motion/) & [GSAP](https://gsap.com/)
- **State/Data Management:** [@tanstack/react-query](https://tanstack.com/query/latest) & [Axios](https://axios-http.com/)
- **Forms & Validation:** [React Hook Form](https://react-hook-form.com/)
- **Authentication:** [Firebase](https://firebase.google.com/)
- **Payments:** [Stripe React](https://stripe.com/docs/stripe-js/react)
- **UI Components & Alerts:** [SweetAlert2](https://sweetalert2.github.io/), [React Toastify](https://fkhadra.github.io/react-toastify/), [Lucide React](https://lucide.dev/), [React Icons](https://react-icons.github.io/react-icons/)

## 📦 Installation & Setup

Follow these steps to run the application locally.

### Prerequisites

Ensure you have the following installed on your local machine:
- Node.js (v18 or higher recommended)
- Git

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/bristbd_foxmenstudio_frontend.git
   cd bristbd_foxmenstudio_frontend
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Environment Variables:**
   Create a `.env.local` file in the root directory and configure the necessary environment variables for Firebase, Stripe, and the backend API URL.
   ```env
   VITE_API_BASE_URL=your_backend_url
   VITE_FIREBASE_API_KEY=your_firebase_api_key
   VITE_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
   VITE_FIREBASE_PROJECT_ID=your_firebase_project_id
   VITE_FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
   VITE_FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
   VITE_FIREBASE_APP_ID=your_firebase_app_id
   VITE_STRIPE_PUBLIC_KEY=your_stripe_public_key
   ```

4. **Run the development server:**
   ```bash
   npm run dev
   ```
   The application will be running locally at `http://localhost:5173`.

## 📂 Project Structure

- `src/components/`: Reusable UI components organized by feature (Hero, Shared, AboutUs, Research, etc.).
- `src/pages/`: Core application pages (Home, Courses, Dashboard, Blog, Research, Settings, etc.).
- `src/hooks/`: Custom React hooks for shared logic (`useAxiosSecure`, etc.).
- `src/Routes/`: Custom routing logic and protected route setups.
- `src/firebase/`: Firebase configuration and utilities.
- `src/assets/`: Static assets such as images and branding materials.

## 🤝 Contributing

We welcome contributions to improve the BIRSTBD platform! Please submit a pull request or open an issue to discuss proposed changes.

## 👨‍💻 Author

**Rayhan Ahmed**
- LinkedIn: [Rayhan Ahmed](https://www.linkedin.com/in/rayhan-ahmed-0ab5aa33a/)
- GitHub: [Rayhan-50](https://github.com/Rayhan-50)
- Email: [rayhanahmed.nstu@gmail.com](mailto:rayhanahmed.nstu@gmail.com)
