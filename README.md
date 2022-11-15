# PackageArchive

This primary package archive for [Hermetic](https://github.com/nosrac-tech/hermetic).

## Creating a New Package

While Hermetic and the PackageArchive are in an early state of developmetn (pre- version 1.0), the format for packages will change dramatically.
This includes changing the process of creating a new package.
Eventually, you will be able to create, submit, and modify packages directly from Hermetic's CLI interface, however this is a roadmap item and isn't currently supported. Currently, you will need to do the following (I apologize for it being _very_ messy right now, this will get better):

- Create a fork of the PackageArchive repository.
- Create your package using the `hermetic create` command for hermetic, and finish setting up the package manually using the prompted editor.
- Create a directory

### Author

Carson Woods, Nosrac Technology.

**NOTE:** Unless you are a package contributor to Hermetic or a Hermetic developer, you will likely not need access to this repository.
