# astro_docker

## How to start?
- Download astro from official
  - downloaded repo has to be inside of `astro` folder (if you don't want to make changes) 
- docker-compose -f docker-compose.yml up (--build | "only the first time")

## …or create a new repository on the command line
```
echo "# astro_docker" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:cjairm/astro_docker.git
git push -u origin main
```

## …or push an existing repository from the command line
```
git remote add origin git@github.com:cjairm/astro_docker.git
git branch -M main
git push -u origin main
```
