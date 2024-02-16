# Creating projects in TypeScript

Projects in Typescript must have a `tsconfig.json` file in the root of the project. This file is used to configure the TypeScript compiler.

Here's an example of the file
```json
{
  "$schema": "https://json.schemastore.org/tsconfig",
  "display": "Node 20",
  "_version": "20.1.0",

  "compilerOptions": {
    "lib": ["es2023", "dom"],
    "module": "node16",
    "target": "es2022",

    "strict": true,
    "esModuleInterop": true,
    "skipLibCheck": true,
    "forceConsistentCasingInFileNames": true,
    "moduleResolution": "node16"
  }
}

```
:star: This repository contains good tsconfig bases. The bases are curated by the community, and they are
good when starting a project https://github.com/tsconfig/bases#centralized-recommendations-for-tsconfig-bases
