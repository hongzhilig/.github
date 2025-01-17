# Simon CSS

![Simon](../simon.png)

This application deliverable demonstrates the use of basic CSS for styling and a responsive design.

The addition of CSS makes our application visually appealing and adds intuitive user interface elements, but it is still not functional due to the lack of interactivity. We will add that in the next deliverable when we introduce JavaScript.

This deliverable adds a single CSS file (`main.css`) that contains the CSS for the entire application. Each of the HTML files references the CSS file using the `link` element.

```html
<link rel="stylesheet" href="main.css" />
```

As the application gets more complicated we will break up the CSS into individual files that correspond to the component they style.

You can view this application running here: [Example Simon CSS](https://simon-css.cs260.click)

![Simon CSS](simonCss.jpg)

## Study this code

Get familiar with what the example code teaches.

- Clone the repository to your development environment.

  ```sh
  git clone https://github.com/webprogramming260/simon-css.git
  ```

- Review the code and get comfortable with everything it represents.
- View the code in your browser by hosting it using the VS Code Live Server extension.
- Make modifications to the code as desired. Experiment and see what happens.

## Make your own version

- Using VS Code, open the `simon` directory for the repository you used for the last Simon assignment.
- Modify the project to use CSS and the Bootstrap CSS framework. Refer to the example class application repository for guidance. Remember that you do not need to create an original work. Just focus on learning the concepts that the example project provides. However, you will learn more if you type everything out, and not just copy and paste the code.
- Set the footer link to point to your code repository. (e.g. https://github.com/youraccount/simon)
- Periodically commit and push your code to your repository as you hit different milestones. (4 commits are required for full credit.)
- Periodically deploy to your production environment using a copy of the `deployFiles.sh` script found in the [example class application](https://github.com/webprogramming260/simon-css/blob/main/deployFiles.sh). Take some time to understand how it works. This is the same script that you used for the Simon HTML version.

  ```sh
  ./deployFiles.sh -k <yourpemkey> -h <yourdomain> -s simon
  ```

  For example,

  ```sh
  ./deployFiles.sh -k ~/keys/production.pem -h yourdomain.click -s simon
  ```

- Update your `start up` repository README.md to record and reflect on what you learned.
- When you have completed your version. Do a final push of your code and deploy to your production environment using the `deployFiles.sh` script.
- Make sure your project is visible from your production environment (e.g. https://simon.yourdomain.click).
- Submit the URL to your production environment for grading using the Canvas assignment page.

## Grading Rubric

- 40% - Extensive use of CSS selectors and declarations
- 30% - Visually appealing interface
- 10% - Use of the CSS framework Bootstrap
- 10% - At least four Git commits for the project (Initial, milestone, ..., milestone, final)
- 10% - Notes in your `start up` repository README.md about what you have learned
