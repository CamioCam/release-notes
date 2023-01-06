## How to Add Release Notes

To add release notes to this repository, follow these steps:

1. Clone the repository locally: Use the following command to clone the repository to your local machine: `git clone https://github.com/[your-username]/[repository-name].git`

2. Create a new branch: Make a new branch for the release notes using the product name and the date of the release. The branch name should be in the format `PRODUCT-NAME-YYYY-MM-DD`. For example, if the product name is "Product A" and the release date is January 5th, 2021, the branch name would be `product-a-2021-01-05`.

3. Create a new file: In the folder for the product that has a new release, create a copy of the `TEMPLATE.md` file found in the [`templates` folder](templates/TEMPLATE.md). Name the file with the date of the release in the format `YYYY-MM-DD.md`.

4. Fill out the template: Open the new file and fill out the sections with the appropriate information. Remove any sections that are not applicable to the release.

5. Create a pull request: Once you have completed the release notes, create a pull request to submit the changes for review. The pull request should be sent to the `main` branch.

6. Merge the pull request: After the changes have been deployed and the features are live, the pull request can be merged into the `main` branch.
