<h3>"Hello there."</h3>- Obi-Wan Kenobi

<br>
<br>

```bash
#!/bin/bash

name="Rob Turner"
age=32
job="sre @ ☁💪"

code=("bash" "python" "dotnet")
certs=("sec+" "az-900" "ms-900" "sc-900")
tools=("neovim" "kubernetes" "helm" "argocd" "gitlab")

print_profile() {
    echo "Name: $name"
    echo "Age: $age"
    echo "Code Skills: ${code[*]}"
    echo "Certifications: ${certs[*]}"
    echo "Tools: ${tools[*]}"
    echo "Job: $job"
}

print_profile
```
