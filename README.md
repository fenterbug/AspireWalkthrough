# AspireWalkthrough

This project explores my journey in learning some of the fundamentals of modern development. 
The end goal is to have:
* [ ] a complex domain,
* [ ] multiple front-ends,
* [ ] a thorough security model,
* [ ] persistence,
* [ ] my own repository layer,
* [ ] database schema migrations,
* [ ] multi-tenancy,
* [ ] custom metrics,
* [ ] and proper logging.

I also want to take advantage of
* [x] unit tests (included with the latest Aspire template),
* [ ] integration tests,
* [ ] UAT tests,
* [ ] benchmarking,
* [ ] issue tracking,
* [ ] multiple branches/forks (probably using the [Git Flow](https://www.gitkraken.com/learn/git/git-flow) workflow)
* [ ] and CI/CD to multiple environments (DEV/TEST/LIVE).

## How to Use

I am starting with the standard Aspire template. As I implement each feature, I will create a single pull request. This allows anyone to see exactly what changed to implement that feature-- and only the changes needed to implement that feature-- simply by doing a diff on that pull request.

So if you want to see how to implement a custom metric, simply find the "Add custom metrics" pull request and view the diffs. That will show you what code changed to implement the feature.

If any feature relies on some other feature, it will be clearly stated in the pull request.

### Note

Please note that I've already added [Shouldly](https://github.com/shouldly/shouldly) to the test project and updated the sample test accordinly. So it's not _exactly_ the default Aspire template. But that's the only difference.

Also note that I created the git repository first, then added this readme file. So the first pull request won't implement any features; it just adds this description.