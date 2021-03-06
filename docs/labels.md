## Labels

> To facilitate the community in finding ways to contribute that match their experiences and skillsets, we have developed a comprehensive system for labelling issues and PRs. This is an introduction to this standard labelling scheme.

> Labels consist of three fields, viz. name, description and color. Label names should have a consistent format to aid both filtering within the github UI as well as scanning visually through the list. The following format is the most suited to this task (where ⎵ denotes a single space):

```
<emoji>⎵<category>:⎵<name>
```

Using the label convention from https://opensource.creativecommons.org/contributing-code/repo-labels/

### Usage

Using the library [xavierchow/github-label-template](https://github.com/xavierchow/github-label-template) to export/import labels with the file `labels.json`

To add a new label, update the `labels.json` file and the GitHub Action will do the rest.
