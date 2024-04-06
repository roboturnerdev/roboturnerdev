#!/bin/bash

name="Rob Turner"
age=32
job="SRE @ ☁ 💪"

code=("bash" "python" "dotnet")
certs=("cka" "sec+" "az-900" "ms-900" "sc-900")
tools=("neovim" "kubectl" "helm" "argocd" "gitlab")

print_profile() {
    echo "********************"
    echo "Name: $name"
    echo "Age: $age"
    echo "Job: $job"
    echo "Code Skills"
    for codeskill in "${code[@]}"; do echo -e "\t$codeskill"; done
    echo "Certifications"
    for cert in "${certs[@]}"; do echo -e "\t$cert"; done
    echo "Tools"
    for tool in "${tools[@]}"; do echo -e "\t$tool"; done
    echo "********************"
}

print_profile
