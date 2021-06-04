# leetcode-practice-python
This repository is a template which automates the boilerplate code when adding solutions to leetcode problems.

Using a single command, one can get the question information, generate the python executable template, generate the test files, and update the table at the end of the README.

## Question Solutions

Please check the [Solution Summary](QUESTIONS.md).

## Usage

Currently, it is necessary to log into leetcode on either chrome or firefox before running the commands.

### Installation

To install the needed libraries:

```shell
$ make setup
```

### Downloading a Question

To generate the files of a given question:

```shell
$ make get-question ID=<question_id>
```

### Submitting a Question

To submit a question to leetcode:

```shell
$ make submit-question ID=<question_id>
```

### Dowloading All Submissions

To download the latest accepted submission for each solved problem:

```shell
$ make get-all-submissions
```

### Removing a Question

To remove a downloaded problem (delete files and remove from readme):

```shell
$ make remove-question ID=<question_id>
```
