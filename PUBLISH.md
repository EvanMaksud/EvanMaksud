# Publish Notes

This folder is prepared for the special GitHub profile repository.

GitHub shows a profile README when:

- The repository name exactly matches the username: `EvanMaksud`.
- The repository is public.
- `README.md` exists in the repository root.
- The README has content.

## Publish Order

Publish the three real project repositories first so the profile links work:

1. `yolo-dataset-auditor`
2. `repo-health-auditor`
3. `job-fit-analyzer`
4. `EvanMaksud` profile repository

The project repos are ready locally under:

```text
E:\ppp 2\real-portfolio-projects
```

## Publish The Project Repos

Create these three public GitHub repositories:

```text
yolo-dataset-auditor
repo-health-auditor
job-fit-analyzer
```

Then push each local repo:

```powershell
cd "E:\ppp 2\real-portfolio-projects\yolo-dataset-auditor"
git remote add origin https://github.com/EvanMaksud/yolo-dataset-auditor.git
git push -u origin main

cd "E:\ppp 2\real-portfolio-projects\repo-health-auditor"
git remote add origin https://github.com/EvanMaksud/repo-health-auditor.git
git push -u origin main

cd "E:\ppp 2\real-portfolio-projects\job-fit-analyzer"
git remote add origin https://github.com/EvanMaksud/job-fit-analyzer.git
git push -u origin main
```

## Publish The Profile Repo

Create a new public GitHub repository named `EvanMaksud`. Do not initialize it with another README if you plan to push this folder directly.

This local folder is already a Git repo. After creating the empty GitHub repo, run:

```powershell
cd "E:\ppp 2\EvanMaksud"
git remote add origin https://github.com/EvanMaksud/EvanMaksud.git
git push -u origin main
```

After publishing, visit:

```text
https://github.com/EvanMaksud
```

## Recommended GitHub Settings

- Pin these repositories: `yolo-dataset-auditor`, `repo-health-auditor`, `job-fit-analyzer`, `Infinite-Mouse-Scroll`, `Object-Detection-YOLO11`, `Sentiment-Analysis-BERT`.
- Add a short GitHub bio such as: `Python developer exploring automation, computer vision, NLP, and practical ML tools.`
- Add repo descriptions so they do not look empty in search and profile cards.

Suggested descriptions:

- `yolo-dataset-auditor`: `CLI tool for auditing YOLO datasets before object-detection training.`
- `repo-health-auditor`: `CLI tool that scores repository readiness for public portfolio use.`
- `job-fit-analyzer`: `CLI tool for comparing a resume against a job description with keyword and skill-category reports.`
- `Sentiment-Analysis-BERT`: `Fine-tuning BERT for multi-class emotion classification with PyTorch and Transformers.`
- `Object-Detection-YOLO11`: `Vehicle detection workflow with YOLO11, OpenCV, PyTorch, and Kaggle notebooks.`
