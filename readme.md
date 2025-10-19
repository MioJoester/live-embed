# 🎵 Spotify Now Playing

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen.svg)](https://live-embed.vercel.app)
[![Spotify API](https://img.shields.io/badge/Spotify-API-1DB954.svg)](https://developer.spotify.com/)

A sleek web application that displays your currently playing Spotify track in real-time. Built with modern web technologies and the Spotify Web API.

## ✨ Features

- 🎧 **Real-time Tracking** - See what you're currently listening to on Spotify
- 🎨 **Modern UI** - Clean, responsive design that works on all devices
- 🔐 **Secure Auth** - OAuth 2.0 implementation for safe Spotify authentication
- 📱 **PWA Ready** - Install as a progressive web app
- 🌙 **Dark Theme** - Easy on the eyes interface
- ⚡ **Fast & Lightweight** - Optimized for performance

## 🚀 Quick Start

### Prerequisites

- Node.js 16+
- VS code with Live server extension
- A Spotify Developer Account
- Modern web browser with JavaScript enabled

# Spotify api setup 

1. Go to Spotify Developer Dashboard (https://developer.spotify.com/dashboard)
2. Create a new app
3. Add http://localhost:3000/ to your Redirect URIs  (add custom ports if you use a different one)
4. copy the client id and client secret and use in the code.

# How it works 

1. Authentication: Users log in with their Spotify account using OAuth 2.0
2. Authorization: The app requests permission to read currently playing track
3. API Integration: Fetches real-time playback data from Spotify Web API
4. Display: Shows track info, album art, and playback progress in a beautiful UI
