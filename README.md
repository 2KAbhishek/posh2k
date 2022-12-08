<div align = "center">

<h1><a href="https://2kabhishek.github.io/Posh2K">Posh2K</a></h1>

<a href="https://github.com/2KAbhishek/Posh2K/blob/main/LICENSE">
<img alt="License" src="https://img.shields.io/github/license/2kabhishek/Posh2K?style=flat&color=eee&label="> </a>

<a href="https://github.com/2KAbhishek/Posh2K/graphs/contributors">
<img alt="People" src="https://img.shields.io/github/contributors/2kabhishek/Posh2K?style=flat&color=ffaaf2&label=People"> </a>

<a href="https://github.com/2KAbhishek/Posh2K/stargazers">
<img alt="Stars" src="https://img.shields.io/github/stars/2kabhishek/Posh2K?style=flat&color=98c379&label=Stars"></a>

<a href="https://github.com/2KAbhishek/Posh2K/network/members">
<img alt="Forks" src="https://img.shields.io/github/forks/2kabhishek/Posh2K?style=flat&color=66a8e0&label=Forks"> </a>

<a href="https://github.com/2KAbhishek/Posh2K/watchers">
<img alt="Watches" src="https://img.shields.io/github/watchers/2kabhishek/Posh2K?style=flat&color=f5d08b&label=Watches"> </a>

<a href="https://github.com/2KAbhishek/Posh2K/pulse">
<img alt="Last Updated" src="https://img.shields.io/github/last-commit/2kabhishek/Posh2K?style=flat&color=e06c75&label="> </a>

<h3>Universal prompt for Power users 💪🌈</h3>

<figure>
  <img src= "images/screenshot.png" alt="Posh2K Demo">
  <br/>
  <figcaption>Posh2K screenshot</figcaption>
</figure>

</div>

## What is this

Posh2K is a prompt for [oh-my-posh](https://ohmyposh.dev/), it works on all shells, has multiple segments with aesthetically pleasing colors.

## Inspiration

Most of my workflow is based on the command line, recently I had to use a Windows system for some work and was really displeased by the CLI experience.

So, I needed a prompt that can work across shells and has support for different segments and Posh2K was born.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed the latest version of [oh-my-posh](https://ohmyposh.dev/docs/installation/linux)

## Getting Posh2K

To get Posh2K, follow these steps:

```bash
git clone https://github.com/2kabhishek/Posh2K

# for Powershell, add this to $Profile
oh-my-posh init pwsh --config ~/PATH_TO_DIR/Posh2K/posh2k.omp.json | Invoke-Expression

# for Zsh, add this to ~/.zshrc
eval "$(oh-my-posh init zsh --config ~/PATH_TO_DIR/Posh2K/posh2k.omp.json)"

# for Bash, add this to ~/.bashrc
eval "$(oh-my-posh init bash --config ~/PATH_TO_DIR/Posh2K/posh2k.omp.json)"

# for Fish, add this to ~/config/fish/config.fish
oh-my-posh init fish --config ~/PATH_TO_DIR/Posh2K/posh2k.omp.json | source

# for nu shell, run
oh-my-posh init nu --config ~/PATH_TO_DIR/Posh2K/posh2k.omp.json
source ~/oh-my-posh.nu

# for cmd, install Clink, then add this
load(io.popen('oh-my-posh init cmd --config ~/PATH_TO_DIR/Posh2K/posh2k.omp.json'):read("*a"))()

```

## Challenges faced

Going through the docs and understanding different segments.

Hit the ⭐ button if you found this useful.

## More Info

<div align="center">

<a href="https://github.com/2KAbhishek/Posh2K">Source</a> | <a href="https://2kabhishek.github.io/Posh2K">Website</a>

</div>
