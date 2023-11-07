# Setup Gitbox
This action install [gitbox](https://github.com/asperan/gitbox) (using cargo) in the runner environment, so that its commands are available for subsequent steps.

## Inputs
| input | required | description |
| ----- | -------- | ----------- |
| gitbox-version | false | The version of gitbox to install. If not present, the default one is installed. |

