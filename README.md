基于jellyfin-web v10.6.4简单修改，打包后复制到vlc的assets/www/目录下。

### Dependencies

- [Yarn 1.22.4](https://classic.yarnpkg.com/en/docs/install)
- Gulp-cli

### Getting Started

1. Clone or download this repository.

   ```sh
   git clone https://github.com/jellyfin/jellyfin-web.git
   cd jellyfin-web
   ```

2. Install build dependencies in the project directory.

   ```sh
   yarn install
   ```

3. Run the web client with webpack for local development.

   ```sh
   yarn serve
   ```

4. Build the client with sourcemaps.

   ```sh
   yarn build:development
   ```

   You can build a nginx compatible version as well.

   ```sh
   yarn build:standalone
   ```
