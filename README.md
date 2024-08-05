# WP-CLI Tool

![Node.js](https://img.shields.io/badge/node.js-%23339933?style=for-the-badge&logo=node.js&logoColor=white) ![License](https://img.shields.io/github/license/yourusername/wp-cli-tool?style=for-the-badge) ![npm](https://img.shields.io/npm/v/wp-cli-tool?style=for-the-badge)

## Overview

**WP-CLI Tool** is a powerful Command Line Interface (CLI) tool designed to simplify the management of local WordPress sites running on XAMPP. This tool provides commands to automate tasks such as creating, listing, starting, stopping, backing up, and deleting WordPress sites with ease.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
  - [Create a WordPress Site](#create-a-wordpress-site)
  - [List Existing WordPress Sites](#list-existing-wordpress-sites)
  - [Start XAMPP Services](#start-xampp-services)
  - [Stop XAMPP Services](#stop-xampp-services)
  - [Backup a WordPress Site](#backup-a-wordpress-site)
  - [Delete a WordPress Site](#delete-a-wordpress-site)
- [Directory Structure](#directory-structure)
- [Customization](#customization)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Create WordPress Sites:** Quickly set up a new WordPress site by downloading WordPress, setting up a database, and configuring the site.
- **List Sites:** View all WordPress sites present in your XAMPP `htdocs` directory.
- **Start/Stop XAMPP Services:** Manage XAMPP services directly from the CLI.
- **Backup Sites:** Backup a WordPress site's database with ease.
- **Delete Sites:** Completely remove a WordPress site, including files and database.
- **User-Friendly Prompts:** Interactive prompts make managing sites straightforward and intuitive.

## Prerequisites

Before using this CLI tool, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (version 16 or higher)
- [npm](https://www.npmjs.com/get-npm) (Node.js package manager)
- [XAMPP](https://www.apachefriends.org/index.html)
- [MySQL](https://www.mysql.com/) (installed with XAMPP)
- [WP-CLI](https://wp-cli.org/) (WordPress CLI)

## Installation

To install and set up the WP-CLI Tool, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/wp-cli-tool.git
   cd wp-cli-tool
   
2. **Install Dependencies::**

   ```bash
   npm install
   
3. **Link the CLI Tool Globally:::**

   ```bash
   npm link

## Usage
This section provides detailed instructions on how to use each command available in the WP-CLI Tool.

  **Create a WordPress Site:**

   ```bash
   wpcli create
   
 **Start XAMPP Services**

   ```bash
   wpcli start
   
3. **Stop XAMPP Services**

   ```bash
   wpcli stop


