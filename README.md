## What is error-hub?

As name, **error-hub** is a repository to post errors and solution about that error. The error should be anything related tech field like: programming, cloud, devops, etc. but I post mainly on linux, cloud and devops.

## Steps to Post

### 1. Create Directory Related to Error

For example if the error is related to **AWS** then, you can create directory `mkdir aws`.

### 2. Write Markdown File to Explain and Provide Context plus Solution Related to Error

- Create a markdown file related to error – the title should reflect the error vividly.
- Follow the Following Format for `.md` file:

```markdown
# Error Title 

## Context of Error

- explain your error in bullet point
- bullet point is preferred (for readability) but not mandatory
- context of error can be anything such as while you are programming, or you are configuring cloud or using terraform or whatever is appropriate
- YOU MUST INCLUDE STEPS TO REPRODUCE

### Steps to Reproduce

- write whatever it is

## Solution

- present tested solution of the error
```

> [!NOTE]
> The bullet points are there to explain the format, the headings are mandatory (to follow some standard for readability noting more than that, you can purpose better format) but how you describe is your freedom.

### 3. Create `pull_request`

- anytime you face error and solve it you can create `pull_request`
- community decides if to be merged or not