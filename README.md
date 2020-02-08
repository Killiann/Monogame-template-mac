# Monogame-template-mac
template for monogame on mac

### SETUP STEPS:

1) install monogame templates : 
```bash
dotnet new -i MonoGame.Templates.CSharp 
```
2) go to empty project folder in terminal and run:
```bash
ddotnet new mgdesktopgl
```
3) run :
```bash
dotnet run
```

### ERRORS: 
error with installing templates: remove all packages and try again, if not, reinstall dotnet.

error with finding SdL libraries: make sure SDL2 is installed, run :
```bash
brew install sdl2
```
