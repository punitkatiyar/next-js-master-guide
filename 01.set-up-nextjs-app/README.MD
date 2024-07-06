# Setup Next Js App 

```
Microsoft Windows [Version 10.0.19045.4598]
(c) Microsoft Corporation. All rights reserved.

C:\Users\ADMIN\Desktop\next-js>node -v
v20.15.0

C:\Users\ADMIN\Desktop\next-js>npm -v
10.1.0

C:\Users\ADMIN\Desktop\next-js>npx create-next-app@latest
Need to install the following packages:
create-next-app@14.2.4
Ok to proceed? (y) y
√ What is your project named? ... my-app
√ Would you like to use TypeScript? ... No / Yes
√ Would you like to use ESLint? ... No / Yes
√ Would you like to use Tailwind CSS? ... No / Yes
√ Would you like to use `src/` directory? ... No / Yes
√ Would you like to use App Router? (recommended) ... No / Yes
√ Would you like to customize the default import alias (@/*)? ... No / Yes
Creating a new Next.js app in C:\Users\ADMIN\Desktop\next-js\my-app.

Using npm.

Initializing project with template: app-tw


Installing dependencies:
- react
- react-dom
- next

Installing devDependencies:
- typescript
- @types/node
- @types/react
- @types/react-dom
- postcss
- tailwindcss
- eslint
- eslint-config-next

npm WARN deprecated inflight@1.0.6: This module is not supported, and leaks memory. Do not use it. Check out lru-cache if you want a good and tested way to coalesce async requests by a key value, which is much more comprehensive and powerful.
npm WARN deprecated @humanwhocodes/config-array@0.11.14: Use @eslint/config-array instead
npm WARN deprecated rimraf@3.0.2: Rimraf versions prior to v4 are no longer supported
npm WARN deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported
npm WARN deprecated @humanwhocodes/object-schema@2.0.3: Use @eslint/object-schema instead

added 361 packages, and audited 362 packages in 48s

137 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
Success! Created my-app at C:\Users\ADMIN\Desktop\next-js\my-app


C:\Users\ADMIN\Desktop\next-js>npm run next
npm ERR! code ENOENT
npm ERR! syscall open
npm ERR! path C:\Users\ADMIN\Desktop\next-js\package.json
npm ERR! errno -4058
npm ERR! enoent Could not read package.json: Error: ENOENT: no such file or directory, open 'C:\Users\ADMIN\Desktop\next-js\package.json'
npm ERR! enoent This is related to npm not being able to find a file.
npm ERR! enoent

npm ERR! A complete log of this run can be found in: C:\Users\ADMIN\AppData\Local\npm-cache\_logs\2024-07-06T13_46_22_186Z-debug-0.log

C:\Users\ADMIN\Desktop\next-js>npm run dev
npm ERR! code ENOENT
npm ERR! syscall open
npm ERR! path C:\Users\ADMIN\Desktop\next-js\package.json
npm ERR! errno -4058
npm ERR! enoent Could not read package.json: Error: ENOENT: no such file or directory, open 'C:\Users\ADMIN\Desktop\next-js\package.json'
npm ERR! enoent This is related to npm not being able to find a file.
npm ERR! enoent

npm ERR! A complete log of this run can be found in: C:\Users\ADMIN\AppData\Local\npm-cache\_logs\2024-07-06T13_46_37_322Z-debug-0.log

C:\Users\ADMIN\Desktop\next-js>
```
