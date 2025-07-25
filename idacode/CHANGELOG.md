# Change Log

## 0.1.0

- Initial release
- IDAPython remote execution
- IDAPython debugger

## 0.1.1

- Added logging support

### 0.1.2

- Enhanced UX
- Added configuration checks

### 0.1.3

- Added support for Python 2

### 0.1.4

- Added "Save on execute" support in settings
 
### 0.2.0

- Added "Execute on save" support in settings
- Fixes Python 3.8 support on Windows (PR #13)
- Introduces `__name__` inside of the script environment as `__main__` (Issue #14)

### 0.2.2

- Updated README

### 0.3.0

- Fixed Python 2 support (PR #17)
- Fixed issue where debugpy would attempt to spawn the current process (Issue #23)

### 0.3.1

- Fixed unnecessary global prototype pollution that broke other extensions (eg GitHub Copilot)