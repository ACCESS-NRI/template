# REPOSITORY SETUP

> [!IMPORTANT]
> **If you have been designated as an admin for this repository, complete the following setup tasks before sharing this repository.**
>
> 1. **Set at least 2 repository admins**<br> Go to **Settings** > **Collaborators and teams** and add at least 2 people as admins (including yourself).
> 2. **Update the About section**<br> Click the gear icon at the top-right of the repository's main page and:
>    - Write a clear repository **Description**
>    - Include the GitHub handles of all admins in the description, e.g. _Admins: @admin1, @admin2_
>    - Add relevant **Topics** — see [topic tags](https://github.com/ACCESS-NRI/dev-docs/wiki/GitHub-Organizations#topic-tags) for guidance
> 3. **Apply branch protection rulesets**<br> Add the appropriate [branch protection rulesets](https://github.com/ACCESS-NRI/.github/tree/main/rulesets#readme) for this repository.
> 4. **Update this README**<br> Modify this README as appropriate for the repository documentation.

## Use this repository as a template

When creating a new repository you [can use this repository as a template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template), to automate the creation of the correct license and COPYRIGHT statements.

## COPYRIGHT Header

Best practice suggests adding a copyright statement at the top of every source code file, or text file where it is possible to add a copyright statement without interfering with the purpose of the file. The reasoning is if a file is separated from the repository in which it resides then it may not be possible to ascertain it's licensing, which may hamper re-use.

Making this as short and concise as possible reduces the overhead in including such a copyright statement. To that end using [SPDX identifiers](https://spdx.dev/ids/) is simple, efficient, portable and machine-readable.

### Examples

An example, short, copyright statement is reproduced below, as it might appear in different coding languages. Copy and add to files as appropriate: 

#### plaintext
It is common to include copyright statements at the bottom of a text document or website page
```text
© 2022 ACCESS-NRI and contributors. See the top-level COPYRIGHT file for details. 
SPDX-License-Identifier: Apache-2.0
```

#### python
For code it is more common to include the copyright in a comment at the top
```python
# Copyright 2022 ACCESS-NRI and contributors. See the top-level COPYRIGHT file for details.
# SPDX-License-Identifier: Apache-2.0
```

#### shell
```bash
# Copyright 2022 ACCESS-NRI and contributors. See the top-level COPYRIGHT file for details.
# SPDX-License-Identifier: Apache-2.0
```

##### FORTRAN
```fortran
! Copyright 2022 ACCESS-NRI and contributors. See the top-level COPYRIGHT file for details.
! SPDX-License-Identifier: Apache-2.0
```

#### C/C++ 
```c
// Copyright 2022 ACCESS-NRI and contributors. See the top-level COPYRIGHT file for details.
// SPDX-License-Identifier: Apache-2.0
```

### Notes

Note that the date is the first time the project is created. 

The date signifies the year from which the copyright notice applies. **NEVER** replace with a later year, only ever add later years or a year range. 

It is not necessary to include subsequent years in the copyright statement at all unless updates have been made at a later time, and even then it is largely discretionary: they are not necessary as copyright is contingent on the lifespan of copyright holder +50 years as per the [Berne Convention](https://en.wikipedia.org/wiki/Berne_Convention).
