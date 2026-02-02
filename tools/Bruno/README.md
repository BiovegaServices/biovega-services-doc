# Bruno API Collection

This repository contains a [Bruno](https://www.usebruno.com/) collection for testing and exploring our APIs.  
This guide walks you through everything — from installing tools to sending your first request.

---

## Table of Contents
- [Bruno API Collection](#bruno-api-collection)
  - [Table of Contents](#table-of-contents)
  - [Step 1: Install Bruno](#step-1-install-bruno)
  - [Step 2: Install Git](#step-2-install-git)
  - [Step 3: Copy Git Url](#step-3-copy-git-url)
  - [Step 4: Clone (Download) the Repository](#step-4-clone-download-the-repository)
  - [Step 5: Open the Collection in Bruno](#step-5-open-the-collection-in-bruno)

---

## Step 1: Install Bruno

1. Go to https://www.usebruno.com/downloads  
2. Download the version for your OS (Windows, macOS, Linux).  
3. Install with the default options.  
4. Launch Bruno once to confirm it opens.

---

## Step 2: Install Git

**Windows**
1. Download from https://git-scm.com/download/win  
2. Run the installer and keep default options.  
3. Open **Git Bash** (installed with Git).


**macOS**

Open **Terminal** and run:

```bash
xcode-select --install

```
**Linux**

Install via your package manager:

```bash
sudo apt install git    # Ubuntu/Debian
sudo dnf install git    # Fedora
```
Verify Git is installed:

```bash
git --version
```

## Step 3: Copy Git Url

1. Open this repository on GitHub in your browser.
2. Click the green “Code” button near the top-right.
3. Make sure HTTPS is selected.
4. Copy the URL that looks like:
```bash
https://github.com/<your-org>/<your-repo>.git
```

## Step 4: Clone (Download) the Repository

1. Open Git Bash (Windows) or Terminal (macOS/Linux).
2. Change to the folder where you want the project, for example:
```bash
cd ~/Documents
```
3. Clone the repo (paste your URL from Step 3):
```bash
git clone https://github.com/<your-org>/<your-repo>.git
```
4. Enter the folder:
```bash
cd <your-repo>
```

## Step 5: Open the Collection in Bruno

1. Launch Bruno.
2. Click Open Collection (or File → Open Collection).
3. Browse to the folder you cloned in Step 4.
4. Select the folder — the collection will load in Bruno.