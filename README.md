Project's templates for jMonkeyEngine 3:

-----
```
basic_3.0:
    url: https://github.com/jMonkeyEngine-Contributions/project_templates
    branch: basic_3.0

basic_3.1:
    url: https://github.com/jMonkeyEngine-Contributions/project_templates
    branch: basic_3.1

jme3_skel:
    url: https://github.com/davidB/jme3_skel
```

# Usage sample

with git (4)

```
git clone --depth 1 -b basic_3.1 https://github.com/jMonkeyEngine-Contributions/project_templates myproject
cd myproject
rm -Rf .git
./gradlew run
```

with download zip (4) (via curl or via your browser)

```
curl -O -L https://github.com/jMonkeyEngine-Contributions/project_templates/archive/basic_3.1.zip
unzip -e basic_3.1.zip -d myproject
cd myproject
./gradlew run
```
