# sddm-tokyo-night-theme

A theme for the [SDDM login manager](https://github.com/sddm/sddm).

- Screen resolution: 3840x2160
- Font: Fira Code Nerd Font

### Preview

You can easily change how it looks in **[config](./theme.conf)**. 
Here are some examples:

![Preview](./Previews/preview1.png)
![Preview](./Previews/preview2.png)
![Preview](./Previews/preview3.png)
![Preview](./Previews/preview4.png)

### Dependencies

```sh
qt6-5compat qt6-declarative qt6-svg sddm
```

### Install

1. Clone this repository:
```sh
sudo git clone https://github.com/RaduAvramescu/sddm-tokyo-night-theme /usr/share/sddm/themes/sddm-tokyo-night-theme
```

2. Set the SDDM theme:
```sh
echo -e "[Theme]\nCurrent=sddm-tokyo-night-theme" | sudo tee /etc/sddm.conf.d/10-theme.conf
```

### Credits

Based on the theme [`sddm-astronaut-theme`](https://github.com/Keyitdev/sddm-astronaut-theme) by **Keyitdev**.