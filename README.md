<div align="center">
  <h1>⚡️ Todo App</h1>
  <p><strong>A modern, real-time todo application built with React Native & Convex</strong></p>
  
  ![Demo App](/assets/images/Todo-app.png)
  
  <p>
    <img src="https://img.shields.io/badge/React%20Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native" />
    <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" alt="Expo" />
    <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
    <img src="https://img.shields.io/badge/Convex-FF6B6B?style=for-the-badge&logo=convex&logoColor=white" alt="Convex" />
  </p>
</div>

---

## 🧑‍🍳 Features

### 📝 **Todos Management**

- ➕ **Add Tasks** - Create new todos with a simple input
- ✅ **Toggle Completion** - Mark tasks as done/undone with a tap
- 📝 **Edit Tasks** - Double-tap to edit existing todos
- 🗑️ **Delete Tasks** - Swipe or long-press to remove
- 📊 **Progress Tracking** - Visual progress bar shows completion status

### ⚙️ **Settings & Preferences**

- 📈 **Task Statistics** - View total, completed, and remaining tasks
- 🌙 **Dark Mode** - Toggle between light and dark themes
- 🔔 **Notifications** - Enable/disable notifications (UI ready)
- 🔄 **Auto-sync** - Control automatic synchronization (UI ready)
- 🚨 **Danger Zone** - Clear all data with confirmation

### 🔄 **Real-Time Sync**

- **Instant Updates** - Changes reflect immediately across all devices
- **Offline Support** - Works offline, syncs when back online
- **Conflict Resolution** - Automatic handling of concurrent edits
- **Multi-device** - Perfect synchronization across iOS, Android, and web

---

## 🛠️ Tech Stack

| Technology        | Purpose              | Version  |
| ----------------- | -------------------- | -------- |
| **React Native**  | Mobile framework     | Latest   |
| **Expo**          | Development platform | ~53.0.17 |
| **TypeScript**    | Type safety          | Latest   |
| **Convex**        | Real-time backend    | ^1.25.2  |
| **Expo Router**   | Navigation           | ~5.1.3   |
| **Async Storage** | Local storage        | ^2.2.0   |

---

## 📁 Project Structure

```
rn-todo-app-master/
├── app/                    # App screens and navigation
│   ├── (tabs)/            # Tab-based navigation
│   │   ├── index.tsx      # Main todos screen
│   │   └── settings.tsx   # Settings screen
│   └── _layout.tsx        # Root layout with Convex provider
├── components/            # Reusable UI components
│   ├── TodoInput.tsx      # Add new todo input
│   ├── ProgressStats.tsx  # Progress bar and stats
│   ├── EmptyState.tsx     # Empty state illustration
│   └── ...
├── convex/                # Backend functions and schema
│   ├── todos.ts          # Todo CRUD operations
│   ├── schema.ts         # Database schema
│   └── _generated/       # Auto-generated Convex files
├── hooks/                 # Custom React hooks
│   └── useTheme.tsx      # Theme management
├── assets/               # Images, fonts, and styles
└── .env                  # Environment configuration
```

---

### Convex Backend

Convex backend includes:

- **Database Schema** (`convex/schema.ts`) - Defines todo data structure
- **API Functions** (`convex/todos.ts`) - CRUD operations for todos
- **Real-time Subscriptions** - Automatic updates across clients
- **Authentication Ready** - Easy to add user auth when needed

---

## 📱 Platform Support

| Platform    | Status          | Notes                       |
| ----------- | --------------- | --------------------------- |
| **iOS**     | ✅ Supported    | Native iOS app via Expo     |
| **Android** | ✅ Supported    | Native Android app via Expo |
| **Web**     | ✅ Supported    | PWA-ready web app           |
| **Desktop** | 🔄 Experimental | Via Expo Desktop (beta)     |

---

## 📚 Learning Resources

- **React Native**: [Official Documentation](https://reactnative.dev/)
- **Expo**: [Expo Documentation](https://docs.expo.dev/)
- **Convex**: [Convex Documentation](https://docs.convex.dev/)
- **TypeScript**: [TypeScript Handbook](https://www.typescriptlang.org/docs/)

---

<div align="center">
  <p>Made with ❤️ using React Native & Convex</p>
  <p>⭐ Star this repo if you found it helpful!</p>
</div>
