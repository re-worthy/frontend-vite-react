# Re:worthy

## Setup

```
# install nvm
# https://github.com/nvm-sh/nvm
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash

# install and use needed node version
nvm install
nvm use

# install needed pnpm version
npm i -g pnpm@10.10.0

pnpm i
```

## Stack

- [Future] pnpm + node
- [Future] Vite
- [Future] React 18
- [Future] Zod (runtime validation)
- [Future] eslint/prettier (linter, prettifier)
- [Future] shadcn (base components)
- [Future] tailwind (style-guides)
- [Future][Probably] storybook (visual representation of components in bare shell)

## Project Structure (TBD)

## Git hooks

```bash
# sets git-hooks local path
git config --local core.hooksPath .git-hooks

# makes files executable
chmod +x ./.git-hooks/pre-commit
chmod +x ./.git-hooks/commit-msg
```

### Prefixes:

- [HF] - hot fix
- [F] - Feature
- [BF] - bug fix
- [DX] - improved Developer eXperience
- [R] - refactor
- [CUSTOM] - something unknown but so much wanted
