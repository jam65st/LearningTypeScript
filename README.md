# LearningTypeScript
This project is a foundation to set up a **TypeScript** project, learn, develop skills and improve the performance in the use and transfer of past experiences in **OOP** (from Java, ActionScript, or another language)

The tutorial about it is available on [DEV.to](https://dev.to/jam65st/setting-up-a-typescript-project-with-intellij-idea-ddg-temp-slug-7192451/)

---

If you want to start a TypeScript project, you could use the green button (Use this template) a GitHub feature on top of the traditional git clone.

GitHub will ask you the new name of your repository (use PascalCase), their description, choose if will be public or private. Also, it ask if you want import all branches of the template (In this moment only has the master branch, then it's unnecessary). And, then you can create the repository from template.

But after creating on **IntelliJ IDEA**, it is highly recommended that updates any files on your repository:
* **.idea**: 
  * In **.name** file, edit and update with your new project name in PascalCase format.
  * Edit your **modules.xml** file, updating the line **5**, replacing learning_typescript, with your project name in snake_case format.
* **learning_typescript.iml**: change the file name to your project name in snake_case format.
* **packages-lock.json**: change your project name on lines **2** and **8** (in snake_case).
* **packages.json**: change your project name on line **2** (in snake_case). I recommend that update almost your description, author, keywords, and license elements.
* **README.md**: Update this file for the purposes of your project name.

And finally, copy the link to your repository.

Once done, you can create a new project on your IntelliJ IDEA application, with the option **Project from Version Control** use your GitHub account and create it (using your link).

But IntelliJ only import the project files, then you must perform any aditional tasks such as:
1. The folder **.idea** must be added to **.gitignore** file.
2. You must run ``npm install`` in your terminal.
3. If this is your first time or if you have time without using this template, you need to follow the steps in the tutorial. With a special focus on 1, 2, 10-13 and test.

    **Remember** that *before starting* you must install *NodeJS*, your favorite *package manager* (npm, yarn, or pnpm), and *TypeScript*. A guide about it will be on DEV.to soon.

Follow me on:
* [DEV.to](https://dev.to/jam65st)
* [Facebook](https://www.facebook.com/jam65st/)
* [GitHub](https://github.com/jam65st)
* [Instagram](https://www.instagram.com/testandfails/)
* [LinkedIn](https://www.linkedin.com/in/jam65st/)
* [Twitter](https://twitter.com/jam65st)