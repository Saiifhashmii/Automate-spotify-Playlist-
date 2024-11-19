# Spotify Playlist Automation with Terraform 🎵

This project demonstrates how to automate the creation of **Spotify playlists** using **Terraform** and the **Spotify Web API**. The goal is to show how **Infrastructure as Code (IaC)** can be used to interact with external services, such as Spotify, to automate the creation and management of playlists based on a user's preferences (e.g., artist-based playlists).

## 🚀 Project Overview

Using Terraform, this project allows users to create and manage Spotify playlists with tracks fetched dynamically based on artist names. The project includes the creation of a sample playlist called "Heartbroken" with predefined tracks, and you can modify the configuration to create playlists with different names and track lists.

### Features:
- Automate the creation of Spotify playlists using **Terraform**.
- Search for tracks from a specific artist using the **Spotify Web API**.
- Easily modify playlists by changing the track list in the Terraform configuration.
- No need to manually add tracks — everything is automated!

## 📋 Requirements

To run this project, you need the following:

1. **Spotify Developer Account**: You need Spotify API credentials (Client ID and Client Secret).
   - Create an app on the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/applications) and get your **Client ID** and **Client Secret**.

2. **Terraform**: You need to have [Terraform](https://www.terraform.io/) installed on your local machine.
   
   - Install Terraform by following the [official Terraform installation guide](https://learn.hashicorp.com/tutorials/terraform/install-cli).

## 🔧 Setup Instructions

### Step 1: Clone the Repository
Clone this repository to your local machine.

```bash
git clone https://github.com/yourusername/spotify-terraform-playlist.git
cd spotify-terraform-playlist
