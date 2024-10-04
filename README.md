# HKBU_iSBLM_FYP_2425_docs

## Task and Functions Work Distribution

| Task                  | Functions/Components               | Status      | Assigned To |
| --------------------- | ---------------------------------- | ----------- | ----------- |
| User Authentication   | Login, User Roles Separation       | In Progress | Chan Antony |
| Project Management    | Project, Course Linkage            | In Progress | Chan Antony |
| User Management       | Users Objects                      | In Progress | Chan Antony |
| File Handling         | Object Upload and Storages         | In Progress | Chan Antony |
| User Interface Design | Basic UI Design                    | In Progress | Chan Antony |
| Additional Features   | TBD                                | In Progress | Team        |
| Form                  | Declaration of Major, Approval     | In Progress | Troy        |
| Modules               | CRUD, Customization, Data Analysis | In Progress | Troy        |
| Testing and Debugging | Unit Tests, Integration Tests      | Not Started | Team        |
| Documentation         | API Documentation, User Guides     | Not Started | Team        |
| Deployment            | CI/CD Pipeline, Server Setup       | Not Started | Team        |

##

## Documentation
* User Auth
  * Pinia System
    * authStore 
  * Three User Roles: 
    * Admin -> View All Users
    * Supervisors -> View Supervised Students
    * Students -> View Corse & Modules
* Proj Manage
* User Manage

This template should help get you started developing with Vue 3 in Vite.

## Test Account
    - Admin
    email: adm1@gmail.com
    password: adm1

    - Supervisor
    email: sup1@gmail.com
    password: sup1

    - Student
    email: std1@gmail.com
    password: std1


## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

# HKBU_iSBLM_FYP_2425_docs