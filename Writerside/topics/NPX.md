# Npx

## Basic Commands

**Execute a package without installing it**
```bash
npx <package_name>
```

**Run a specific package version**
```bash
npx <package_name>@<version>
```

**Run a local project’s binary**
```bash
npx <binary_name>
```

**Execute a command from a GitHub repository**
```bash
npx github:<user>/<repo>
```

**Create a new project with a generator**
```bash
npx <generator_name> <project_name>
```

## Miscellaneous Commands

**Run a command with no cache**
```bash
npx --no-install <package_name>
```

**View NPX version**
```bash
npx --version
```

**Clear NPX cache**
```bash
npx clear-npx-cache
```

**Create a new React app**
```bash
npx create-react-app <app_name>
```

**Create a new Next.js app**
```bash
npx create-next-app <app_name>
```

**Create a new NestJS project**
```bash
npx @nestjs/cli new <project_name>
```

## Advanced Usage

**Execute a script from a gist**
```bash
npx gist.github.com/<gist_id>
```

**Run a package in a different Node version (via npx)**
```bash
npx -p node@<version> <command>
```

**Run a package and pass additional parameters**
```bash
npx <package_name> -- <parameters>
```
