# DevOps Tp

### Historique des commits

```bash
PS D:\2MPSWM S3\devops\tp\devops-tp> git log
commit 957b6b5839601f7f7aca33fda09712b4f159c6e7 (HEAD -> main)
Author: sidi ahmed <sidiahmedhabib@gmail.com>
Date:   Tue Oct 8 10:39:39 2024 +0100

    Premier commit : ajout de index.html
PS D:\2MPSWM S3\devops\tp\devops-tp>
```

```bash
PS D:\2MPSWM S3\devops\tp\devops-tp> git log --oneline
e8b97fb (HEAD -> main) add readme file
957b6b5 Premier commit : ajout de index.html
PS D:\2MPSWM S3\devops\tp\devops-tp>
```

### Afficher les différences entre deux commits

````bash
PS D:\2MPSWM S3\devops\tp\devops-tp> git diff 957b6b5 e8b97fb
diff --git a/README.md b/README.md
new file mode 100644
index 0000000..200f1e8
--- /dev/null
+++ b/README.md
@@ -0,0 +1,12 @@
+# DevOps Tp
+### Historique des commits
+
+```bash
+PS D:\2MPSWM S3\devops\tp\devops-tp> git log
+commit 957b6b5839601f7f7aca33fda09712b4f159c6e7 (HEAD -> main)
+Author: sidi ahmed <sidiahmedhabib@gmail.com>
+Date:   Tue Oct 8 10:39:39 2024 +0100
+
+    Premier commit : ajout de index.html
+PS D:\2MPSWM S3\devops\tp\devops-tp>
+```
PS D:\2MPSWM S3\devops\tp\devops-tp>
````

### Git Flow

```bash
PS D:\2MPSWM S3\devops\tp\devops-tp> git log --oneline --graph
*   4af743d (HEAD -> main, origin/main) Merge branch 'release/0.2'
|\
| * 4e0f282 (release/0.2, dev) added js file
|/
* 4f00928 (origin/ma-fonctionnalite, origin/HEAD, ma-fonctionnalite) Modification de ma-fonctionnalite
* 9ffeef5 modify readme file
* e8b97fb add readme file
* 957b6b5 Premier commit : ajout de index.html
PS D:\2MPSWM S3\devops\tp\devops-tp>
```

#### branchs

```bash
PS D:\2MPSWM S3\devops\tp\devops-tp> git branch
  dev
  ma-fonctionnalite
* main
  release/0.2
PS D:\2MPSWM S3\devops\tp\devops-tp>
```
