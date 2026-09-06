# Troubleshooting

## gke-mcp: command not found on macOS or Linux

If you run `gke-mcp` after using the manual install method and get an error like `-bash: gke-mcp: command not found`, it usually means the directory where Go places compiled programs is not included in your shell's `PATH` environment variable.

Here are the steps to fix this:
ter completing these steps, you should be able to run the `gke-mcp` command successfully.
