# openwrt-master-wrapper

**KISS+.** OpenWRT is a great project — truly. This wrapper just makes it
a little more friendly.

## Why this wrapper?

- **A release upgrade is real simple.** Your project lives outside the
  OpenWRT tree, so moving to a new OpenWRT release is swapping the
  engine, not rebuilding your project.
- **A lower entry point.** Menus and a defconfig gallery instead of a blank
  config on day one.
- **Your work survives.** Your project files never live inside the engine
  sandbox, so the cleans (`make repoclean`, `make totalclean`) can't eat
  them.

**NOTE:** This is still a work in progress. I am working at the corresponding sibling project **buildroot-wrapper**
