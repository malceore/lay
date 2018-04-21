# lay and hatch

Lay and hatch are a project scaffolding tool kit I am working on. Right now it just sets up a run script, commit script, readme, .gitignore and makes an initial commit.

## Getting Started

// Create a new project folder with projects name
lay <project name>

// List all projects tracked my lay
lay -l

// Move to project folder
lay -j <project name>

### Installing

To install simply place the repo in a static directory like: /opt/ or /usr/local/ and then create a symlink to a bin in your path.

```
cd /opt/
git clone https://github.com/malceore/lay.git
ln -s /usr/bin/ lay
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

