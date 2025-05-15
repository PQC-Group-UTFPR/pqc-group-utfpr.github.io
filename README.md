<!-- HEADER -->
<p align="left">
  <img src="./images/logo-grupo-pqc-utfpr.svg" alt="PQC UTFPR Logo" width="48" style="vertical-align: middle;"/>
  <span style="font-size: 1.75em; font-weight: bold; vertical-align: middle; margin-left: 10px;">pqc-group-utfpr.github.io</span>
</p>

---

Welcome to the **PQC Research Group** website at
[UTFPR – Toledo Campus](http://portal.utfpr.edu.br/campus/toledo)!

Here is where we showcase our team, our projects, and our passion for
post-quantum cryptography research.

---

## 🚀 How to Join Our Website Team and Add Yourself!

Want your face and info to shine on our **Team Page**? It's super easy — just
follow these simple steps and become part of our digital family:

### 1. Create your GitHub account  

If you don’t have one yet, [sign up here](https://github.com/) — it’s free and
essential for collaborating with us.

### 2. Get invited and accept  

Send us your GitHub username by email, and we’ll add you as a collaborator.
Don’t forget to accept the invitation when you receive it!

### 3. Grab a copy of the website repository  

Clone the repo to your computer with:  
```bash
git clone https://github.com/PQC-Group-UTFPR/pqc-group-utfpr.github.io
````

Or download it directly from GitHub if you prefer.

### 4. Create your own branch

To keep things neat, create a new branch just for your changes:

```bash
git checkout -b add-seunome-to-group-members
```

*You can also create a branch right in GitHub’s web editor when editing files.*

### 5. Upload your photo

Head over to the folder `images/team-fotos` and add your portrait there. If you
want, do it straight from GitHub’s web interface: click **Add file** → **Upload
files** → select your photo → **Commit changes**.

### 6. Edit `group_members.html` and add your info

Open the file `group_members.html` and find this template block:

```html
            <!-- SEU NOME COMPLETO -->
            <div class="member-card">
              <div class="member-photo">
                <img src="./images/team-fotos/SUA_FOTO_AQUI" alt="SEU NOME COMPLETO">
              </div>
              <div class="member-info">
                <h3>SEU NOME COMPLETO</h3>
                <p class="member-position">Undergraduate Student</p>
                <p class="member-details">Computer Engineering</p>
                <div class="member-links">
                  <a href="https://github.com/SEU_GITHUB" target="_blank" rel="noopener noreferrer" class="member-link">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                      <path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path>
                    </svg>
                    GitHub
                  </a>
                </div>
              </div>
            </div>
```

Make it your own by replacing:

* `SEU NOME COMPLETO` with your full name
* `SUA_FOTO_AQUI` with your photo’s filename
* `Undergraduate Student` with your role
* `Computer Engineering` with your course
* `https://github.com/SEU_GITHUB` with your GitHub

### 7. Commit and push your changes

When you’re ready:

* On GitHub web: commit your changes and select **Create a new branch for this
  commit and start a pull request** — then submit the PR.
* Or via terminal:

```bash
git add group_members.html images/team-fotos/SUA_FOTO.jpg
git commit -m "add SEU_NOME to group members"
git push origin add-seunome-to-group-members
```

### 8. Open a Pull Request (PR)

Go to GitHub and open a PR so we can review your awesome addition and merge it
into the main page.

---

🎉 Congratulations — you’re officially part of the PQC UTFPR team! 🎉

If you get stuck or have questions, don’t hesitate to reach out by email or in
our GitHub discussions.

---

We’re excited to see you on the team page soon — welcome aboard! 🚀

_**- Team PQC UTFPR**_
