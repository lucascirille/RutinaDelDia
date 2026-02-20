# 📅 Rutina del Día

A visual routine management tool designed to provide structure and predictability. This project aims to reduce anxiety through clear, visual scheduling.

## ✨ Technologies
### Cient
- `React`
- `TypeScript`
### Server
- `.NET` (Famework 8.0)
- `Entity Framework Core` (ORM)
- `Postgres` (DBMS)
### Tool for design
- `Figma`

## 🚀 Features

- **Isolated Accounts**: Children cannot change their role because it requires a code known only by the guardian.
- **Role-Based Interfaces**: The child interface focuses on completing routines, while the guardian interface is designed for managing them.
- **AI-Generated Routines**: You can create a routine simply by asking.
- **Telegram Notifications**: Both the guardian and the person with neurodiverse needs receive notifications. The latter receives a reminder for an active routine, while the guardian is notified of a cancelled routine. These are sent via Telegram.
- **Visual Timeline**: A simplified view of daily activities to help users navigate their day.
- **Customized Profiles**: The Users created can customize options for a unique experience
- **High-Contrast Design**: Optimized for readability and focus.
- **Task Management**: Easy-to-follow steps for daily habits.
  
## 📍 The Process

Our mission was to create a digital bridge for people with neurodiverse needs. Built under Inclusive Design principles, this app simplifies daily routines for individuals with ASD. By adhering standards like**WCAG guidelines**, we ensured the UI is intuitive and distraction-free. The platform connects users with their guardians in real-time, fostering independence for the user and peace of mind for the caregiver.

## 🚦 Running the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/lucascirille/RutinaDelDia.git
   cd RutinaDelDia
2. **Install dependencies**
   from the client:
   ```bash
   cd rutinadeldiacliente/
   npm install
   ```
   from the server:
   ```bash
   cd rutinadeldiaservidor/rutinadeldiaservidor/rutinadeldiaservidor/
   dotnet restore
   dotnet tool install --global dotnet-ef
   dotnet ef database update
   dotnet run
   ```
4. **Launch the development server**
   ```bash
   npm run dev

## 🎨 Design Reference
The UI/UX was originally designed as a mobile experience. You can view the full mockup here:
[View Figma Mockup](https://www.figma.com/design/vpIjAw2QYoxmp3BulTLTga/mock-up-app-TEA?node-id=0-1&t=9Y2DrmbYfu65biCV-1)

---

## 📝 Licencia

Distribuido bajo la licencia MIT.

<p align="center">
  Hecho con ❤️ por el equipo de RutinaDelDia (Pedro, Joaco, Lucas, Feli, Valen)
</p>
