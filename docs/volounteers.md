# For Volounteers

This is a guide for volounteers who want to help out at Coding Pirates Nyborg.

- [For Volounteers](#for-volounteers)
  - [Setting Up Your Development Environment](#setting-up-your-development-environment)
    - [Windows](#windows)
    - [Linux](#linux)
  
---

## Setting Up Your Development Environment

This is **ONLY** intended for volounteer who want to work on their own machine. *If you are using a Coding Pirates Nyborg computer*, you can skip this section.

### Windows

![Download Installation - Script](https://github.com/coding-pirates-nyborg/config/environment/windows/setup-env.ps1)

```powershell

# Download the setup-env.ps1 script

$uri = "https://github.com/coding-pirates-nyborg/config/environment/windows/setup-env.ps1"
Invoke-WebRequest -Uri $uri -OutFile setup-env.ps1

```

```powershell

# Run the setup-env.ps1 script

.\setup-env.ps1

```

> If you get an error about the execution policy, you can bypass it by running the following command:

```powershell
 Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```

### Linux

![Download Installation - Script](https://github.com/coding-pirates-nyborg/config/environment/windows/setup-env.ps1)

```bash

# Download the setup-env.sh script

uri = "https://github.com/coding-pirates-nyborg/config/environment/linux/setup-env.sh"

wget $uri -O setup-env.sh

```

```bash

# Make the setup-env.sh script executable

chmod +x setup-env.sh

```

```bash
# Run the setup-env.sh script

./setup-env.sh

```

---

