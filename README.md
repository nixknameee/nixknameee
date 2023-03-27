Hi, I'm Nikoll  👋🏻 🧑🏻‍💻

<a href="https://www.42vienna.com/bewerbung/?gclid=Cj0KCQjwqoibBhDUARIsAH2OpWg4u53DRd-TsD7nheSeyPgLNdj1NF3xg8bbXBECb1wNGZy8ne4MMvsaAo1AEALw_wcB">
<img src= "https://media-exp1.licdn.com/dms/image/D4D16AQENFYfzitZ4_g/profile-displaybackgroundimage-shrink_350_1400/0/1665241654995?e=1672876800&v=beta&t=jYtSVKTP43QRlCztOYiLnT6ALwj0wYm73sv4N2UzlCk" target="_blank">
<a/>




<p>
I'm a Software Engineer👨‍💻 & Electrical Engineer⚡ student.
I'm studying Software Engeeniring at the Campus of 42 Ecole in Vienna.


- 🔭 I’m currently working on the philopsohers dinning problem.
- 🌱 I’m currently learning C and python
- 💬 Ask me about anything.

 
 
  
 
  
  
  
</p>
on:
  schedule:
    - cron: '0 */12 * * *' # every 12 hours
  push:
    branches:
      - master
      - main
jobs:
  publish:
    runs-on: ubuntu-latest
    steps:
    - uses: actions/checkout@v3
      with:
        fetch-depth: 0
    - name: Generate README.md
      uses: teoxoy/profile-readme-stats@v2
      with:
        token: ${{ secrets.USER_TOKEN }}
    - name: Update README.md
      run: |
        if [[ "$(git status --porcelain)" != "" ]]; then
        git config user.name github-actions[bot]
        git config user.email 41898282+github-actions[bot]@users.noreply.github.com
        git add .
        git commit -m "Update README"
        git push
        fi
 <a href="https://www.instagram.com/nk.gjk/">
  <img src="https://github.com/nixknameee/nixknameee/blob/main/nk.gjk_qr.png?raw=true"
       width="350" height="350" target="_blank" hspace="20">
 <a/>
  
 <a href="https://www.linkedin.com/in/nikoll-gjokaj-929249240/">
  <img src="https://github.com/nixknameee/nixknameee/blob/main/LinkedIn.jpeg?raw=true"
       width="350" height="350" target="_blank"> 
 <a/>
