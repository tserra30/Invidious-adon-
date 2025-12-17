# Home Assistant Add-on: Invidious

## How to use

This add-on is intended to provide Invidious, a privacy-friendly alternative YouTube frontend.

**Note:** This add-on is currently in development. The current version is a template that demonstrates basic add-on functionality.

When started, it will:
- Print the configured message (or "Hello World..." by default) in the log
- Write "All done!" to `/share/example_addon_output.txt` to demonstrate the usage of `map` in the addon config

## Configuration

Add-on configuration:

```yaml
message: "Your custom message here"
```

### Option: `message`

The message that will be printed to the log when starting this add-on.

**Note:** This is an optional field. If not specified, the default message "Hello World..." will be used.
