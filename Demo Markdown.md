# Organizations

## Branches
* [Create a Branch](#create-a-branch)

* [Create an Alias](#create-an-alias)

* [Remove an Alias](#remove-an-alias)

Contentstack provides \**Branches** to allow you to create multiple copies of your stack content. Every stack has a *main branch* by \~~default~~. To create a new branch, you can fork a branch off of the main branch.

When you create a branch for the first time, the main branch becomes your \_source branch_. For all subsequent branches you create, you need to specify a source branch from which it will \__inherit data__.

> **Note**: The *Branches* feature is only available in the [new Contentstack interface][new-app].

Branches are useful for:
* Content managers
* Developers
- Admins
- Org owners
    - Release managers

### Create a Branch
To create a branch, log in to your account, go to your stack, and perform the following steps:
1. Click the “Settings” icon on the left navigation panel, and select **Branches**.
2. Click on **+ New Branch**.
3. Enter a unique ID for the branch.
4. Select a branch from the dropdown from which this new branch should inherit data.
5. Click on **Create** to save your branch.

The following code highlights JSON schema for a branch:

```json
{
    "data_type": "text",
    "display_name": "Single line textbox",
    "uid": "single_line",
    "field_metadata": {
        "description": "",
        "default_value": ""
    },
    "format": "",
    "error_messages": {
        "format": ""
    },
    "multiple": false,
    "mandatory": false,
    "unique": false
}
```
---
___
## Aliases
### Create an Alias
### Remove an Alias
---
___

![Capgemini PRISMA][prisma-app]

Some `javascript` code for reference:
```javascript
<script type="text/javascript" src="/path/to/contentstack.min.js"></script>;
```

```bash
npm i capgemini
```

| type    | default | optional |
| :------- | :------- | :-------- |
| boolean | true    | yes      |

- [x] Task 1
- [x] Task 2
- [] Task 3

* [x] Task 1
* [x] Task 2
* [] Task 3

[new-app]: https://www.contentstack.com/docs/new-contentstack "Venus Interface"
[prisma-app]: https://gitlab.acidspace.nl/cge-prisma/prisma/-/blob/development/Help/Help%20source/risktool_helpfiles_troubleshooting_files/image001.png