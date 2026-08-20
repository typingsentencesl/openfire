# OpenFire

AI coding in your terminal. Desktop IDE included.

## Install

### CLI

```
pip install --upgrade https://github.com/typingsentencesl/openfire/releases/download/v1.4.6/openfire_ai-1.4.6-py3-none-any.whl
```

Then run from any project folder:

```
openfire
```

### Desktop IDE (Linux)

```
curl -L -o OpenFire.AppImage https://github.com/typingsentencesl/openfire/releases/download/v1.4.6/OpenFire-1.4.6.AppImage
chmod +x OpenFire.AppImage
./OpenFire.AppImage
```

### Desktop IDE (Windows)

Download [OpenFire-Setup-1.4.6.exe](https://github.com/typingsentencesl/openfire/releases/download/v1.4.6/OpenFire-Setup-1.4.6.exe) and run the installer. 64-bit Windows.

Sign in with your email on first launch. No API keys. CLI and IDE share `~/.openfire/session.json`.

## Usage

```
openfire                 launch in current directory
openfire -d ~/myproject  set project directory
openfire -m claude-opus-5
```

## Commands

| Command | Description |
|---------|-------------|
| `/help` | Show help |
| `/clear` | Clear conversation |
| `/model` | Switch model |
| `/reasoning` | Reasoning effort (1.0x–5.0x token cost) |
| `/cost` | Token usage |
| `/update` | Check for updates |
| `/login` | Sign in |
| `/logout` | Sign out |
| `/exit` | Quit |

Ask OpenFire to create, edit, or run things in your project — it writes files and runs commands directly, no copy-paste.
