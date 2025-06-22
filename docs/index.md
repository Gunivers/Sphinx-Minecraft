# Sphinx Minecraft

```{include} ../README.md
:start-after: <!-- start-include-here -->
:end-before: <!-- end-include-here -->
```

## Available components

### Tree views

These components are based on [sphinx-treeview](https://github.com/Altearn/Sphinx-Tree-View).

#### Minecraft directory tree
**Usage:**
```rst
:::{treeview}
- {mcdir}`folder` folder
  - {mcdir}`mcfunction` function.mcfunction
  - {mcdir}`mcmeta` pack.mcmeta
  - {mcdir}`nbt` structure.nbt
- {mcdir}`folder` folder2
  - {mcdir}`file` file.txt
  - {mcdir}`audio` sound.ogg
  - {mcdir}`image` texture.png
  - {mcdir}`json` advancement.json
  - {mcdir}`yml` config.yml
:::
```
**Result:**

:::{treeview}
- {mcdir}`folder` folder
  - {mcdir}`mcfunction` function.mcfunction
  - {mcdir}`mcmeta` pack.mcmeta
  - {mcdir}`nbt` structure.nbt
- {mcdir}`folder` folder2
  - {mcdir}`file` file.txt
  - {mcdir}`audio` sound.ogg
  - {mcdir}`image` texture.png
  - {mcdir}`json` advancement.json
  - {mcdir}`yml` config.yml
:::

#### NBT tree
**Usage:**
```rst
:::{treeview}
- {nbt}`compound` A compound tag
  - {nbt}`bool` A boolean tag
  - {nbt}`byte` A byte tag
  - {nbt}`short` A short tag
  - {nbt}`int` An integer tag
  - {nbt}`long` A long tag
  - {nbt}`float` A float tag
  - {nbt}`double` A double tag
  - {nbt}`string` A string tag
  - {nbt}`list` A list tag
  - {nbt}`number` A number tag
  - {nbt}`any` A tag to represent any type
- {nbt}`compound` A compound tag
  - {nbt}`long-array` A long array tag
  - {nbt}`byte-array` A byte array tag
  - {nbt}`int-array` An integer array tag
:::
```
**Result:**

:::{treeview}
- {nbt}`compound` A compound tag
  - {nbt}`bool` A boolean tag
  - {nbt}`byte` A byte tag
  - {nbt}`short` A short tag
  - {nbt}`int` An integer tag
  - {nbt}`long` A long tag
  - {nbt}`float` A float tag
  - {nbt}`double` A double tag
  - {nbt}`string` A string tag
  - {nbt}`list` A list tag
  - {nbt}`number` A number tag
  - {nbt}`any` A tag to represent any type
- {nbt}`compound` A compound tag
  - {nbt}`long-array` A long array tag
  - {nbt}`byte-array` A byte array tag
  - {nbt}`int-array` An integer array tag
:::
