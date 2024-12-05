# Spotifly

**Spotifly** is a Spotify clone that provides users with personalized playlists, podcasts, and radio stations, just like Spotify. Designed to offer a seamless and high-quality music experience, Spotifly helps you discover and enjoy your favorite tracks with a user-friendly interface.

---

## Features

- **Personalized Playlists**: Get custom playlists tailored to your taste based on your listening habits.
- **Podcast Support**: Stream podcasts across various genres and topics.
- **Radio Stations**: Listen to curated radio stations with various genres and moods.
- **Responsive Design**: Fully optimized for different screen sizes, from mobile to desktop.
- **Music Controls**: Play, pause, skip, and repeat tracks with an intuitive player interface.
- **Search Functionality**: Quickly find tracks, albums, artists, and playlists.
- **User Authentication**: Sign in and manage your playlists using Spotify’s OAuth 2.0 authentication.

---

## Setup

### Prerequisites
- Node.js and npm (or yarn) installed on your system.
- A Spotify Developer account for API credentials.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/egeuysall/spotifly.git
   cd spotifly
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and add your Spotify API credentials:

   ```env
   REACT_APP_SPOTIFY_CLIENT_ID=your-client-id
   REACT_APP_SPOTIFY_CLIENT_SECRET=your-client-secret
   ```

4. Start the development server:

   ```bash
   npm start
   ```

5. Visit `http://localhost:3000` in your browser to access Spotifly.

---

## API Integration

Spotifly integrates with the Spotify Web API to authenticate users and fetch track, album, and playlist data.

### Authentication
Spotifly uses OAuth 2.0 for user authentication. Users must log in with their Spotify credentials to access their personalized playlists and music recommendations.

### Rate Limits
Please note that the Spotify API has rate limits. Be mindful of the number of requests made in a given period to avoid hitting these limits.

---

## Technologies Used

- **Frontend**: React, HTML, CSS, JavaScript
- **API**: Spotify Web API
- **Authentication**: OAuth 2.0
- **State Management**: React Context API

---

## Contributing

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`.
3. Make your changes and commit them: `git commit -am 'Add new feature'`.
4. Push to your branch: `git push origin feature/your-feature`.
5. Create a pull request.

---

## License

This project is open source and available under the [MIT License](LICENSE).

---

## Acknowledgments

- The **Spotifly** project is a clone of **Spotify** and utilizes the Spotify Web API for functionality.
- Thanks to the Spotify Developer Team for providing the API and documentation.
