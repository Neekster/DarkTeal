# Midnight Teal Theme

## Lovelace Dashboard
#### The Midnight Teal theme comes in two different varieties; dark and light. If you want the true midnight effect, select dark mode. 
#### Light Mode
![image](https://user-images.githubusercontent.com/58367045/148668482-71e80713-3fe0-4153-9b53-ce77c053057b.png)

#### Dark Mode
![image](https://user-images.githubusercontent.com/58367045/148667117-a56bc26b-f922-41e1-8189-bd76f7cab250.png)

## History
![image](https://user-images.githubusercontent.com/58367045/147864421-3028d86d-688a-4f1d-a682-de3d0c55753f.png)

## Settings
![image](https://user-images.githubusercontent.com/58367045/147864075-0d3852e6-abdc-44e8-8d91-260d96c5c1c2.png)

## Installation

Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

### HACS

1. Go to the Community Store.
2. Search for `Midnight Teal`.
3. Navigate to `Midnight Teal` theme.
4. Press `Install`.

### Manual

Clone this repository in your existing (or create it) `themes/` folder.

```bash
cd themes/
git clone https://github.com/Neekster/MidnightTeal/blob/master/themes/MidnightTeal.yaml
```

Or using submodules:

```bash
cd themes/
git submodule add https://github.com/Neekster/MidnightTeal/blob/master/themes/MidnightTeal.yaml
```
