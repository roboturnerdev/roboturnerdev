#!/bin/bash

name="Rob Turner"
age=33
job="SRE @ ☁ 💪"

code=("bash" "python" "golang" "dotnet" "typescript")
certs=("cka" "sec+" "az-900" "ms-900" "sc-900")
tools=("neovim" "kubectl" "helm" "argocd" "gitlab")

print_profile() {
    echo "********************"
    echo "Name: $name"
    echo "Age: $age"
    echo "Job: $job"
    echo "Code Skills"
    for skill in "${code[@]}"; do echo -e "\t$skill"; done
    echo "Certifications"
    for cert in "${certs[@]}"; do echo -e "\t$cert"; done
    echo "Tools"
    for tool in "${tools[@]}"; do echo -e "\t$tool"; done
    echo "********************"
}

print_profile
