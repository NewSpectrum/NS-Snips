<head>
	<link id="prism-css" href="">
</head>


# Textastic `.sh` Snippets

Create snippets for files using the UNIX `shellscript` Syntax.



<br />

---

# Usage & Compatibility

## Default Files

The `shell.json` Snippets file *should* automatically apply to the following files.

#### NOTE: Auto-Detected Language Syntax is *not* Perfect

Textastic, like most __[Code Editors](wiki)__ & __[IDEs](wiki)__, automatically configure's the __[Syntax Definition](wiki)__ used while editing based on:

1. The __[File Extension](wiki)__ (default)
2. The whole __[Filename](wiki)__
	- To override __#1__ for specifically-defined files, such as...
		- [Hidden System Files (UNIX)](wiki): `.filename.ext` or `.filename`
		- Files without any extension, such as a [`Dockerfile`](wiki) used by [Docker](wiki) to build [Images](wiki)

### Linux

| Filename | Default Location | Purpose |
| :---     | :---             | :---    |
| `bash.bashrc` | <pre><code class="language-shell">/etc/bash.bashrc</code></pre> | System-Wide __[Bash Shell Customization](wiki)__ |



```bash
function usage() {
	cat <<- EOT

  Usage: [options] [--] 

  Options: 
  -i | --interactive			Run interactive utility
  -y | --youtube [url]			Download from YouTube links
  -g | --google-drive [url]		Download from Google Drive
  -o | --other-source [url]		Download from Google Drive
  -a | --audio					Convert the video to an '.mp3' file
  
  -h | --help       			Display this message
  -v | --version    			Display script version

EOT
}
```

https://github.com/NewSpectrum#:~:text=Hi%2C-,please,-be%20aware%20that