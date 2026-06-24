# Linux Basics

## File

### Definition

A file is a unit of stored data that contains information such as text, code, images, videos, or configuration data.

### Examples

* notes.md
* app.py
* image.jpg
* config.txt

### Important Points

* Files store data.
* A file can be empty or contain information.
* Files are organized inside directories.

---

## Directory

### Definition

A directory is a container used to organize files and other directories.

### Examples

```text
Documents/
Downloads/
Projects/
Cloud-Engineering-Journey/
```

### Important Points

* Directories can contain files and subdirectories.
* Directories help organize data.

---

## Current Working Directory (CWD)

### Definition

The current working directory is the directory in which commands are currently being executed.

### Command

```bash
pwd
```

### Example

```text
/home/hemansh/cloud-practice
```

---

## Hidden Files

### Definition

Files or directories whose names begin with a dot (`.`) are hidden by default in Linux.

### Examples

```text
.bashrc
.profile
.ssh
.git
```

### Why Hidden Files Exist

* Keep directories organized.
* Store configuration files.
* Reduce clutter for users.

### Important Points

* Hidden files are not hidden for security.
* They can be viewed using:

```bash
ls -la
```

---

# Basic Linux Commands

## pwd

### Purpose

Displays the current working directory.

### Syntax

```bash
pwd
```

---

## ls -la

### Purpose

Lists all files and directories, including hidden files, along with detailed information.

### Syntax

```bash
ls -la
```

---

## mkdir

### Purpose

Creates a new directory.

### Syntax

```bash
mkdir directory-name
```

### Example

```bash
mkdir cloud-practice
```

---

## cd

### Purpose

Changes the current directory.

### Syntax

```bash
cd directory-name
```

### Example

```bash
cd cloud-practice
```

---

## touch

### Purpose

Creates an empty file if it does not exist, or updates the file's timestamp if it already exists.

### Syntax

```bash
touch filename
```

### Example

```bash
touch notes.md
```

---

## cat

### Purpose

Displays the contents of a file in the terminal.

### Syntax

```bash
cat filename
```

### Example

```bash
cat notes.md
```

### Important Points

* Commonly used to view small files.
* Can also be used to combine multiple files.

---

## whoami

### Purpose

Displays the username of the current user.

### Syntax

```bash
whoami
```

---

## hostname

### Purpose

Displays the hostname of the current machine.

### Syntax

```bash
hostname
```

---

## ip addr

### Purpose

Displays network interface information and IP addresses.

### Syntax

```bash
ip addr
```

### Information Displayed

* IP Address
* Network Interfaces
* MAC Address
* Network Status

---

# SSH

## Definition

SSH (Secure Shell) is a secure protocol used to remotely access and manage computers over a network.

### Example

```bash
ssh username@server-ip
```

### Important Points

* Uses encryption.
* Default port is 22.
* Commonly used to manage Linux servers.

---

# SSH Keys

## Public Key

Can be shared with servers and is used for verification.

## Private Key

Must remain secret and is used to authenticate the user.

## SSH Directory

```text
~/.ssh
```

Common files:

```text
id_ed25519
id_ed25519.pub
known_hosts
```
