# ServicePlus

ServicePlus is a Next.js-based service listing and booking platform. It allows users to search for businesses, view details, and book services easily.

## 🚀 Features

- **Modern UI** with Tailwind CSS
- **Dynamic Routing** for business details
- **Booking Management** for users
- **Search Functionality** with category filters
- **Authentication** with NextAuth.js
- **API Integration** for service data

## 📂 Project Structure

```
ServicePlus/
├── app/                 # Main application components & pages
│   ├── (routes)/        # Page routes
│   │   ├── details/     # Business details pages
│   │   ├── mybooking/   # Booking history
│   │   ├── search/      # Search functionality
│   ├── _components/     # Shared components
│   ├── _services/       # API services
│   ├── api/auth/        # Authentication API
├── components/ui/       # UI elements (buttons, dialogs, etc.)
├── public/              # Static assets
├── lib/utils.js         # Utility functions
├── package.json         # Dependencies
├── next.config.mjs      # Next.js configuration
├── tailwind.config.js   # Tailwind CSS configuration
└── README.md            # Project documentation
```

## 📦 Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/shashican17/ServicePlus.git
   cd ServicePlus
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Run the development server:**
   ```sh
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🔧 Configuration

- **Authentication:** Update `api/auth/[...nextauth]/route.js` for authentication settings.
- **API Endpoints:** Modify `app/_services/GlobalApi.js` to connect with external services.

## 📸 Screenshots

Add screenshots of your application here:

![Image](https://github.com/user-attachments/assets/4ab478ab-2fbb-4839-b947-bc3492c47356)

![Image](https://github.com/user-attachments/assets/82631a34-2b0e-48a9-8785-50cf1038aaa9)

![Image](https://github.com/user-attachments/assets/cd759f4e-f3d1-44ba-9592-a9ff552ab66b)

![Image](https://github.com/user-attachments/assets/eda81ae3-f113-48af-bdf1-b471fb80fb97)

![Image](https://github.com/user-attachments/assets/268ea7df-89e0-4ef8-ac11-31990e95e4a4)

![Image](https://github.com/user-attachments/assets/1fa57a0b-a6da-4510-b0e0-63da8b6459b7)

![Image](https://github.com/user-attachments/assets/c9eaf1db-3c4c-4b14-b83d-a134d41dc391)

![Image](https://github.com/user-attachments/assets/6cd07011-97a8-4224-aa11-a3cfa8f42492)

![Image](https://github.com/user-attachments/assets/557caf2f-9d7d-4b80-a5c0-c113fc04e99c)

## 🛠️ Technologies Used

- **Next.js** – React framework for SSR and static generation
- **Tailwind CSS** – Utility-first styling
- **NextAuth.js** – Authentication handling
- **PostCSS** – CSS transformations


