# OpenEdu MonoRepo

This is a monorepo for the OpenEdu project. It contains the following submodules:

- [openedu-frontend](https://github.com/synthAI-Labs/WebClient-OpenEdu.git)
- [openedu-backend](https://github.com/synthAI-Labs/server-OpenEdu.git)

## Getting Started

To clone the repository:

```bash
git clone https://github.com/synthAI-Labs/openedu.git
```

To initialize the submodules:

```bash
git submodule init
git submodule update
```

To update the submodules:

```bash
git submodule update --remote
```

## Launching the Application:

1. Install all dependencies:

```bash
yarn install
```

2. Start the application in development mode:
   - localhost:3000 (frontend)
   - localhost:4000 (backend)

```bash
yarn dev
```

3. Build the application for production:

```bash
yarn build
yarn start
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
