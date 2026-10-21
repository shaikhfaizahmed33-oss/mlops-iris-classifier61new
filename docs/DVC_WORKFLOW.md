# DVC Workflow Documentation
1. Configured local DVC remote at ~/dvc-remote-storage.
2. Tracked dataset using: dvc add -> git add .dvc -> git commit.
3. Uploaded data using: dvc push.
4. Compared versions using: dvc diff and checking the MD5 hashes.
5. Used `git checkout <hash> -- <file>.dvc` and `dvc checkout` to switch between dataset versions.
