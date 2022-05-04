### IntelliJ IDEA auto-import code completion 

Edit file `b/src/B.js` by typing at the top on a line by itself `import ` followed by CTRL+Space to trigger code
completion and choose file A.js:

* In IntelliJ IDEA 2022.1 (Ultimate Edition) Build #IU-221.5080.210 this results in a pop-up message saying `Cannot build a module path for importing`.
* In IntelliJ IDEA 2021.2.4 (Ultimate Edition) Build #IU-212.5712.43 this results in the line `import A from "../../a/src/A.js";` being inserted.