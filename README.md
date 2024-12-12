# Overview 

Programming is fun.

I believe that everyone should be able to learn to program, but I fully understand that it can be difficult to get started.

After talking with my brother, a brilliant chemical engineer and writer that showed an interest in programming, I quickly realized that intelligence is not the issue with getting started at basic programming.

For people with full-time jobs, the issue is *time*.

Figuring out how to install all the tools just to do get ready to figure out the boilerplate code for a hello world program is a large time commitment.

That's why I created this project.

If you are interested in learning to program, this project is for you.

# Getting Started

## Installing

> [!WARNING]
> This project is made to be used with [devenv](https://devenv.sh/) to manage your development environment so that you can skip the installation steps. This requires you to install Nix and Devenv. This also requires either Unix or Linux.

We will be following the instructions from the [Devenv documentation](https://devenv.sh/getting-started/) to install everything.

First, we need to install Nix.

`sh <(curl -L https://nixos.org/nix/install) --daemon`

Next, we need to install devenv.

`nix-env -iA devenv -f https://github.com/NixOS/nixpkgs/tarball/nixpkgs-unstable`

Finally, we need to enter our shell (basically a terminal with everything installed in your terminal).

`devenv shell`

You should now see a new prompt that looks like this:

```bash
hello from devenv
git version 2.47.0
```

If so, you are ready to go!

## Starting Your Hello World

Now that you are in your shell, you can start your first program.

```bash
python3 python/main.py
```

This should print out `hello from python`.

Congrats on getting started!
