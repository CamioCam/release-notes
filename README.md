# Release Notes

Welcome to the public release notes repository for all Camio products. Here, you can find information on the new features, improvements, and bug fixes included in each release, as well as any known issues and upgrade instructions (if applicable).

## How to Use

To view the release notes for a specific product, follow these steps:

1. Navigate to the product's folder in the repository.
2. Select the release notes file for the version you are interested in. The file will be in Markdown format and can be viewed in a text editor or online using a tool like GitHub's built-in Markdown viewer.
3. The release notes will include sections for new features, improvements, bug fixes, deprecations and removals, known issues, and upgrade instructions.

## Feedback

If you have any feedback or suggestions for the release notes, please open an issue in the repository or contact us directly.

## How to Add Release Notes

To add release notes to this repository, follow these steps:

1. Clone the repository locally: Use the following command to clone the repository to your local machine: `git clone https://github.com/[your-username]/[repository-name].git`

2. Create a new branch: Make a new branch for the release notes using the product name and the date of the release. The branch name should be in the format `PRODUCT-NAME-YYYY-MM-DD`. For example, if the product name is "Product A" and the release date is January 5th, 2021, the branch name would be `product-a-2021-01-05`.

3. Create a new file: In the folder for the product that has a new release, create a copy of the `TEMPLATE.md` file found in the [`templates` folder](templates/TEMPLATE.md). Name the file with the date of the release in the format `YYYY-MM-DD.md`.

4. Fill out the template: Open the new file and fill out the sections with the appropriate information. Remove any sections that are not applicable to the release.

5. Create a pull request: Once you have completed the release notes, create a pull request to submit the changes for review. The pull request should be sent to the `main` branch.

6. Merge the pull request: After the changes have been deployed and the features are live, the pull request can be merged into the `main` branch.
