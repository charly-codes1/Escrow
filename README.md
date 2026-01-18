# ESCROW

A cross platform mobile application that supports wallet and escrow transactions built with React Native.

## Overview

Escrow allow users manage thier wallet and escrow transactions using an intuitive, mobile-friendly interface.
This project showcases my ability to convert Figma designs into clean, responsive mobile applications.

## 🎨 Features

- Clean user Interface
- User feedback
- State management with Redux
- Cross platform
- Responsive acrross devices
- Responsive on landscape and portrait orientation

## 🧠 Tech Stack

- React Native
- Redux - State management
- Github - deployment

## 🖼️ Screenshots

![App Screenshot](/assets/images/escrow.png)

## Run Locally

Clone the project

```bash
  git clone https://github.com/charly-codes1/Escrow.git
```

Go to the project directory

```bash
  cd Escrow
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```

## 📁 Folder Structure

Escrow/
│
app/
┣ (auth)/
│ ┣ \_layout.tsx
│ ┣ Onboarding.tsx
│ ┣ Login.tsx
│ ┣ Signup.tsx
│ ┣ Verify.tsx
│ ┗ AllSet.tsx
│
┣ (tabs)/
│ ┣ \_layout.tsx
│ ┣ Transactions.tsx
│ ┣ Settings.tsx
│ ┗ home/
│ ┣ \_layout.tsx
│ ┣ index.tsx
│ ┣ NewEscrow.tsx
│ ┣ Transactions.tsx
│ ┗ Escrow/
│ ┣ \_layout.tsx
│ ┣ index.tsx
│ ┗ Summary.tsx
│
┣ \_layout.tsx ← Root layout (handles splash/loading + route groups)
┗ index.tsx ← Default route (redirects to onboarding or home)

components/
┣ Button.tsx
┣ Input.tsx
┣ Header.tsx
┗ ...

data/
┗ UI.tsx ← Can contain reusable UI constants, lists, etc.

lib/
┣ index.tsx
┗ types/
┗ index.ts

commonStyles.ts ← Global style constants

## 🌟 Key Takeaways

- Improved my Mobile application navigation knowledge

- Enhanced my design-to-code workflow from Figma to mobile applications
- Improved my understanding of state management with Redux.
- Gained the experience of building FinTech applications

## 🚀 About Me

Oluwaseun Bamgbala: A mobile and web Frontend Engineer. I help founders, startups, enterprise and business owners build the ideal websites that Attract Users, Keep Users, and Generate Sales

🚀 Looking for a frontend developer for your next project? Let's talk!

[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://charly-codes1.github.io/Portfolio/)
[![vercel](https://img.shields.io/badge/vercel-000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com/charly-codes1)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/oluwaseun-bamgbala-b9a134233)
