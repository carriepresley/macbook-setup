# MacBook Setup for Software Development!

## 1.XCode
    xcode-select --install
    
## 2. Homebrew
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    
## 3. ZSH 
  ### a. Check the version:
        zsh --version
        
  ### b. Install if needed:
        brew install zsh
        
  ### c. Set zsh as default shell:
        chsh -s /bin/zsh
        
  ### d. Check to ensure zsh is the default (expected result: /bin/zsh)
       echo $SHELL
    
    
## 4. VSCode
    brew install --cask visual-studio-code


## 5. Node.js
    brew install node
