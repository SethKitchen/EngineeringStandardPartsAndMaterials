# Engineering Standard Library

The Engineering Standard Library is a community-maintained collection of reusable engineering assets for PermitCAD and other applications.

It exists to make modeling faster by providing drag-and-drop starter content such as:

- sketches
- finished parts
- materials
- textures

This library is meant to grow over time. Contributions are welcome, especially:

- more structural steel profiles
- more lumber sizes and species
- more fasteners and hardware
- more common construction materials
- more manufacturing materials
- more reference parts and stock shapes
- better textures with clear licensing and attribution

If you have a useful real-world material, a reusable part family, or a high-quality starter sketch, please open a pull request.

## What Lives Here

The standard library currently contains four kinds of assets:

- `*.sketch`: reusable PermitCAD sketch/project files
- `*.part`: reusable PermitCAD part/project files
- `*.material`: engineering material definitions
- `*.jpg` / `*.jpeg` / `*.png`: texture assets referenced by materials or applied directly

## Repository Layout

~~~text
assets/standard_library/
  sketches/
    fasteners/
    steel/
    wood/
  parts/
    fasteners/
    steel/
    wood/
  materials/
  textures/
~~~

Notes:

- `sketches` and `parts` are organized into subfolders.
- `materials` and `textures` are currently stored flat on disk.
- In the app UI, materials and textures may be grouped into logical categories such as composite, metal, plastic, wood, and other.

## Contribution Guidelines

Please keep contributions:

- reusable
- clearly named
- technically accurate
- easy to import
- safe to redistribute

Please prefer real engineering values and cite sources whenever possible.

For materials, the best submissions include:

- a clear material name
- a short description
- units for each property
- a source for each property when available
- an appropriate texture if one exists

For parts and sketches, the best submissions include:

- a clean file name
- one intended asset per file
- a correct active sketch index
- valid geometry that imports without errors
- a material assignment when appropriate

## Naming Conventions

Use lowercase ASCII file names with underscores.

Good examples:

- `structural_steel_a36_.material`
- `wood_pine.jpg`
- `imperial_hex_050in_13unc_L4p00in.part`
- `W10x22_40ft.sketch`
- `lumber_2x4_L096in.part`

Try to include enough detail in the file name to identify the asset:

- family or type
- key size
- length
