# 🌐 VGNet Lab Website

## Vikendrit Gyaan Network (VGNet) Lab

This repository contains the **official website for the VGNet Lab**, focused on research in **Distributed Systems, Machine Learning, and Networking**.

🔗 Link: https://faculty.iisertvm.ac.in/vgnet/#

---

## 📌 Status

**This project is actively used and maintained.**

* The website dynamically fetches and displays research data
* Integrated with a backend (Supabase) for real-time updates
* Designed as a lightweight, framework-free web application

---

## 📖 About This Project

The website is built as a **multi-page static site with dynamic data integration**, showcasing:

* 📄 Publications (Journal, Conference, Patents)
* 📰 Latest News & Updates
* 🧪 Research Projects (Ongoing & Completed)
* 🤝 Collaborations (Industrial, Government, Academic)
* 👥 Team Members
* 🖼️ Gallery
* 💰 Funding & Sponsors
* 🎯 Vision, Mission, and Objectives of the Lab

---

## 🚀 Features

* Dynamic content rendering using Supabase
* Pagination system for publications
* Category-based data organization
* Real-time updates without page reloads
* Custom animated canvas backgrounds
* Modular and reusable JavaScript functions
* Graceful handling of empty datasets

---

## 🛠 Tech Stack

* **Frontend:**
  * HTML5
  * CSS3
  * Vanilla JavaScript (ES Modules)

* **Backend / Database:**
  * Supabase

* **Graphics:**
  * HTML5 Canvas API

---

## 🧩 Core Functionalities

### 📄 Publications
* Categorized into:
  * Journal Papers
  * Conference Papers
  * Patents
* Sorted by latest date
* Paginated view

### 🧪 Projects
* Displays:
  * Ongoing projects
  * Completed projects
* Includes:
  * Description
  * Sponsor details
  * Images

### 📰 Info Section
* Highlights:
  * Latest patent
  * Recent news
  * Recently completed project

### 👥 Team Section
* Dynamically grouped members
* Removes empty categories automatically

### 🤝 Collaborations
* Organized into:
  * Industrial
  * Government
  * Academic

### 🖼️ Gallery
* Image-based layout with captions

### 💰 Sponsors
* Separate display for:
  * Government funding
  * Industrial collaborators

### 🎨 Canvas Animations
* Particle-based animated backgrounds
* Responsive and interactive visuals

---

## 🔌 Supabase Integration

The project uses Supabase to manage dynamic content from the following tables:

* `publication`
* `projects`
* `news`
* `collabs`
* `team`
* `gallery`
* `fundings`

---

## ⚙️ Setup & Usage

1. Clone the repository:

```bash
git clone https://github.com/NeelayK/VGnetLabWebsite.git
cd VGnetLabWebsite
