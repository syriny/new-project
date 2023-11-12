How to Set Up a New Git Repository and Create a Development Branch for `new-project`

Preconditions:

* Git installed on your local machine
* A GitHub account

Steps:

### 1. Create a new directory for your project:

```
mkdir new-project
cd new-project
```

### 2. Initialize a new Git repository:

```
git init
```

### 3. Create a new development branch:

```
git checkout -b development
```

### 4. Create a new README file:

```
touch README.md
```

### 5. Add your code to the repository and commit it:

```
git add 
git commit -m init
```

### 6. Push your changes to the remote repository:

```
git push origin development
```

### 7. Create a pull request to merge your changes into the main branch:

```
git checkout main
git pull origin main
git merge development
git push origin main
```