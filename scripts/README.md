# Powershell Scripts

## Windows
You probably already have powershell installed.

`powershell ./windows.darkslack.ps1`

## Mac
1. Install [homebrew](https://brew.sh/) (if you haven't already)
2. Install powershell core: `brew cask install powershell`
3. `sudo pwsh ./mac.onedark.ps1`

## Modifying

You can modify the scripts pretty easily. The bulk of the work is in the custom css variable.

```
   let customCustomCSS = `
   :root {
      /* Modify these to change your theme colors: */
      --primary: #09F;
      --text: #CCC;
      --background: #080808;
      --background-elevated: #222;
   }
```

Just modify those however you want.