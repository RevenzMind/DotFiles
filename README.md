# PWSH Dotfiles 😺❤️

```
 /\_/\  
( o.o ) 
 > ^ <
```

## Installation Steps 😺

1. Download this repository:
   ```powershell
   git clone https://github.com/RevenzMind/DotFiles.git
   ```

2. Move the `.config` folder to `C:\Users\%USERNAME%`:
   ```powershell
   move .\DotFiles\.config C:\Users\%USERNAME%\
   ```

3. Install Starship using Winget in PowerShell:
   ```powershell
   winget install --id Starship.Starship --source winget
   ```

4. Install the JetBrains Mono Nerd Font from: [JetBrainsMono.zip](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.2/JetBrainsMono.zip)
   > Note: The JetBrains Mono Nerd Font is needed for proper display of icons and symbols in the terminal.

5. Install the latest version of PowerShell from Microsoft Store: [PowerShell](https://apps.microsoft.com/store/detail/powershell/9MZ1SNWT0N5D?hl=en-us&gl=us)

6. Set Windows Terminal as the default terminal:
   ```powershell
   Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
   ```

7. Open Windows Terminal, go to **Settings** and find the option **"Open JSON file"**, then replace its content with the `settings.json` file from this repository.
   > Note: The `settings.json` file configures the terminal's appearance and behavior. You can find it in the root of this repository.

8. Copy the `PowerShell` folder from this repository to your `Documents` directory:
   ```powershell
   copy .\DotFiles\PowerShell C:\Users\%USERNAME%\Documents\
   ```
   > Note: The PowerShell profile needs to be copied to the `Documents` directory to be recognized by PowerShell.

9. Reopen Windows Terminal to see the PowerShell changes take effect.

10. Final Notes on Name Customization:
    You can modify the following line in the PowerShell profile (`C:\Users\%USERNAME%\Documents\PowerShell\Microsoft.PowerShell_profile.ps1`):
    ```powershell
    $ENV:initial = "<Kendo>"
    ```
    to display your preferred name in the terminal.
