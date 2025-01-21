# jottad-cli

Great package registration tool that is used to parse code through older nix repos on  jottacloud-cli

# nix-env
```
nix-env -iA nixos.jotta-cli
```
# Nix-Configuration

```
  environment.systemPackages = [
    pkgs.jotta-cli
  ];
```

# nix-shell

```
nix-shell -p jotta-cli
```
