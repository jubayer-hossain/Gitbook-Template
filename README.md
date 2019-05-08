# Gitbook Template

### `Step-1`: Create a new repository on github.com  

### `Step-2`: Create a bare clone of this repository
```bash
git clone --bare https://github.com/jubayer-hossain/Gitbook-Template.git
```
### `Step-3`: Mirror-push to new repository
```bash
cd Gitbook-Template.git
```
```bash
git push --mirror https://github.com/useraccount/new-repository.git
```

### ` Step-4`: Remove the temporary repository create above  
```bash
cd ..
```
```bash 
rm -rf old-repository.git
```
