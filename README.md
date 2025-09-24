# Balanced Faster Construction - X4Foundations

This mod rebalances station module construction in X4: Foundations by adjusting build times across all module types. The new timings are carefully tuned based on community feedback, my personal feeling, and reference data to provide a more streamlined, faster, and balanced station building experience.

## What’s Changed?

### Connection Modules

- All connection modules now complete in **90 seconds**.

### Defense Modules

- Claim modules take **8 minutes** to build, while all other defense modules complete in **5 minutes**.

### Docking Modules
<!-- 4 minutes Low Tech, 6 minutes Normal, 7 minutes High Tech, 15 minutes XL + 60 seconds for "02" -->
- Construction time scales with tech level:
  - **4 minutes** for the low tier
  - **6 minutes** for the standard tier
  - **7 minutes** for the high tier
- "02" modules take **60 seconds** longer to build.
- XL modules take **12 minutes** to build.

### Habitat Modules

- Times now vary by module size:
  - **3 minutes** for small
  - **6 minutes** for medium
  - **10 minutes** for large habitat modules

### Pier Modules

- Construction time scales with size:
  - **5 minutes** for the smallest
  - **8 minutes** for the next size
  - **13 minutes** for larger ones

### Builder Modules

- Builder modules are adjusted by size:
  - **5 minutes** for small
  - **7 minutes** for medium
  - **11 minutes** for large
  - **14 minutes** for extra-large

### Equipment Modules

- Similar scaling as Builder modules:
  - **5 minutes** for default L
  - **9 minutes** for default XL
  - **8 minutes** for dockarea

### Production Modules

- Production modules are tiered (per data from [x4prodchart.com](https://x4prodchart.com/)):
  - **3 minutes** for the fastest tier
  - **8 minutes** for the mid tier
  - **12 minutes** for the slowest

### Storage Modules

- Storage module build times depend on size:
  - **4 minutes** for small
  - **6 minutes** for medium
  - **8 minutes** for large

### Other Modules

- All remaining modules: including venture platforms, welfare gambling halls, casinos, radar dishes and scrapworks now consistently build in **4 minutes**.

### Resources Production

- All resources are generated **15% faster**.

### Workunits Production

- All units are generated **20% faster**.

### Xenon Modules 

- All modules take around **75%** of the vanilla build time.

## How It Works

The mod uses XML `<replace>` directives to update the build time values in the game’s files. For example, all “Other” category modules have been set to 300 seconds (5 minutes), ensuring a uniform, faster build time across these components.

Enjoy a more responsive and balanced station construction experience with these optimized build times!

## Contributions

<a href="https://github.com/iomatix/Balanced-Faster-Construction-X4Foundations/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=iomatix/Balanced-Faster-Construction-X4Foundations" />
</a>

## Supporting Development

My mods are **always free to use**.

If you appreciate my work, you can support me by [buying me a coffee](https://buymeacoffee.com/iomatix).


