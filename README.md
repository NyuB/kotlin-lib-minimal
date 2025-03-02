# Cookiecutter template for a minimal Kotlin library

## Usage

**NB**: The [cookiecutter documentation](https://cookiecutter.readthedocs.io/en/stable/usage.html) will always be the most up-to-date regarding cookiecutter usage. The following instruction are just a quickstart helper.

```console
$ cookiecutter gh:NyuB/kotlin-lib-minimal
[1/7] name (lib): my-awesome-lib
...
$ ls my-awesome-lib
src/
pom.xml
...
```

## Template variables

- **name**: Your project's name, artifact id, and the generated folder's name.
- **group**: Maven group id
- **description**: A description of the library
- **author**: Your name
- **repository**: Your git repo formatted as `user/repo`
- **repository_url**: Full url to your git repo
- **java_version**: The targeted version of Java
- **kotlin_version**: The Kotlin compiler version to use