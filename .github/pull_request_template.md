# Pull Request Guidelines

### Code guidelines

Please go through these guidelines before submitting the PR.
1. The changes must be reasonable and should not contain only syntax changes or similar. For example: The Pull Request #41
2. The changes must be in some what working condition before it is made fully functional and merged. Preferrably it should work perfectly with no issues.
3. The changes must be practical and cannot not have a temporary fix for only specific conditions. For example: The Pull Request #32.
4. The changes must not be working with only deprecated version(s) of NodeJS, dependencies, or any other external dependencies.
5. The versions of Lazap must follow [SemVer](https://semver.org) versioning.

### Merge guidelines
1. The PR must have a good and understandable title.
	1. The title must start with capital letter. It should also have capital letters at appropriate places.
	2. There should be no grammatical mistakes in the title.
	3. If there are any mistakes edit it out immediately.
2. The PR must follow the template provided below.
	1. If not followed, the Pull Request will be closed.
3. The PR must have a description with all the information labelled with required.
	1. Any missing information can create delay in merge or may get straight up closed.
4. The PR must not have the base set as "main" branch.
	1. Only under special circumstances will this be allowed.
	2. The PR will instantly be closed, otherwise.

*Pull Request is abbreviated as "PR"

__**MAKE SURE TO REMOVE THIS WHEN SUBMITTING A PULL REQUEST**__

- - - -

#### **Description**
Following changes were made to

#### **Changes(in short)**
```diff
+ Added [...]
- Removed [...]
= Changed [...]
+ Added [...]
```

#### **Affected OS(es)**

Windows(8, 10, 11), Linux(Arch, Manjaro, etc.), MacOS


#### **Changes(in detail)**

* This PR adds [...] which helps fixing [...] and also improving [...].
* This PR also removes [...] because it reduces [...] resulting in [...].


#### **Additional Information**

There is a chance for [...] to happen and I have no idea how to prevent it.


#### **Checklist**

- [ ] Does the app work in Windows?

- [ ] Does the app work in Linux?

<!-- - [ ] Does the app work in MacOS? --->

- [ ] Is there any condition specific errors?

- [ ] Are the features of this PR completed?

- [ ] Is the PR following all the guidelines?
