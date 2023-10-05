# CNN Classifier Project
$ git init
Initialized empty Git repository in E:/prarit/code/cnnclasifier/.git/

AML@DESKTOP-28RNVKM MINGW64 /e/prarit/code/cnnclasifier (master)
$ pwd
/e/prarit/code/cnnclasifier

AML@DESKTOP-28RNVKM MINGW64 /e/prarit/code/cnnclasifier (master)
$ touch README.md

AML@DESKTOP-28RNVKM MINGW64 /e/prarit/code/cnnclasifier (master)
$  git config --global user.email "prarit26@gmail.com"

AML@DESKTOP-28RNVKM MINGW64 /e/prarit/code/cnnclasifier (master)
$ git config --global user.name "prarit26"

AML@DESKTOP-28RNVKM MINGW64 /e/prarit/code/cnnclasifier (master)
$ git pull origin master

## workflow

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config.
6. Update the components
7. Update the pipeline
8. Test run pipeline stage
9. run tox for testing your package
10. Update the dvc.yaml
11. run "dvc repro" for running all the stages in pipeline