# default-project-template

![default-project-template](banner.png)

Find the project online at [projects.raspberrypi.org/en/projects/default-project-template](https://projects.raspberrypi.org/en/projects/default-project-template)

## Resources
For project materials and solutions, see [en/resources](https://github.com/raspberrypilearning/default-project-template/tree/master/en/resources) and [en/solutions](https://github.com/raspberrypilearning/default-project-template/tree/master/en/solutions).

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md)

## Licence
See [LICENCE.md](LICENCE.md)

## Crowdin setup

To make use of the Github workflows in this project repository for automating translation setup, you need to add the project's Crowdin ID to the repository's secrets on Github.

### Adding the project ID to Github

1. Once the project is created on Crowdin, copy the project ID. 

    - You should find this on the project's Crowdin dashboard, in a grey box on the right-hand side of the screen. It will be in the `Details` field, in the format `ID: 818746`. You just need the number.

2. In the Github repository for the project, go to `Settings`, then `Secrets and variables` which is in the `Security` section.

3. Click `Actions` and then go down to the `Repository secrets` section. 

4. Click to add a `New repository secret`.

5. **Enter the secret name, which should be `CROWDIN_PROJECT_ID`**

6. Paste the project ID number into the `Secret` field.

7. Press `Add secret` and you're done!
