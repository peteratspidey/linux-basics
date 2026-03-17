If you want commands like

`docker start -ai vivek_shigella`

to appear **colorful and easier to read**, the best option is to use **Zsh with Oh-My-Zsh**. It is widely used on Linux for a **colorful prompt, command highlighting, and auto-suggestions**.

---

## 1. Recommended Shell: **Zsh + Oh My Zsh**

### Install Zsh

Inside Ubuntu run:

```bash
sudo apt update
sudo apt install zsh -y
```

Check installation:

```bash
zsh --version
```

---

### Install Oh-My-Zsh

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

This automatically:

* changes default shell to **zsh**
* installs **themes**
* adds **color prompt**

---

## 2. Install Useful Plugins (for color + suggestions)

Edit the config:

```bash
nano ~/.zshrc
```

Find:

```bash
plugins=(git)
```

Change to:

```bash
plugins=(git docker zsh-autosuggestions zsh-syntax-highlighting)
```

---

### Install plugins

```bash
git clone https://github.com/zsh-users/zsh-autosuggestions ~/.oh-my-zsh/custom/plugins/zsh-autosuggestions
```

```bash
git clone https://github.com/zsh-users/zsh-syntax-highlighting ~/.oh-my-zsh/custom/plugins/zsh-syntax-highlighting
```

Reload shell:

```bash
source ~/.zshrc
```

---

## 3. What You Get

Now commands will appear like this:

* **green** → valid commands
* **red** → invalid commands
* **grey suggestion** → auto completion
* **colored prompt**

Example:

```
➜ docker start -ai vivek_shigella
```

---

## 4. Popular Themes

Edit in `~/.zshrc`:

```
ZSH_THEME="agnoster"
```

or very popular:
```bash
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git \
${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```
```bash
ZSH_THEME="powerlevel10k/powerlevel10k"
```

---

✅ **For your Docker + bioinformatics workflow**, the best terminal setup is:

* **Zsh**
* **Oh-My-Zsh**
* **Powerlevel10k theme**
* **syntax highlighting plugin**
* **autosuggestions plugin**

This makes Docker commands, Git commands, and Linux commands **much clearer and faster to type**.

---

If you want, I can also show you a **very powerful terminal setup used by bioinformatics engineers (Zsh + Powerlevel10k + Tmux)** that makes **Docker pipeline development much easier.**
