# Publish Notes

This folder is prepared for the special GitHub profile repository.

GitHub shows a profile README when:

- The repository name exactly matches the username: `EvanMaksud`.
- The repository is public.
- `README.md` exists in the repository root.
- The README has content.

## Publish With Git

Create a new public GitHub repository named `EvanMaksud`. Do not initialize it with another README if you plan to push this folder directly.

Then run:

```powershell
cd "E:\ppp 2\EvanMaksud"
git init
git add README.md PUBLISH.md repo-readme-drafts
git commit -m "Add profile README"
git branch -M main
git remote add origin https://github.com/EvanMaksud/EvanMaksud.git
git push -u origin main
```

After publishing, visit:

```text
https://github.com/EvanMaksud
```

## Recommended Profile Settings

- Pin these repositories: `Infinite-Mouse-Scroll`, `Object-Detection-YOLO11`, `Sentiment-Analysis-BERT`.
- Add a short GitHub bio such as: `Python developer exploring automation, NLP, and computer vision.`
- Add repo descriptions for the notebook projects so they do not look empty in search and profile cards.

Suggested descriptions:

- `Sentiment-Analysis-BERT`: `Fine-tuning BERT for multi-class emotion classification with PyTorch and Transformers.`
- `Object-Detection-YOLO11`: `Vehicle detection workflow with YOLO11, OpenCV, PyTorch, and Kaggle notebooks.`

