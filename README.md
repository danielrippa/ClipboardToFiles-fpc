## Usage

```cmd
clipboardtofiles.exe [options]
```

### Options

- **No flags**: Default mode - fails safely when destination exists
- **/force** or **/f**: Overwrites existing files and folders
- **/rename** or **/r**: Auto-renames conflicts (e.g., "file (1).txt", "folder (2)")

## Supported Clipboard Formats

### CF_HDROP (File Objects)
Files and folders copied from Windows Explorer, file managers, etc.

### CF_TEXT (Text Paths)
File/folder paths copied as text from:
- Address bars
- Command prompts
- Text editors
- Directory listings
