
***

# Setup Go! (GitHub Action)

This project is a GitHub action for the Go! programming language by Francis McCabe. It was created 5 years before Google released their Go programming language.

```
Timeline
2004 - Go! created
2009 - Go created
```

This action supports the Go! programming language on Linux (Ubuntu, Fedora, Arch) MacOS, and Windows. It is a CI (Continious Integration) workflow.

## Functionality

This project is not yet functional. It is my first GitHub action, I am new to making them. The syntax was modified from the Go workflow.

## Install

Copy and paste your preferred platform(s) scripts from below to a workflow file in the directory path `/.github/workflows/filename.yml`

<details open><summary><p lang="en">Click/tap here to expand/collapse this section</p></summary>

### Ubuntu Linux

```yaml
name: Go! (2004) for Ubuntu Linux
# Supports the Go! programming language on Ubuntu Linux
# Not to be confused with Google Golang (2009) this action is for the Agent-based language by Francis McCabe named Go! (from 2004)
# Action version (1, Saturday, 2021 December 18th at 5:00 pm)

on:
  push:
    branches: [ main ]
  pull_request:
    branches: [ main ]

# Ubuntu Linux
jobs:

  build:
    runs-on: ubuntu-latest
    steps:
    - uses: actions/checkout@v2

    - name: Set up Go! (2004) on Ubuntu (latest)
      uses: actions/https://github.com/fgmccabe/go@v2
      with:
        go2004-version: 2015.12.02

    - name: Build
      run: go! build -v ./...

    - name: Test
      run: go! test -v ./...
```

### Fedora Linux

```yaml
name: Go! (2004) for Fedora Linux
# Supports the Go! programming language on Fedora Linux
# Not to be confused with Google Golang (2009) this action is for the Agent-based language by Francis McCabe named Go! (from 2004)
# Action version (1, Saturday, 2021 December 18th at 5:02 pm)

on:
  push:
    branches: [ main ]
  pull_request:
    branches: [ main ]

# Ubuntu Linux
jobs:

  build:
    runs-on: fedora-latest
    steps:
    - uses: actions/checkout@v2

    - name: Set up Go! (2004) on Fedora Linux (latest)
      uses: actions/https://github.com/fgmccabe/go@v2
      with:
        go2004-version: 2015.12.02

    - name: Build
      run: go! build -v ./...

    - name: Test
      run: go! test -v ./...
```

### Arch Linux

```yaml
name: Go! (2004) for Arch Linux
# Supports the Go! programming language on Arch Linux
# Not to be confused with Google Golang (2009) this action is for the Agent-based language by Francis McCabe named Go! (from 2004)
# Action version (1, Saturday, 2021 December 18th at 5:04 pm)

on:
  push:
    branches: [ main ]
  pull_request:
    branches: [ main ]

# Arch Linux
jobs:

  build:
    runs-on: arch-latest
    steps:
    - uses: actions/checkout@v2

    - name: Set up Go! (2004) on Arch Linux (latest)
      uses: actions/https://github.com/fgmccabe/go@v2
      with:
        go2004-version: 2015.12.02

    - name: Build
      run: go! build -v ./...

    - name: Test
      run: go! test -v ./...
```

### MacOS 12 (Monterey)

```yaml
name: Go! (2004) for MacOS
# Supports the Go! programming language on MacOS
# Not to be confused with Google Golang (2009) this action is for the Agent-based language by Francis McCabe named Go! (from 2004)
# Action version (1, Saturday, 2021 December 18th at 5:06 pm)

on:
  push:
    branches: [ main ]
  pull_request:
    branches: [ main ]

# MacOS
jobs:

  build:
    runs-on: macos-latest
    steps:
    - uses: actions/checkout@v2

    - name: Set up Go! (2004) on MacOS (latest)
      uses: actions/https://github.com/fgmccabe/go@v2
      with:
        go2004-version: 2015.12.02

    - name: Build
      run: go! build -v ./...

    - name: Test
      run: go! test -v ./...

```

### Windows 11

```yaml
name: Go! (2004) for Windows
# Supports the Go! programming language on Windows (latest)
# Not to be confused with Google Golang (2009) this action is for the Agent-based language by Francis McCabe named Go! (from 2004)
# Action version (1, Saturday, 2021 December 18th at 4:57 pm)

on:
  push:
    branches: [ main ]
  pull_request:
    branches: [ main ]

# Windows 11
jobs:

  build:
    runs-on: windows-latest
    steps:
    - uses: actions/checkout@v2

    - name: Set up Go! (2004) on Windows (latest)
      uses: actions/https://github.com/fgmccabe/go@v2
      with:
        go2004-version: 2015.12.02

    - name: Build
      run: go! build -v ./...

    - name: Test
      run: go! test -v ./...

```

</details>

## Versions of Go!

I plan to support all versions of the Go! language. As far as I can currently tell, there is only 1 version.

***

## README File info

**File type:** `Markdown Document (*.md *.mkd *.mdown *.markdown)`

**File version:** `1 (2021, Saturday, December 18th at 5:20 pm)`

**Line count (including blank lines and compiler line):** `221`

**File language:** `English (US) / Markdown / HTML5`

**All times are UTC-7 (PDT/Pacific Time)**

**You may need special rendering support for the `<dropdown>` HTML tag being used in this document**

***
