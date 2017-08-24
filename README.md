# Using oXygen Web Author for casual contributions

 Access the free trial oXygen Web Author environment at[https://www.oxygenxml.com/webapp-demo-aws/app/oxygen.html](https://www.oxygenxml.com/webapp-demo-aws/app/oxygen.html)

## Connect to the sample GitHub repository
1. Under `Open`, select `Git`.
2. Select `Login with GitHub`.
3. Enter `https://github.com/fviolette/doc-casual-contribution` as the Git repository URL.
4. Click `Browse`.

## Writing a new article
For the purpose of this test, creating a new article means editing the template located in your test folder.

1. Navigate to your test folder (e.g. cgauthier/, danderson/).
2. Select `article.ditamap` and click `Choose`.
3. Open the sections you want to edit (e.g. `what_is_concept.dita`, `list_of_components.dita`).
4. Make all required edits (add new content, upload images).
5. When you are done, press `Ctrl+S`.
6. Enter a commit message.
7. Select the `Create Pull Request automatically` checkbox.
8. Click `Commit`.

The Git connector will automatically do the following:
- Fork the project into your account, if it is not already.
- Create a new branch from the edited branch.
- Commit your changes on this newly created branch.
- Create a pull request from your newly created branch to the originally edited branch.
- Switch the editor to your branch so further save operations will just add new commits to your branch, thus updating the pull request with new changes.

## Editing an exisitng article

1. Navigate to the `_samples/` test folder.
2. Select `article.ditamap` and click `Choose`.
3. Open the sections you want to edit (e.g. `what_is_concept.dita`, `list_of_components.dita`).
4. Make all required edits (add new content, upload images).
5. When you are done, press `Ctrl+S`.
6. Enter a commit message.
7. Select the `Create Pull Request automatically` checkbox.
8. Click `Commit`.