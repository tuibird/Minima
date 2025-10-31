## Minima

Minimalist Starship prompt preset.

A really basic prompt to blend into your terminal theme.

If you have Noctalia Shell, ive included a matugen user template so it adapts to your colourschemes and most likely becomes more colourful.

Note: Only tested using fish. So it might work on zsh etc, but also might blow up into 1000 pieces and set your favirote pot plant on fire.

## Installation


```bash
  # Install the two dependencies, starship & a nerd font
  
  # Back up your current starship.toml

  # Grab Minima & install
  git clone https://github.com/tuibird/Minima.git
  cd Minima
  cp starship.toml ~/.config

  # If you want Matugen functionality with Noctalia
  # First go into Noctalia settings colorscheme tab, scroll to the bottom and enable user templates
  cat config.toml >> ~/.config/noctalia/user-templates.toml
  cp starship-colors.toml ~/.config/noctalia 
```
    
## Examples

![App Screenshot](https://raw.githubusercontent.com/tuibird/Minima/refs/heads/main/example2.png)

![App Screenshot](https://raw.githubusercontent.com/tuibird/Minima/refs/heads/main/example3.png)
