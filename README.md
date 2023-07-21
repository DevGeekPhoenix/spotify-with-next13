# Spotify-with-Next13

Spotify-with-Next13 is a web application that replicates the basic functionality of the popular music streaming service, Spotify. It is built using Next.js, a React framework for server-side rendering and Supabase, making it a full-stack application.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Contributing](#contributing)

- ## Features

- User authentication: Allows users to sign up, log in, and log out to access personalized features.
- Search: Users can search for their favorite songs, albums, artists, and playlists.
- Music playback: Users can play, pause, skip, and control the volume of songs they choose.
- Liked playlist: Users can create, modify, and delete their liked playlists, adding or removing tracks as they like.
- Responsive design: The app is designed to be mobile-friendly and accessible on various devices.

## Installation

To run the Spotify-with-Next13 application locally, follow these steps:

1. Clone the repository to your local machine using:

```bash
git clone https://github.com/FrontPhoenix/spotify-with-next13.git
```

2. Navigate to the project directory:

```bash
cd spotify-with-next13
```

3. Install the required dependencies:

```bash
yarn install
```

4. Create a `.env.local` file in the root directory and provide the necessary environment variables:

```bash
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
SUPABASE_SERVICE_ROLE_KEY=your_supabase_service_role_key
```


## Usage

Once you have completed the installation steps, you can start the application by running the following command:

```bash
yarn dev
```

This will start the development server, and you can access the application by visiting `http://localhost:3000` in your web browser.

### Production Address

The application is also deployed and accessible on the production server. You can visit the live version by clicking the link below:

[Spotify-with-Next13 Production](https://front-phoenix-spotify.vercel.app/)


## Technologies

The Spotify-with-Next13 application utilizes the following technologies:

- Next.js: For server-side rendering and client-side rendering of React components.
- React: For building the user interface and managing the application's state.
- Node.js: For handling the server-side logic and API calls to Spotify.
- Tailwind CSS: For styling the project.
- Supabase: For managing the application's database and handling data storage and users authentication.

## Contributing

Contributions to Spotify-with-Next13 are welcome and encouraged! If you find any bugs or have ideas for new features, please open an issue or submit a pull request following the standard GitHub workflow.

1. Fork the repository on GitHub.
2. Clone the forked repository to your local machine.
3. Create a new branch from the `master` branch for your feature/bug fix.
4. Make your changes, commit them, and push the changes to your fork.
5. Submit a pull request to the `master` branch of the original repository.

Please ensure that your pull request includes a detailed description of the changes you've made and any relevant testing or documentation updates.

---

I hope you enjoy using this project! If you have any questions or feedback, please don't hesitate to reach out to me. Happy listening!
