# Nx

## Basic NX Commands

**Create a new NX workspace**
```bash
npx create-nx-workspace@latest
```

**Add NX to an existing project**
```bash
npx add-nx-to-monorepo
```

**Run the NX console**
```bash
nx console
```

**Run a specific target (e.g., build, serve, test) for a project**
```bash
nx run <project>:<target>
```

**Run a build for a project**
```bash
nx build <project>
```

**Serve a project**
```bash
nx serve <project>
```

## NX Workspace Management

**Generate a new project**
```bash
nx generate <schematic> <project_name>
```

**Generate a new library**
```bash
nx generate library <lib_name>
```

**Generate a new application**
```bash
nx generate app <app_name>
```

**Run migrations**
```bash
nx migrate latest
```

**Format all workspace files**
```bash
nx format
```

**Lint all files in the workspace**
```bash
nx lint
```

## Testing & Affected Commands

**Run tests for a project**
```bash
nx test <project>
```

**Run e2e tests for a project**
```bash
nx e2e <project>
```

**Run affected projects (based on changes)**
```bash
nx affected --target=<target>
```

**Show graph of affected projects**
```bash
nx affected:graph
```

## Caching & Dependency Graph

**Clear the NX cache**
```bash
nx reset
```

**Show dependency graph for all projects**
```bash
nx dep-graph
```

**Show the dependency graph for affected projects**
```bash
nx affected:dep-graph
```

## Miscellaneous

**Check NX version**
```bash
nx --version
```