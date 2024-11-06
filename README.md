## Notes about basic functioning

- `content/`: includes the sources of your slides
    - **`_generator.md`**: this file is processed to generate **`_index.md`** files

## How to run slides

```
git submodule update --init --recursive
```

### Linux

```bash
./shared-slides/serve.sh
```

navigate:

### Other

```bash
UID=`id -u` GID=`id -g` docker compose up --build
```
