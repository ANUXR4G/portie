#Setup Of Github Larfe File System

Linux (Ubuntu/Debian)
```bash
sudo apt install git-lfs
```
macOS (Homebrew)
```bash
brew install git-lfs
```

After installation, initialize Git LFS in your repository
```bash
git lfs install
```

Track Large Files

Identify the types of files to track (e.g., .psd, .zip, .mp4, etc.).

Use the git lfs track command to track these file types:

```bash
git lfs track "*.file_extension"
```

Commit and Push
```bash
git add .gitattributes
```

```bash
git commit -m "Set up Git LFS to track large files"
```

```bash
git commit -m "Set up Git LFS to track large files"
```

```bash
git add your-large-file.png
git commit -m "Add large file"
```

```bash
git push origin main
```
Then Push All Files

```bash
git add .
```

```bash
git commit -m "Initial Commit"
```

```bash
git push origin main
```