# website-experiments
This allows you to add something to my [website](https://blackdrgn.nl/) in form of an experiment.
### What is an experiment?
An experiment is a small "webapp" which can be used from my website. This could be a clock, game or whatever you come up with.
### Adding an experiment
An experiment can be added by creating a directory with a manifest.json file. The manifest.json file should look like this i.e
```json
{
    "pretty_name": "Simple Clock",
    "name": "simple_clock",
    "author": "BlackDragon",
    "file": "index.html",
    "sociallink": "https://blackdrgn.nl",
    "active": true
}
```
| Key Name      | Description   | Example  |
| ------------- |:-------------:| -----:|
| pretty_name   | Name that will be displayed as title. | Simple Clock |
| name          | Name that will be used for technical stuff, must not contain following chars (-/\()'"$% ).      |   simple_clock |
| author        | The name of the person that created this experiment      |    BlackDragon |
| file          | The file that contains the experiment      |    index.html |
| sociallink    | A link to anything, it can be a link to a website or a social media profile      |    https://blackdrgn.nl |
| active        | Determines if the experiment is active or not. true/false      |    true |
When the code is finished and ready create a PR to put the code in the repo. It takes max. 10 minutes to have the code applied to the page. The example experiment is in the example dir.
### Guidelines
Please don't include any harmful code in the experiment and use common sense. You should know when something is not ok.
#### Styling
Please keep in mind that the website is in darkmode. This means that it would be the best to design the experiment with the thought in-mind that the experiment will be displayed on a dark mode page.
