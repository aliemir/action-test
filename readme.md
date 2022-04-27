# Action Test

## Command

```bash

echo "$(git config user.name)" > test/"action-test"_$(date "+%s").md;git add .;git commit -q -m "push test";git push -q origin main;echo "done. exit code: " $?;
 
```
