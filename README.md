# StockEZ - Storage and File Sharing Platform

[`StockEZ`](https://stockez.vercel.app/) is a modern cloud storage management platform designed for seamless file organization and sharing. Inspired by solutions like Google Drive, Dropbox, and OneDrive, StockEZ provides a scalable, high-performance experience with dynamic dashboards, multi-file uploads, and secure sharing capabilities.

![Screenshot 2024-11-30 at 1 00 04 PM](https://github.com/user-attachments/assets/57779706-b476-4e6c-bd10-16705c8457df)

## Table of Contents  
1. Introduction  
2. Tech Stack  
3. Features  
4. Quick Start  

## Introduction  

[`StockEZ`](https://stockez.vercel.app/) is a robust storage management and file-sharing platform that allows users to effortlessly upload, manage, and share files. Built using **Next.js 15** and the **Appwrite Node SDK**, StockEZ ensures a reliable and secure experience for file management.  

![Screenshot 2024-11-30 at 2 06 42 PM](https://github.com/user-attachments/assets/1802a782-6f2f-4d28-882b-ff4fd1bdbe3a)

## Tech Stack  

- Figma - for Design.  
- React.js - 19 for the user interface.
- Next.js 15 - for server-side rendering and API routes. 
- Appwrite - for backend features like authentication and storage.
- TailwindCSS - for styling.
- ShadCN UI - for styling.
- TypeScript - for type-safe development.
- Chart.js - for creating visualizations on the dashboard.

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Features  

### 1. User Authentication  
Secure signup, login, and logout functionality powered by **Appwrite Authentication**.

![Screenshot 2024-11-30 at 2 06 42 PM](https://github.com/user-attachments/assets/7f9af986-7bb5-495b-b0f9-f8dcd2158fba)

### 2. File Uploads  
Upload various file types, including documents, images, videos, and audio files. 

![Screenshot 2024-11-30 at 2 10 39 PM](https://github.com/user-attachments/assets/162ca913-6caa-45ec-9ece-c053e916b83b)

### 3. File Management  
- Browse, view, rename, and delete uploaded files stored in **Appwrite Storage**.  
- Open files in a new tab for detailed viewing.  

![Screenshot 2024-11-30 at 1 00 04 PM](https://github.com/user-attachments/assets/ade6f68c-12f1-49b7-9d05-def8e2153bef)

### 4. File Downloading  
Download files to your device for instant offline access. 

![Screenshot 2024-11-30 at 2 11 51 PM](https://github.com/user-attachments/assets/67c61463-1815-4d60-a4e2-6e9b62ccd0e6)

### 5. File Sharing  
Share files easily with others, enabling efficient collaboration.

![Screenshot 2024-11-30 at 1 00 22 PM](https://github.com/user-attachments/assets/4ba6e586-b0c0-4e4d-b5af-106c9358a510)

### 6. Dynamic Dashboard  
A visually informative dashboard that provides:  
- An overview of total and consumed storage.  
- Summaries of files grouped by type.  
- Recent uploads displayed prominently.

![Screenshot 2024-11-30 at 2 13 51 PM](https://github.com/user-attachments/assets/ca6be2bf-f65a-4add-9325-35da04d77335)

### 7. Global Search  
Quickly locate files and shared content across the platform.

![Screenshot 2024-11-30 at 12 59 25 PM](https://github.com/user-attachments/assets/e1d67238-afba-4a3b-bc48-22bf96f71949)

### 8. Sorting Options  
Organize files by date, name, or size for easier access.  

![Screenshot 2024-11-30 at 2 15 04 PM](https://github.com/user-attachments/assets/70fd6e63-be8d-4c22-9971-d3667cbddb06)

### 9. Modern UI/UX  
A responsive, minimalist design ensures usability across all devices.

![WhatsApp Image 2024-11-30 at 14 38 40](https://github.com/user-attachments/assets/c24931b5-97a7-46d9-9914-4a90ba317927)

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Quick Start  

### Prerequisites  
Ensure the following are installed:  
- **Git**  
- **Node.js**  
- **npm**  

### Setup Steps  

1. Clone the Repository  
   ```bash  
   git clone https://github.com/your-username/stockez.git  
   cd stockez  
   ```  

2. Install Dependencies  
   ```bash  
   npm install  
   ```  

3. Configure Environment Variables  
   Create a `.env.local` file in the project root and add the following content:  
   ```env  
   NEXT_PUBLIC_APPWRITE_ENDPOINT="https://cloud.appwrite.io/v1"  
   NEXT_PUBLIC_APPWRITE_PROJECT=""  
   NEXT_PUBLIC_APPWRITE_DATABASE=""  
   NEXT_PUBLIC_APPWRITE_USERS_COLLECTION=""  
   NEXT_PUBLIC_APPWRITE_FILES_COLLECTION=""  
   NEXT_PUBLIC_APPWRITE_BUCKET=""  
   NEXT_APPWRITE_KEY=""  
   ```  
   Replace the placeholders with your **Appwrite** credentials.  

4. Run the Development Server  
   ```bash  
   npm run dev  
   ```  
   Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.  

---

## Contribution  

Contributions are welcome! Feel free to fork the repository, submit issues, or create pull requests to improve [`StockEZ`](https://stockez.vercel.app/).

---

## Contact  

For inquiries or feedback, please contact themihirmathur@gmail.com.  

---  

Transform your file management experience with [`StockEZ`](https://stockez.vercel.app/).

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>
