# Marvin's Website

## How to Setup
- Setup cluster
- Setup Portainer
- Create secret
    ```
    marvin-music-secret
    APP_SECRET="app_secret"
    DATABASE_URL="mysql://{user}:{password}@{host}:{port}/{table}?serverVersion=mariadb-10.6.4"
    SPOTIFY_ENCODED_SECRET="spotify_secret"
    SPOTIFY_REFRESH_TOKEN="spotify_token"
    ```
- Setup application
