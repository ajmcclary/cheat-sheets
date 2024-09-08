# Npm

## Basic Commands

**Check NPM version**
  ```bash
  npm --version
  ```

**Initialize a new Node.js project**
  ```bash
  npm init
  ```

**Initialize a new Node.js project with default options**
  ```bash
  npm init -y
  ```

**Install all dependencies from package.json**
  ```bash
  npm install
  ```

**Install a specific package**
  ```bash
  npm install <package_name>
  ```

**Install a package globally**
  ```bash
  npm install -g <package_name>
  ```

**Install a package as a development dependency**
  ```bash
  npm install <package_name> --save-dev
  ```

**Install a package at a specific version**
  ```bash
  npm install <package_name>@<version>
  ```

**Uninstall a package**
  ```bash
  npm uninstall <package_name>
  ```

**Uninstall a global package**
  ```bash
  npm uninstall -g <package_name>
  ```


## Running Scripts

**Run a script defined in package.json**
  ```bash
  npm run <script_name>
  ```

**Start a project (runs the 'start' script)**
  ```bash
  npm start
  ```

**Run tests (runs the 'test' script)**
  ```bash
  npm test
  ```

**Run linting (if defined)**
  ```bash
  npm run lint
  ```


## Package Management

**List all globally installed packages**
  ```bash
  npm list -g --depth=0
  ```

**List all locally installed packages**
  ```bash
  npm list --depth=0
  ```

**Update all outdated local packages**
  ```bash
  npm update
  ```

**Update a specific package**
  ```bash
  npm update <package_name>
  ```

**Update global packages**
  ```bash
  npm update -g
  ```

**Check for outdated packages**
  ```bash
  npm outdated
  ```

**Audit dependencies for vulnerabilities**
  ```bash
  npm audit
  ```

**Fix vulnerabilities**
  ```bash
  npm audit fix
  ```

**Rebuild node modules**
  ```bash
  npm rebuild
  ```


## Package Caching

**Clear npm cache**
  ```bash
  npm cache clean --force
  ```

**View npm cache**
  ```bash
  npm cache verify
  ```


## Versioning & Publishing

**Bump package version (major, minor, or patch)**
  ```bash
  npm version <major|minor|patch>
  ```

**Publish a package to the npm registry**
  ```bash
  npm publish
  ```

**Unpublish a package (for private packages)**
  ```bash
  npm unpublish <package_name>
  ```

**Login to npm registry**
  ```bash
  npm login
  ```

