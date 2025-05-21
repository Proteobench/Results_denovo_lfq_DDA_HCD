# Results_denovo_lfq_DDA_HCD

This repository contains all the information necessary to plot the figure of the ProteoBench module `De Novo - DDA - HCD`.
It is generated automatically when benchmark runs are uploaded for public submission.

## Delete keys manually

In the version controlled folder, delete keys manaually using `delete_keys.py` and commit the changes.

```bash
# pip install pandas # needs pandas
python delete_keys.py --json_file jsonfile_name --keys key
```

See the logged manipulation in [`delete_log.txt`](delete_log.txt).
