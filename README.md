<div align="center">

```
███████╗██╗  ██╗ █████╗ ███╗   ███╗███╗   ███╗██╗
██╔════╝██║  ██║██╔══██╗████╗ ████║████╗ ████║██║
███████╗███████║███████║██╔████╔██║██╔████╔██║██║
╚════██║██╔══██║██╔══██║██║╚██╔╝██║██║╚██╔╝██║██║
███████║██║  ██║██║  ██║██║ ╚═╝ ██║██║ ╚═╝ ██║██║
╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝     ╚═╝╚═╝     ╚═╝╚═╝
```

### 🐳 DevOps Engineer · Automating everything, one pipeline at a time

![Bengaluru](https://img.shields.io/badge/📍_Bengaluru,_IN-0d1117?style=flat-square&labelColor=21262d&color=21262d)
![DevOps](https://img.shields.io/badge/DevOps-0d1117?style=flat-square&logo=linux&logoColor=3fb950&labelColor=0d2416&color=0d2416)
![Open to Work](https://img.shields.io/badge/Open_to_Work-0d1117?style=flat-square&labelColor=0c1f3a&color=0c1f3a&logoColor=58a6ff)

</div>

---

## `$ whoami`

```bash
shammi@devbox:~$ cat about.txt
→ DevOps Engineer passionate about cloud infrastructure & automation
→ Building scalable systems with Infrastructure as Code
→ Container whisperer 🐳 · CI/CD obsessed · Pipeline architect
→ Believer in "automate everything or die trying"
```

---

## `$ ls -la ~/tech-stack`

<div align="center">

### ⚙️ Core Tools

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)

### 🔁 CI/CD

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)

### ☁️ Cloud & Monitoring

![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

### 💻 Languages & Scripting

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-CB171E?style=for-the-badge&logo=yaml&logoColor=white)

</div>

---

## `$ cat ~/projects/featured`

<div align="center">

| Project | Description | Stack |
|---|---|---|
| 🔁 **[ci-autopilot](https://github.com/shammi05/ci-autopilot)** | Zero-touch CI/CD framework for microservice deployments | Shell · Docker · GitHub Actions |
| ☸ **[k8s-lab](https://github.com/shammi05/k8s-lab)** | Local Kubernetes playground with Helm charts & monitoring | YAML · Helm · Prometheus |
| 🏗 **[infra-as-code](https://github.com/shammi05/infra-as-code)** | Terraform modules for AWS ECS, RDS, and VPC provisioning | HCL · AWS · Terraform |
| 📊 **[devops-dashboard](https://github.com/shammi05/devops-dashboard)** | Grafana + Prometheus monitoring for deployment health | Python · Grafana · PromQL |

</div>

---

## `$ git log --stat`

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=shammi05&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=3fb950&text_color=8b949e)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=shammi05&theme=github-dark-blue&hide_border=true&background=0d1117&ring=58a6ff&fire=3fb950&currStreakLabel=8b949e)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=shammi05&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e)

</div>

---

## `$ watch -n1 contributions --snake`

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/shammi05/shammi05/blob/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/shammi05/shammi05/blob/output/github-contribution-grid-snake.svg" />
  <img alt="contribution snake animation" src="https://github.com/shammi05/shammi05/blob/output/github-contribution-grid-snake-dark.svg" />
</picture>

</div>

<!--
   Snake animation setup — run this once:
  1. Create folder: .github/workflows/
  2. Create file:   .github/workflows/snake.yml
  3. Paste the workflow below, commit & push
  4. Go to Actions tab → run "Generate Snake" manually the first time

  ───────────── snake.yml ─────────────
  name: Generate Snake

  on:
    schedule:
      - cron: "0 0 * * *"
    workflow_dispatch:

  jobs:
    generate:
      runs-on: ubuntu-latest
      steps:
        - uses: Platane/snk/svg-only@v3
          with:
            github_user_name: shammi05
            outputs: |
              dist/github-contribution-grid-snake.svg
              dist/github-contribution-grid-snake-dark.svg?palette=github-dark
        - uses: crazy-max/ghaction-github-pages@v3
          with:
            target_branch: output
            build_dir: dist
          env:
            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  ─────────────────────────────────────
-->

---

## `$ ping shammi05`

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-shammi05-0d1117?style=for-the-badge&logo=github&logoColor=white&labelColor=21262d)](https://github.com/shammi05)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/shammi05)
[![Email](https://img.shields.io/badge/Email-Drop_a_line-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shammi05@example.com)

</div>

---

<div align="center">

```
while true; do
  automate()
  deploy()
  monitor()
  sleep 0  # no rest for the pipelines
done
```

*⚡ Powered by caffeine, containers, and an unhealthy obsession with uptime*

</div>
