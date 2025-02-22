# Balanced Faster Construction - X4Foundations

This mod rebalances station module construction in X4: Foundations by adjusting build times across all module types. The new timings are carefully tuned based on community feedback, my personal feeling, and reference data to provide a more streamlined, faster, and balanced station building experience.

## What’s Changed?

### Connections

- All connection modules now complete in **3 minutes**.

### Defense

- Claim modules take **12 minutes** to build, while all other defense modules complete in **7 minutes**.

### Docking Modules

- Build times are set at **6, 9, 13, and 15 minutes** (for the respective tiers).

### Piers

- Construction time scales with size:
  - **4 minutes** for the smallest
  - **8 minutes** for the next size
  - **13 minutes** for larger ones
  - **16 minutes** for the largest

### Habitat

- Times now vary by module size:
  - **4 minutes** for small
  - **8 minutes** for medium
  - **13 minutes** for large habitat modules

### Builder

- Builder modules are adjusted by size:
  - **7 minutes** for medium
  - **13 minutes** for large
  - **18 minutes** for extra-large

### Equipment

- Similar scaling as Builder modules:
  - **7 minutes** for medium
  - **13 minutes** for large
  - **18 minutes** for extra-large equipment modules

### Production

- Production modules are tiered (per data from [x4prodchart.com](https://x4prodchart.com/)):
  - **3 minutes** for the fastest tier
  - **8 minutes** for the mid tier
  - **12 minutes** for the slowest

### Storage

- Storage module build times depend on size:
  - **4 minutes** for small
  - **8 minutes** for medium
  - **10 minutes** for large

### Other Modules

- All remaining modules: including venture platforms, welfare gambling halls, casinos, and scrapworks now consistently build in **5 minutes**.

## How It Works

The mod uses XML `<replace>` directives to update the build time values in the game’s files. For example, all “Other” category modules have been set to 300 seconds (5 minutes), ensuring a uniform, faster build time across these components.

Enjoy a more responsive and balanced station construction experience with these optimized build times!

By downloading from Nexus you will support the author

Created by iomatix.